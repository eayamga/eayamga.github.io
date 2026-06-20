---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: 'Do Front-of-Package Sugar Labels Shift Consumer Demand away from Diabetes-Risk Foods'
      text: |-
        This paper evaluates the impact of a U.S. front-of-package (FOP) sugar labeling policy on consumer demand for ready-to-eat (RTE) cereals. Using NielsenIQ retail scanner data and a difference-in-differences design, we find no evidence of product reformulation or significant demand shifts around the 5- and 10-gram added sugar thresholds following the introduction of the table-format FOP label. Although we detect a modest substitution pattern beginning around 7.5 grams of added sugar, the magnitude is economically small and unlikely to meaningfully affect diet-related health outcomes. To rationalize these limited effects, we develop and estimate a structural Berry–Levinsohn–Pakes (BLP) demand model augmented with a rational inattention framework in which information processing costs enter utility directly. We allow the cost of processing nutritional information to vary by label format, with the highest cost associated with table-format labels, followed by letter-grade labels, color-grade labels, and the lowest cost for warning labels. Structural estimates indicate that high information-processing costs substantially attenuate the effectiveness of table-format labels. Counterfactual simulations show that simplified formats particularly warning labels significantly reduce demand for high-sugar cereals and generate welfare gains. Overall, our findings suggest that reducing cognitive costs through simplified FOP designs can meaningfully improve consumer welfare and shift consumption away from unhealthy products. [Dowload](https://dx.doi.org/10.2139/ssrn.5784502)

    subtitle: 'Forecasting the future: applying Bayesian model averaging for exchange rates drivers in Ghana'
    text: |-
    Exchange rate forecasts and stability have been a challenge for developing economies. This study analyses the possible exchange rate predictors in Ghana that are needed for policymaking. We perform an out-of-sample exchange rate forecast for the Ghana Cedis (GHS) per the United States dollar (USD) and the Euro (EUR) and the nominal effective exchange rate (NEER) using the Bayesian model averaging for 1, 3 and 6-month horizons. We observed that domestic predictors largely drive the exchange rates in Ghana with the stock market index and fiscal operations exhibiting the strongest predictive power followed by the Taylor rule, and the real economic sector. Moreover, there is an international spillover from the US economy to Ghana’s exchange rate. Finally, we noticed that forecast accuracy improved at the 3-month-ahead. [Download](https://doi.org/10.1080/00036846.2024.2339188)
       
    design:
      columns: '2'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300'
        css_style: ''
---
