# crotfiles

**Note:** Although the name sounds similar to [`dotfiles`](https://github.com/citrusui/dotfiles), it adds no aliases or additional functionality to the current login shell. This _only_ applies to the crosh and Secure Shell extensions.

## Optional

Install the [Secure Shell extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo).

If you're on Chrome OS, this extension is not necessary.

## Install

- Open crosh or Secure Shell with the following URLs, respectively:

`chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/crosh.html`

`chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh.html`

- Open the JavaScript console with `CTRL+SHIFT+J` or `Command-Option-J`.
- Code and paste the following code into the Console and press Enter.

```js
term_.prefs_.set('background-color', "#292e33");
term_.prefs_.set('color-palette-overrides', [
  '#40484f',
  '#e03431',
  '#79ce80',
  '#e8e366',
  '#4ea5d9',
  '#e031a8',
  '#4ed4d8',
  '#f9f9f9',
  '#40484f',
  '#e03431',
  '#79ce80',
  '#e8e366',
  '#4ea5d9',
  '#e031a8',
  '#4ed4d8',
  '#f9f9f9'
]);
term_.prefs_.set('ctrl-c-copy', true);
term_.prefs_.set('ctrl-v-paste', true);
term_.prefs_.set('cursor-color', "#6b7a86");
term_.prefs_.set('desktop-notification-bell', true);
term_.prefs_.set('foreground-color', "#f9f9f9");
term_.prefs_.set('font-family', ["Menlo, Terminal, monospace"]);
term_.prefs_.set('font-size', "13");
```

# Uninstall

**Warning:** All preferences will be reset to system defaults.

```js
term_.prefs_.resetAll();
```

If you prefer, you can change the settings manually:

_crosh_: `chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/nassh_preferences_editor.html`

_Secure Shell_: `chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh_preferences_editor.html`
