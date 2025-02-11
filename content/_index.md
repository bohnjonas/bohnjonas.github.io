---
title: 'Jonas Bohn'
date: 2025-02-11
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_2025.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      title: Experience
      items:
       - title: 'Research Assistant'
         company: 'ETH Zurich'
         company_url: 'https://www.ethz.ch/en.html'
         company_logo: eth_logo_kurz_pos
         location: 'Zurich, Switzerland'
         date_start: '2021-09-19'
         date_end: '2025-02-19'
         description: |-
           - Conducting research in the field of robotics and machine learning
           - Developing algorithms for object detection and pose estimation
           - Collaborating with other researchers and students
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      columns: '2'
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: collection
    id: projects
    content:
      title: Selected Projects
      subtitle: ''
      text: 'Check out my recent projects below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - projects
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: article-grid
      # Choose single or dual column layout
      columns: 2
  - block: languages
    content:
      title: Languages
      username: admin
---
