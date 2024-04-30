# zomo

## What is it?

A pomodoro timer script made with _bash_ and _zenity_ dialogs.

## Installation

### Downloading zomo

To get 'zomo' you can download it via git:

`$ git clone https://github.com/gabrielproencaalves/zomo.git`

Or, by a [.zip file](https://github.com/gabrielproencaalves/zomo/archive/refs/heads/main.zip). Unzip it after downloading it:

`$ unzip zomo-main.zip`


### Configuring zomo

After downloading, you need to make the script located in the newly extracted folder executable:

`$ chmod +x zomo`

Or

`$ chmod 0711 zomo`


And then move the executable to a directory included in your system PATH. This may require super user permissions, depending on the directory. For example:

`# cp zomo /usr/local/bin/`

With these steps done, you will be able to run zomo normally on your system.

# Usage

```shell
  $ zomo <MODE> [OPTIONS]

  MODES:
  work     - work cycle. default: 25 min.
  pause    - pause cycle. default: 5 min.
  long     - long pause cycle. default: 15 min.
  full     - four pomodoro cycles ended by a long pause.
  infinite - endless full mode.
  status   - displays current time status.
  kill     - terminates the current timer cycle.

  OPTIONS:
  -wd - work duration  (in minutes).
  -pd - pause duration (in minutes).
  -ld - long duration  (in minutes).
```
