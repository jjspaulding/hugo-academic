---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: features
#    content:
#      title: Skills
#      items:
#        - name: R
#          description: 90%
#          icon: r-project
#          icon_pack: fab
#        - name: Statistics
#          description: 100%
#          icon: chart-line
#          icon_pack: fas
#        - name: Photography
#          description: 10%
#          icon: camera-retro
#          icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Experience
      subtitle: "At-a-glance"
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      text: |-
        {{% callout note %}}
        See my full [Curriculum Vitae]({{< relref "/cv" >}})
        {{% /callout %}}
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lead Associate
          company: Booz Allen Hamilton
          company_url: 'https://www.boozallen.com/'
          company_logo: BAH
          location: Rome, NY (Hybrid)
          date_start: '2021-07-01'
          date_end: ''
          description: |2-
            _[Booz Allen](https://www.boozallen.com/) is a Fortune 500 professional services company, providing a broad range of services and solutions in management, technology, consulting, and engineering._
            <br>
            <br>
            * Served as the Technical Lead responsible for defining the roadmap and guiding the architecture on [GARDEM](https://govtribe.com/award/federal-idv-award/indefinite-delivery-contract-fa875019d0003) (Global Application Research, Development, Engineering & Maintenance), a multi-million dollar contract to develop a cloud-enabled platform for the [Air Force Research Labs](https://www.afrl.af.mil/) (AFRL).
            * Tasked and monitored the technical execution of geographically-distributed Agile teams consisting of 30+ Engineers, QA Testers, Product Leads, and Support Staff.
            * Conducted and oversaw small research & development teams to enhance and further develop the technology and architecture under GARDEM.
            * Reviewed technical proposals and authored white papers for business development.
             
        - title: #Assistant Professor of Computer Science
          company: Canisius College
          company_url: 'http://www.canisius.edu'
          company_logo: canisius
          location: Buffalo, NY
          date_start: '2019-08-01'
          date_end: ''
          description: |2-
            <span class="section-subheading text-muted exp-title">Adjunct Professor of Computer Science</span><span class="text-muted exp-meta" style="float:right">2021--Present</span>
            * Instructed and trained graduate students in various courses in Computer Science & Cybersecurity.
            <br>
            {style="margin-bottom: 10px"}
            <span class="section-subheading text-muted exp-title">Director, Graduate Cybersecurity Program</span><span class="text-muted exp-meta" style="float:right">2020--2021</span>
            * Hired, trained, mentored, evaluated and managed Instructors & Graduate Assistants.
            * Advised students (scheduling, registration) and supervised, reviewed & approved Master’s projects/theses.
            <br>
            {style="margin-bottom: 10px"}
            <span class="section-subheading text-muted exp-title">Assistant Professor of Computer Science</span><span class="text-muted exp-meta" style="float:right">2019--2021</span>
            * Developed and taught new courses/materials in: Cryptography, Machine Learning, Information Security, Ethical Hacking, and Software Engineering.
            * Established partnerships with top industry certifying organizations (CompTIA, ECCouncil, Offensive Security).
              
        - title: Assistant Professor of Computer Science
          company: Niagara University
          company_url: 'http://www.niagara.edu'
          company_logo: nu
          location: Lewiston, NY
          date_start: '2018-08-01'
          date_end: '2019-08-01'
          description: |2-
            * Prepared hands-on computer lab assignments and delivered lectures.
            * Supervised and mentored undergraduate and graduate research projects.
        - title: Research Assistant
          company: Security & Analytics Lab (SeAL)
          company_url: 'https://seal.cs.ucf.edu/index.html'
          company_logo: ucf
          location: Univ. at Buffalo & Univ. of Central Florida
          date_start: '2015-08-01'
          date_end: '2018-08-01'
          description: |2-
            * Managed multiple projects and collaborated with other graduate students to gather and analyze data for articles, reports and presentations.
            * Mentored junior graduate research assistants for thesis and conference submissions
        - title: Senior Software Engineer
          company: CUBRC Inc.
          company_url: 'https://cubrc.org/'
          company_logo: cubrc1
          location: Buffalo, NY
          date_start: '2011-01-01'
          date_end: '2018-05-01'
          description: |2-
            _[CUBRC](https://cubrc.org/) is an independent non-profit research and development company._
            <br>
            <br>
            * Authored proposals & technical reports, and conducted technical demonstrations to customers.
            * Lead User Interface Developer on web applications for the Air Force Research Labs (AFRL) and the Office of Naval Research (ONR):
              
        - title: Field Application Engineer
          company: NaturalMotion Inc.
          company_url: 'https://www.naturalmotion.com/'
          company_logo: NaturalMotion
          location: San Francisco, CA
          date_start: '2007-12-01'
          date_end: '2011-01-01'
          description: |2-
            _[NaturalMotion](https://www.naturalmotion.com/) is a games and technology company based in England, and a subsidiary of [Zynga](https://www.zynga.com/)._
            <br>
            <br>
            * Integrated the [morpheme animation engine](https://web.archive.org/web/20121013084931/http://www.naturalmotion.com/products/morpheme-3/) in C++ with commercial and proprietary 3D graphics engines for Windows and Game Console platforms.
            * Solved technical issues for clients remotely and on-site at software development companies in the US, Canada, Japan.
            
        - title: Software Engineer II
          company: Dynamic Animation Systems, Inc.
          company_url: 'https://www.d-a-s.com/'
          company_logo: das
          location: Fairfax, VA
          date_start: '2006-11-01'
          date_end: '2007-11-01'
          description: |2-
            _[Dynamic Animation Systems](https://www.d-a-s.com/) develops modeling and simulation solutions for engineering research and analysis._
            <br>
            <br>            
            * Developed and maintained the user interface in C++ and Win32 for the [3D Wildland Fire-Simulator](https://www.d-a-s.com/fema-nfa-detail1), a fire-fighting training simulator for the National Fire Academy that provides a physically realistic fire propagation model based on fuel types, various environmental conditions, and terrain topology.
            
        - title: Software Engineer
          company: NGI Systems Inc.
          company_url: 'https://web.archive.org/web/20131025034227/http://ngisystems.com/Content/Company/Company.aspx'
          company_logo: ngi
          location: Rome, NY
          date_start: '2004-08-01'
          date_end: '2006-05-01'
          description: |2-
            _NGI Systems was a software company primarily working with the Air Force Research Labs (AFRL) in Rome, NY._
            <br>
            <br>
            * Redesigned and implemented the UI in Java for the _Causal Analysis Tool (CAT)_, a Bayesian Network tool originally written in C/C++ for managing uncertainty in causal models for the AFRL.
    design:
      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
  - block: collection
    id: publications
    content:
      title: Featured Publications
      subtitle: Journal Articles
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Publications
      subtitle: Conference & Workshop Papers
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: true
        tag: 'Conference'
      archive:
        enable: true
        text: See all Publications
        link: publication/
    design:
      columns: '2'
      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Let's get in touch:
      # Contact (add or remove contact options as necessary)
#      email: spauldi6@canisius.edu
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
      address:
        street: #450 Serra Mall
        city: 
        region: I'm based out of the Buffalo/Niagara Falls Region in Western New York, United States
        postcode: #'14086'
        country: United States
        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: formspree
        formspree:
          id: xvonjqll
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
      coordinates:
        latitude: '42.9006'
        longitude: '-78.6703'
    design:
      columns: '2'
---
