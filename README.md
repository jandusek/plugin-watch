@twilio-labs/plugin-watch
=========================

Access and stream your Twilio debugger logs along with your calls and messages.

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @twilio-labs/plugin-watch
$ twilio COMMAND
running command...
$ twilio (-v|--version|version)
@twilio-labs/plugin-watch/1.0.2 win32-x64 node-v12.4.0
$ twilio --help [COMMAND]
USAGE
  $ twilio COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`twilio watch`](#twilio-watch)

## `twilio watch`

Keep an eye on incoming alerts, messages, and calls. Polls every 1 second.

```
USAGE
  $ twilio watch

OPTIONS
  -l=(debug|info|warn|error|none)  [default: info] Level of logging messages.
  -o=(columns|json|tsv)            [default: columns] Format of command output.
  -p, --project=project            Shorthand identifier for your Twilio project.
  --properties=properties          [default: date, type, code, text] event properties you would like to display
  --show-recent-history            show recent events that occurred prior to beginning my watch
```

_See code: [src\commands\watch.js](https://github.com/twilio-labs/plugin-watch/blob/v1.0.2/src\commands\watch.js)_
<!-- commandsstop -->
