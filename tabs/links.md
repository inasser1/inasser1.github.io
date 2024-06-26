---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Links"
    info: "Useful Websites I have used to better my portfolio and learn coding and other skills throughout my career"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "LinkedIn"
      type: id_linkedin
      color: "gray"
    - title: "Coding"
      type: id_coding
      color: "#F4A273"

  list:
    # linkedin links
    - type: id_linkedin
      title: "LinkedIn"
      url: "https://www.linkedin.com/?trk=content-hub-home-page_nav-header-logo"
      info: "Create an account to find jobs and connect with professionals throughout the world. Using it will help you build connections and find job opportunities."

    # coding
    - type: id_coding
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web."
    - type: id_coding
      title: "GeeksforGeeks"
      url: "https://www.geeksforgeeks.org/"
      info: "Similar to W3Schools, this website offers free online references, practice, and tips for learning new coding languages."
    - type: id_coding 
      title: "Stack Overflow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow is a question and answer website that professionals and people seeking help and advice use."
---
