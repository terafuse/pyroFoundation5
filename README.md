##A PyroCMS Theme built w/ Foundation 5

#PyroFoundation5  
	
`Version: (v1.5)  
- Author: antiksink  
- Date: 01/01/2014`  

>*PyroFoundation5* is a PyroCMS theme template built w/ Compass and Zurb Foundation 5. This theme is meant to serve as a base starting point for a new Foundation5 / PyroCms project.  

>Included are a couple Pyro page layouts derived from the Foundation 5 [HTML Templates found here.](foundation.zurb.com/templates.html) and modified for PryoCMS page_types.

---
  
**PyroCMS**  
	
 - [https://www.pyrocms.com/](https://www.pyrocms.com/)  
 - [https://github.com/pyrocms/pyrocms](https://github.com/pyrocms/pyrocms)

**Zurb-Foundation**  

 - [http://foundation.zurb.com/](http://foundation.zurb.com/) 
 - [https://github.com/zurb/foundation](https://github.com/zurb/foundation)  
 
---  
## Instructions: Foundation Compass Set-up  
  
**Follow the _Quikstart_ from the _Foundation 5 README.md_ below and apply for use with _pyroFoundation5_ theme template.**  

> Built from ZURB / [foundation-compass-template](https://github.com/zurb/foundation-compass-template/archive/master.zip) to be a quick start and easily updated to the current build of _Foundation 5_.

## Foundation Compass Template
_Foundation 5 README.md_  
The easiest way to get started with Foundation + Compass.

## Requirements

  * Ruby 1.9+
  * [Node.js](http://nodejs.org)
  * [compass](http://compass-style.org/): `gem install compass`
  * [bower](http://bower.io): `npm install bower -g`

## Quickstart

  * Unzip template and go to directory
  * Run `bower install` to install the latest version of Foundation
  
Then when you're working on your project, just run the following command:

```bash
compass watch
```

## Upgrading

If you'd like to upgrade to a newer version of Foundation down the road just run:

```bash
bower update
```

---

## Instructions: PyroCMS Theme  

1. Follow the _Quikstart_ from the _Foundation 5 README_ 
 - go to theme directory, run 'bower update' 
 - use 'compass compile' or 'compass watch' to compile changes 
* Compress template files into .zip folder called pyroFoundation5.zip  
* Upload pyroFoundation5.zip to PryoCMS Themes under Ad-ons menu and activate.  

> Note: `app.js, foundation.min.js, jquery.js, modernizr.js` have been copied from `themeDir/bower_components/.../` to `themeDir/js` for PyroCMS reference.
Any changes or updates to these files should be copied to `themeDir/js` also.

***Page Types:***  

>A couple PyroCMS page_types are included which are a good start to create a new layout. Copy code from files in `themeDir/views/page_types/` and paste into PyroCMS (Page Type / Layout) section, save and add all (new Fields) to the new Page Type.  



