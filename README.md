# warp-themes

This repo shares all the themes I've created for the [Warp terminal](https://www.warp.dev/best-mac-terminal). Please feel free to use them!

## Setup

After installing Warp and cloning this repo -
1. Create the following directory:
```
mkdir -p ~/.warp/themes/
```

2. Restart Warp so that it can discover the new themes directory.
   
4. Add themes from this repo to your Warp themes directory with the following command:
```
cp -r ~/{{path_to_the_directory_this_repo_was_cloned_in}}/warp-themes/{dark,light}/* ~/.warp/themes
```

4. You should now be able to select the themes in Warp. In order to open the theme picker after launching Warp, use the ^⌘T shortcut or open the command palette with ⌘+p and enter "Open Theme Picker".
