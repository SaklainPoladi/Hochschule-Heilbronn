# Idealize- Frontend

This project was generated with [Docker Containers](https://www.docker.com/resources/what-container/) version 6.0.8.

## IDE Setup

### IntelliJ - Code Formatting

[Prettier](https://prettier.io/) is used to format code in this project. In order to use automatic
code formatting in IntelliJ use the following steps:

1. Install the [Prettier plugin](https://plugins.jetbrains.com/plugin/10456-prettier)
2. Enable Prettier:
    1. Navigate to `Settings` -> `Languages & Frameworks` -> `JavaScript` -> `Prettier`
    2. Activate `On 'Reformat Code' action` and `On save` to enable automatic formatting
    3. Add HTML files to the `Run for files` setting. Value could look like this
       then `{**/*,*}.{js,ts,jsx,tsx,html}`

If you also use the [Save Actions plugin](https://plugins.jetbrains.com/plugin/7642-save-actions).
Please disable code formatting for this plugin. So it's not interfering with Prettier.

### VSCode - Code Formatting

[Prettier](https://prettier.io) is used to format code in this project. In order to use automatic
code formatting in VSCode use the following steps:

1. Install the [Prettier plugin](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) via Extensions (left bar) in VSCode
2. Enable Prettier:
    1. In the Settings (ctrl+shift+p, type `Settings`) navigate to `Text Editor` -> `Default
       Formatter` and set default formatter to `Prettier`
    2. Navigate to `Text Editor` -> `Default Formatter` -> `Formatting` and activate `Format On
       Save` and `Format On Paste`

## Development server

Run `docker compose up` for a dev server. Navigate
to `https://localhost/`. The app will automatically reload if you change any of the source
files.

```shell
docker compose up
```


## Code scaffolding


## Build


## Linting

## Formatting

To format all the files in the repository according to our Prettier configuration just execute
`npx prettier --write .`. You can replace the `.` with any file or folder to only format a
subset of the repository's files.

## Further help


## Deployment

