---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: AI in Haptics
      text: "**Discuss the future of haptics with AI**"
      details: "July 08, 2025 \n\nIEEE World Haptics Conference"
      items:
        #- name: "Speakers"
        #  description: "300+"
        #- name: "Attendees"
        #  description: "4,000+"
        - name: "Venue"
          description: "Suwon Convention Center"
        - name: "Location"
          description: "Suwon, Korea"
      design:
        container_max_width: "10xl"
        css_style: |
          .prose {
            max-width: 100%;
            min-width: 100%;
          }
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: "Until the workshop:"
      # text_after: "SAVE UP TO $1,000!"
      date: '2025-07-08 14:00:00'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: The Era of AI
          text: Join us for this open workshop, where experts will explore the opportunities and challenges of AI-driven haptic research through engaging talks and discussions. We hope this workshop will provide valuable insights and knowledge about AI to the haptics community.
          # Upload image to `assets/media/` and reference the filename here
          image: 1.png
      design:
        spacing:
          padding: ["3rem", "3rem", "3rem", "3rem"]
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    id: organizer
    content:
      title: Organizer
      text: ""
      user_groups: ['Organizer']
    design:
      show_role: true
      show_social: true
      show_interests: false
  - block: people
    id: speakers
    content:
      title: Speakers
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: true
      show_interests: false
  - block: table
    id: agenda
  - block: logos
    content:
      title: "Sponsors Making This Possible"
      text: "Thanks to the following sponsors for making this incredible event possible!"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: newsletter
    content:
      title: "Stay up to date"
      text: "Be the first to receive conference updates"
      text_cta: "Sign up to our newsletter 🔥"
      button:
        text: "Subscribe"
      convertkit:
        form_id: ''
        msg_subscribed: "Success! Please check your email to confirm your subscription."
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
