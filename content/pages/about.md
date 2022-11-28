---
title: About Ayam Secure Cloud
layout: PageLayout
sections:
  - type: HeroSection
    elementId: ''
    colors: colors-a
    title: About
    subtitle: Ayam Secure was founded by Jay Kannaiyan and has a primary mission of enabling people to take control of their personal data.
    media:
      type: ImageBlock
      url: /images/privacy.jpg
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: Contact us
    text: We'll respond as soon as we can.
    form:
      type: FormBlock
      variant: variant-a
      elementId: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: first-name
          label: Your first name
          hideLabel: true
          placeholder: First name
          isRequired: false
          width: 1/2
        - type: TextFormControl
          name: last-name
          label: Your last name
          hideLabel: true
          placeholder: Last name
          isRequired: false
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Your email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextFormControl
          name: address
          label: Your address
          hideLabel: true
          placeholder: Address
          isRequired: false
          width: full
      submitLabel: Submit
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-24
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: center
      text:
        textAlign: center
    type: ContactSection
---
