# Quote Kirbytag for Kirby CMS v3

Forked from [Jannik Beyerstedt](https://github.com/jbeyerstedt/kirby-kirbytag-quote) by [Julien Bidoret](https://accentgrave.net).

**license:** GNU GPL v3  
**version:** v2.0.0

## Introduction
This Kirbytag creates a html `blockquote` tag with the option to add an author and a source URL via a footer tag.


## User Manual

#### Installation
For manual installation, copy all of these files to `site/plugins/kirbytag-quote`.

If you are using git submodules to manage the plugins, use this command:
```
git submodule add https://github.com/jbidoret/kirby-kirbytag-quote site/plugins/kirbytag-quote
```

#### Configuration
Default classname can be added in your `config.php`:

```php
return [
    'accentgrave.quote.blockquote_classname' => 'pullquote',
]
```

#### Usage
Use this kirbytag as every other one in your text. Here are some examples:

```
(quote: Awesome quote author: me)
(quote: False quote author: Donald url: https://donald.com)
(quote: Nonsense quote author: Donald url: https://donald.com urltext: Guess who )

```

##### Parameters

* quote: The sentence or paragraph you want to cite
* class: (optional) css class to add to the blockquote
* author: (optional) the author, will be set a footer html tag
* url: (optional) url for blockquote source
* urltext: (optional) clickable text for url
