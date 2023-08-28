---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Advisors
          - Members
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  
  # Hidden Join Us section
  # - block: markdown
  #   content:
  #     title: Join Us
  #     subtitle: Welcome to IDS NLP-SIG 😃
  #     text: |
  #       {{% cta cta_link="https://forms.gle/Bu3CohBX5urM4p5n6" cta_text="I'm in!" %}}
  #   design:
  #     columns: '1'
---