---
type: PageLayout
title: About
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: ABOUT
      color: text-dark
    subtitle: ''
    text: >
      ****![](/images/IMG-20250228-WA0035.jpg)


      **Hugging Clouds Guest House** is a cozy and scenic guesthouse located
      near **Adam's Peak** in Sri Lanka, specifically in the town of
      **Dalhousie** (also known as Nallathanniya). It has become a place to stay
      for people who are planning to hike Adam’s Peak, a famous pilgrimage site
      known for its stunning sunrise and the sacred footprint. The guesthouse is
      situated in a peaceful, serene environment, surrounded by lush greenery
      and misty clouds, hence the name "Hugging Clouds." It provides stunning
      views of the surrounding mountains and forests, making it an ideal spot
      for nature lovers.


      *   **Accommodation**:


      We provides simple, clean, and comfortable rooms. The accommodation
      options are often basic but cozy, with modern amenities to ensure a
      comfortable stay. Rooms often have large windows with beautiful views of
      the surrounding scenery, which adds to the charm of staying here.


      *   **Hospitality & Service**:


      The staff at Hugging Clouds is known for being friendly and welcoming.
      They typically provide guests with useful information about the Adam's
      Peak trek, including the best time to start the hike and what to expect
      along the way. also hugging clouds offers meals, and many guests recommend
      trying the home-cooked food, which is a great way to experience local Sri
      Lankan flavors.


      *   **Booking & Availability**:


      Since Hugging Clouds is a small guesthouse, it’s often advisable to book
      in advance, especially during peak pilgrimage seasons (typically from
      December to May).
    actions:
      - type: Button
        label: BOOK NOW
        altText: ''
        url: >-
          /www.booking.com/searchresults.en-gb.html?aid=318615&label=New_English_EN_SG_20153755105-ZwsmidGEETVW79m3dWtGeAS217272541619%3Apl%3Ata%3Ap1%3Ap2%3Aac%3Aap%3Aneg&gclid=Cj0KCQiA2oW-BhC2ARIsADSIAWrq2-4tbJrWkZRKIDGFvCmDibIJvbROngjlp5a8QHBeIa7FfFDvIQMaAne-EALw_wcB&highlighted_hotels=1673282&redirected=1&city=900052927&hlrd=no_dates&source=hotel&expand_sb=1&keep_landing=1&sid=549a6e87dfd8243b005a62db72800999
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    media:
      type: ImageBlock
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Featured items section subtitle
    items:
      - type: FeaturedItem
        title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Learn from the tutorial and build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
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
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /about
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---
