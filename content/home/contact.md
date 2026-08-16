---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: alexander.tolbert@emory.edu
  address:
    street: 36 Eagle Row, 5th Floor, PAIS 570
    city: Atlanta
    region: GA
    postcode: '30322'
    country: United States
    country_code: US
  directions: Department of Data and Decision Sciences, Emory University
  office_hours:
    - 'To be determined'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/xanderdoesphil?lang=en'

design:
  columns: '2'
---
