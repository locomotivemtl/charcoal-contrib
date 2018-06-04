# Charcoal Contrib

Community supported 3rd party packages for Charcoal.

Contrib serves as a boilerplate and forum for discussing issues and new features for Charcoal.

### Officially Supported Plugins

#### [mcaskill/charcoal-support](https://packagist.org/packages/mcaskill/charcoal-support) ![Latest Stable Version](https://img.shields.io/packagist/v/mcaskill/charcoal-support.svg?style=flat-square)
> Support package for Charcoal

#### [mcaskill/charcoal-recaptcha](https://packagist.org/packages/mcaskill/charcoal-recaptcha) ![Latest Stable Version](https://img.shields.io/packagist/v/mcaskill/charcoal-recaptcha.svg?style=flat-square)
> Google reCAPTCHA for Charcoal

#### [mducharme/charcoal-presenter](https://packagist.org/packages/mducharme/charcoal-presenter) ![Latest Stable Version](https://img.shields.io/packagist/v/mducharme/charcoal-presenter.svg?style=flat-square)
> The missing layer between models and views

#### [locomotivemtl/charcoal-contrib-communicator](https://packagist.org/packages/locomotivemtl/charcoal-contrib-communicator) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-communicator.svg?style=flat-square)
> Standardizes email communications destined for users and administors.

#### [locomotivemtl/charcoal-contrib-content-builder](https://packagist.org/packages/locomotivemtl/charcoal-contrib-content-builder) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-content-builder.svg?style=flat-square)
> Utilities for content builder style attachments, using group attachment widget.

---

### Package Skeleton

The skeleton, named "foobar", can be found under the [`/package-name`](package-name) directory.

1.  Vendor/Package:
    -   `charcoal-contrib-%my-feature%`
2.  Replace:
    -   `charcoal-contrib-foobar`
    -   `foo-bar`
    -   `FooBar`
    -   "Charcoal service provider for my cool feature."
3.  Remove:
    -   `metadata/charcoal/foo-bar/example-interface.json`
    -   `src/Charcoal/FooBar/ExampleInterface.php`
    -   `tests/Charcoal/FooBar/ExampleTest.php`
4.  Update:
    -   [`composer.json`](/package-name/composer.json)
    -   [`.travis.yml`](/package-name/.travis.yml)
    -   [`README`](/package-name/README.md)
