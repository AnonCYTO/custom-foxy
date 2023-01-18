<div align="center">
    <h1>
        <ins>Foxy-Config</ins>
</div>

> ## TF does this do?
> 1. Removes/hides the ugly ahh tab bar on the top in Firefox
> 2. Hides `TreeStyleTabs` top bar
>
> ## Requirements:
> 1. The Firefox extension named `TreeStyleTabs`

## How to use:

- Find firefox profile's root directory in `about:profiles`
    - Make a folder named `chrome`
        - Make a file named `userChrome.css`
        - Put the above code 

- In 'about:config', set bool to:
    - "toolkit.legacyUserProfileCustomizations.stylesheets" = true

> ### Important Links:
>    https://github.com/piroor/treestyletab/wiki/Code-snippets-for-custom-style-rules#hide-top-bar-and-move-close-minimize-restore-buttons-to-top-left-macos-big-sur-firefox-89
