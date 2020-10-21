# Dutch Language Pack for [Flarum](http://flarum.org/)

Extension to localize the Flarum forum software and its official extensions into Dutch.

## Information

### Compatibility

This language pack is compatible with:

* [Flarum core](https://github.com/flarum/core) (v0.1.0-beta.14)
    * All bundled extensions

* Third party extensions:
    * [Discussion views](https://discuss.flarum.org/d/7339)
    * [Profile views](https://discuss.flarum.org/d/7596)
    * [Mybb to Flarum](https://discuss.flarum.org/d/18962)
    * [Fof Follow tags](https://discuss.flarum.org/d/20525)
    * [Fof forum stats](https://discuss.flarum.org/d/22380)
    * [Fof nightmode](https://discuss.flarum.org/d/21492)
    * [Google Login](https://discuss.flarum.org/d/18250)

## Installation

### Using Composer

Flarum uses Composer to manage its dependencies and extensions. The Dutch language pack, available [on Packagist](https://packagist.org/packages/michaelbelgium/flarum-dutch), is also manageable with Composer. Make sure that [Composer](https://getcomposer.org/) is installed on your machine, then run the following command in the location where Flarum is installed:

```
composer require michaelbelgium/flarum-dutch
```

### Manual Installation

You can also manually ADD the Dutch language pack as Flarum's dependency. Open the *composer.json* file located at the root of your Flarum installation (not the language pack one!) with [a text editor](https://en.wikipedia.org/wiki/Comparison_of_text_editors), then add to the list of Flarum's dependencies (which are listed below the `"require"` property) the following line in a new line:

```
"michaelbelgium/flarum-dutch": "^3.0"
```

### Third party extensions

This language pack does not supply translations for third party extensions. If you need an extension translated you should either contact the extension creator or create it yourself and make a PR to this repository. You can also ask me to do it, maybe I'll have some sparetime ;)

**I recommend creating a pull request to this repository in stead of adding a pull request to the third party extension**

### License

Released under the MIT License. Please see the LICENSE file.

## Contributing

Thank you a lot to wish to contribute. It means a lot. Using and enjoying the localization is already a huge support. Best other ways to contribute are, among other things:

- Open [issues](https://github.com/MichaelBelgium/flarum-dutch/issues) on GitHub. Because the localization will be better with your feedbacks.
- Open pull requests on GitHub. Submit fixes and improvements and be listed as contributor!
