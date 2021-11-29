---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¡Hola! Muchas gracias por su interés en trabajar juntos. Por favor
      complete el formulario de contacto a continuación.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Favor escoger
        options:
          - Error en el sitio
          - Patrocinio
          - Otros
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que puedan ser contactados.
    submit_label: Enviar Mensaje
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
