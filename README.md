# Refresh AWS

Refresh all AWS tabs simultaneously in Chrome or Safari on macOS

## Description

Simple AppleScript service which enables batch refreshing of all AWS tabs in
Chrome and Safari. This is useful to refresh your expired login session for all
AWS tabs simultaneously after signing back in to the AWS Console.

## Requirements

* macOS
* Chrome or Safari

## Installation

* Clone this repo or download the raw workflow script for your preferred browser (Chrome or Safari)
* Double click the workflow script to install it as a macOS service extension for Chrome or Safari
* Workflow script will be automatically moved to ~/Library/Services by default upon installation

## Usage

* Leave all AWS Console tabs open, and log back into the AWS console from one tab to refresh session
* From the menu bar, click `Services > Refresh AWS (Chrome or Safari)` to refresh all AWS tabs
* All tabs with root domain \*aws.amazon.com will be simultaneously refreshed, and login session will be restored

## License

This project is licensed under the MIT License - see the LICENSE file for details
