SublimeCakePHP
=================

Sublime CakePHP is a bundle of Snippets for [CakePHP](http://cakephp.org). The snippets are geared towards the baked results from CakePHP 2.0.X.

####Provides the following features:

Model Specific Snippets:

    * belongsTo                     : bt
    * hasAndBelongsToMany           : habtm
    * hasMany                       : hm
    * hasOne                        : ho
    * validate                      : val

Helper Snippets

    * $this->Html->css              : css
    * $this->Html->link             : link
    * $this->Html->script           : script
    * $this->Html->url              : url

    * $this->Number->addFormat      : addFormat
    * $this->Number->currency       : currency
    * $this->Number->format         : format
    * $this->Number->precision      : precision
    * $this->Number->toPercentage   : toPercentage
    * $this->Number->toReadableSize : toReadableSize

    * $this->Time->format           : timef
    * $this->Time->nice             : timen

Misc Snippets

    * $this->data                   : td
    * $this->request->data          : trd
    * debug();                      : db

Utilities

    * Inflector::camelize           : camelize
    * Inflector::classify           : classify
    * Inflector::humanize           : humanize
    * Inflector::pluralize          : pluralize
    * Inflector::reset              : reset
    * Inflector::rules              : rules
    * Inflector::singularize        : singularize
    * Inflector::slug               : slug
    * Inflector::tableize           : tablize
    * Inflector::underscore         : underscore
    * Inflector::variable           : variable

Installing
----------

*With Package Manager:*

* Press "ctnl+shift+p"
* Enter "Package Control: Add Repository"
* Enter "https://github.com/openam/SublimeCakePHP"
* Press "ctnl+shift+p"
* Enter "Package Control: Install Package"
* Enter "SublimeCakePHP"

*Without Git:* Download the latest source from http://github.com/openam/SublimeCakePHP and copy the whole directory into the Packages directory.

*With Git:* Clone the repository in your Sublime Text 2 Packages directory, located somewhere in user's "Home" directory:

> git clone git://github.com/openam/SublimeCakePHP.git

The "Packages" directory should be located at:

* Windows:
    %APPDATA%\Sublime Text 2\Packages
* OS X:
    ~/Library/Application Support/Sublime Text 2/Packages
* Linux:
    ~/.config/sublime_text_2/Packages
* Portable Installation:
    Sublime Text 2/Data/Packages

License
-------
These snippets are based on code from the [CakePHP](http://cakephp.org) framework and is released under the MIT license.