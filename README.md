# fonts-asset-Devicon
Devicon for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/devicon
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/devicon/devicon.css">
```

## Credit

[Devicon](https://github.com/devicons/devicon)