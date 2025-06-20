### v1.0.11
* bump ruby version to 3.2.2
* add support for ESR reference

### v1.0.10
* fixed pipeline error (new svg style attribute) -> style=fill:#000
* fixed locales error for EN and FR

### v1.0.9
* added support for address of type "K"

### v1.0.8
* added SVG support

### v1.0.7
* make default locale dynamic

### v1.0.6
* fix amount formatting ('%.2f') - in generator as well
* adjust qr error code to m as specs: see PR#18 - in generator as well

### v1.0.5
* fix amount formatting ('%.2f')
* adjust qr error code to m as specs: see PR#18

### v1.0.4
* remove rake dependency

### v1.0.3
* switch CI from Travis to CircleCI

### v1.0.2
* fix typo for French
* fix locale setting in html template

### v1.0.1
* fix typo in constant

### v1
* change license to BSD-3
* improve tests
* improve comments
* improve validations for supported qr bills
* improve readme / documentation
* fix typo in param: alternative_scheme_parameters

### v0.3
* refactoring and fix typos
* remove RMagick and use ChunkyPNG
* add output format qrcode-png
* fix import of locales

### v0.2.2
* fix locales / translations

### v0.2.1
* add locales path params to reference from Rails
* remove deprecation warning of RMagick dependency

### v0.2
* add creditor reference ISO-11649 generator

### v0.1.2
* fix layout

### v0.1.1
* fix generator

### v0.1
* first release
* qr generation
* multilanguage support
* export as html-layout