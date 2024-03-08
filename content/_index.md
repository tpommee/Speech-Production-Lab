---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: The Speech Production Lab
      text: |
      The Speech Production Lab (SPL) is housed in the Department of Speech-Language Pathology at Temerty Faculty of Medicine, University of Toronto and is directed by Prof. Yana Yunusova. 

      Our lab is dedicated to the study of normal and disordered aspects of speech motor control and to innovation in the assessment and rehabilitation of individuals with neurologic and neurodegenerative disorders affecting speech and orofacial motor control.

      We are also present at:
      - KITE – UHN: [KITE – UHN](https://kite-uhn.com/scientist/yana-yunusova)
    design:
      columns: '1'
  - block: portfolio
    id: research
    content:
      title: Research
      filters:
        folders:
          - research
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: ALSBDI
          tag: ALSBDI
        - name: UMNLMN
          tag: UMNLMN
        - name: SDM
          tag: SDM
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: portfolio
    id: tools
    content:
      title: Tools
      filters:
        folders:
          - tools
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: VSLP
          tag: VSLP
        - name: OPEX
          tag: OPEX
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: portfolio
    id: people
    content:
      title: People
      filters:
        folders:
          - people
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:       
      # Contact (add or remove contact options as necessary)
      phone: (416)-946-8637
      address:
        street: 160-500 University Avenue
        city: Toronto
        region: ON
        postcode: 'M5G 1V7'
        country: Canada
        country_code: CA
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '43.65581957734069'
        longitude: '-79.38895771287245' 
        
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
