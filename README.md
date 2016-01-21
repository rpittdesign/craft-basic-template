# Craft Basic Template
A bare-bones framework for Craft, for a quicker start to templating.

## What's included?

- Home page: /craft/templates/index.html
- News listing page: /craft/templates/news/index.html
- News entry page: /craft/templates/news/_entry.html
- Simple page: /craft/templates/simple.html
- Error 404 page: /craft/templates/404.html

## Installation

1. [Install Craft](https://craftcms.com/docs/installing) as normal.
2. Copy **/craft/config/general.php** into your folder structure and set your own custom control panel trigger word. This changes it from the default of /admin to /cms - change this to something that suits your needs. Make sure to also update the assets folder to the folder you will be using in your /public folder. Note, your server set-up may call this root folder /httpdocs.
3. Copy **/craft/templates** into your folder structure.
4. Copy **/public/assets** folder into your folder structure. This contains some basic CSS including normalize. I've also included the SCSS files to give you base to build upon. If you are using these files, be sure to copy **/public/config.rb** into your folder structure too. This structure assumes you have used assets in your /craft/config/general.php file.
