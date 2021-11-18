---
title: Home
sections:
  - type: hero_section
    title: 'Hey, I’m Megan'
    subtitle: >-
      A dentist, originally from Belfast, now located in the North East of
      England. Having graduated in 2016 from the University of Glasgow I now
      have over 5 years professional experience in a vast range of dental
      treatments.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: /images/megan.jpeg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: grid_section
    title: Trusted by Companies Big and Small
    subtitle: Who I work with
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Logo 1
        image_align: center
      - image: images/logo-2.svg
        image_alt: Logo 2
        image_align: center
      - image: images/logo-3.svg
        image_alt: Logo 3
        image_align: center
      - image: images/logo-4.svg
        image_alt: Logo 4
        image_align: center
      - image: images/logo-5.svg
        image_alt: Logo 5
        image_align: center
      - image: images/logo-6.svg
        image_alt: Logo 6
        image_align: center
      - image: images/logo-7.svg
        image_alt: Logo 7
        image_align: center
      - image: images/logo-8.svg
        image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: features_section
    title: My treatments
    subtitle: What I do
    features:
      - title: Composite Bonding
        subtitle: Affordable teeth restoration
        content: >
          Composite bonding is the process of colour matching and restoring a
          tooth with composite ensuring a natural blend with the colour of your
          teeth. It can be carried out in a single session and is an affordable
          alternative to veneers. This is a discreet and minimally invasive
          method of repairing a damaged (cracked/chipped) or misshapen tooth.
        actions:
          - label: Get in touch
            url: /contact
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/cracktooth.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
        align: left
      - title: Advanced Facial Aesthetics & Medical Skincare
        subtitle: 'Product updates, inventory and pricing.'
        content: >-
          Managing an online business is a full-time job. I will make sure your
          products look great, sound great, and sell more on your choice of
          ecommerce platform.
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/botox.svg
        image_alt: Feature 2 illustration
        media_position: left
        media_width: sixty
      - title: Tooth Straightening & Whitening
        subtitle: 'Your products and services, at scale.'
        content: >-
          I will dive into the ins and outs of your product or service and make
          sure the right information is communicated throughout your
          documentation, pamphlets, manuals and technical documents.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Testimonials
    subtitle: What My Clients Say
    grid_items:
      - content: |
          Can't believe I didn't get them done sooner! Thank you so much!

          **A.W**- 14 September 2021
        image: /images/logo (1)-c4c8a96f.svg
        image_position: left
        image_width: twenty-five
      - content: >
          Megan you are amazing at what you do! I can't wait to come back for my
          next treatment, it's the best service I've had! Thank you


          **ANON** - 2 August 2021
        image: /images/logo (1)-c4c8a96f.svg
        image_position: left
        image_width: twenty-five
      - content: >
          I recommend Megan highly. She is so lovely and always keeps in touch
          between appointments... IO used to fear the dentist and now I love it!


          **S.M** - 22 October 2020
        image: /images/logo (1)-c4c8a96f.svg
        image_position: left
        image_width: twenty-five
      - content: >
          Megan was so lovely with me. She explained every bit of the process
          and didn't make me feel embarrassed about the state of my teeth.


          **K.M** - 12 October 2020
        image: /images/logo (1)-c4c8a96f.svg
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
    section_id: testimonials
  - type: form_section
    content: >
      ## Treatment Enquiries


      If you would like more information about my treatments and pricing, please
      contact me using this form.


      ## Testimonials


      If you would like to submit a testimonial to be features on my website /
      social pages please use this form.


      ## Response Time


      I aim to respond to all queries within 48 business hours, however during
      busy periods and holidays this may not always be possible.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
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
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
    section_id: contact-us
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
