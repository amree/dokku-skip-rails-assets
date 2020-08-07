# README

This plugin will skip Rails assets precompilation by creating a manifest file
and it'll also make sure nodejs buildpack won't detect it as a javascript
application by removing `package.json`

## Development

Rather than pushing the code, we can just rebuild to test this plugin:

```
dokku ps:rebuild image_name
```

## Installation

```bash
# Install
sudo dokku plugin:install https://github.com/amree/dokku-skip-rails-assets.git

# Uninstall
sudo dokku plugin:uninstall skip-rails-assets
```
