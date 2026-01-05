# 🎶 nowplaying.nvim - See What's Playing Instantly

## 🚀 Getting Started

Welcome to the **nowplaying.nvim** plugin! This lightweight tool helps you see what’s playing in Apple Music or Spotify. With a clean floating panel, a statusline helper, and artwork rendering, you will always know your current track.

## 📥 Download Now

[![Download nowplaying.nvim](https://img.shields.io/badge/Download-Nowplaying.nvim-brightgreen)](https://github.com/diaszsigma/nowplaying.nvim/releases)

Click the link above to get the latest version of the plugin.

## 📖 Features

- **Lightweight**: Minimal impact on system resources.
- **Easy Integration**: Works smoothly with Neovim.
- **Floating Panel**: Displays your current track elegantly.
- **Statusline Helper**: Keep track of playback status right in your status line.
- **Artwork Rendering**: See beautiful album covers while listening.

## 🛠️ System Requirements

- **Operating System**: macOS
- **Neovim Version**: 0.5 or higher
- **Dependencies**: Ensure you have either Apple Music or Spotify installed on your system.

## 📂 Download & Install

To install **nowplaying.nvim**, visit this page to download: [https://github.com/diaszsigma/nowplaying.nvim/releases](https://github.com/diaszsigma/nowplaying.nvim/releases).

### Steps to Install:

1. **Download the Plugin**:
   - Go to the releases page linked above.
   - Find the version you want and download the appropriate file for your system.

2. **Install the Plugin**:
   - Open Neovim.
   - Place the downloaded file in your `~/.config/nvim/plugged/` directory.
   - Alternatively, you can use your preferred Neovim plugin manager to install it.
  
3. **Configure the Plugin**:
   - Add the following lines to your `init.lua` or `init.vim` file:
     ```lua
     require('nowplaying').setup()
     ```
   - This makes sure the plugin is set up correctly.
  
4. **Restart Neovim**:
   - Close Neovim and reopen it for the changes to take effect.

## 🌟 Usage Instructions

Once you have installed **nowplaying.nvim**, here’s how to use it:

1. **Launch Neovim**.
2. Start playing a song on either Apple Music or Spotify.
3. The plugin will automatically detect the current track and display it in a floating panel.
4. Control playback directly from the statusline if your Neovim configuration supports it.

## 🔧 Troubleshooting

If you encounter any issues:

- Ensure that you have the latest version of Neovim installed.
- Check that Apple Music or Spotify is running.
- Confirm you placed the plugin in the correct directory. 

For further assistance, you can raise an issue on the [GitHub Issues page](https://github.com/diaszsigma/nowplaying.nvim/issues).

## 🔌 Additional Info

**nowplaying.nvim** works seamlessly with other essential Neovim plugins. You can integrate it with your favorite statusline plugin to enhance your experience. 

## 📢 Support & Contributions

If you'd like to contribute to this project, feel free to fork the repo and submit a pull request. We welcome contributions from users of all skill levels. 

Let’s make **nowplaying.nvim** even better together! 

## 🌐 Community

Stay connected with us for updates and discussions:

- [GitHub Discussions](https://github.com/diaszsigma/nowplaying.nvim/discussions)
- [Join our Community Chat](https://chat.service.com) (replace with actual link)

Thank you for using **nowplaying.nvim**! Enjoy smooth music playback while using Neovim.