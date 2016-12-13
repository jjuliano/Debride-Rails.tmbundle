Debride-Rails.tmbundle
================

Debride-Rails (https://github.com/seattlerb/debride) Textmate 2 Bundle

(c) 2017 Joel Bryan Tiam Juliano joelbryan.juliano@gmail.com

Supports
--------
* analysing dead and uncalled methods
* different icons for analysis

Install
-------

Make sure $TM_RUBY is set to current ruby directory, then:

    gem install debride
    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone https://github.com/jjuliano/Debride-Rails.tmbundle.git

To generate and use a whitelist.txt:

    rake routes > routes.txt
    debride_rails_whitelist routes.txt logfiles...| sort -u > whitelist.txt

Then set the $RAILS_WHITELIST (via TextMate > Preferences > Variables) pointing to the whitelist.txt file.

Screenshot
----------
![screenshot](Support/screenshot.png?raw=true "screenshot")

Credits
-------
Emoji provided free by http://emojione.com
