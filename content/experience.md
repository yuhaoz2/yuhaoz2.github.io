---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      background:
        color: '#F4F4F4' #black
        text_color_light: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      background:
        color: white #black
        text_color_light: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      background:
        color: '#F4F4F4' #black
        text_color_light: false
  - block: resume-service
    content:
      title: Services
      username: admin
    design:
      background:
        color: white #black
        text_color_light: false

  - block: markdown
    content:
      title: 'Services'
      subtitle: ''
      text: |
        - IEEE CDC 2021,2022,2023,2024, Reviewer 
        - ACC 2022,2023,2024, Reviewer 
        - IEEE L-CSS, Reviewer
        - IEEE TCST, Reviewer
        - Control Engineering Practice, Reviewer
    design:
      columns: '1'
      background:
        color: white #black
        text_color_light: false
  
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: admin
---
