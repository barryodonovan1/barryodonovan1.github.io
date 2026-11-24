---
title: 'Projects'
date: 2024-05-19
type: landing

# Hidden for now: don't build this page or anything under it.
# Delete these build/cascade lines (and uncomment the menu entry) to bring it back.
build:
  render: never
  list: never
cascade:
  build:
    render: never
    list: never
    publishResources: false

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
