# DavisSiteUpgrade #

***This program uses middleman to construct a new website for Dr. James Davis.***

##Requirements##
- Ruby v2.2.2
- Ubuntu 14.04 LTS
- Mozilla Firefox
- The 'middleman' gem
```
//To install required gem, do:
$ gem install middleman
```
```
//The installation process will add one new command to your environment/directory, with features you can use:
$ middleman init
$ middleman server
$ middleman build
```

> **NOTE:**
> - This has only been tested with the above requirements. Other operating systems and other versions of Ruby may also work.

##Starting the Program##
To run the program, do:
```
$ cd <path/to/DavisSiteUpgrade/directory>
$ ruby run.rb
```
After running **run.rb**, the program will begin

> - Changes can be viewed live while editing /DavisSiteUpgrade/source/*.html.erb

##Debugging##
If firefox opens but the page does not load, check the terminal and look for something like the following:
```
== The Middleman uses a different port "<some number>" then the configured one "4567" because some other server is listening on that port.
== View your site at "http://VirtualBox.local:<some number>", "http://10.0.2.15:<some number>"
```
Follow the instructions and type ```http://VirtualBox.local:<some number>``` into your browser to view the page.
