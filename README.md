<img src="https://github.com/davidykmisha2015-prog/systemGNOME/raw/main/assets/preview.png">

# systemGNOME

a customizable, tui-style discord theme. inspired by [spicetify text theme](https://github.com/spicetify/spicetify-themes/tree/master/text).

<img src="https://github.com/davidykmisha2015-prog/systemGNOME/raw/main/assets/screenshot.png">

## discord server

need help? want to get notified about updates? have feedback? join <https://discord.gg/nz87hXyvcy>

## install

### vencord/betterdiscord (or any client that supports theme files)

1. download the theme file, [`systemGNOME.theme.css`](https://github.com/davidykmisha2015-prog/systemGNOME/blob/main/systemGNOME.theme.css). (there should be a download button at the top right of the page)
2. drag the file into your theme folder. (there should be a button to open the theme folder in theme settings)
3. (optional) customize the theme by editing the options in `systemGNOME.theme.css`.

### install through link

add `https://davidykmisha2015-prog.github.io/systemGNOME/systemGNOME.css` to your theme import links. you will need to copy the theme variables to your quickcss in order to customize the theme.

## flavors

curently doesn't have any variant of this theme :(

## contributing

this theme depends on [system24](https://discord.gg/nz87hXyvcy) for its core styles. if you're looking to contribute, please consider which theme you actually want to work on. feel free to open an issue and ask if you're unsure.

this theme uses a dev script to check for changes in the /src .css files and combine them into a build file in /build. note that both the /src files and the /build file are tracked in git, so any changes you contribute should exist in both places!!

to run locally:

1. clone the repository.
2. run `npm i`.
3. create a `.env` file in the project root with the paths of any local theme files you want to update (comma separated)
4. DEV_OUTPUT_PATH=C:\Users\USERNAME\AppData\Roaming\Vencord\themes\systemGNOME-dev.theme.css  
5. run `npm run dev`.
6. make changes to any file in `/src` or the main theme file. the local theme files you listed will automatically be updated, along with the build file in `/build`.
7. make a pull request with your changes!

## credits

[spicetify text theme](https://github.com/spicetify/spicetify-themes/tree/master/text) for primary design inspiration.

sorry but currently doesn't have any contributors :(
