---
title: Programs
sections:
  - type: hero_section
    title: My Programs
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
    subtitle: Designed to fit and improve your life
    background_image: /images/20170702_171101.jpg
    background_image_repeat: no-repeat
    background_image_opacity: 40
  - type: blog_feed_section
    blog_feed_cols: two
    enable_cards: true
    show_recent: false
    category: src/data/categories/programs.yaml
    show_date: false
    show_categories: false
    show_author: false
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: Subscribe to our newsletter to make sure you don’t miss anything
    title_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
    submit_label: Subscribe
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
seo:
  type: stackbit_page_meta
  title: Posts in Programs
  description: This is the category archive page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Posts in Programs
      keyName: property
    - name: 'og:description'
      value: This is the category archive page
      keyName: property
    - name: 'og:image'
      value: images/post-2.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Posts in Programs
    - name: 'twitter:description'
      value: This is the category archive page
    - name: 'twitter:image'
      value: images/post-2.jpg
      relativeUrl: true
template: advanced
---
