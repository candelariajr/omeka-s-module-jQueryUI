# jQueryUI for Omeka S

This module does nothing on itself but provides [jQueryUI] JS library for other modules

## Usage

Install and activate this module, then add the following to your templates:

```php
$this->headScript()->appendFile($this->assetUrl('jquery-ui.min.js', 'jQueryUI'));
$this->headLink()->appendStylesheet($this->assetUrl('jquery-ui.min.css', 'jQueryUI'));
```

To make this usable globally, place here: 
/theme/theme_name/view/layout.phml

[jQueryUI]: https://jqueryui.com/
