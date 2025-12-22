# My minimal theme for Firefox/Librewolf

- In `about:config`, set:
   - `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
   - `browser.uidensity` to `1`

- Go to current profile folder, then clone the repo into a folder called `chrome`:

```
# Windows
cd %APPDATA%\librewolf\Profiles\*default-default

# Linux
cd ~/.librewolf/*default-default

# Linux (flatpak)
cd ~/.var/app/io.gitlab.librewolf-community/.librewolf/*default-default

git clone git@github.com:derryleng/minimal-firefox-theme.git chrome
```
