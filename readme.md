# kirby CMS - tag: quote
by Jannik Beyerstedt from Hamburg, Germany  
[jannikbeyerstedt.de](http://jannikbeyerstedt.de) | [Github](https://github.com/jbeyerstedt)  
**license:** GNU GPL v3

## Introduction
This Kirbytag creates a html blockquote tag with the option to add an author via a footer tag.
For everyone using the Boostrap framework, the default Boostrap classes can be activated in the settings.

## User Manual

#### Installation
store the php file in

```
site/tags/
```
    
#### Configuration
To enable the styling classes used by Boostrap 4, add this to your `config.php`:

```php
c::set('quote.default_style', 'bs');
```


#### Usage
Use this kirbytag as every other one in your text. Here are some examples:

```
(quote: Awesome quote author: me)
```

##### Parameters

* quote: The sentence or paragraph you want to cite
* author: (optional) the author, will be set a footer html tag
* class: (optional) css class to add to the blockquote
* cite: (optional) cite tag at the end of the footer tag


## Contribution
Feel free to fork this repository and make it better. If there is a bug I missed, please let me know by opening an issue.
