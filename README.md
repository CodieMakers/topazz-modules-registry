# Topazz Modules Registry

Repository containing list of available modules and themes for Topazz CMS.


## Add your module/theme

If you want your module or theme to be available in Topazz CMS, 
- fork this repository 
- add your module name and info into the appropriate file
- and create pull request

### Recognizable options

| Option | Example | Description |
|:-------|:----------------|:------------|
composer | `vendor/package` | Name of package to be installed via Composer
description | `Awesome package` | Some short text to describe your awesome work
license | `GPL-2.0` | License in format of SPDX (see [list of license IDs](https://spdx.org/licenses/))
author.name | `John Doe` | Name of the author
author.email | `john.doe@example.com` | Email of the author
author.url | `https://johndoe.example.com` | URL of the author's homepage
support | `https://support.myorg.com/mypackage/` | Support page or email
issues | `https://github.com/mynick/mypackage/issues` | Issue tracker's homepage
picture | `http://raw.github.../picture.png` | Representative picture that can be provided in administration

#### :warning: Required `composer`
If the `composer` option is not specified, the module cannot be installed. All other options are optional but recommended.
