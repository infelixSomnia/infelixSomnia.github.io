---

# 📂 Vault

vault:
  kit_folder: 'C:\Users\McKenna Skoczen\Documents\obsidian\DnD\skocz'
  include: 
    - '^(kitrc|index|navbar).md$'
    - '^2-World'
    - '^1-Party'
    - '^1-Session Journals'
    - '^1- DM Toolkit\Welcome.md'
  exclude: 
    - '^kit/'
    - '^templates/'
    - '^blog/draft'


# 🧰 Kit

kit:
  version: latest
  dirs: false


# 🖥️ Site

site:
  id: 
  name: https://publish.obsidian.md/skocz/
  description: Welcome to https://publish.obsidian.md/skocz/
  url: https://publish.obsidian.md/skocz/
  keyswords: publishkit, blogging, markdown

og:
  image: https://publishkit.dev/attachements/og-image.png


# 🔌 Plugins

plugins: 
  theme: "@default"
  header: true
  darkmode: true
  navbar: true
  toc: true
  search: true
  social: true
  dataview: '@dataview'
  templater: '@templater-obsidian'
  dnd-ui: 'https://github.com/hay-kot/obsidian-dnd-ui-toolkit.git'



# ⚙️  Plugins settings

social:
  github: https://publishkit.dev
  discord: https://publishkit.dev

---
# KITRC

KITRC stands for Kit **R**un **C**ommands.
It holds your app global configuration. 


Edit settings or add plugins, and export the file in your kit. If the file is valid frontmatter wise, you should see a `kitrc.json` at the root of your kit folder.


Check out https://publishkit.dev