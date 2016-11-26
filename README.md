# crotfiles

**Note:** Although the name sounds similar to dotfiles, it adds no aliases, fancy prompts, or additional functionality not available in the current shell. This _only_ applies to the crosh and Secure Shell extensions.

### Optional

If you are on Windows, macOS, or Linux, install the [Secure Shell extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo). On Chrome OS, Secure Shell will replace (but not overwrite) crosh when `CTRL+ALT+T` is pressed.

## Install

- Open crosh or Secure Shell with the following URLs, respectively:

`chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/crosh.html`

`chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh.html`

- Open the JavaScript console with `CTRL+SHIFT+J` or `Command-Option-J`.
- Copy and paste the [latest code](https://raw.githubusercontent.com/citrusui/crotfiles/master/install.js) into the Console and press Enter.

## Uninstall

**Warning:** All preferences will be reset to system defaults.

```js
term_.prefs_.resetAll();
```

If you prefer, you can change the settings manually:

**crosh:** `chrome-extension://nkoccljplnhpfnfiajclkommnmllphnl/html/nassh_preferences_editor.html`

**Secure Shell:** `chrome-extension://pnhechapfaindjhompbnflcldabbghjo/html/nassh_preferences_editor.html`
