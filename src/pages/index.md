---
title: Home
sections:
  - type: heroblock
    title: 'Hi, This is my development blog.'
    section_id: hero
    component: HeroBlock
    content: >-
      This is my space to document, and explain to myself, what I have learned
      and any thoughts I need to see written down.




      This site was built using Stackbit, Gatsby and Netlify CMS. I dont profess
      to fully understand everything thats going on behind the curtain here, but
      I hope to learn as I go and eventually make this my own.
  - view_all_text: View All
    num_projects_displayed: 6
    section_id: latest-projects
    view_all_url: portfolio/index.html
    subtitle: An optional subtitle of the section
    title: Recent Work
    type: portfolioblock
    layout_style: mosaic
    component: PortfolioBlock
  - type: postsblock
    title: Latest from the Blog
    section_id: latest-posts
    component: PostsBlock
    subtitle: An optional subtitle of the section
    num_posts_displayed: 2
    actions:
      - label: View Blog
        url: blog/index.html
  - type: contactblock
    title: Contact Us
    section_id: contact
    component: ContactBlock
    subtitle: An optional subtitle of the section
menus:
  main:
    title: Home
    weight: 1
template: home
---
