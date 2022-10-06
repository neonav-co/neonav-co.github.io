---
layout: home
header:
  title: A browser built for large screens, multitasking and privacy
  text: >
    Neo Navigator allows you to view multiple web pages side by side in one window and multitask easily, it has build-in password manager, ads blocker, multi-workspace support, spellchecker and (a lot) more.
  action: # action button is optional
    label: Watch a quick demo
    url: '#demo'
    class: btn-light

sections:
  - type: demo.html
    # background_style: bg-light
    projects:
      - title: A quick demo
        text: Click to see the full size demo
        icon: neonav-demo.gif
        url: '#'
    action: # action button is optional
      label: Download
      url: '#download'
      class: btn-secondary

  - type: services.html
    section_id: features
    # background_style: bg-info
    title: Feature summary
    services:
      - title: Tiled Panes
        text: Use tiling panes to view websites instead of tabs. Split them vertically and horizontally with one click
        icon: fa-border-all text-info

      - title: Password Autofill
        text: Build-in password manager allowing you to log in to sites and fill forms securely and easily. Rest assured that you passwords are encrypted and stored on your device only
        icon: fa-key  text-secondary

      - title: Ads Shield
        text: Blocks all the annoying ads and trackers, giving you better privacy.
        icon: fa-shield text-success

      - title: Reader Mode
        text: Allows you read the essential content by removing webpage cluster e.g. graphics, banners and other superfluous elements
        icon: fa-book-open text-secondary

      - title: Multiple Workspaces
        text: Group your websites into different workspaces and switch the context from the sidebar.
        icon: fa-layer-group text-primary

      - title: Spellcheck
        text: Spell check the words and correct misspelled ones by selecting the suggestions in the context menu.
        icon: fa-spell-check text-warning

      - title: Flexible Layout
        text: Creates as many windows as you want, resize them, and drag and drop them around to create the layout you prefer in your workspaces
        icon: fa-table-columns text-info

      - title: Dark Theme 
        text: Simple yet intuitive user interface removing all the clutter for you, with one click to toggle between light and dark them.
        icon: fa-circle-half-stroke text-dark

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Tiled panes
        text: Four tiled panes, with three showing info about stocks information and one taking notes
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: tiles.png
        url: '#'
      - title: Drag and drop panes
        text: Drag the pane around and drop it anywhere you see fit
        icon: drag-drop.png
        url: '#'
      - title: Password saving and autofill 
        text: Prompt you to save the password
        icon: save-password.png
        url: '#'
      - title: Build-in password manager
        text: Manage you password easily with the build-in password manager
        icon: password-manager.png
        url: '#'
      - title: Spellcheck
        text: Spellcheck with suggestions in the context menu
        icon: spellcheck.png
        url: '#'
      - title: Keyboard shortcuts
        text: Manage your workspaces and navigate the panes with keyboard shortcuts
        icon: keyboard-shortcuts.png
        url: '#'
      

  - type: download.html

  - type: contact.html
    section_id: contacts
    title: Let's get in touch!
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
