---
title: Blog
sections:
  - type: hero_section
    title: Let's Talk!
    subtitle: Here are some discussions you might be interested in.
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    show_date: false
    show_categories: false
    show_author: false
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
    title: Recent Posts
    category: src/data/categories/tips.yaml
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
  - title: lorem-ipsum
    subtitle: lorem-ipsum
    actions: []
    blog_feed_cols: three
    enable_cards: false
    show_recent: false
    recent_count: 0
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    show_image: true
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: blog_feed_section
seo:
  type: stackbit_page_meta
  title: Lake City Coaching Blog
  description: This is the blog page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Lake City Coaching Blog
      keyName: property
    - name: 'og:description'
      value: This is the blog page
      keyName: property
    - name: 'og:image'
      value: images/lakecitylogo_xs.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Lake City Coaching Blog
    - name: 'twitter:description'
      value: This is the blog page
    - name: 'twitter:image'
      value: images/lakecitylogo_xs.png
      relativeUrl: true
template: advanced
---
