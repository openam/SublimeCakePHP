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

Components

    * $this->Session->check         : check
    * $this->Session->delete        : delete
    * $this->Session->destroy       : destroy
    * $this->Session->flash         : flash
    * $this->Session->read          : read
    * $this->Session->setFlash      : setFlash
    * $this->Session->write         : write

Helpers

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

    * $this->Text->autoLink         : autoLink
    * $this->Text->autoLinkEmails   : autoLinkEmails
    * $this->Text->autoLinkUrls     : autoLinkUrls
    * $this->Text->excerpt          : excerpt
    * $this->Text->highlight        : highlight
    * $this->Text->stripLinks       : stripLinks
    * $this->Text->tail             : tail
    * $this->Text->toList           : toList
    * $this->Text->truncate         : truncate

    * $this->Time->convert           : convert
    * $this->Time->convertSpecifiers : convertSpecifiers
    * $this->Time->dayAsSql          : dayAsSql
    * $this->Time->daysAsSql         : daysAsSql
    * $this->Time->format            : format
    * $this->Time->fromString        : fromString
    * $this->Time->gmt               : gmt
    * $this->Time->i18nFormat        : i18nFormat
    * $this->Time->isThisMonth       : isThisMonth
    * $this->Time->isThisWeek        : isThisWeek
    * $this->Time->isThisYear        : isThisYear
    * $this->Time->isToday           : isToday
    * $this->Time->isTomorrow        : isTomorrow
    * $this->Time->listTimezones     : listTimezones
    * $this->Time->nice              : nice
    * $this->Time->niceShort         : niceShort
    * $this->Time->serverOffset      : serverOffset
    * $this->Time->timeAgoInWords    : timeAgoInWords
    * $this->Time->timezone          : timezone
    * $this->Time->toAtom            : toAtom
    * $this->Time->toQuarter         : toQuarter
    * $this->Time->toRss             : toRss
    * $this->Time->toServer          : toServer
    * $this->Time->toUnix            : toUnix
    * $this->Time-> wasWithinLast    : wasWithinLast
    * $this->Time->wasYesterday      : wasYesterday

Misc Snippets

    * $this->data                   : td
    * $this->request->data          : trd
    * debug();                      : db

Utilities

    * Cache::clear                  : clear
    * Cache::clearGroup             : clearGroup
    * Cache::config                 : config
    * Cache::decrement              : decrement
    * Cache::delete                 : delete
    * Cache::gc                     : gc
    * Cache::increment              : increment
    * Cache::read                   : read
    * Cache::set                    : set
    * Cache::write                  : write

    * CakeLog::config               : config
    * CakeLog::configured           : configured
    * CakeLog::defaultLevels        : defaultLevels
    * CakeLog::disable              : disable
    * CakeLog::drop                 : drop
    * CakeLog::enable               : enable
    * CakeLog::enabled              : enabled
    * CakeLog::levels               : levels
    * CakeLog::stream               : stream
    * CakeLog::write                : write
    * CakeLog::alert                : alert
    * CakeLog::critical             : critical
    * CakeLog::debug                : debug
    * CakeLog::emergency            : emergency
    * CakeLog::info                 : info
    * CakeLog::notice               : notice

    * CakeNumber::addFormat         : addFormat
    * CakeNumber::currency          : currency
    * CakeNumber::defaultCurrency   : defaultCurrency
    * CakeNumber::format            : format
    * CakeNumber::formatDelta       : formatDelta
    * CakeNumber::fromReadableSize  : fromReadableSize
    * CakeNumber::precision         : precision
    * CakeNumber::toPercentage      : toPercentage
    * CakeNumber::toReadableSize    : toReadableSize

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