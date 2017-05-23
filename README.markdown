SublimeCakePHP
=================

Sublime CakePHP is a bundle of Snippets for [CakePHP](http://cakephp.org). The snippets are geared towards the baked results from CakePHP 3.x.

####Provides the following features:

Controller Specific Snippets:

    * afterFilter                    : afterFilter
    * beforeFilter                   : beforeFilter
    * beforeRender                   : beforeRender

Model Specific Snippets:

    * afterDelete                    : afterDelete
    * afterFind                      : afterFind
    * afterSave                      : afterSave
    * afterValidate                  : afterValidate
    * beforeDelete                   : beforeDelete
    * beforeSave                     : beforeSave
    * beforeValidate                 : beforeValidate
    * belongsTo                      : bt
    * hasAndBelongsToMany            : habtm
    * hasMany                        : hm
    * hasOne                         : ho
    * validate                       : val

Components

    * $this->Auth->allow             : allow
    * $this->Auth->authenticate      : authenticate
    * $this->Auth->deny              : deny
    * $this->Auth->loggedIn          : loggedIn
    * $this->Auth->login             : login
    * $this->Auth->logout            : logout
    * $this->Auth->mapActions        : mapActions
    * $this->Auth->redirectUrl       : redirectUrl

    * $this->Session->check          : check
    * $this->Session->delete         : delete
    * $this->Session->destroy        : destroy
    * $this->Session->flash          : flash
    * $this->Session->read           : read
    * $this->Session->setFlash       : setFlash
    * $this->Session->write          : write

Helpers

    * $this->Form->create            : create
    * $this->Form->end               : end
    * $this->Form->input             : input
    * $this->Form->inputs            : inputs
    * $this->Form->label             : label
    * $this->Form->text              : text
    * $this->Form->password          : password
    * $this->Form->hidden            : hidden
    * $this->Form->textarea          : textarea
    * $this->Form->checkbox          : checkbox
    * $this->Form->radio             : radio
    * $this->Form->select            : select
    * $this->Form->file              : file
    * $this->Form->submit            : submit
    * $this->Form->button            : button
    * $this->Form->postButton        : postButton
    * $this->Form->postLink          : postLink
    * $this->Form->dateTime          : dateTime
    * $this->Form->year              : year
    * $this->Form->month             : month
    * $this->Form->day               : day
    * $this->Form->hour              : hour
    * $this->Form->minute            : minute
    * $this->Form->meridian          : meridian
    * $this->Form->error             : error
    * $this->Form->isFieldError      : isFieldError
    * $this->Form->inputDefaults     : inputDefaults
    * $this->Form->unlockField       : unlockField
    * $this->Form->secure            : secure

    * $this->Html->addCrumb          : addCrumb
    * $this->Html->charset           : charset
    * $this->Html->css               : css
    * $this->Html->div               : div
    * $this->Html->dockType          : dockType
    * $this->Html->getCrumbList      : getCrumbList
    * $this->Html->getCrumbs         : getCrumbs
    * $this->Html->image             : image
    * $this->Html->link              : link
    * $this->Html->loadConfig        : loadConfig
    * $this->Html->media             : media
    * $this->Html->meta              : meta
    * $this->Html->nestedList        : nestedList
    * $this->Html->para              : para
    * $this->Html->script            : script
    * $this->Html->scriptBlock       : scriptBlock
    * $this->Html->scriptEnd         : scriptEnd
    * $this->Html->scriptStart       : scriptStart
    * $this->Html->style             : style
    * $this->Html->tableCells        : tableCells
    * $this->Html->tableHeaders      : tableHeaders
    * $this->Html->tag               : tag
    * $this->Html->url               : url
    * $this->Html->useTag            : useTag

    * $this->Number->addFormat       : addFormat
    * $this->Number->currency        : currency
    * $this->Number->format          : format
    * $this->Number->precision       : precision
    * $this->Number->toPercentage    : toPercentage
    * $this->Number->toReadableSize  : toReadableSize

    * $this->Text->autoLink          : autoLink
    * $this->Text->autoLinkEmails    : autoLinkEmails
    * $this->Text->autoLinkUrls      : autoLinkUrls
    * $this->Text->excerpt           : excerpt
    * $this->Text->highlight         : highlight
    * $this->Text->stripLinks        : stripLinks
    * $this->Text->tail              : tail
    * $this->Text->toList            : toList
    * $this->Text->truncate          : truncate

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
    * $this->Time->wasWithinLast     : wasWithinLast
    * $this->Time->wasYesterday      : wasYesterday

Misc Snippets

    * $this->data                    : td
    * $this->request->data           : trd
    * debug();                       : db

    * firecake();                    : fc
    * FireCake::dump();              : fcd
    * FireCake::error();             : fce
    * FireCake::info();              : fci
    * FireCake::log();               : fcl
    * FireCake::warn();              : fcw

Utilities

    * Cache::clear                   : clear
    * Cache::clearGroup              : clearGroup
    * Cache::config                  : config
    * Cache::decrement               : decrement
    * Cache::delete                  : delete
    * Cache::gc                      : gc
    * Cache::increment               : increment
    * Cache::read                    : read
    * Cache::set                     : set
    * Cache::write                   : write

    * CakeLog::config                : config
    * CakeLog::configured            : configured
    * CakeLog::defaultLevels         : defaultLevels
    * CakeLog::disable               : disable
    * CakeLog::drop                  : drop
    * CakeLog::enable                : enable
    * CakeLog::enabled               : enabled
    * CakeLog::levels                : levels
    * CakeLog::stream                : stream
    * CakeLog::write                 : write
    * CakeLog::alert                 : alert
    * CakeLog::critical              : critical
    * CakeLog::debug                 : debug
    * CakeLog::emergency             : emergency
    * CakeLog::info                  : info
    * CakeLog::notice                : notice

    * CakeNumber::addFormat          : addFormat
    * CakeNumber::currency           : currency
    * CakeNumber::defaultCurrency    : defaultCurrency
    * CakeNumber::format             : format
    * CakeNumber::formatDelta        : formatDelta
    * CakeNumber::fromReadableSize   : fromReadableSize
    * CakeNumber::precision          : precision
    * CakeNumber::toPercentage       : toPercentage
    * CakeNumber::toReadableSize     : toReadableSize

    * Inflector::camelize            : camelize
    * Inflector::classify            : classify
    * Inflector::humanize            : humanize
    * Inflector::pluralize           : pluralize
    * Inflector::reset               : reset
    * Inflector::rules               : rules
    * Inflector::singularize         : singularize
    * Inflector::slug                : slug
    * Inflector::tableize            : tablize
    * Inflector::underscore          : underscore
    * Inflector::variable            : variable
    
    * Configure::read                : read
    * Configure::write               : write

Installing
----------

*With Package Manager:*

* Press "ctrl+shift+p"
* Enter "Package Control: Add Repository"
* Enter "http://github.com/openam/SublimeCakePHP"
* Press "ctrl+shift+p"
* Enter "Package Control: Install Package"
* Enter "SublimeCakePHP"

*Without Git:* Download the latest source from http://github.com/openam/SublimeCakePHP and copy the whole directory into the Packages directory.

*With Git:* Clone the repository in your Sublime Text 3 Packages directory, located somewhere in user's "Home" directory:

> git clone git://github.com/openam/SublimeCakePHP.git

The "Packages" directory should be located at:

* Windows:
    %APPDATA%\Sublime Text 3\Packages
* OS X:
    ~/Library/Application Support/Sublime Text 3/Packages
* Linux:
    ~/.config/sublime-text-3/Packages
* Portable Installation:
    Sublime Text 3/Data/Packages

License
-------
These snippets are based on code from the [CakePHP](http://cakephp.org) framework and is released under the MIT license.
