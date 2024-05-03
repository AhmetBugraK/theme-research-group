---
# Leave the homepage title empty to use the site title
title: BeBetter
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        BeBetter
      image:
        filename: asam_logo.jpg
        width: 10px # Adjust the width as needed
      text: |
        <br>
        Empower Your Mental Well-being at Work!

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Supervisor
        - Software Developers
      sort_by: Params.last_name
      sort_ascending: true
---
