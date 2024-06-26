---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
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
  #  content:
  #    title: Skills
  #    text: ''
  #    # Choose a user to display skills from (a folder name within `content/authors/`)
  #    username: admin
  #  design:
  #    columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Aug 2021
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern (80% full-time internship)
          company: Marine Robotics Lab (University of Wisconsin)
          company_url: 'https://mrl.engr.wisc.edu/'
          # company_logo: org-gc
          location: Madison, Wisconsin, USA
          date_start: '2024-06-01'
          date_end: '2024-09-01'
          description: |2-
              * Research on control algorithm of autonomous surface vessel (ASV)
              * Design my omnidirectional vessel called "the Ontario"
              * Supervise by Prof. Wei Wang
        - title: Machine Learning Research Engineer (full-time internship)
          company: Noah's Ark Lab, Huawei Canada
          company_url: 'https://dev3.noahlab.com.hk/'
          # company_logo: org-gc
          location: Markham, Ontario, Canada
          date_start: '2023-05-01'
          date_end: '2024-06-01'
          description: |2-
              * Research on control and planning of autonomous driving vehicles.
              * Participate in Carla competition with my team and worked on perception module and motion prediction. 
              * Propose autonomous driving constraint learning algorithm with Prof. Pascal Poupart's modified MaxEnt formulation.
        - title: Research Intern
          company: embARC Research Group (University of Toronto)
          company_url: 'https://www.embarclab.com/'
          # company_logo: org-x
          location: Toronto, Ontario, Canada
          date_start: '2023-01-01'
          date_end: '2024-06-01'
          description: |2-
              * Working on computer vision and real-time 3D reconstruction projects (SLAM, NeRF, 3DGS).
              * Implement and open-source Packet for real-time image transmission.
              * Design framework for resource-constraint devices to leverage computer perception algorithm.
              * Working with Ruofan Liang, supervised by Prof. Nandita Vijaykumar
        - title: Machine Learning Researcher
          company: Sunnybrook Health Science Center
          company_url: 'https://sunnybrook.ca/'
          # company_logo: org-x
          location: Remote (office in Toronto, Ontario, Canada)
          date_start: '2023-01-01'
          date_end: '2023-12-01'
          description: |2-
              * Designing ML archetecture to classify patients' sleeping stage.
              * Designing signal alignment (synchronization) algorithm for signals from multiple sensors.
              * Wrote scripts to use ComputeCanada to train our model.
              * Supervised by Prof. Andrew Lim.
        - title: Automation Developer (full-time internship)
          company: Nokia
          company_url: 'https://www.nokia.com/'
          # company_logo: org-x
          location: Remote (office in Ottowa, Ontario, Canada)
          date_start: '2022-05-01'
          date_end: '2022-09-01'
          description: |2-
              * Worked in Netguard Base Platform team to write bash scripts that can automatically finish operations for our customer like automation migration tool. 
              * Used kubernetes and helm to manage our software on server and learnt to use DevOps tools like Jira and Jenkins.
        - title: Research Asistant
          company: Robot Vision and Learning Lab (University of Toronto)
          company_url: 'https://rvl.cs.toronto.edu/'
          # company_logo: org-gc
          location: Mississauga, Ontario, Canada
          date_start: '2021-09-01'
          date_end: '2021-12-31'
          description: |2-
              * Worked on boat environment monitoring project in order to model the distribution of the pollutant on the Lake Ontario. 
              * Developed visualization program with React.js, Robot Operating System, Python, socketio, and Clearpath Heron USV.
              * Supervised by Prof. Florian Shkurti and Prof. Tim Barfoot

    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2023-07-01'
          date_start: '2023-11-01'
          description: See our results at leaderboard 2.0 map track at https://leaderboard.carla.org/leaderboard/
          title: Top 1 in CARLA Autonomous Driving Challenge 2023 on Map Track
          url: https://leaderboard.carla.org/leaderboard/
        - date_end: '2025-06-30'
          date_start: '2020-09-01'
          description: Got Dean List for all four years and earn 1000 CAD scholarship for in-course performance.
          title: Dean List and in-course scholar
          url: 
        - date_end: ''
          date_start: '2018-09-01'
          description: Got Distinction awards in American Math Contest, Euclid Math Contest, and Third prize in Chinese High School Math Tournament.
          title: Math Competition Prizes
          url: 
    design:
      columns: '2'

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'



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


  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     # Choose a map provider in `params.yaml` to show a map from these coordinates
  #     coordinates:
  #       latitude: '37.4275'
  #       longitude: '-122.1697'  
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
