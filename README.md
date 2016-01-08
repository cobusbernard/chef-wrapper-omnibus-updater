# chef-wrapper-omnibus-updater-cookbook

Wrapper cookbook to handle the updating of the Chef clients usint Omnibus.

## Supported Platforms

Ubuntu 14.04

## Usage

### chef-wrapper-omnibus-updater::default

Include `chef-wrapper-omnibus-updater` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-wrapper-omnibus-updater::default]"
  ]
}
```

## License and Authors

Author:: Cobus Bernard (<me@cobus.io>)
