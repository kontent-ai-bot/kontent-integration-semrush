## :warning: Deprecation notice
> This repository has been archived and is no longer maintained.

> ⚠ Source code of this repository is private due to security and legal reasons

[![Core integration][core-shield]](https://kontent.ai/integrations/semrush)
[![Gallery][gallery-shield]](https://kentico.github.io/kontent-custom-element-samples/gallery/)

![Last modified][last-commit]
[![Issues][issues-shield]][issues-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![MIT License][license-shield]][license-url]

[![Stack Overflow][stack-shield]](https://stackoverflow.com/tags/kentico-kontent)
[![GitHub Discussions][discussion-shield]](https://github.com/Kentico/Home/discussions)

<p align="center">
<image src="docs/kk-logo.png" alt="kontent logo" width="200" /><br/>
<image src="docs/semrush-logo.png" alt="semrush logo" width="350" >
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#configuring-the-custom-element">Installation & Configuration</a> •
  <a href="#authentication">Authentication</a> •
  <a href="#contributors">Contributors</a> •
  <a href="#additional-resources">Resources</a>
</p>

This [custom element](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features) extension for [Kontent by Kentico](https://kontent.ai) allows users to analyze keywords through [Semrush](https://www.semrush.com). 

## Features
Editors can analyze lists of keywords accross different regions. The editor needs to have working semrush account in order to log into the application. 

## Demo

![Demo Animation][product-demo]

## Configuring the Custom Element

To install and configure your extensions, simply create a custom element in your desired content model and fill out the following values:

![config]

The __keywordsElementCodename__ has to contain a codename of a text element/custom element that contains your keywords. There has to be a **semicolon** between the different values. 

Please, keep in mind, that you have to pick the same keyword element from the dropdown under the hosted code URL so the application can access the element and read from it.

## Authentication
Once the extension is setup, everybody accessing the page with the custom element will be prompted to login into their Semrush account.

<p align="center">
<image src="docs/login1.png" alt="semrush login1" >
</p>

Once you login, you'll have to approve Kontent's integration accessing the analytics data. 

<p align="center">
<image src="docs/login2.png" alt="semrush login2" >
</p>

Once this is setup, you'll be able to work with the integration and analyze inserted keywords.

## What is Saved
This custom element doesn't save any value.

## Contributors
We have collected notes on how to contribute to this project in [CONTRIBUTING.md](CONTRIBUTING.md).

<a href="https://github.com/Kentico/kontent-integration-semrush/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Kentico/kontent-integration-semrush" />
</a>

## Additional Resources

- [Custom Element Gallery on github](https://kentico.github.io/kontent-custom-element-samples/gallery/)
- [Kontent's Integration documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrations-overview)
- [Custom Element documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/content-editing-extensions)
- [Custom Element API reference](https://docs.kontent.ai/reference/custom-elements-js-api)



[last-commit]: https://img.shields.io/github/last-commit/Kentico/kontent-integration-semrush?style=for-the-badge
[review]: https://img.shields.io/static/v1?label=warning&message=under%20review&style=for-the-badge&color=orange
[contributors-shield]: https://img.shields.io/github/contributors/Kentico/kontent-integration-semrush.svg?style=for-the-badge
[contributors-url]: https://github.com/Kentico/kontent-integration-semrush/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Kentico/kontent-integration-semrush.svg?style=for-the-badge
[forks-url]: https://github.com/Kentico/kontent-integration-semrush/network/members
[stars-shield]: https://img.shields.io/github/stars/Kentico/kontent-integration-semrush.svg?style=for-the-badge
[stars-url]: https://github.com/Kentico/kontent-integration-semrush/stargazers
[issues-shield]: https://img.shields.io/github/issues/Kentico/kontent-integration-semrush.svg?style=for-the-badge
[issues-url]: https://github.com/Kentico/kontent-integration-semrush/issues
[license-shield]: https://img.shields.io/github/license/Kentico/kontent-integration-semrush.svg?style=for-the-badge
[license-url]: https://github.com/Kentico/kontent-integration-semrush/blob/master/LICENSE
[core-shield]: https://img.shields.io/static/v1?label=&message=core%20integration&style=for-the-badge&color=FF5733
[gallery-shield]: https://img.shields.io/static/v1?label=&message=extension%20gallery&style=for-the-badge&color=51bce0
[stack-shield]: https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white&style=for-the-badge
[discussion-shield]: https://img.shields.io/badge/GitHub-Discussions-FE7A16.svg?logo=github&style=for-the-badge
[product-demo]: docs/semrush.gif?raw=true
[config]: docs/configuration.png
[login1]: docs/login1.png
[login2]: docs/login2.png
