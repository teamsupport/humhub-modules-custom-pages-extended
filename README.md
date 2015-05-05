Custom Pages Extended
============

Allows admins to add custom pages (html, **php**, or markdown), widgets (php), iframes or external links to various navigations (e.g. top navigation, account menu).

- __Status:__ Alpha v0.2.1
- __Module website:__ <https://github.com/WASasquatch/humhub-modules-custom-pages-extended/>
- __Author:__ Jordan Thompson, Luke
- __Author website:__ [Jordan Thompson @ HumHub](http://community.humhub.org)

### New Features in Extended Version

- **Widgets** Create widgets with inline-modules!
- **PHP** Pages for Inline-Module Creation!
- **Active User Model** data passed for Inline-Module creation, or other software, such as use for chat nicknames.
- **More Soon** ...

### Installation

- Simply drop the module as **custom_pages** into your `/protected/modules/` folder
- Activate the module

### PHP Page / Widget Usage

- The PHP pages run off the eval() functioning, meaning all supplied input needs to be already in PHP Mode. Do not start, or end with `<?php ... ?>`, instead write as if already in PHP Mode. 
- You can use the object var `$user` to access user information such as the user display name `$user->displayName`
- [Example Inline-Module HStats](https://github.com/WASasquatch/humhub-modules-custom-pages-extended/blob/master/docs/example.md)

For more  information visit parent module:
<https://github.com/humhub/humhub-modules-custom-pages>
