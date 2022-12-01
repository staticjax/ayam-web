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

  - type: FeatureHighlightSection
    elementId: 'BitWarden'
    colors: colors-f
    backgroundSize: inset
    title: Why BitWarden?
    text: >
      Your online world revolves around passwords. To stay safe from data breaches, you need to create strong and unique passwords for every account, but remembering them all without help gets tricky.


      Using an open source password manager lets you easily protect yourself and your data. Bitwarden generates, stores, and secures your most important digital assets in an end-to-end encrypted vault.
    badge:
      type: Badge
      label: Encrypted Password Management
      styles:
        self:
          textAlign: left
    actions:
      - type: Button
        label: Get Started
        url: /#featured-items
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-0
          - mr-0
        padding:
          - pt-10
          - pb-10
          - pl-10
          - pr-10
        justifyContent: center
        flexDirection: row
        alignItems: center
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      url: /images/bitwarden1.png
      altText: Bitwarden
      caption: Bitwarden
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock

  - type: FeatureHighlightSection
    elementId: 'Nextcloud'
    colors: colors-f
    backgroundSize: inset
    title: Why Nextcloud?
    text: >
      Your modern digital life revolves around important personal documents that should be private and stored securely. Keeping these documents on your personal computer isn't a foolproof solution as you may lose that device. Today, it is best practice to backup your documents to a cloud storage solution.


      Using Nextcloud, the most popular open source file storage service, you can securely backup and sync your files and photos using end-to-end encryption. You can then access your documents from a secure web portal or via clients for your desktop or mobile phone.
    badge:
      type: Badge
      label: Encrypted File Storage
      styles:
        self:
          textAlign: left
    actions:
      - type: Button
        label: Get Started
        url: /#featured-items
        style: primary
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-0
          - mr-0
        padding:
          - pt-10
          - pb-10
          - pl-10
          - pr-10
        justifyContent: center
        flexDirection: row-reverse
        alignItems: center
        borderRadius: xx-large
        boxShadow: xx-large
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    media:
      url: /images/nextcloud1.png
      altText: Nextcloud
      caption: Nextcloud
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock

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
