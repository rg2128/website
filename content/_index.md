---
# Leave the homepage title empty to use the site title
title: 'Home'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/Resume_RG.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: FB_IMG_1721244062073.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
---
