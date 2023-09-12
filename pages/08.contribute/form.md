---
title: Aufgabe Einsenden
visible: false
form:
    name: contact-form
    fields:
        name:
          label: Name
          placeholder: Enter your name
          autofocus: on
          autocomplete: on
          type: text
          validate:
            required: true

        email:
          label: Email
          placeholder: Enter your email address
          type: email
          validate:
            required: true

        aufgabe:
          label: Aufgabenstellung (in Latex oder Text)
          placeholder: Berechne...
          type: textarea
          validate:
            required: true

        tipp:
          label: Tipp zum Vorgehen (Text)
          placeholder: Skizziere die Situation...
          type: textarea
          validate:
            required: false

        loesungsidee:
          label: Lösungsidee (1-2 Sätze, ohne Formeln)
          placeholder: Mit Hilfe der allgemeinen quadratischen Gleichung...
          type: textarea
          validate:
            required: false

        loesung:
          label: Lösung (ausführliche Lösungen erwünscht)
          placeholder: 1. Die Sinusfunktion hat eine Periode von... 2. Die Lösung der gegebenen Funktion ist deshalb...
          type: textarea
          validate:
            required: true

        schwierigkeit:
          label: Wie schwer ist die Aufgabe? (1-3)
          placeholder: 2
          type: text
          validate:
            required: true

        dauer:
          label: Zeitaufwand (in Minuten)
          placeholder: 10'
          type: text
          validate:
            required: true


        collection:
          type: checkboxes
          label: Gehört zu
          default:
            - option1
          options:
            option1: Aufgaben
            option2: basale Kompetenz
            option3: Maturaaufgabe
            option4: Maturakurzaufgabe

        file:
          type: file
          multiple: false
          destination: 'self@'
          accept:
            - image/*

    buttons:
        submit:
          type: submit
          value: Submit
        reset:
          type: reset
          value: Reset

    process:
        email:
          from: "{{ config.plugins.email.from }}"
          to:
            - "{{ config.plugins.email.to }}"
            - "{{ form.value.email }}"
          subject: "[Feedback] {{ form.value.name|e }}"
          body: "{% include 'forms/data.html.twig' %}"
        save:
          fileprefix: feedback-
          dateformat: Ymd-His-u
          extension: txt
          body: "{% include 'forms/data.txt.twig' %}"
        message: Danke für die Aufgabe!

---

# Aufgabe einsenden

Vielen Dank für das Einsenden einer Aufgabe. Ein paar wenige Infos:

- Die mit Stern <span class="required">*</span> gekennzeichneten Felder müssen ausgefüllt werden.
- Aufgabenstellung und Lösung gerne [als Latex formatiert](latex-referenz), sonst als Text.
