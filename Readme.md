# hyperterm

## TODO

- [ ] Listen on `resize` event *coming* from the pty.
- [ ] Add support for zsh and other popular shells
- [ ] Figure out process title extraction on other platforms.
- [ ] Define extensibility surface and APIs
- [ ] Define approach to conf management (`~/.hyperterm.json` ?)
- [ ] Admit Ctrl+C as a way of closing webview
- [ ] When webview is shown, replace title of tab with <title>
- [ ] Linkify urls in stdout. If clicked, inline webview. If cmd+clicked, default browser.
- [ ] Show icon that triggers contextmenu in tab, when hovered.
  - [ ] "Open in default browser" option in webview mode
  - [ ] Close
- [ ] Test on Windows, Linux
- [ ] Investigate startup time improvements
  - [ ] Optimistic (mosh-style) prompt that memoizes PS1
  - [ ] Smaller bundle (ie: uglify, but currently doesnt work with ES6)
  - [ ] Inline all the CSS/JS in the page instead of extra file