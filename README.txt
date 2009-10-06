
        $Id$


        bs_blocker
        Provided by http://webschuur.com
        Developed by Bèr Kessels
        
        This module is really simple: it does nothing itself. 
        All it does, is insert some IP-patterns on installation into Drupals access
        table. This Drupal access system allows blocking users by host or mail. 
        
        NOTE: The teezir bot can probably switch to other IP addresses really easy. 
              So untill we find a more complete list of IP addresses or patterns, 
              this module will probably not help at all.
        NOTE: You block an entire company, not just one bot. They run more bots, so installing
              this blocker, may break your business if any other of the teezir servers need to 
              have access to you site.
        NOTE: Do not rely on this module to protect you from copyright issues. Even íf, 
              this module would block the bot entirely (and it will most probably not)
              people can still visit your site manually.
        NOTE: You should not steal and distribute copyrighted material. You should 
              actually try some Creative Commons works, instead: http://creativecommons.org.
              Or any other "alternatively" licenced work.
        
        This module is not meant as a working, running and serious thing. 
        It is meant for illustration of how silly the Dutch Buma/Stemra is acting. 
        
        More on this on just about every Dutch Blog. 
        A good starting point here http://3voor12.vpro.nl/artikelen/artikel/42560165
        
        -------------------------------------------------------------------------------
        INSTALLATION
        -------------------------------------------------------------------------------

        Upload to your Drupal site: place in path/to/drupal/sites/all/modules/bs_blocker

        -------------------------------------------------------------------------------
        INFORMATION AND ADDITIONS
        -------------------------------------------------------------------------------

        Patterns are placed in the array in in bs_blocker.install
        A basic wildcard pattern is in place: 
          % Matches any number of characters, even zero characters.
          _ Matches exactly one character.

        Please contact me at twitter:berkes, IM:berkes@jabber.org.uk or on 
          bler.webschuur.com/bs_blocker if you know more patterns for the Teezir bot.
        
        Initial information on the bot can be found at http://www.teezir.com/?tabid=81
        
        Info on the IPs behind the domain teezir.com here http://www.robtex.com/ip/77.243.161.175.html

        Info on Drupal's blocking system in the handbook: http://drupal.org/getting-started/6/admin/user/rules
