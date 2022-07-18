---
# An instance of the Contact widget.
widget: contact

# Activate this widget? true/false
active: true

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
  email: jgourdine@lclark.edu
  phone: 503 768 7531
  address:
    615 S Palatine Hill Rd
    city: Portland
    region: OR
    postcode: '97219'
    country: United States
    country_code: US
  coordinates:
    latitude: '45.45142505491972'
    longitude: '-122.66752210202921'
  directions: OLIN 223
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'bit.ly/OfficeHoursJPG'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/docteurjayp'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'bit.ly/DrJPZoom'

design:
  columns: '2'
---
