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
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Engineer (Data Analytics and Reliability)
          company: Ayar Labs
          company_url: 'https://www.ayarlabs.com/'
          company_logo: ayar
          location: Santa Clara, California USA
          date_start: '2023-05-22'
          date_end: ''
          description: |2-
              As a Sr. Engineer, I focus on data analytics for the Multi-Wavelength Source (MWS) product development for Ayar Labs.  This includes developing data pipelines for the reliability team and executing reliability test plans for the MWS product.
        - title: Graduate Researcher
          company: University of Chicago
          company_url: ''
          company_logo: uchi
          location: Chicago, Illinois USA
          date_start: '2019-11-01'
          date_end: '2023-03-01'
          description: Working in Jeff McMahon's experimental cosmology group, I characterized and modeled optical elements for the Simons Observatory, a next-generation cosmology experiment.
        - title: Graduate Researcher
          company: University of Michigan
          company_url: ''
          company_logo: umich
          location: Ann Arbor, Michigan USA
          date_start: '2017-09-01'
          date_end: '2019-07-01'
          description:
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://science.osti.gov/wdts/scgsr/
          date_end: ''
          date_start: '2022-01-25'
          description: 'The SCGSR program provides supplemental awards to outstanding U.S. graduate students (US citizens or lawful permanent residents) to pursue part of their graduate thesis research at a DOE laboratory/facility in areas that address scientific challenges central to the Office of Science mission.'
          organization: Department of Energy Science Graduate Student Research (SCGSR) Program
          organization_url: https://science.osti.gov/wdts/scgsr/
          title: Department of Energy SCGSR Fellow
          url: 'https://science.osti.gov/wdts/scgsr/'
        - certificate_url: https://www.nsfgrfp.org/
          date_end: ''
          date_start: '2018-07-01'
          description: 'The purpose of the NSF Graduate Research Fellowship Program (GRFP) is to ensure the quality, vitality, and diversity of the scientific and engineering workforce of the United States. GRFP seeks to broaden participation in science and engineering of underrepresented groups, including women, minorities, persons with disabilities, and veterans.'
          organization: NSF Graduate Research Fellowship
          organization_url: https://www.nsfgrfp.org/
          title: NSF Graduate Research Fellow
          url: https://www.nsfgrfp.org/
        - certificate_url: https://www.nasa.gov/directorates/spacetech/strg/nstgro
          date_end: ''
          date_start: '2018-07-01'
          description: 'The goal of NSTRF is to sponsor U.S. citizen and permanent resident graduate students who show significant potential to contribute to NASA’s goal of creating innovative new space technologies for our Nation’s science, exploration and economic future.  Declined award offer.'
          organization: NASA Space Technology Research Fellowship
          organization_url: https://www.nasa.gov/directorates/spacetech/strg/nstgro
          title: 'NASA Space Technology Research Fellow'
          url: 'https://www.nasa.gov/directorates/spacetech/strg/nstgro'
    design:
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      email: grace@ayarlabs.com
      contact_links:

      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
