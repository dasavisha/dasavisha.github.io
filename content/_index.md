---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-04-01
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
    # design:
    #   columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Fellow
          company: Arizona Advanced AI & Innovation (A3I) Hub, Mayo Clinic Arizona
          company_url: ''
          company_logo: ''
          location: Phoenix, Arizona
          date_start: '2023-11-01'
          date_end: ''
          description: |2-
              * Security and Clinical LLMs
              * Federated Learning and Critical Findings Retrieval
        - title: Postdoctoral Research Scholar
          company: School of Biomedical Informatics, University of Texas Health Science Center
          company_url: ''
          company_logo: ''
          location: Houston, Texas
          date_start: '2021-04-01'
          date_end: '2023-11-30'
          description: |2-
            * Conversational Agents for Psychotherapy and Emotional Support
            * Biomedical Literature Mining and Real-time Knowledge Distillation
        - title: Graduate Assistant 
          company: Computer Science, University of Houston
          company_url: ''
          company_logo: ''
          location: Houston, Texas
          date_start: '2020-12-01'
          date_end: '2014-08-30'
          description: 'Thesis: Proactive Defense through Automated Attack Generation: A Multi-pronged Study of Generated Deceptive Content'
        - title: Data Science-NLP Intern
          company: Occidental (Oxy) Petroleum Corporation
          company_url: ''
          company_logo: ''
          location: The Woodlands, Texas
          date_start: '2019-05-01'
          date_end: '2019-08-30'
          description: Designed and optimized a reinforcement learning-based virtual conversational assistant to aid in digital operations and provide guided insights into system maintenance and failure detection to engineers at remote on-shore drilling rigs.
        - title: Summer Research Intern
          company: Production Solutions Team, Halliburton Energy Services
          company_url: ''
          company_logo: ''
          location: Houston, Texas
          date_start: '2018-05-01'
          date_end: '2018-08-30'
          description: Implemented and designed an optimized tool for real-time automated failure and anomaly detection and prediction by leveraging supervised machine learning models trained on offshore subsea riser pipes, improving timely tool maintenance and failure detection rate by 15%.
        - title: Data Science Intern
          company: 2H Offshore Inc.
          company_url: ''
          company_logo: ''
          location: Houston, Texas
          date_start: '2017-06-01'
          date_end: '2017-08-30'
          description: Developed an auto-regressive neural model for fast and reliable estimation of fatigue damage in offshore drilling risers by analyzing real-time motion and temperature data from submerged sensors assessing failure estimation and maintenance. 

    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards, Honors and &shy;Others'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2024-04-30'
          date_start: '2022-05-01'
          description: ''
          icon: ''
          organization: CPRIT and UTHealth-Houston
          organization_url: https://www.uth.edu/big-tcr/
          title: CPRIT BIG-TCR Postdoctoral Training Program Fellowship
          url: https://www.uth.edu/big-tcr/people/trainees.htm
        - certificate_url: ''
          date_end: ''
          date_start: '2022-03-01'
          description: ''
          icon: ''
          organization: National Center for Advancing Translational Sciences (NCAT)
          organization_url: 'https://ncats.nih.gov/funding/challenges/litcoin'
          title: Second Place in Litcoin NLP Challenge 
          url: https://ncats.nih.gov/funding/challenges/litcoin/winners
        - certificate_url: ''
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: ''
          organization: 'University of Houston, Houston, TX'
          organization_url: ''
          title: 'Cullen Graduate Success Fellowship'
          url: ''
        - certificate_url: ''
          date_end: '2014-12-21'
          date_start: '2010-07-01'
          description: ''
          icon: ''
          organization: 'Ministry of Human Resources-India, India'
          organization_url: ''
          title: 'Merit-based Scholarship for Undergraduate Education'
          url: ''
        - certificate_url: ''
          date_end: '2022-12-01'
          date_start: '2014-08-01'
          description: |2-
            * Annual Meeting of the Association for Computational Linguistics (ACL), 2020, 2022
            * Grace Hopper Conference for Women in Computing (GHC), 2015, 2016, 2018
            * International Workshop on Security and Privacy Analytics (IWSPA), 2017, 2018
            * Empirical Methods in Natural Language Processing Conference (EMNLP), 2016
            * Women in CyberSecurity Conference (WiCyS), 2016, 2017
            * Computing Research Association for Women (CRA-W), 2015
          icon: ''
          organization: 'Various'
          organization_url: ''
          title: 'Travel Grants'
          url: ''
        - certificate_url: ''
          date_end: '2018-07-01'
          date_start: '2017-07-01'
          description: |2-
            * First Place (DecorateAR), CodeRED Discovery, University of Houston, 2018
            * Third Place , CodeRED Exploration, University of Houston, 2017
            * Winner (HarveyTrack), Social Track at HackRice 7, Rice University, 2017
          icon: ''
          organization: 'Various'
          organization_url: ''
          title: 'Hackathons'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: talks
    content:
      title: Invited Talks 
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - talks
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
      view: compact
      columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  
---
