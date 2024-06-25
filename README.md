# Zephyr™ Mechanical Keyboard (ZMK) Firmware

This is my personal version of ZMK modified for my 
[Kinesis Advantage 360 Pro][1] Ergo Keyboard.

I chose to maintain my own version of ZMK with some of the features of the
stock Kinesis ZMK fork in order to being able to use latest ZMK as well as
use my Advantage 360 Pro for active ZMK development.

## Custom Features

The following is a list of features my personal fork of ZMK adds
specifically for the Advantage 360 Pro.

* LED indicator to show which Bluetooth profile is currently in use
* LED indicator to show which ZMK keymap layer is currently active
* LED indicator to show battery charge on both sides
    - \>= 50% charge = green
    - \< 50% charge = yellow
    - \< 20% charge = red

## Usage

My configuration and how this fork of ZMK is used can be found in my
[zmk-advantage-360-pro][2] configuration repository.

## Original ZMK

[![Discord](https://img.shields.io/discord/719497620560543766)](https://zmk.dev/community/discord/invite)
[![Build](https://github.com/zmkfirmware/zmk/workflows/Build/badge.svg)](https://github.com/zmkfirmware/zmk/actions)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

[ZMK Firmware](https://zmk.dev/) is an open source ([MIT](LICENSE)) keyboard firmware built on the [Zephyr™ Project](https://www.zephyrproject.org/) Real Time Operating System (RTOS). ZMK's goal is to provide a modern, wireless, and powerful firmware free of licensing issues.

Check out the website to learn more: https://zmk.dev/.

You can also come join our [ZMK Discord Server](https://zmk.dev/community/discord/invite).

To review features, check out the [feature overview](https://zmk.dev/docs/). ZMK is under active development, and new features are listed with the [enhancement label](https://github.com/zmkfirmware/zmk/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement) in GitHub. Please feel free to add 👍 to the issue description of any requests to upvote the feature.

[1]: https://kinesis-ergo.com/shop/adv360pro/
[2]: https://github.com/huber-th/zmk-advantage-360-pro
