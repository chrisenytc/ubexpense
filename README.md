
# UbExpense

> A Nylas N1 plugin to help people see how much they had spent with Uber.

## Status

# [![Github All Releases](https://img.shields.io/github/downloads/chrisenytc/ubexpense/total.svg?maxAge=2592000)](https://github.com/chrisenytc/ubexpense/releases) [![Maintenance](https://img.shields.io/maintenance/yes/2017.svg?maxAge=2592000)]() [![GitHub release](https://img.shields.io/github/release/chrisenytc/ubexpense.svg?maxAge=2592000)]() [![License](https://img.shields.io/github/license/chrisenytc/ubexpense.svg?maxAge=2592000)](https://github.com/chrisenytc/ubexpense/blob/master/LICENSE) [![Twitter Follow](https://img.shields.io/twitter/follow/chrisenytc.svg?style=social&label=Follow&maxAge=2592000)](http://twitter.com/chrisenytc) [![Twitter URL](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&maxAge=2592000)](https://twitter.com/intent/tweet?text=Awesome%20https://github.com/chrisenytc/ubexpense%20via%20@chrisenytc)

## How to install this plugin

1. Download and run N1

2. Download the latest version of [UbExpense](https://github.com/chrisenytc/ubexpense/releases/latest)

3. Navigate to Preferences > Plugins and click "Enable" beside the plugin.

4. You also will need to change some personal constants on [lib/calculate-button.jsx](lib/calculate-button.jsx#L16)

## Build documentation

```shell
$ cjsx-transform lib/main.cjsx > docs/main.coffee
$ docco docs/main.coffee
$ rm docs/main.coffee
```

## Donate

If **UbExpense** was helpful for you, send a donation as a thank you. :)

![Bitcoin](bitcoin-address.png)

**Bitcoin Adddress**: `3QbTQcSfWAUntPwTrWNQ3aHYYmvJS5HoUY`

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/chrisenytc/ubexpense](https://github.com/chrisenytc/ubexpense). This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

1. Fork it [chrisenytc/ubexpense](https://github.com/chrisenytc/ubexpense/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am "Add some feature"`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Support
If you have any problem or suggestion please open an issue [here](https://github.com/chrisenytc/ubexpense/issues).

## License 

Check [here](LICENSE).
