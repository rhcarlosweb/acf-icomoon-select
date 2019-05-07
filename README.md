**This just my first plugin for WordPress, so feel free to contribute :)**

# ACF IcoMoon
Is a ACF Field Type to show ico select field based on selection.json generated from IcoMoon App

## Screenshots
![Field Type Settings ACF](/screenshots/screenshot-acf-config.jpg?raw=true "Field Type Settings ACF")

![Icon List](/screenshots/screenshot-acf-rendered-field.jpg?raw=true "Icon List")

## Compatibility

This ACF field type is compatible with ACF version:

* ACF 5+

## Installation

Soon

## Filters

```php
/**
* Update JSON file URL selection.json generated by icomoon
*
* This will change the URL of selection.json file for all created IcoMoon fields
*
* @return string
*/
add_filter( 'rhicomoon_json_url', 'change_icomoon_json_url' );
function change_icomoon_json_url() {
   return 'https://example.com/selection.json';
}
```

Thanks [@swashata](https://github.com/swashata) and [@micc83](https://github.com/micc83) for the amazing jquery plugin fonticonpicker
