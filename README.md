# laravel-plugins
Plugin system for Laravel 5.x and Lumen 5.x.
Plugins can overwrite and extend each other.

## Usage
For Lumen add to bootstrap/app.php:
`$app->register(\Oneso\LaravelPlugins\PluginServiceProvider::class);`

For Laravel add to 'providers' array in config/app.php:
`\Oneso\LaravelPlugins\PluginServiceProvider::class,`
