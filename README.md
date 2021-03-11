# Refresh AWS

Refresh all AWS tabs simultaneously in Chrome or Safari on macOS

## Description

Simple AppleScript service which enables batch refreshing of all AWS tabs in
Chrome and Safari. This is useful to refresh your expired login session for all
AWS tabs simultaneously after signing back in to the AWS Console, rather than
reloading each tab individually to refresh its session.

## Requirements

* macOS
* Chrome or Safari

## Installation

* Clone this repo, or download the individual raw workflow package (e.g., `Refresh AWS Safari.workflow`) for your preferred browser (Chrome or Safari)
* Double click the top-level workflow package (directory ending in `.workflow`) to install the contained AppleScript as a macOS service extension for Chrome or Safari
* The workflow package will be automatically moved to ~/Library/Services by default upon installation

## Usage

* After your AWS Console login session has expired, leave all AWS Console tabs open and log back into the AWS console from one tab to refresh the login session
* From the application menu bar, click `Safari > Services > Refresh AWS Safari` (or the equivalent menu path for Chrome) to refresh all AWS tabs
* All tabs with root domain \*aws.amazon.com will be simultaneously refreshed, restoring logged in sessions for each tab

## License

This project is licensed under the MIT License - see the LICENSE file for details
