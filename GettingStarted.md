# Getting Started #

## Default Demo ##
To start the work with the default GXT RTL (Right to Left) demo download the project content from the repository or [downloads](https://code.google.com/p/gxt-rtl/downloads/list) section.

RTL version of demo has own html files with the "-rtl" suffix in the name. So to run desktop demo in RTL use desktop-rtl.html. To run explorer demo use index-rtl.html. Default locale in the demo is "fa\_IR" which is RTL. You can switch to another RTL locale by modifying corresponding meta tag:

`<meta name="gwt:property" content="locale=fa_IR">`

Also you can remove this tag and use locale URI parameter. See more in [GWT i18n section](http://code.google.com/intl/en/webtoolkit/doc/latest/DevGuideI18nLocale.html)

## Add GXT RTL to existing project ##

To add GXT RTL to existing project you need to replace gxt-2.2.x-gwt22 jar with the gxt-2.2.x-gwt22-wrtl.jar provided in the [downloads](https://code.google.com/p/gxt-rtl/downloads/list) section.

Next you need to create html files for the rtl version of your project. In the css section replace

`<link rel="stylesheet" type="text/css" href="gxt/css/gxt-all.css" />`

with the

`<link rel="stylesheet" type="text/css" href="gxt/css/gxt-all-rtl.css" />`

Next you need to replace gxt resources folder under the war folder of your project to the one provided with the GXT RTL project.

Run you application with some RTL locale and with the modified html file which includes RTL css.

That's it.