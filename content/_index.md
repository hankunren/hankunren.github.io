---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: showcase
      columns: '1'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: card
      spacing:
        padding: ['20px', '0', '0', '0']
  - block: collection
    content:
      title: 
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation
      spacing:
        padding: ['0', '0', '20px', '0']
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '1'
      view: compact
  - block: contact
    id: contact
    content:
      title: contact
      # Contact (add or remove contact options as necessary)
      email: han.ren@eng.ox.ac.uk
      address:
        street: Department of Engineering Science, University of Oxford, Parks Road
        city: Oxford
        region: Oxfordshire
        postcode: 'OX1 3PJ'
        country: United Kingdom
        country_code: UK
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '51.76025'
        longitude: '-1.25966'  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '1'
---
