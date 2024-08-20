---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Thiele Venture
      color: text-neutral
      type: TitleBlock
    subtitle: ''
    text: |
      Curating Trends, Delivering Dreams
    actions: []
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-32
          - pr-16
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-20
          - pb-20
          - pr-20
  - subtitle: Brands we represent
    images: []
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Thiele Venture
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >
      Thiele Venture is your destination for trendy consumer goods online. We
      blend innovation with quality by creating unique brands and dedicated
      stores for each product category. Our mission is to deliver the latest
      trends right to your doorstep, offering a seamless and inspiring customer
      experience. From home décor to fashion and electronics – we have
      everything to make your life easier and more stylish.
    badge:
      label: We deliver ecom
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - title:
      text: PixelPop
      color: text-dark
      type: TitleBlock
    subtitle: Est. 2024
    text: |
      More Than Photos, It's Your Memories
    actions:
      - label: Shop now
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: Coming soon
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Example
      color: text-dark
      type: TitleBlock
    subtitle: Est. ****
    text: |
      ExampleExampleExample
    actions:
      - label: Shop now
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: Comming soon
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: ''
      color: text-dark
      type: TitleBlock
    subtitle: >-
      We'd love to hear from you! Whether you have questions, feedback, or just
      want to say hello, feel free to reach out to us.
    text: |
      **Thiele Venture**
      Email: [douglas@thieleventure.com]()
      Phone: +46 76 918 36 52
      Address: Vagnsgatan 6, 177 48 Järfälla
      Org. Number: 041012-5751
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home
  metaDescription: Official site for Thiele Venture.
  socialImage: /images/main-hero.jpg
  type: Seo
  addTitleSuffix: true
type: PageLayout
---
