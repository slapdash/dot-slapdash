<img src="dot-slapdash.svg" height="80" /> 

### A magical folder on your computer that helps you customize Slapdash.

In the tradition of unix utilities and IDEs, when the [Slapdash desktop app](https://slapdash.com/) is installed on your computer, it creates a hidden folder called `.slapdash` in your user's home directory. Things can be added to this folder to change how Slapdash looks and behaves.

![Dot-Slapdash-Demo](https://user-images.githubusercontent.com/57078134/110828723-3e2cf500-828f-11eb-8afe-2d11d3c69712.gif)

## Get Started

- [Download Slapdash](https://slapdash.com/download), install it and run it.
- On first run, Slapdash will create the `.slapdash` folder in your user's home directory.
  - Linux: `/home/yourusername/`
  - Mac: `/Users/yourusername/`
  - Windows: `C:\Users\yourusername\`
- Open `.slapdash/settings.toml` in your favourite editor and override settings for Slapdash.
- Save your changes. They will be automatically picked up by the app.

## Files To Edit

### settings.toml

This is a configuration file to override application settings. It's written using [TOML](https://toml.io/en), a simple language designed specifically for configuration files. To see every setting you can override, you can check the commented-out ['settings.toml' example](.slapdash/settings.toml) committed to this repository.

| Property                  | Description                                                                                                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| `theme.action`            | Main color used to guide people to the main action at hand.                                                                                          |
| `theme.actionHover`       | The hover color for the main action.                                                                                                                 |
| `theme.actionText`        | Text color to used alongside the main action.                                                                                                        |
| `theme.background`        | Background color of the windows.                                                                                                                     |
| `theme.commandBarFocus`   | Color for highlighting active option in the Command Bar.                                                                                             |
| `theme.elementBackground` | Background color of some smaller elements.                                                                                                           |
| `theme.focus`             | Color, a stark "you are here" marker, used sparsely to concentrate attention.                                                                        |
| `theme.focusSoft`         | Color, a less stark "you are here" marker.                                                                                                           |
| `theme.navBackground`     | Background color of the nav bar.                                                                                                                     |
| `theme.navFocus`          | Background color of a nav bar item when it's selected.                                                                                               |
| `theme.navText`           | Text color of a nav bar item.                                                                                                                        |
| `theme.opacityOverlay`    | Color used to mask a layer below, for example when displaying modals.                                                                                |
| `theme.scrollBar`         | Scroll bar color.                                                                                                                                    |
| `theme.shadow`            | Color, used as the shadow for components that sit on top of others.                                                                                  |
| `theme.stroke`            | Color, a thin stroke that's used to create separation between elements. Serves as an outline that works well in the context of the background color. |
| `theme.text`              | Regular color for any text.                                                                                                                          |
| `theme.textError`         | Text color for errors.                                                                                                                               |
| `theme.textSecondary`     | Color, usually used alongside the `text` color, provides some visual hierarchy by way of color.                                                      |
| `theme.textTertiary`      | Color, even less prominent than `textSecondary`. Helpful for inactive states or form input placeholders.                                             |
