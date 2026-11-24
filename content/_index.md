
---
title: ""
summary: "Professional profile of Dr David Collins Owuor, genomic epidemiologist and bioinformatician working in pathogen genomics, molecular surveillance and public health."
date: 2026-11-24
type: landing

sections:
  # 1. Professional biography
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        url: uploads/resume.pdf
        text: Download CV
      headings:
        about: Professional Summary
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 2. Professional experience timeline
  - block: resume-experience
    content:
      username: me
    design:
      title: "Professional Experience"
      date_format: "January 2006"
      is_education_first: false

  # 3. Research and public health focus
  - block: markdown
    id: research
    content:
      title: "Research and Public Health Focus"
      subtitle: "From pathogen sequence data to public health action"
      text: |
        My work focuses on the application of pathogen genomics, bioinformatics and molecular epidemiology to infectious disease surveillance, outbreak investigation and public health decision-making.

        Key areas include:

        - 🧬 Pathogen genomics and genomic epidemiology
        - 🦠 Poliovirus and vaccine-derived poliovirus surveillance
        - 💉 Influenza evolution, transmission and phylogeography
        - 🔬 Measles whole-genome sequencing
        - 🧪 SARS-CoV-2 genomic surveillance
        - 💧 Wastewater-based pathogen surveillance
        - 🤖 Artificial intelligence and data science for public health
        - 🌍 Genomic surveillance systems and laboratory capacity strengthening
    design:
      columns: "1"

  # 4. Technical skills
  - block: resume-skills
    content:
      username: me
      title: "Technical Skills"

  # 5. Selected publications
  - block: collection
    id: papers
    content:
      title: "Recent Publications"
      text: "Peer-reviewed research and scientific contributions."
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: 1

  # 6. Collaboration and contact
  - block: markdown
    id: contact
    content:
      title: "Collaboration and Contact"
      text: |
        I am interested in collaborations in pathogen genomics, genomic epidemiology, molecular surveillance, bioinformatics, laboratory systems strengthening and public health research.

        Connect with me on [LinkedIn](https://www.linkedin.com/in/david-collins-owuor/) or explore my work on [GitHub](https://github.com/DCollinsOwuor).
    design:
      columns: "1"
---
