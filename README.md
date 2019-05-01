# @intuit/renovate-config

[![npm](https://img.shields.io/npm/v/@intuit/renovate-config.svg)](https://www.npmjs.com/package/@intuit/renovate-config)
[![CircleCI](https://circleci.com/gh/intuit/renovate-config/tree/master.svg?style=shield)](https://circleci.com/gh/intuit/renovate-config/tree/master)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)

This repo serves as the base line for all renovate configs used within Intuit.

## Install

```bash
yarn add @intuit/renovate-config --dev
```

And then go to your renovate config locally and add:

```json
"extends": ["@intuit"]
```

# Usage

You don't have to do anything beyond the above if you are ok with the defaults. However, if you would like to customize your usage, you can change the config in your repo to extend and change certain rules for your teams needs.

## Resources

You can learn more about configuring Renovate with [shareable configs](https://renovatebot.com/docs/config-presets/)
You can learn more about [Renovate](http://renovatebot.com)
