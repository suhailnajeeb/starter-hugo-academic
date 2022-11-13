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
#  form:
#    provider: netlify
#    formspree:
#      id:
#    netlify:
#      # Enable CAPTCHA challenge to reduce spam?
#      captcha: false

  # Contact details (edit or remove options as required)
  email: suhailnajeeb@proton.me
  # phone: 888 888 88 88
  address:
    street: University of Melbourne
    city: Melbourne
    region: VIC
    postcode: '3010'
    country: Australia
    country_code: AU
  coordinates:
    latitude: '-37.7983'
    longitude: '144.9610'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Mon-Fri 9:00 to 17:00'
  appointment_url: 'https://calendly.com/suhailnajeeb'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: twitter
      link: 'https://twitter.com/najeeb_suhail'
#    - icon: video
#      icon_pack: fas
#      name: Zoom Me
#     link: 'https://zoom.com'

design:
  columns: '2'
---
