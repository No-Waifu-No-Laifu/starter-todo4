#Change Log

#####Team membership:  

    - GL[Jia Qi Lee (NamBlue)] (Captain)
    - SM[Steven Ma] (Mate)

Team conventions: Allman notation, markdown for changelog  
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 


## Version Log
### Version 2.0 - GL, SM
Release Date: 10.19.17

##### New Components
    - controllers     
        - Mtce - Maintenance controller
        - Roles
    - model     
        - N/A
    - view
        - itemlist
        - oneitem
	- itemnav
    - others
        - N/A

##### Updated components
    - controllers
        - Mtce - Shows role on pagetitle, added pagination
	- View - updated makePrioritizedPanel(), created complete()
    - model     
        - N/A
    - view
        - _menubar - added role selector
	- itemlist - added pagination tag
	- by_priority - added form tag
    - others
        - autoload - enabled sessions
        - config - Changed link routing for Maintenance
                 - Session path set
        - constants - Added application constants
	- updated core/Memory_Model
        

##### Bugfixes
    - controllers
        - N/A    
    - model     
        - N/A
    - view
        - Fixed bootstrap for
    - others
	- N/A

### Version 1.0 - GL, SM
Release Date: 10.12.17

##### New Components
    - controllers     
        - Views
        - Helpme
    - model     
        - Added Tasks.php
    - view
        - by_priority
        - by_category
    - others
        - data/jobs.md
        - imported liraries/Parsdown.php

##### Updated components
    - controllers     
        - Updated Welcome.php
        - MY_Controller - fixed bug
        - 
    - model     
        - N/A
    - view
        - Updated homepage.php
    - others
        - config - Changed link routing for work link
                 - Changed link to route Help Wanted link
        - autoload - Added reference to load Parsedown library