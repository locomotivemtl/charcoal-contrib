# Charcoal Contrib

Community supported 3rd party packages for Charcoal.

Contrib serves as an index and forum for discussing issues and new features for Charcoal.

### Officially Supported Packages

#### [locomotivemtl/charcoal-contrib-communicator](https://packagist.org/packages/locomotivemtl/charcoal-contrib-communicator) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-communicator.svg?style=flat-square)
> Standardizes email communications destined for users and administors.

#### [locomotivemtl/charcoal-contrib-content-builder](https://packagist.org/packages/locomotivemtl/charcoal-contrib-content-builder) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-content-builder.svg?style=flat-square)
> Utilities for content builder style attachments, using group attachment widget.

#### [locomotivemtl/charcoal-contrib-embed](https://packagist.org/packages/locomotivemtl/charcoal-contrib-embed) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-embed.svg?style=flat-square)
> Service provider for an embed parser widget that stores parsed data into a table (with support for locomotivemtl/charcoal-cache).

#### [locomotivemtl/charcoal-contrib-filepond](https://packagist.org/packages/locomotivemtl/charcoal-contrib-filepond) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-filepond.svg?style=flat-square)
> Service provider for Filepond integration.

#### [locomotivemtl/charcoal-contrib-formio](https://packagist.org/packages/locomotivemtl/charcoal-contrib-formio) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-formio.svg?style=flat-square)
> Service provider for form.io integration (form builder property input).

#### [locomotivemtl/charcoal-contrib-guide](https://packagist.org/packages/locomotivemtl/charcoal-contrib-guide) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-guide.svg?style=flat-square)
> Admin guide module.

#### [locomotivemtl/charcoal-contrib-mailchimp](https://packagist.org/packages/locomotivemtl/charcoal-contrib-mailchimp) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-mailchimp.svg?style=flat-square)
> Service provider for Mailchimp integration.

#### [locomotivemtl/charcoal-contrib-notification](https://packagist.org/packages/locomotivemtl/charcoal-contrib-notification) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-notification.svg?style=flat-square)
> Admin notification module.

#### [locomotivemtl/charcoal-contrib-property-filter](https://packagist.org/packages/locomotivemtl/charcoal-contrib-property-filter) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-property-filter.svg?style=flat-square)
> Admin collection filtering widget that uses model properties as filters.

#### [locomotivemtl/charcoal-contrib-search](https://packagist.org/packages/locomotivemtl/charcoal-contrib-search) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-search.svg?style=flat-square)
> Search module.

#### [locomotivemtl/charcoal-contrib-sitemap](https://packagist.org/packages/locomotivemtl/charcoal-contrib-sitemap) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-sitemap.svg?style=flat-square)
> Sitemap builder.

#### [locomotivemtl/charcoal-contrib-tinify](https://packagist.org/packages/locomotivemtl/charcoal-contrib-tinify) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-tinify.svg?style=flat-square)
> Service provider for Tinify integration.

#### [locomotivemtl/charcoal-contrib-translatable-strings](https://packagist.org/packages/locomotivemtl/charcoal-contrib-translatable-strings) ![Latest Stable Version](https://img.shields.io/packagist/v/locomotivemtl/charcoal-contrib-translatable-strings.svg?style=flat-square)
> Admin interface for translating strings found in templates and controllers.

#### [mcaskill/charcoal-support](https://packagist.org/packages/mcaskill/charcoal-support) ![Latest Stable Version](https://img.shields.io/packagist/v/mcaskill/charcoal-support.svg?style=flat-square)
> Utility belt.

#### [mcaskill/charcoal-recaptcha](https://packagist.org/packages/mcaskill/charcoal-recaptcha) ![Latest Stable Version](https://img.shields.io/packagist/v/mcaskill/charcoal-recaptcha.svg?style=flat-square)
> Service provider for Google reCAPTCHA integration.

---

### Package Skeleton

We provide a template repository, [locomotivemtl/charcoal-contrib-template](https://github.com/locomotivemtl/charcoal-contrib-template), to help you create new repositories with the same directory structure and files as used by existing Charcoal packages.

1.  Vendor/Package:
    -   `charcoal-contrib-%my-feature%`
2.  Replace:
    -   `charcoal-contrib-foobar`
    -   `foo-bar`
    -   `FooBar`
    -   "Charcoal service provider for my cool feature."
3.  Remove:
    -   `config/config.json`
    -   `metadata/admin/charcoal/foo-bar/example-interface.json`
    -   `metadata/charcoal/foo-bar/example-interface.json`
    -   `src/Charcoal/FooBar/ExampleInterface.php`
    -   `tests/Charcoal/FooBar/ExampleTest.php`
4.  Update:
    -   `composer.json`
    -   `.travis.yml`
    -   `README`
    -   `LICENSE`
