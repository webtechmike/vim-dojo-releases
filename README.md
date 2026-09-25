# VimDojo

A calm, untimed dojo in your terminal that teaches vim through **repetition**,
**fundamentals** and **industry best practices**. Earn nine belts, White
through Black, by solving real editing tasks at par, then keep your edge sharp
with a daily kata.

**White, Yellow and Orange Belts are free.** No account, no key, no sign-up.

This repository holds the downloads only. See [`LICENSE`](LICENSE) for the
terms.

## Download

Pick the file for your computer from the
[latest release](https://github.com/webtechmike/vim-dojo-releases/releases/latest):

| Your computer | File |
|---|---|
| Mac with Apple Silicon (M1 or later) | [`vim-dojo-darwin-arm64`](https://github.com/webtechmike/vim-dojo-releases/releases/latest/download/vim-dojo-darwin-arm64) |
| Mac with an Intel processor | [`vim-dojo-darwin-x64`](https://github.com/webtechmike/vim-dojo-releases/releases/latest/download/vim-dojo-darwin-x64) |
| Linux (64-bit Intel/AMD) | [`vim-dojo-linux-x64`](https://github.com/webtechmike/vim-dojo-releases/releases/latest/download/vim-dojo-linux-x64) |
| Windows (64-bit) | [`vim-dojo-win32-x64.exe`](https://github.com/webtechmike/vim-dojo-releases/releases/latest/download/vim-dojo-win32-x64.exe) |

Each release also lists `SHA256SUMS`, the third-party notices, and the license.

## Install

**macOS and Linux**: download straight into place, make it executable, run it.
Change the file name at the end of the URL to the one for your computer:

```bash
mkdir -p ~/.local/bin
curl -fL -o ~/.local/bin/vim-dojo \
  https://github.com/webtechmike/vim-dojo-releases/releases/latest/download/vim-dojo-darwin-arm64
chmod +x ~/.local/bin/vim-dojo
vim-dojo
```

If your shell says `vim-dojo: command not found`, add
`export PATH="$HOME/.local/bin:$PATH"` to your `~/.zshrc` (or `~/.bashrc`) and
open a new terminal.

Downloaded with a browser instead, macOS may say the developer cannot be
verified. Clear the download flag once with
`xattr -d com.apple.quarantine ~/.local/bin/vim-dojo`, or allow it under
System Settings → Privacy & Security.

**Windows**: rename the file to `vim-dojo.exe` and run it from Windows Terminal
or PowerShell. If SmartScreen warns you, choose **More info → Run anyway**.

**Requirements**: a terminal at least 80×24 characters. Nothing else to
install; Node.js is built in.

## Unlocking every belt

From **Green Belt** on, and for the **daily kata** past Black Belt, you need a
license. [Buy one here](https://buy.polar.sh/polar_cl_9OXtMpUZuBZazQnXCC6Rcl9VgMElF1cblZDWz2lyTl9); your key arrives by email.

```bash
vim-dojo --activate YOUR-LICENSE-KEY
```

Every belt opens, and your progress so far carries straight over.

A license covers **one machine at a time**. To move to a new computer:

```bash
vim-dojo --deactivate   # on the old machine
vim-dojo --activate YOUR-LICENSE-KEY   # on the new one
```

The dojo checks your license about once a week while you're online. Offline it
keeps working for **30 days** after the last successful check. A check sends
only your license key, a one-way hash of your machine's hardware ID, and your
computer's name to our payment provider, [Polar](https://polar.sh). Your
progress, scores and certificate never leave your machine.

A refund ends the license; the free belts stay open.

## Help

- **"That key was not recognized"**: check the key was copied whole.
- **"That key can't be activated here"**: it's most likely active on another
  machine. Run `vim-dojo --deactivate` there, then activate again here.
- **Anything else**: email [webtechmike@gmail.com](mailto:webtechmike@gmail.com).
