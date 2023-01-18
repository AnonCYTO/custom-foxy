<div align="center">
    <h1>
        <ins>Foxy-Config</ins>
</div>

> ### Link to the WiKi:
> <a href="https://github.com/piroor/treestyletab/wiki/Code-snippets-for-custom-style-rules#hide-top-bar-and-move-close-minimize-restore-buttons-to-top-left-macos-big-sur-firefox-89">TreeStyleTab Wiki</a>

&nbsp;

## TF does this do?
- Removes/hides the ugly ahh tab bar on the top in Firefox
- Hides `TreeStyleTab` top bar

&nbsp;

## Requirements:
- The Firefox extension named `TreeStyleTab`

&nbsp;

## How to use:
1. Find firefox profile's root directory in `about:profiles`
    
2. clone, copy and delete the repo as shown in the following:
    ```zsh
    git clone https://github.com/AnonCYTO/foxy-config.git  
    cp -r /foxy-config/chrome /path/to/firefox/profile/
    rm -rvf /foxy-config/
    ```
3. In `about:config`, set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
