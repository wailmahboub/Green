# Site info
site_name: Mee6 Documentation
site_url: https://mee6.github.io/Mee6-documentation
repo_url: https://github.com/mee6/Mee6-documentation
repo_name: mee6/Mee6-documentation
site_author: Sil Boydens
# Theme settings
theme:
  name: material
  palette:
    primary: blue
    accent: light-blue
  # font:
  #   text: Lato
  #   code: Inconsolata
  logo:
    icon: info
  favicon: 'pics/favicon.ico'
extra:
  search:
    language: en
  social:
    - type: 'github'
      link: 'https://github.com/mee6'
    - type: 'twitter'
      link: 'https://twitter.com/mee6bot'
markdown_extensions:
  - admonition
  # - codehilite:
  #     guess_lang: false
  - toc:
      permalink: true
# Pages
pages:
  - Home: index.md
  - Custom Commands:
    - Overview: commands.md
    - Variables: commands_variables.md
  - Timers: timers.md
  - Levels:
    - Overview: levels.md
    - Experience Per Level: levels_xp.md
  - Moderator: moderator.md
  - Music: music.md
  - Record: record.md
  - Search Anything: search_anything.md
  - Help Me!: help_me.md
  - Twitch & co.: twitch_n_co.md
  - Reddit: reddit.md
  - Welcome: welcome.md
  # - Example: example.md
