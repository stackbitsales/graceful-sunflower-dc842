---
title: Home
layout: PageLayout
sections:
  - elementId: ''
    colors: colors-f
    title: This Is A Big Hero Headline
    subtitle: The section subtitle
    badge:
      label: This is the badge
      elementId: ''
      styles:
        self:
          textAlign: left
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: /
        style: secondary
    media:
      type: ImageBlock
      url: /images/livelikeakng.png
      altText: 'Budweiser - Live Like a King - Win $1,000,000'
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-0
          - pb-0
          - pl-0
          - pr-0
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection Full
  - colors: colors-a
    elementId: home-products
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Budweiser
        text: |
          Budweiser is a medium-bodied, flavorful, crisp American-style lager.
        featuredImage:
          url: /images/budweiser_home-desktop.png
          altText: Budweiser Beer Bottle
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: center
        actions:
          - label: CHECK IT OUT
            altText: ''
            url: /
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
            type: Button
      - type: FeaturedItem
        title: Budweiser Zero
        text: >
          Budweiser Zero, an alcohol free brew with the taste of Budweiser at
          only 50 calories and zero grams of sugar.
        featuredImage:
          url: /images/bud-zero_home-desktop.png
          altText: Budweiser Zero Can
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: center
        actions:
          - label: CHECK IT OUT
            altText: ''
            url: /
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
            type: Button
      - type: FeaturedItem
        title: Budweiser Select
        text: >
          Select from Budweiser has the full beer flavor you love, but with the
          calories and refreshment of a light beer.
        featuredImage:
          url: /images/bud-select_home-desktop.png
          altText: Budweiser Select Can
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: center
        actions:
          - label: CHECK IT OUT
            altText: ''
            url: /
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: secondary
            elementId: ''
            type: Button
    actions: []
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedItemsSection
    title: OUR PRODUCTS
  - colors: colors-a
    elementId: home-bottom
    subtitle: ''
    items:
      - type: FeaturedItem
        featuredImage:
          url: /images/Budweiser_Desktop_Heritage_BuyBeer.jpg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: center
            padding:
              - pr-5
        actions: []
        text: |
          ### Find a Bud Near Your

          [BUY BEER](/)
      - type: FeaturedItem
        featuredImage:
          url: /images/Budweiser_Desktop_Heritage_BuyGear.jpg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          self:
            textAlign: center
            padding:
              - pl-5
        actions: []
        text: |
          ### Shop Bud Merch

          [Shop Gear](/)
    actions: []
    columns: 2
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedItemsSection
---
