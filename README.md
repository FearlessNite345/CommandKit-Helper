<div align="center">
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/npm/v/commandkit-helper?style=for-the-badge" alt="npm version" />
  </a>
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/npm/dt/commandkit-helper?style=for-the-badge" alt="npm downloads" />
  </a>
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/npm/l/commandkit-helper?style=for-the-badge" alt="npm license" />
  </a>
  <br />
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/github/issues/FearlessNite345/commandkit-helper?style=for-the-badge" alt="npm license" />
  </a>
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/github/stars/FearlessNite345/commandkit-helper?style=for-the-badge" alt="npm license" />
  </a>
  <a href="https://www.npmjs.com/package/commandkit-helper">
    <img src="https://img.shields.io/github/forks/FearlessNite345/commandkit-helper?style=for-the-badge" alt="npm license" />
  </a>
</div>

# commandkit-helper

commandkit-helper is a simple library that will help with building comamnds to work with [CommandKit](https://www.npmjs.com/package/commandkit)

> **Works with Discord.JS V14**

## Features

-   Extremely Beginner friendly
-   Allows you to have command builders for [CommandKit](https://www.npmjs.com/package/commandkit)

## Installation

```bash
npm install commandkit-helper
```

## Documentation

You can find the main documentation [here](https://fearlessnite345.github.io/commandkit-helper/)

# Changelog

### v1.5.0
-   Added the `addCustomOption()` function to the `UserContextCommand` and `MessageContextCommand`
-   Deprecated the `setGuildOnly()` function more info in the [docs](https://fearlessnite345.github.io/commandkit-helper/)
-   Added support for type `Omit<SlashCommandBuilder, "addSubcommand" | "addSubcommandGroup">` in the [`AnySlashCommandData`](https://fearlessnite345.github.io/commandkit-helper/docs/typedef/anyslashcommanddata/) (this will allow you to not have to do `.toJSON()` at the end of the slash command builder if you have options on it)

### v1.4.0

-   Added [ValidationBuilder](https://fearlessnite345.github.io/commandkit-helper/docs/classes/validationbuilder/) to make it beginner friendly as it will add the typings for you
-   Added new method in the [SlashCommand](https://fearlessnite345.github.io/commandkit-helper/docs/classes/slashcommand/) called **addCustomOption()** which allows you to add a custom option to the commandObj
-   Fixed a issue where you could not set the command data to a **SlashCommandSubcommandsOnlyBuilder** type