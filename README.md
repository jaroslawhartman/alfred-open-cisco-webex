# alfred-open-cisco-webex
A MacOS Alfred workflow to open a predefined Webex session.

Pre-requisites: 

*  [Alfred](https://www.alfredapp.com/) - free
*  [Alfred Power Pack](https://www.alfredapp.com/powerpack/buy/) - commericial, but I strongly recommend

# Introduction

It's pretty basic, but helps me to speed up a very common activity (which I always tend to do on very last second when a my conference call is about to start)...

So when I urgently need to open Webex conference, instead of searching through my browser bookmarks, just press Option-Space and type _webex_:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-01.png)

Then press Enter to get the list of your web conferences, for example:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-02.png)

Hit cursor down or up to select bridge you want to open and just press enter.

# Installation

After downloading the workflow, just doubleclick the file and it will get imported to your Alfred.

# Configuration

Ok, how you could add your most frequently used Webex URLs to the list? Navigate to Alfred workflows, find Webex workflow and select _Open in Finder_:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-03.png)

Then open `configuration.txt` in your text editor:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-04.png)

In the file, set your URLs in format `<Name>|<URL>`, for example `Jarek|https://webex.com/joint/jarek.hartman`:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-05.png)

Save and done!