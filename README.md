# generamba-templates
[Generamba](https://github.com/rambler-digital-solutions/Generamba) - code generator for Xcode. Repository contains templates.

## List of templates

* [MVP screen](https://github.com/Jopses/generamba-templates/tree/master/main_mvp_screen) - generates a new screen of MVP architecture.
* [MVP table screen](https://github.com/Jopses/generamba-templates/tree/master/main_mvp_table_screen) - generates a new screen of MVP architecture contains UITableView.
* [VIPER screen](https://github.com/Jopses/generamba-templates/tree/master/main_viper_screen) - generates a new screen of VIPER architecture.
* [VIPER table screen](https://github.com/Jopses/generamba-templates/tree/master/main_viper_table_screen) - generates a new screen of VIPER architecture contains UITableView.

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/Jopses/generamba-templates'

### Templates
templates:
- {name: template_name}
```
