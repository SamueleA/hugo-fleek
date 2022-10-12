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
  # Contact (add or remove contact options as necessary)
  email: test@example.org
  phone: 888 888 88 88
  appointment_url: 'https://calendly.com'
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: '94305'
    country: United States
    country_code: US
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  contact_links:
  - icon: twitter
    icon_pack: fab
    name: DM Me
    link: 'https://twitter.com/Twitter'
  - icon: skype
    icon_pack: fab
    name: Skype Me
    link: 'skype:echo123?call'
  - icon: video
    icon_pack: fas
    name: Zoom Me
    link: 'https://zoom.com'

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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim. Aenean non pretium metus. Proin mauris quam, euismod tincidunt consequat eu, consequat sed velit.
