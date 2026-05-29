---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
          # Providing manual colors forces the engine to change from default colors to sea colors:
          colors:
            - "#002b49"  # Deep Abyssal Blue
            - "#004b6e"  # Deep Sea Navy
            - "#007a99"  # Marine Teal
            - "#33a6cc"  # Shallow Water Cyan
      name:
        size: sm
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      #background:
      #  gradient_mesh:
      #    enable: true

      # Name heading sizing to accommodate long or short names
      #name:
      #  size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
---
