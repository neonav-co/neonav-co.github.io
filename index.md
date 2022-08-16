---
layout: home
header:
  title: A new way to navigate websites
  text: >
    Neo Workspace is a smart tiling window manager for your websites, allowing you to view their contents simultaneously without switching tabs and to organize them with multiple workspaces.
  action: # action button is optional
    label: Find Out More
    url: '#features'
    class: btn-light


sections:
  - type: services.html
    section_id: features
    # background_style: bg-info
    title: Feature Summary
    services:
      - title: Tiling Windows
        text: Use tiling windows to view websites instead of tabs. Split them vertically and horizontally with one click
        icon: fa-window-maximize text-info
      - title: Password Autofill
        text: Build-in password manager allowing you to log in to sites and fill forms securely and easily. Rest assured that you passwords are encrypted and stored on your device only
        icon: fa-key text-success
      - title: Flexible layout
        text: Create as many windows as you want, resize them, and drag and drop them around to create the layout you prefer in your workspaces
        icon: fa-table-columns text-info
      - title: Multiple Workspaces
        text: Group your websites into different workspaces and switch the context easily
        icon: fa-layer-group text-primary
      - title: Data Auto Saving
        text: Everything in your workspace is automatically saved, be it the websites you are viewing, the size and location of the windows. You can start from exactly where you left off.
        icon: fa-box-archive text-success
      - title: Dark Theme 
        text: Simple yet intuitive user interface removing all the clutter for you, with one click to toggle between light and dark them.
        icon: fa-circle-half-stroke text-dark

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Tiling windows
        text: Four tiling windows, with three showing info about stocks information and one taking notes
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: tiles.png
        url: '#'
      - title: Drag and drop windows
        text: Drag the window around and drop it anywhere you see fit
        icon: drag-drop.png
        url: '#'
      - title: Multiple workspaces
        text: You can create multiple workspaces and quickly switch among them with one click
        icon: multi-workspaces.png
        url: '#'
      - title: Password saving and autofill 
        text: Prompt you to save the password
        icon: save-password.png
        url: '#'

  - type: download.html

  - type: contact.html
    section_id: contacts
    title: Let's Get in Touch!
    text: >-
      Want more features or need some help? Send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: E-Mail
      icon: fa-envelope
      url: mailto:support@neonav.co
    - title: Twitter
      icon: fa-twitter
      icon_type: fab
      url: 'https://twitter.com/neonav_co'

---
