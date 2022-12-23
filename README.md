# Fabled Theme For Replugged
## Prerequisites

- NodeJS
- pnpm: `npm i -g pnpm`
- [Replugged](https://github.com/replugged-org/replugged#installation)

## Install

1. [Create a copy of this template](https://github.com/replugged-org/theme-template/generate)
2. Clone your new repository and cd into it
3. Install dependencies: `pnpm i`
4. Build the theme: `pnpm run build`
5. Reload Discord to load the theme

## Troubleshooting

### Make sure Replugged is installed and running.

Open Discord settings and make sure the Replugged tab is there. If not,
[follow these instructions](https://github.com/replugged-org/replugged#installation) to install
Replugged.

### Make sure the theme is installed.

Check the [theme folder](https://github.com/replugged-org/replugged#installing-plugins-and-themes)
for your OS and make sure the theme is there. If not, make sure you have built the theme and that
the `NO_INSTALL` environment variable is not set.  
You can run `replugged.themes.list().then(console.log)` in the console to see a list of themes in
the theme folder.
