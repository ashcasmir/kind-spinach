---
title: Contact
sections:
  - type: section_contact
    section_id: contact
    title: Contact Us
    content: >
      Do you want to increase sales to your business, or do you want to build an
      offers program for your customers? 


      Let's talk!
    background: gray
    form_id: contactForm
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        is_required: true
      - type: form_field
        input_type: email
        name: email
        label: Email
        is_required: true
      - type: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - I want to increase my sales
          - I want to build more rewards / offers for my customers
      - type: form_field
        input_type: textarea
        name: message
        label: Message
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
seo:
  type: stackbit_page_meta
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
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: landing
---
