<p align="center">
    <img src="/art/header.png?1" alt="collector header">
    <p align="center">
        <a href="https://github.com/olivernybroe/collections-intellij/workflows"><img alt="GitHub Workflow Status (master)" src="https://github.com/olivernybroe/collections-intellij/workflows/Build/badge.svg"></a>
        <a href="https://plugins.jetbrains.com/plugin/15246"><img alt="Total Downloads" src="https://img.shields.io/jetbrains/plugin/d/15246"></a>
        <a href="https://plugins.jetbrains.com/plugin/15246"><img alt="Latest Version" src="https://img.shields.io/jetbrains/plugin/v/15246"></a>
	    <a href="https://plugins.jetbrains.com/plugin/15246"><img alt="Latest EAP Version" src="https://img.shields.io/badge/dynamic/xml?label=EAP version&query=%2Fplugin-repository%2Fcategory%2Fidea-plugin%5B1%5D%2Fversion&url=https%3A%2F%2Fplugins.jetbrains.com%2Fplugins%2Flist%3Fchannel%3Deap%26pluginId%3D15246"></a>
    </p>
</p>

# Collector - A collection's plugin for PhpStorm

<!-- Plugin description -->
This plugin adds support for Laravel Collections.

It contains a bunch of handy refactorings for making your collections better.
It can also convert normal PHP statements into collections.
<!-- Plugin description end -->

## Installation
The plugin is still pending validation from IntelliJ! Only manual install is possible until then.


- Using IDE built-in plugin system:

  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "Collector"</kbd> >
  <kbd>Install Plugin</kbd>

- Manually:

  Download the [latest release](https://github.com/olivernybroe/collections-intellij/releases/latest) and install it manually using
  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Using Early Access Program (EAP) builds:

  <kbd>Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Manage plugin repositories</kbd>

  Add a new entry for [`https://plugins.jetbrains.com/plugins/eap/15246`](https://plugins.jetbrains.com/plugins/eap/15246)

  Then search for the plugin and install it as usual.

## Features

- `foreach` to collection
- `array_map` to collection

## Credits

- [Oliver Nybroe](https://github.com/olivernybroe)
- [All contributors](https://github.com/olivernybroe/collector-intellij/contributors)

Special thanks to [Caneco](https://twitter.com/caneco) for the logo ✨

---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
