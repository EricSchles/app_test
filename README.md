# App Test

A framework for testing an html page, full websites, and sets of html pages.  No server required (depending on what you want to test).

##How to use:

All interfacing with the tool is done through main.py

Simply run:

python main.py [options] 

specific options:

-p html_page.html

Expects a single html page and will test for spelling errors and bad links or missing pictures

-s html_page_1.html html_page_2.html

Expects a series of pages and will do the same thing as testing the above page

-d web_app_dir/

Expects a directory and will start a tiny test server to test the application.
The framework will test for bad links, spelling errors, broken images, webpages that are unreachable, and code or libraries that do not load.

Note: only one of these options may be passed in.  If more than one option is passed in, an error will be raised.

 