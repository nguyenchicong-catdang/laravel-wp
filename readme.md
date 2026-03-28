## laravel-app/composer.json
```json
"repositories": [
        {
            "type": "path",
            "url": "../../laravel-wp-local-packages",
            "options": {
                "symlink": true
            }
        }
    ],

    "require": {
    "php": "^8.3",
    "laravel/framework": "^13.0",
    "laravel/tinker": "^3.0",
    "laravel-wp-local-packages": "dev" 
},

    "minimum-stability": "dev",
```

> composer update