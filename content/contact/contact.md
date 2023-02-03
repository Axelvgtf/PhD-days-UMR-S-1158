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
  address:
    street: 83 Bd de l'Hôpital
    city: Paris
    region: 
    postcode: '75013'
    country: France
    country_code: US
  coordinates:
    latitude: '48.836705'
    longitude: '2.364828'
  office_hours:
    - 'Mardi 28 Mars 08:00 - 18:00'
    
  appointment_url: 'https://calendly.com'
  

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

