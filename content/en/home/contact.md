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
      captcha: true

  # Contact details (edit or remove options as required)
  email: jkliting@163.com
  phone: 156 9474 6038
  address:
  #  street: 450 Serra Mall
    city: 呼和浩特
    region: 内蒙古
  #  postcode: '94305'
  #  country: United States
  #  country_code: US
  coordinates:
    latitude: '40.8183'
    longitude: '111.6708'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---