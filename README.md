# Minimal vanilla Firefox theme

- When width > 1440px, puts tabs and address bar on one line
- Hides forward button when unavailable

Suggested layout and how it looks below 1440px width and above 1440px width:
![Width below 1440px](assets/below_1440px.png)
![Width above 1440px](assets/above_1440px.png)

## Installation

1. In the `about:config` page, set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
2. In the `about:profiles` page, open the folder for the Root Directory of the current profile in use, make a new folder called `chrome` and copy the `userChrome.css` file inside.
3. Fully close and reopen Firefox for any changes to `userChrome.css` to take effect.
