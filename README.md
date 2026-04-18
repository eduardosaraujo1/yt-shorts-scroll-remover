### How to use

1. Download the UserScript runner [ViolentMonkey](https://violentmonkey.github.io/)
   - You can also try [TamperMonkey](https://www.tampermonkey.net), though that has not been tested
2. Open the file [main.user.js](https://raw.githubusercontent.com/eduardosaraujo1/yt-shorts-scroll-remover/refs/heads/main/main.user.js) in raw mode
3. If ViolentMonkey is installed properly, you should be able to see the Install button [as shown here](./docs/expected-install-screen.jpg).
4. If the step above doesn't work:
   - Select the entire script (Ctrl+A or Cmd+A) and copy it (Ctrl+C or Cmd+C)
   - Click on the ViolentMonkey extention and look for the **Create a new script** button as shown [here](./docs/violentmonkey-newscript.png)
   - Paste the previously copied content in the text window (Ctrl+A then Ctrl+V or Cmd+A then Cmd+V)
   - Save the script contents (Ctrl+S or Cmd+S)

### Expected behavior

Opening a Youtube Short should display the video as usual, but you should not be able to scroll down to see the next suggested video.

---

If you encounter any bugs, please open a [GitHub Issue](https://github.com/eduardosaraujo1/yt-shorts-scroll-remover/issues/new/choose), preferably including your current device, browser and all logs from the Javascript Console.
