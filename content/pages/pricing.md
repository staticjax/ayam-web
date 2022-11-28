---
title: Pricing for Ayam Secure Cloud
layout: PageLayout
sections:
  - type: HeroSection
    elementId: ''
    colors: colors-a
    title: Pricing Plans
    subtitle: Pick the package that suits your needs. Contact us if you have custom requirements.
    # media:
    #   type: ImageBlock
    #   url: /images/hero-4.jpg
    #   altText: Hero section image
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
        flexDirection: col
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  - type: FeaturedItemsSection
    colors: colors-a
    elementId: ''
    title:
    subtitle:
    items:
      - type: FeaturedItem
        title: Secure Basic
        subtitle: Perfect for getting started for a single user.
        text: >+
          Includes:


          ✓ 1 User


          ✓ BitWarden Password Manager


          ✓ NextCloud with 10 GB File Storage 


        text2: sample test
        featuredImage:
          url: /images/diy1.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions:
          - type: Button
            label: Buy Basic for $4/month
            url: /
            style: primary
        styles:
          self:
            textAlign: left
            borderColor: border-tertiary
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Secure Premium
        subtitle: Ideal for couples, families, and small teams.
        text: >
          Includes:


          ✓ 3 Users


          ✓ BitWarden Password Manager


          ✓ NextCloud with 1 TB File Storage

        featuredImage:
          url: /images/cloud.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions:
          - type: Button
            label: Buy Premium for $20/month
            url: /
            style: primary
        styles:
          self:
            textAlign: left
            borderColor: border-tertiary
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Secure Custom
        subtitle: Custom plan to suit your needs.
        text: >
          Includes:


          ✓ Custom Users


          ✓ BitWarden Password Manager


          ✓ NextCloud with up to 100 TB File Storage

        featuredImage:
          url: /images/locked.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        actions:
          - type: Button
            label: View All Services
            url: /
            style: primary
        styles:
          self:
            textAlign: left
            borderColor: border-tertiary
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
    columns: 3
    enableHover: false
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
          - pt-20
          - pb-20
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start

  - elementId: contact-form
    colors: colors-f
    backgroundSize: inset
    title: Not seeing the right package? Contact us.
    text: We can customize our offering to suit your needs. Get in touch.
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
