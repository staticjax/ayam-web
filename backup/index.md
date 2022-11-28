---
title: Ayam Secure
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: 'Your Data in a Private Cloud.'
    subtitle: 'Your data is only truly secure and private when it is on your terms. Take back control of your files, passwords, messaging, email, and more. Then you can say "Ayam Secure".'
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
      - type: Link
        label: Learn More
        url: /
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
          - pb-20
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
      Free digital services from Google, Facebook, Yahoo, DropBox, etc. make our lives very convenient but you're paying by giving up your personal information. It doesn't have to be like this. You can extricate yourself from big tech and leverage open source software to get similar services that are secure and private.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Link
        label: Learn More
        url: /
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
          - pt-20
          - pb-20
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
      It seems daunting but you can progress towards data sovereignity by taking small steps. Start with your files, then maybe your passwords, then maybe finally email.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
      - type: Link
        label: Learn More
        url: /
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
          - pt-20
          - pb-20
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

  # - elementId: ''
  #   colors: colors-f
  #   backgroundSize: inset
  #   title: Where did everyone go?
  #   text: >
  #     Learn how top tech companies have learned working remote using our
  #     product.
  #   badge:
  #     type: Badge
  #     label: Case study
  #     styles:
  #       self:
  #         textAlign: left
  #   actions:
  #     - type: Button
  #       label: Get Started
  #       url: /
  #       style: primary
  #     - type: Link
  #       label: Watch Video
  #       url: /
  #       showIcon: true
  #       icon: playCircle
  #       iconPosition: left
  #   styles:
  #     self:
  #       height: auto
  #       width: wide
  #       margin:
  #         - mt-24
  #         - mb-0
  #         - ml-4
  #         - mr-4
  #       padding:
  #         - pt-16
  #         - pb-16
  #         - pl-16
  #         - pr-16
  #       justifyContent: center
  #       flexDirection: row
  #       alignItems: center
  #       borderRadius: xx-large
  #       boxShadow: xx-large
  #     title:
  #       textAlign: left
  #     subtitle:
  #       textAlign: left
  #     text:
  #       textAlign: left
  #     actions:
  #       justifyContent: flex-start
  #   type: FeatureHighlightSection
  #   media:
  #     url: /images/hero-3.jpg
  #     altText: Where did everyone go?
  #     caption: Team meeting
  #     elementId: ''
  #     styles:
  #       self:
  #         opacity: 100
  #     type: ImageBlock

  - type: FeaturedItemsSection
    colors: colors-a
    elementId: ''
    title: Choose your path to data sovereignity
    subtitle: >-
      We believe that data privacy is a fundamental human right. Unfortunately it's not free but it's affordable.
    items:
      - type: FeaturedItem
        title: Do-It-Yourself
        text: >
          Spin up a linux server and run these open source projects via Docker containers. We have excellent documentation to enable you but you will need to have some experience with linux.
        featuredImage:
          url: /images/diy1.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Ayam Secure SaaS
        text: >
          Let us manage the software services and you pay for what you use. All our services are secure and can be end-to-end encrypted if you need it.
        featuredImage:
          url: /images/cloud.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
      - type: FeaturedItem
        title: Private Cloud
        text: >
          You own the server and control access but we help you get started with configuration and provide on-going support.
        featuredImage:
          url: /images/locked.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: left
            borderColor: border-dark
            borderWidth: 1
            borderStyle: solid
            borderRadius: large
            padding:
              - pt-4
              - pl-4
              - pb-6
              - pr-4
    columns: 3
    enableHover: true
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
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-a
    variant: variant-b
    title: We sometimes write things. You should read it, it might shed some
      light on why we’re doing what we’re doing
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
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation, At the office, working together is often a
          distraction, on remote, it could be motivation, At the office, working
          together is often a distraction, on remote, it could be motivation
      - question: How is this different from what we have today?
        answer: >-
          At the office, working together is often a distraction, on remote, it
          could be motivation. At the office, working together is often a
          distraction, on remote, it could be motivation. At the office, working
          together is often a distraction, on remote, it could be motivation.
      - question: How is this different from what we have today?
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
    variant: variant-a
    testimonials:
      - quote: >
          Such a great experience to be using this product. It really helped
          with what I needed help with.
        name: Carla Rogers
        title: Happy customer
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
      Sign up your team today to be the first to try out our new product to
      increase your team’s productivity
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
