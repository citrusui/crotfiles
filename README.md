# crotfiles

dotfiles for crosh and Secure Shell.

## Optional

Install the [Secure Shell extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo).

If you're on Chrome OS, this extension is not necessary.

## Install

- Open [crosh](chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/crosh.html) or [Secure Shell](chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh.html).
- Open the JavaScript console with `CTRL+SHIFT+J` or `Command-Option-J`.
- Paste the following code below and press Enter.

```js
term_.prefs_.set('background-color', "#40484f");
term_.prefs_.set('color-palette-overrides', [
  '#000',
  '#e03431',
  '#79ce80',
  '#e8e366',
  '#4ea5d9',
  '#e031a8',
  '#4ed4d8',
  '#f9f9f9',
  '#000',
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

If you prefer, you can configure [crosh](chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/nassh_preferences_editor.html) and [Secure Shell](chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh_preferences_editor.html) manually.
