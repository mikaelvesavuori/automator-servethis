# ServeThis: Web server running as a Mac OS X Automator service

Sometimes you just need the tiniest, simplest thing. Like a web server. But those tend to be bloated experiences, and you don't want to run a ton of scripts or installs or anything. Or you just get very intimidated by those things. Either way is fine! ServeThis has you covered.

## Prerequisites

- You are running a Mac OS X system
- The service expects that the folder you provide it with contains a Node project
- The service expects you to have NPM/Node installed
- The service expects you to have a script in your `package.json` called `start`

## Installation

- Double click the workflow file, `ServeThis.workflow`, to install it

## Using it

- Right click a folder, and you should see `ServeThis` under the Services category

![Usage demonstration](usage.png)
_Usage demonstration_

## Source code

The tiny script that gets run is available under `ServeThis.sh`.

## Automator configuration

![How the service is configured in Automator](automator-config-servethis.png)
_How the service is configured in Automator_
