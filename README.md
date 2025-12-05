Agency Jekyll theme
====================

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# How to open

    1. Open the repository and download it as a ZIP.
    2. Place the ZIP file into a folder of your choice, and unzip the file.
    3. Open an IDE of your choice, and open the folder with the unzipped file.

# How to make your own website

    1. Download Jekyl and Ruby
    2. Download GIT
    3. Open Command Prompt as Administrator
    4. Type cd [your desired folder's link]
    5. Copy the https of your desired theme
    6. Type git clone [the link] into the Command Prompt
    7. Type gem install bundler jekyll
    8. Type cd [your theme name] (in this case it is "cd agency-jekyll-theme)
    9. Type bundle init
    10. Open the desired folder with your IDE
    11. Type this into the gem file: 
        "
        
        # frozen_sting_literal: true

        source "https://rubygems.org"

        # gem "rails"
        gen "jekyll", "~> 4.3"
        
        "

    12. Finally, type bundle exec jekyll serve into your IDE's terminal in order to run the website

# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)
