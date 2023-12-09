---
title: Team members
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   5 = Showcase


# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: Principal Investigator
      subtitle: Alberto Maspero
      text: 
  - block: markdown
    id: section-2
    content:
      title: Postdocs
      subtitle: A subtitle
      text: Add your Section 2 content here...

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
---