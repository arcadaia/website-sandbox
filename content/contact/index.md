---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        For collaborations and join the lab please contact:
      email: vishalja@andrew.cmu.edu
      phone: 888 888 88 88
      address:
        street: 4400 Fifth Avenue 
        city: Pittsburgh
        region: PA
        postcode: '15213'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.44678'
        longitude: '-79.95111'
      directions: Enter Building and go to the lobby to get lift and then go to Office 166A on Floor 1
      office_hours:
        - 'Monday-Friday 9:00 to 18:00'

      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
