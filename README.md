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



## Requirements:
- The Firefox extension named `TreeStyleTab`

&nbsp;

## How to use:
Find firefox profile's root directory in `about:profiles`  

```zsh
git clone https://github.com/AnonCYTO/foxy-config.git  
cp -r /foxy-config/chrome /path/to/firefox/profile/
rm -rvf /foxy-config/
```

In 'about:config', set bool to:
    - "toolkit.legacyUserProfileCustomizations.stylesheets" = true
