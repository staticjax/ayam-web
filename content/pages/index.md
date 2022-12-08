---
title: Ayam Secure
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: 'Your Data in a Private Cloud.'
    subtitle: 'Your personal data is only truly secure and private when it is on your terms. Take back control of your passwords, files, messaging, email, and more. Then you can really say "Ayam Secure".'
    actions:
      - type: Button
        label: Get Started
        url: /#featured-items
        style: primary
      - type: Link
        label: Learn More
        url: /#bitwarden
        showIcon: true
        icon: arrowRight
        iconPosition: right
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
          - pt-20
          - pb-10
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  - type: FeatureHighlightSection
    elementId: 'sub-section-1'
    colors: colors-a
    title: 'If you are not paying, then you are the product.'
    text: >
      Free digital services from Google, Facebook, Yahoo, Dropbox, etc. make our lives very convenient but you're paying by giving up your attention and personal information. It doesn't have to be like this. You can extricate yourself from proprietary technology and leverage open source software to get similar services that are secure and private.
    actions:
      - type: Link
        label: Learn More
        url: /#bitwarden
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/vector-product.jpg
      altText: Hero section image
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
          - pt-10
          - pb-10
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  - type: FeatureHighlightSection
    elementId: 'sub-section-2'
    colors: colors-a
    title: Own your data.
    text: >
      It seems daunting but you can progress towards data ownership by taking small steps. Start with your passwords (move from LastPass to Bitwarden), then maybe your files (move from Google Drive, Dropbox to Nextcloud), then maybe messaging (move from Whatsapp to Matrix/Element), then maybe email (move from gmail to docker-mailserver).
    actions:
      - type: Link
        label: Learn More
        url: /#bitwarden
        showIcon: true
        icon: arrowRight
        iconPosition: right
    media:
      type: ImageBlock
      url: /images/vector-secure.jpg
      altText: Hero section image
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
          - pt-10
          - pb-10
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start

  # - type: FeatureHighlightSection
  #   elementId: 'sub-section-3'
  #   colors: colors-a
  #   title: 'Leverage Open Source Software.'
  #   text: >
  #     For file and photo sync, use Nextcloud.
  #     For password management, use Bitwarden.
  #     For private messaging, use Matrix / Element.
  #     For email, use Docker-Mailserver and RoundCube.
  #     For encrypted notes, use Standard Notes.
  #   actions:
  #     - type: Link
  #       label: Learn More
  #       url: /#bitwarden
  #       showIcon: true
  #       icon: arrowRight
  #       iconPosition: right
  #   media:
  #     type: ImageBlock
  #     url: /images/vector-opensource.jpg
  #     altText: Hero section image
  #   styles:
  #     self:
  #       height: auto
  #       width: wide
  #       margin:
  #         - mt-0
  #         - mb-0
  #         - ml-0
  #         - mr-0
  #       padding:
  #         - pt-10
  #         - pb-10
  #         - pl-4
  #         - pr-4
  #       alignItems: center
  #       justifyContent: center
  #       flexDirection: row-reverse
  #     title:
  #       textAlign: left
  #     subtitle:
  #       textAlign: left
  #     text:
  #       textAlign: left
  #     actions:
  #       justifyContent: flex-start

  - type: FeatureHighlightSection
    elementId: 'bitwarden'
    colors: colors-f
    backgroundSize: inset
    title: Why Bitwarden?
    text: >
      Your online world revolves around passwords. To stay safe from data breaches, you need to create strong and unique passwords for every account, but remembering them all without help gets tricky.


      Using an open source password manager like Bitwarden lets you easily protect yourself and your data. Bitwarden generates, stores, and secures your most important digital assets in an end-to-end encrypted vault.
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
      Your modern digital life revolves around important personal documents that should be kept private and stored securely. Keeping these documents on your personal computer isn't a foolproof solution as you may lose that device. Today, it is best practice to backup your documents to a secure cloud storage solution.


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

  - type: FeaturedItemsSection
    colors: colors-a
    elementId: 'featured-items'
    title: Choose your path to data ownership
    subtitle: >-
      We believe that data ownership is a fundamental human right. Unfortunately it is not free but it is affordable.
    items:
      - type: FeaturedItem
        title: Do It Yourself Cloud
        text: >
          Spin up a linux server and run the recommended open source projects via Docker containers. We have excellent documentation to enable you but you will need to have some experience with linux.
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
          - type: Link
            label: View Documentation
            url: /
            showIcon: true
            icon: chevronRight
            iconPosition: right
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
        title: Ayam Secure Cloud
        text: >
          Let us manage the software services on our secure and private cloud and you pay for what you use with no vendor lock-in. All our services are secure and can be end-to-end encrypted if you need it.
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
          - type: Link
            label: View Pricing
            url: /pricing
            showIcon: true
            icon: chevronRight
            iconPosition: right
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
        title: Custom Cloud
        text: >
          For maximum security, you should own the server and other resources and control access but we can help you get started with configuration and provide on-going support on a custom basis.
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
          - type: Link
            label: Request Quote
            url: /contact
            showIcon: true
            icon: chevronRight
            iconPosition: right
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

  - type: MediaGallerySection
    colors: colors-h
    subtitle: Standing on the shoulders of these great open source projects
    elementId: ''
    images:
      - type: ImageBlock
        url: /images/nextcloud.svg
        altText: Apple
        caption: Apple
      - type: ImageBlock
        url: /images/bitwarden.jpg
        altText: Google Play
        caption: Google Play
      - type: ImageBlock
        url: /images/ubuntu.png
        altText: PlayStation
        caption: PlayStation
      - type: ImageBlock
        url: /images/traefik-labs.svg
        altText: Gatsby
        caption: Gatsby
      - type: ImageBlock
        url: /images/docker.png
        altText: Xbox
        caption: Xbox
      - type: ImageBlock
        url: /images/lets-encrypt.png
        altText: Skype
        caption: Skype
      - type: ImageBlock
        url: /images/cloudflare.png
        altText: ZCOOL
        caption: ZCOOL
    spacing: 3
    columns: 7
    aspectRatio: 'auto'
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        margin:
          - mt-0
          - mb-0
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
    imageSizePx: 240

  - type: FeatureHighlightSection
    elementId: 'email'
    colors: colors-f
    backgroundSize: inset
    title: 'Coming soon: End-to-end Encrypted Email'
    text: >
      We are working on our private email service offering that uses open source, independently audited end-to-end encryption and zero-access encryption to secure your communications. This protects against data breaches and ensures no one (not even us) can access your inbox. Only you can read your messages.
    badge:
      type: Badge
      label: End-To-End Encrypted Email Service
      styles:
        self:
          textAlign: left
    actions:
      - type: Button
        label: Sign up for early access
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
      url: /images/email.png
      altText: Bitwarden
      caption: Bitwarden
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock

  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-a
    variant: variant-b
    title: Taking control of your data comes with the responsibility of learning about data privacy, data security, and data sovereignty.
    actions:
      - type: Link
        label: See all posts
        url: '/blog'
        showIcon: true
        icon: arrowRight
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
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
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    showDate: true
  - type: FaqSection
    colors: colors-f
    elementId: ''
    title: Need Answers?
    items:
      - question: Why is open source software better than proprietary software?
        answer: >-
          There's no definite reason as it depends on what you value. Gmail is proprietary software from Google and it's a really great email service. But we can't tell what Google is doing with all our email data. Open source means that the software source code is publicily available and anyone can inspect the code and determine what is being done when the software is running. This allows for greater security.
      - question: What's the difference between Ayam Secure Cloud and Custom Cloud?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: Do you offer a free trial?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How can I trust you with my data?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation. At the office, working together is often a
          distraction, on remote, it could be motivation. At the office, working
          together is often a distraction, on remote, it could be motivation.
      - question: Do you offer data migration services?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation. At the office, working together is often a
          distraction, on remote, it could be motivation. At the office, working
          together is often a distraction, on remote, it could be motivation.
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
        textAlign: left
      subtitle:
        fontWeight: '400'
        textAlign: center
    actions:
      - altText: ''
        url: /faq
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
        type: Link
        label: See all
  - type: TestimonialsSection
    elementId: ''
    colors: colors-a
    variant: variant-c
    testimonials:
      - quote: >
          It's been such a great experience migrating away from Google and Dropbox and finally feeling like I'm in control of my data.
        name: Carla Rogers
        title: Ayam Secure Cloud Customer
        image:
          type: ImageBlock
          url: /images/carla.jpg
          altText: Photo of Carla Rogers
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-20
          - pb-20
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - type: ContactSection
    colors: colors-f
    backgroundSize: inset
    title: Get early access
    text: >
      Sign up for our newsletter to be notified about new open source projects and other interesting happenings in data privacy.
    form:
      type: FormBlock
      variant: variant-b
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
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
          - ml-4
          - mr-4
        padding:
          - pt-20
          - pb-20
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
---
