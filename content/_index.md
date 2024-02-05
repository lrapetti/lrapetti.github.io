---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lrapetti
      # Override your bio text from `authors/lrapetti/_index.md`?
      text:
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Robotics Engineer
          company: Lab0
          company_url: 'https://www.lab0.com/'
          # company_logo: iit
          # location: Genoa, Italy
          date_start: '2024-01-01'
          date_end: ''
          description:
        - title: Postdoctoral Researcher
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2023-01-01'
          date_end: '2023-12-31'
          description:
        - title: PhD Fellow
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2019-01-01'
          date_end: '2022-12-31'
          description:
        - title: Research Fellow
          company: Istituto Italiano di Tecnologia
          company_url: 'https://www.iit.it/'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2018-05-01'
          date_end: '2018-12-31'
          description:
        - title: Graduate Research Fellow
          company: University of Illinois College of Medicine
          company_url: 'https://medicine.uic.edu/'
          company_logo: uic
          location: Chicago, US
          date_start: '2016-09-01'
          date_end: '2017-05-31'
          description: 
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: lorenzo.rapetti@lab0.com
      # Automatically link email and phone or display as text?
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
