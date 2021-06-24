---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: To get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Job offer
          - 'I need your help '
          - Blog comments
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact Ivan De Martino
  description: >-
    If you need help with Digital Marketing for your indie Video Game. Don't
    hesitate to contact me.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact Ivan De Martino
      keyName: property
    - name: 'og:description'
      value: >-
        If you need help with Digital Marketing for your indie Video Game. Don't
        hesitate to contact me.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact Ivan De Martino
    - name: 'twitter:description'
      value: >-
        If you need help with Digital Marketing for your indie Video Game. Don't
        hesitate to contact me.
    - name: 'og:image'
      value: images/contact.PNG
      keyName: property
      relativeUrl: true
    - name: 'twitter:image'
      value: images/contact.PNG
      keyName: property
      relativeUrl: true
layout: advanced
---
