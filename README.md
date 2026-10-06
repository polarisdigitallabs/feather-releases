###### Feather
<img width="64" height="64" alt="icon" src="https://github.com/user-attachments/assets/e56045cc-35de-48b7-99ed-95c4496653fe" />

---

Replace Acrobat, Reader and Bridge with something lighter, cheaper and more enjoyable to use.

- Open, edit and save PDFs and images. Play video. View folders.
- Intuitively moodboard, categorize, and organize tens-of-thousands of files performantly on a Figma-like canvas.

---

**[Download the latest release](https://github.com/polarisdigitallabs/feather-releases/releases/latest)**

## Which file do I need?

| System | File |
| --- | --- |
| Windows | `Feather-Setup-<version>.exe` |
| macOS (Apple Silicon) | `Feather-<version>-arm64.dmg` |
| Linux | `Feather-<version>.AppImage` or `feather_<version>_amd64.deb` |

## First launch

Feather isn't code-signed yet, so your system will warn you the first time you open it.

- **Windows:** on the "Windows protected your PC" screen, click **More info**, then **Run anyway**.
- **macOS:** open the `.dmg` and drag Feather into Applications, then open it from Applications.
  - If macOS says it can't verify Feather, or can't check it for malicious software, close the message. Then **Control-click** Feather in Applications, choose **Open**, and click **Open** again. If that option isn't there, go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**. You only need to do this once.
  - If it says Feather "is damaged", run this once in Terminal, then open it again:

    ```
    xattr -cr /Applications/Feather.app
    ```

- **Linux:** run `chmod +x Feather-*.AppImage`, then open the AppImage. For the `.deb`, run `sudo apt install ./feather_*_amd64.deb`.

## Updates

The installed Windows app and the Linux AppImage check for updates when they start and install them when you quit. You can also use **Help → Check for Updates…**.

On macOS, download new versions from the [releases page](https://github.com/polarisdigitallabs/feather-releases/releases) for now.

## Privacy

Once a day, Feather sends an anonymous check-in: its version, your OS and CPU type, your language setting, and a random ID created when you first run it. That's how we know how many people use Feather and which versions they're on. It never sends your files, file names, or anything you do in the app, and IP addresses aren't stored.

To turn it off, go to **Settings → General → Anonymous usage stats**.






#### hello, world!
---

###### First public release of **Feather**
<img width="80" height="80" alt="icon" src="https://github.com/user-attachments/assets/b6ba610d-9610-4a3b-8da9-fbf96ab7f0f9" />

\
Replace Acrobat, Reader and Bridge with something lighter, cheaper and more enjoyable to use.
- Open, edit and save PDFs and images. Play video. View folders.
- Intuitively moodboard, categorize, and organize tens-of-thousands of files performantly on a Figma-like canvas.

### Known limitations
- Not code-signed yet, so Windows and macOS warn you on first launch (see the README)
- The macOS build is Apple Silicon only, and doesn't update itself yet