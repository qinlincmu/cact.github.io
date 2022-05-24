---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: z.gao@csuohio.edu
  phone: 216-687-3528
  address:
    street: Fenn Hall 320, 2121 Euclid Avenue
    city: Cleveland
    region: OH
    postcode: 'OH 44115'
    country: United States
    country_code: US
  coordinates:
    latitude: '41.5034'
    longitude: '-81.6728'
  directions: Enter Fenn Hall and take the elevator to Office 320 on Floor 3
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
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
---
Please leave your name, email, and brief messages.