---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    


  - block: contact
    id: contact
    content:
      title: Contact
      text: If you want to contact me, please use the email address below directly.

      # Contact (add or remove contact options as necessary)
      email: chenyuanz(at)student(dot)unimelb(dot)edu(dot)au

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
      columns: '2'
---
