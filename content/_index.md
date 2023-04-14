---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 100%
      icon: qgis-icon64
      icon_pack: custom
      name: QGIS
    - description: 100%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 80%
      icon: python
      icon_pack: fab
      name: Python
    - description: 90%
      icon: chart-line
      icon_pack: fas
      name: Estatística
    - description: 90%
      icon: database
      icon_pack: fas
      name: SQL
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Secretaria de Saúde de Belém do Pará
      company_logo: sesma-vertical
      company_url: ""
      date_end: ""
      date_start: "2021-11-01"
      description: |2-
          Responsabilidades:

          * Análise de dados
          * Epidemiologia espacial
          * Database Administrator
          * Modelagem
          * Deploying
      location: Belém-PA
      title: Cientista de Dados Geoespacial
    - company: Regea Geologia, Engenharia e Estudos Ambientais
      company_logo: regea-logo
      company_url: ""
      date_end: "2022-09-01"
      date_start: "2022-06-01"
      description:  Interpretação de imagens aéreas utilizando o software QGIS, vetorização e correção de hidrografia.
      location: Remoto
      title: Intérprete de imagens de satélite
    title: Experiências
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: "2022-06-25"
      date_start: "2022-04-25"
      description: "Data Science Academy (60h)"
      organization: dsa
      organization_url: https://www.datascienceacademy.com.br
      title: Python Fundamentos Para Análise de Dados 3.0
      url: ""
    - certificate_url: https://www.edx.org
      date_end: "2021-05-21"
      date_start: "2021-03-21"
      description: Data Science Academy (72h)
      organization: dsa
      organization_url: https://www.edx.org
      title: Microsoft Power BI Para Data Science
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2021-11-30"
      date_start: "2021-05-01"
      description: "Capacitação em geotecnologias aplicadas à gestão de áreas protegidas (80h)"
      organization: ufabc
      organization_url: https://www.datacamp.com
      title: Capacitação em Geotecnologias
      url: ""
    subtitle: null
    title: Certificados
  design:
    columns: "2"
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
# - block: collection
#   content:
#     filters:
#       exclude_featured: true
#       folders:
#       - publication
#     text: |-
#       {{% callout note %}}
#       Quickly discover relevant content by #[filtering publications](./publication/).
#       {{% /callout %}}
#     title: Recent Publications
#   design:
#     columns: "2"
#     view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Belém
      country: Brazil
      country_code: BR
      #postcode: "94305"
      region: PA
      #street: 450 Serra Mall
    #appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: github
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: ermesonfds
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: ermeson.freitas@hotmail.com
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    # subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #   ut magna et, vehicula efficitur enim.
    title: Contato
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
