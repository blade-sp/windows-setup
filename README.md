# Windows Setup with GlazeWM and Zebar

## PowerToys

I like to use [PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) to enhance my Windows experience. Especially for the following features:

- [Powertoys Run](https://learn.microsoft.com/en-us/windows/powertoys/run)

## Window Manager Setup

I prefer to use a tiling window manager, I use [GlazeWM](https://github.com/glzr-io/glazewm).
- [GlazeWM Config File](./config.yaml)

GlazeWM comes with the option to use top bar. If you use workspaces, it's a must have.

- [Zebar](https://github.com/glzr-io/zebar)

## Zebar Setup

1. Copy the content of [vanilla-clear](./vanilla-clear) widget to Zebar starter directory
2. Set vanilla-clear as the default widget in your Zebar config file:

```
 "startupConfigs": [
    {
      "path": "starter/vanilla-clear.zebar.json",
      "preset": "vanilla-clear"
    }
  ]
``` 