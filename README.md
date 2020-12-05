<h3 align="center">Codename: Summer CMS (our October CMS update proposal) - Legal Module</h3>

<p align="center"><img src="https://github.com/ayumi-cloud/sc-legal-module/blob/master/src/assets/images/legal-cover.jpg"></p>

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/stars.svg" alt="stars"> <a href="https://travis-ci.org/#"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/travis.svg" alt="Build Status"></a> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/php.svg"> <a href="https://codecov.io/gh/#"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/coverage.svg" alt="Codecov"></a> <a href="https://pullreminders.com?ref=badge"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/pull.svg" alt="Pull Reminders"></a> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/conduct.svg" alt="conduct"> <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/docs.svg" alt="docs"></p>

<p align="center"><a href="https://paypal.me/#"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/paypal-button.svg"></a></p>

<p align="center">This repo to gather legal enhancement ideas and to monitor progress. Feel free to add issues containing legal ideas, requests and infomation.</p>

<p align="center"><strong>The legal code is not held in this repo - but in a private repo (being heavily developed)</strong></p>

---

## Summer CMS Modules :eyes:

**Note: (*) This is a very brief overview of the modules and doesn't list the full features included in each module (this is intended to give users an overview picture).**

- **[Security Module](https://github.com/ayumi-cloud/sc-security-module)** - Enhanced security features including firewall, virus scanner, code checker, 2fa, u2f, security api's etc.
- **[Legal Module](https://github.com/ayumi-cloud/sc-legal-module)** - Legal features including tools for GDPR, ePrivacy, CCPA, Cookie Policy, Privacy Policy, Terms and Conditions, 2257 etc.
- **Protocol Module** - Intergrated features including HTTP/2, HTTP/3 with QUIC, IPFS, preloading, predictive prefetching etc.
- **Progressive Web Apps Module** - PWA and DPWA, Service workers, caching, manifest, banners, icons, badges, native api's etc.
- **AMP-HTML Module** - AMP-HTML features making it easier to create AMP-Content, AMP-Email and AMP-Stories etc.
- **Semantic Module** - Schema.org, JSON-LD, microformats, ontologies etc.
- **Frameworks Module** - Vanilla js ajax framework (no more jquery), intergrated features for Angular, React, Vue.js, Bootstrap, Web Components etc.

- **Developer Module** - 

- **CDN Module** - 

- **Layout and Dashboard Module** - 

- **Performance Module** - 

- **Internalization Module** - 

- **Crypto and Web 3.0 Module** - 

- **Form Module** - 


...more modules will be uploaded

## Table of contents

- [Transparency](#transparency-)
- [Introduction](#intro-)
- [Naming Prefix](#naming-prefix-%EF%B8%8F)
- [Goals](#goals-soccer)
- [Privacy Controls](#privacy-controls-sparkles)
- [Machine Learning](#machine-learning-computer)
- [Citation](#citation-)
- [Usage](#usage-)
  - [Requirements](#requirements-)
  - [Enable the following Apache httpd modules](#enable-the-following-apache-httpd-modules-)
  - [Microsoft IIS Server](#microsoft-iis-server-%EF%B8%8F)
  - [Nginx Server](#nginx-server-)
  - [API's](#apis-gem)
- [Issues](#issues-)
- [Completed Issues](#completed-issues-)
- [Reporting a Vulnerability](#reporting-a-vulnerability-)
- [Code of Conduct](#code-of-conduct-)
- [For Future](#for-future-)
- [Contributing](#contributing-)
- [PSR](#psr-%EF%B8%8F)
- [Semantic Versioning](#semantic-versioning-)
- [Copyright and License](#copyright-and-license-)

## Transparency 📢

This project is completely transparent and honest, before we started we contacted and discussed this project with the authors and admins of the October project. We have given the links to this repo to the authors and we continue to want to be transparent throughout the whole process! We feel it's important to state this and be open. This repo is made up of one module, which is part of several other modules all dedicated to different sections of an Summer CMS proposal. Instead of writing ideas and suggestions, we have taken a pro-active approach and are actively coding a fully working solution. The code is held on private repo's because the code is being heavily developed and changed on a daily basis. We will release a stable release to the admins and authors in private for feedback before releasing to the general public. This is a long-term project and will continue to grow!

Over years we have coded and created well over a hundred pull requests (under various github accounts) which have been merged to the October version one projects core, we have never asked or recevived any money for any of the pull requests. We use the cms for professional purposes and therefore it is beneficial for our companies to have a professional working solution to give our end-users and clients. In order for us to delivery a high quality product we made the discussion to update the cms as there have been a lot of new api's, frameworks, libraries  and technologies been added to the internet over the years since the initial release of the cms.

## Introduction :star:

There are lots of many mediocre projects trying to tackle this subject and use either insecure cookies or dont even pass ePrivacy and GDPR laws properly. Laravel is a wonderful framework and we have built all the tools directly into the Summer CMS framework for developers and webmasters to easily create all their legal web pages for their websites and apps. Everything is fully customizable and takes very little time to setup.

The legal module has been fully optimized to work with `Desktop`, `Mobile`, `DPWA`, `PWA`, `AMP-HTML` and `AMP-HTML Stories`.

(*) More platforms will be added in the near future.

## Naming Prefix ✒️

**Summer CMS uses the `sc-` naming prefix to advoid conflicts.**

## Goals :soccer:

The legal module makes it easier to create and manage with custom built tools for the following:

- 18 U.S.C. 2257 Compliance Notice
- California Consumer Privacy Act (CCPA)
- Cookie Policy
- Copyright Notification
- Copyscape Plagiarism Policy
- Creative Commons License
- Data Protection Officer (DPO)
- Digital Millennium Copyright Act (DMCA)
- ePrivacy
- EU Representative
- EU-U.S. Privacy Shield Frameworks
- GDPR
- Guidelines for Law Enforcement
- Health Insurance Portability and Accountability Act (HIPAA)
- Master Services Agreement (MSA)
- Opt-In Policy
- Opt-Out Policy
- Privacy Policy
- Push Notification Policy
- Spam Abuse
- Swiss-U.S. Privacy Shield Frameworks
- Terms and Conditions

## Privacy Controls :sparkles:

This module allows the website / app's external users to have full control of their privacy policies giving them all the correct infomation and controls to adjust their settings they way they want. The developer is given easy to use tools to setup the privacy controls, using a simple wrapper method on sections of code they wish to allow the end-users to be able to control. Webmasters can setup their privacy in no time at all, without needing to write any code at all, using the module's custom tools and be able to preview everything in the backend, without needing to switch to the frontend to preview the end result.

## Machine Learning :computer:

This module uses machine learning to help speed up creating the legal pages for your website / app and uses custom json datasets.

## Citation 📚

<a href="https://zenodo.org/">
  <img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/citation.svg" />
</a>

If you use this legal module for your research, then kindly cite it. Click the above badge for more information regarding the complete citation for this legal module and the diffferent citation formats like: IEEE, APA, BibTeX, CSL, DataCite, Dublin Core, DCAT, JSON, JSON-LD, GeoJSON, MARCXML and Mendeley etc.

## Usage 🔧

<img src="https://github.com/ayumi-cloud/sc-legal-module/blob/master/src/assets/images/laravel.svg">

- Laravel `5.x` to `8.x` are supported.

### Requirements 🚩

This library requires the following:

- PHP `7.3` or greater (in the near future we hope to increase this to php 7.4 or 8.0). PHP `7.3+` allows `SameSite` Cookie protection.

PHP `8.0` is coming around November 2020 and we have plans to update our code around the end of this year. PHP is currently releasing **major** updates every two years! Therefore we plan to update and review the code every two years periodically. For update instructions please see here: [PHP 8.0 UPGRADE NOTES](https://github.com/php/php-src/blob/master/UPGRADING#L20)

- Laravel 6.0 LTS (we currently use the latest LTS versions, due to the community consensus).

<p align="center"><img src="https://github.com/ayumi-cloud/sc-legal-module/blob/master/src/assets/images/laravel-history.png"></p>

Laravel 7 continues the improvements made in Laravel 6.x by introducing Laravel Airlock. Laravel Airlock provides a featherweight authentication system for SPAs (single page applications), mobile applications, and simple, token based APIs. We recommend the following:

- Laravel 6.0 LTS to use [Laravel Passport](https://laravel.com/docs/6.x/passport).

- Laravel 7 to use [Laravel Airlock](https://laravel.com/docs/master/airlock). To learn more you can watch this video: [Laravel Airlock with Vue for SPA Auth](https://www.youtube.com/watch?v=D9oIu6jiYLk).

- Laravel 8 is Now Released, for full details of new features see here: https://laravel-news.com/laravel8 and https://laravel.com/docs/8.x/releases

- SQLite 3.7.11 or greater (we recommend the latest version of SQLite, which can be found here: [Latest Release](https://www.sqlite.org/index.html)).

#### Enable the following Apache httpd modules 🔧

We have a dedicated Apache section for users using `.htaccess` some configurations won't have any effect if the appropriate modules aren't enabled. So, in order for everything to work as intended, you need to ensure the you have the following Apache modules enabled:

* [`mod_autoindex.c` (autoindex_module)](https://httpd.apache.org/docs/current/mod/mod_autoindex.html)
* [`mod_deflate.c` (deflate_module)](https://httpd.apache.org/docs/current/mod/mod_deflate.html)
* [`mod_expires.c` (expires_module)](https://httpd.apache.org/docs/current/mod/mod_expires.html)
* [`mod_filter.c` (filter_module)](https://httpd.apache.org/docs/current/mod/mod_filter.html)
* [`mod_headers.c` (headers_module)](https://httpd.apache.org/docs/current/mod/mod_headers.html)
* [`mod_include.c` (include_module)](https://httpd.apache.org/docs/current/mod/mod_include.html)
* [`mod_mime.c` (mime_module)](https://httpd.apache.org/docs/current/mod/mod_mime.html)
* [`mod_rewrite.c` (rewrite_module)](https://httpd.apache.org/docs/current/mod/mod_rewrite.html)
* [`mod_setenvif.c` (setenvif_module)](https://httpd.apache.org/docs/current/mod/mod_setenvif.html)

For more detailed information on configuration files and how to use them, please check the appropriate Apache documentation:

* <https://httpd.apache.org/docs/current/configuring.html>
* <https://httpd.apache.org/docs/current/howto/htaccess.html>

##### **Support**

 * Apache **2.4.10 or greater** (we are looking at adding some version 2.5 features in the near future)

#### Microsoft IIS Server 🛠️

The server settings target IIS7+ where replacement config is available for IIS8 (or simplification) it will be marked.

##### **Support**

 * **IIS7+**

#### Nginx Server 🔨

Using the Nginx server settings has a few required steps to be able to work.

* [Nginx Beginners Guide](https://nginx.org/en/docs/beginners_guide.html)
* [Nginx Request Processing](https://nginx.org/en/docs/http/request_processing.html)

##### **Support**

* Nginx v**1.8.0**+

#### API's :gem:

- Javascript uses **Trusted Types API** to prevent DOM-based cross-site scripting vulnerabilities. Also the **MutationObserver API** to update the machine learning DOM nodes.

## Issues 🔨

<img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/ayumi-cloud/sc-legal-module?style=plastic"> <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/ayumi-cloud/sc-legal-module">

If you face any issue, you can create a new issue in the Issues Tab and we will be glad to help you out!

## Reporting a Vulnerability 💥

We strive to make the code accessible to a wide audience of beginner and experienced users.

We welcome bug reports, false positive alert reports, evasions, usability issues, and suggestions for new detections.
Submit these types of non-vulnerability related issues via Github.

Please include your installed version and the relevant portions of your audit log.

False negative or common bypasses should [create an issue](https://github.com/ayumi-cloud/sc-legal-module/issues/new) so they can be addressed.

Do this before submitting a vulnerability:

1) Verify that you have the latest version of October CMS II.
2) Validate which Paranoia Level this bypass applies to. If it works in PL4, please send us an email.
3) If you detected anything that causes unexpected behavior of the engine via manipulation of existing provided rules, please send it by email.

We are happy to work with the community to provide CVE identifiers for any discovered security issues if requested.

If in doubt, feel free to reach out to us!

## Code of Conduct 💯

In order to ensure that the Summer CMS proposal community is welcoming to all, please review and abide by the [Code of Conduct](https://github.com/ayumi-cloud/sc-legal-module/blob/master/CODE_OF_CONDUCT.md).

## For Future 🔮

Shoutout to people willing to contribute to this project. Please take a look at the [projects board](https://github.com/ayumi-cloud/sc-legal-module/projects) for a list of things to be done.

## Contributing ✨

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/builtWith.svg"></p>

If you find any bugs in the code or have any improvements in mind then feel free to generate a pull request.

**Note:** Please use Unit Testing and Coding Best Practices in order to have a valid pull request 😉

Patches and pull requests are encouraged. All code should follow the [PSR-1](https://www.php-fig.org/psr/psr-1/) and [PSR-2](https://www.php-fig.org/psr/psr-2/) style guidelines. **Please include unit tests whenever possible!**

### PSR ♻️

This legal module uses some PSR standards to be the most interoperable possible:

- [PSR-6](https://www.php-fig.org/psr/psr-6/) Caching Interface.
- [PSR-7](https://www.php-fig.org/psr/psr-7/) Standard interfaces to represent http requests, responses and uris.
- [PSR-17](https://www.php-fig.org/psr/psr-17/) Standard factories to create PSR-7 objects.
- [PSR-18](https://www.php-fig.org/psr/psr-18/) Standard interface to send a http request and return a response.

We also suggest using Cross-browser testing provided by BrowserStack (*) where a real-browser can't be used in-house.

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/browser-stack.png"></p>

## Semantic Versioning ✅

The legal Module code uses [Semantic Versioning](https://semver.org/).

We have two types of releases, Major releases (3.0.0, 3.1.0, 3.2.0 etc.) and point releases (3.0.1, 3.0.2 etc.).

We officially support the two point releases with security patching preceding the current major release.

We are happy to receive and merge PR's that address security issues in older versions of the project, but the team itself may choose not to fix these.

Along those lines, the team may not issue security notifications for unsupported software.

| Version     | Supported          |
| ----------- | ------------------ |
| 3.3.x-dev   | :white_check_mark: |
| 3.3.x-rc    | :white_check_mark: |
| 3.3.x-beta  | :white_check_mark: |
| 3.3.x-aplha | :white_check_mark: |
| 2.2.x       | :white_check_mark: |
| 2.1.x       | :white_check_mark: |
| 1.0.x       | :white_check_mark: |
| 1.0.x.x     | :x:                |

When the version tag is not stable; e.g. `1.0.0-alpha`, `1.0.0-beta`, `1.0.0-dev` or `1.0.0-rc` (see https://semver.org/#spec-item-11)

Example:

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/semantic.png"></p>

## Copyright and License 📄

<p align="left"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/buttons/mit.svg"></p>

This is free software, licensed under the MIT, Open Source Initiative.

[⬆ back to top](#table-of-contents)

<p align="center"><img src="https://github.com/ayumi-cloud/oc-security-module/blob/master/src/assets/images/luv.png"></p>
