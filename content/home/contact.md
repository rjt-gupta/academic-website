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
  email: rgupta415@gatech.edu
  address:
    street: 756 West Peachtree St NW, CODA Building, SSLab 5th floor
    city: Atlanta
    region: GA
    postcode: '30309'
    country: United States
    country_code: US
  #coordinates:
   # latitude: '37.4275'
    # longitude: '-122.1697'
  # directions: 
  # office_hours:
    # - 
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/z3ta_rjt'
    #- icon: video
     # icon_pack: fas
      #name: Zoom Me
      #link: 'https://zoom.com'

design:
  columns: '2'
---
