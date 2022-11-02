# Site
repository: Git repository where your resume will be hosted, only required if you are hosting on GitHub (eg. sproogen/modern-resume-theme)
# favicon: Directory of your favicon (eg. images/favicon.ico)(optional)

# Content configuration version
version: 2

# Personal info
name: Deep Patel
title: Web Developer
email: deepips09@gmail.com
# email_title: Email (Email title override)
phone: (431)990 2009
# phone_title: Phone (Phone title override)
#website:
# website_title: Web (Website title override)

# Dark Mode (true/false/never)
darkmode: false

# Social links

# Additional icon links
#additional_links:
#- title: Link name
# icon: Font Awesome brand icon name (eg. fab fa-twitter) (https://fontawesome.com/icons?d=gallery&s=brands&m=free)
#url: Link url (eg. https://google.com)
# - title: another link
#   icon: font awesome brand icon name (eg. fab fa-twitter) (https://fontawesome.com/icons?d=gallery&s=brands&m=free)
#   url: Link url (eg. https://google.com)

# Google Analytics and Tag Manager
# Using more than one of these may cause issues with reporting
# gtm: "GTM-0000000"
# gtag: "UA-00000000-0"
# google_analytics: "UA-00000000-0"

# About Section
# about_title: About Me (Use this to override about section title)
about_profile_image: images/profilepic.jpg
about_content: | # this will include new lines to allow paragraphs
  A web developer who loves to work in team, has leadership skill, and is a quick lerner. Eager to see myself as a successful web developer who is responsible for designing and implementing front and back end of web applications.
content:
  - title: Projects # Title for the section
    layout: list # Type of content section (list/text)
    content:
      - layout: left
        border:
          weak # Value of `weak` will display a weak border below this item. # Any
          # other value (or no value) means no border will be displayed
        title: Fitness Forever
        link: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
        #link_text: Link Text
        #additional_links:
        #- title:  Github page for project (eg. sproogen/modern-resume-theme)
        # icon: fab fa-github
        # url: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
        #- title:  Github page for project (eg. sproogen/modern-resume-theme)
        # icon: fab fa-github
        # url: Link to project (eg. sproogen.github.io/modern-resume-theme)(optional)
        quote: >
          A multipage fitness website
        description: | # this will include new lines to allow paragraphs
          To create and maintain this website following tools were used:  
          -HTML   
          -CSS  
          -JavaScript  
          -React framework   
          -GitHub
  - title: Experience
    layout: list
    content:
      - layout: top-right
        title: Brewers' Distributor Limited
        sub_title: SAP software specialist
        caption: May 2022 - current

        quote: >
        description: | # this will include new lines to allow paragraphs
          Description of role
          - Helping in basic wraehouse operations such as receiving stocks, inventory management, shipping stocks with the help of SAP SCM software.

  - title: Education
    layout: list
    content:
      - layout: top-right
        title: University of Manitoba
        sub_title: Bachelor of computer science
        caption: May 2018 - current
        quote: >
        description: | # this will include new lines to allow paragraphs
          Relevant coursework:
          - Human Computer Interaction
          - Advance Human Computer Interaction
          - Software engineering

  - title: Skills
    layout: text
    content: | # this will include new lines to allow paragraphs
      -	HTML / CSS    
      -	JavaScript    
      -	Git / GitHub    
      -	SQL / SQL Server    
      -	Responsive designing with the use of React framework and Angular    
      -	Testing and debugging
# Footer
footer_show_references: true
# references_title: References on request (Override references text)

# Build settings
# theme: modern-resume-theme (Use this is you are hosting your resume yourself)
# remote_theme: sproogen/modern-resume-theme (Use this if you are hosting your resume on GitHub)

sass:
  sass_dir: _sass
  style: compressed

plugins:
  - jekyll-seo-tag

exclude:
  [
    "Gemfile",
    "Gemfile.lock",
    "node_modules",
    "vendor/bundle/",
    "vendor/cache/",
    "vendor/gems/",
    "vendor/ruby/",
    "lib/",
    "scripts/",
    "docker-compose.yml",
  ]
