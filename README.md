# Steam-Deck-Help-FAQ

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/142779553-82147e51-7e6d-47bd-9db6-fe2f5ad95355.png">
  <br />
  Steam Deck Guide
</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/142779557-400f19c8-6084-41ee-9449-fb08a15d6c45.png">
<br />
</p>


#### A guide covering Steam Deck including the applications and tools that will make you a better and more efficient with your Steam Deck device.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) or the handy online tool [AnyConv](https://anyconv.com/md-to-pdf-converter/).**

**Note 2: This guide will constantly be updated with new info as becomes available and please feel to make an [issue](https://github.com/mikeroyal/Steam-Deck-Guide/issues) if you think something should be added.**

# Table of Contents

1. [Getting Started with the Steam Deck](https://github.com/rawdatafeel/Steam-Deck-Help-FAQ#getting-started-with-the-steam-deck)

     - [Steam Deck Accessories](https://github.com/mikeroyal/Steam-Deck-Guide#Steam-Deck-Accessories)
     - [Steam Deck Development](https://github.com/mikeroyal/Steam-Deck-Guide#steam-deck-development)
     - [SteamDB](https://github.com/mikeroyal/Steam-Deck-Guide#steamdb)
     - [Getting Software](https://github.com/mikeroyal/Steam-Deck-Guide#getting-software)
     - [Other Linux Operating Systems for the Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#Other-Linux-Operating-Systems-for-the-Steam-Deck)
     - [Getting Windows 10 or 11 on the Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#Getting-Windows-10-or-11-on-the-Steam-Deck)
     - [Improving Battery Life](https://github.com/mikeroyal/Steam-Deck-Guide#improving-battery-life)
     - [Tools to Copy/Transfer files to your Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#tools-to-copytransfer-files-to-your-steam-deck)
     - [Running Android Apps on your Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#running-android-apps-on-your-steam-deck)
     - [Running Bottles on your Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#running-bottles-on-your-steam-deck)
     - [Steam Deck Power Tools](https://github.com/mikeroyal/Steam-Deck-Guide#steam-deck-power-tools)
     - [Steam Tinker Launch](https://github.com/mikeroyal/Steam-Deck-Guide#steam-tinker-launch)
     - [RetroDECK](https://github.com/mikeroyal/Steam-Deck-Guide#RetroDECK)
     - [Adding Btrfs on Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#btrfs-on-steam-deck)
     - [Plugin Loader for Steam Deck](https://github.com/mikeroyal/Steam-Deck-Guide#plugin-loader)

2. [Gaming](https://github.com/mikeroyal/Steam-Deck-Guide#gaming)

     - [Steam](https://github.com/mikeroyal/Steam-Deck-Guide#steam)
     - [ProtonDB](https://github.com/mikeroyal/Steam-Deck-Guide#protondb)
     - [Lutris](https://github.com/mikeroyal/Steam-Deck-Guide#lutris)
     - [GameHub](https://github.com/mikeroyal/Steam-Deck-Guide#gamehub)
     - [Epic Games Store](https://github.com/mikeroyal/Steam-Deck-Guide#epic-games-store)
     - [Game Streaming](https://github.com/mikeroyal/Steam-Deck-Guide#game-streaming)
     - [Game Emulators](https://github.com/mikeroyal/Steam-Deck-Guide#game-emulators)

3. [Game Development](https://github.com/mikeroyal/Steam-Deck-Guide#game-development)

4. [Vulkan Development](https://github.com/mikeroyal/Steam-Deck-Guide#vulkan-development)

5. [DirectX Development](https://github.com/mikeroyal/Steam-Deck-Guide#directx-development)

6. [OpenGL Development](https://github.com/mikeroyal/Steam-Deck-Guide#opengl-development)

7. [Wayland Development](https://github.com/mikeroyal/Steam-Deck-Guide#wayland-development)

8. [Audio Development](https://github.com/mikeroyal/Steam-Deck-Guide#audio-development)


# Getting Started with the Steam Deck
[Back to the Top](https://github.com/mikeroyal/Steam-Deck-Guide#table-of-contents)

[Steam Deck](https://www.steamdeck.com/) is a handheld gaming computer developed by [Valve Corporation](https://valvesoftware.com/) in cooperation with [Advanced Micro Devices (AMD)](https://www.amd.com/). It allows users to play their entire Steam game library but can be modified by the user to run other gaming storefronts or applications. The Steam Deck started shipping in February 2022.

[Steam Deck Teardown by Jeff Suovanen | iFixit](https://www.ifixit.com/News/57101/steam-deck-teardown)

[Unlock Steam Deck tutorial | Chris Titus Tech](https://christitus.com/unlock-steam-deck/)

[Steam Deck Hardware Review by Linus Tech Tips](https://www.youtube.com/watch?v=HjZ4POvk14c)

[Steam Deck Unboxing Experience by Linus Tech Tips](https://www.youtube.com/watch?v=_UB9XoPlJ0U)

[Steam Deck Tear Down by Linus Tech Tips](https://www.youtube.com/watch?v=ZK43RAc90ZA)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/142779563-30ada576-1bf4-42fb-8ad5-3fa3a6e40103.png">
<br />
</p>

Steam Deck device. Source: [Steam Deck](https://www.steamdeck.com/)

[Steam OS 3.0](https://store.steampowered.com/steamdeck) is an [immutable](https://en.wikipedia.org/wiki/Immutable_object) Operating System(OS) using the [KDE Plasma](https://kde.org/plasma-desktop) desktop. This allows you to install applications in containers using [Flatpak](https://flatpak.org/), rather than onto the root filesystem. This means not only that the installation of applications is isolated from the core filesystem, but also that the ability for malicious applications to compromise/break your system is significantly reduced.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157353163-6f5c4c1a-a89f-4ee5-9ffe-1d9f991c773c.png">
  <br />
  SteamOS 3.0 with KDE Plasma Desktop
</h3>
