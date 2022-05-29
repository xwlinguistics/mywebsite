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
  email: xuan.wang@ku.edu
  address:
    street: Department of Linguistics, Blake Hall, KU
    city: Lawrence
    region: Kansas
    postcode: '66046'
    country: United States
    country_code: US
  directions: Enter Blake Hall and take the lift to Office 428 on Floor 4
  office_hours:
    - 'Mondays 11:00 to 13:00'
  
design:
  columns: '2'
---
