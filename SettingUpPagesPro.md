# Downloading and Installing Pages Pro

**NOTE**: This is for creating "Pages Pro" not Pages! if you want to check out how to install and use `Github Pages` check it out [here]()!

**NOTE#2**: You must have a repostiry created without branches! more info here: [link](https://kadedevteam.github.io/Pages-Guides/creating-site)

**NOTE#3**: you should be familiar with the commandline. If not, read this short [guide](https://kadedevteam.github.io/GithubPagesPro/commandline).

## Dependinces!
1. Install [Github Desktop](https://desktop.github.com/)!
2. After installing [Github Desktop](https://desktop.github.com/) Install the [Github Pages](https://kadedevteam.github.io/Desktop/) add-on for Github Desktop!
3. Install `git`.
	 - Windows and MacOS: install from the [git-scm](https://git-scm.com/downloads) website.
	 - Linux: install the `git` package: `sudo apt install git` (ubuntu), `sudo pacman -S git` (arch), etc... (you probably already have it)
4. Download The Libararys written here in the [commandLine](https://kadedevteam.github.io/GithubPagesPro/)
   - `lib Install git`
   - `lib Install githubDesk`
   - `lib Install windowsShell2.90`
   - `lib install hscript`
   - `lib git linc_luajit https://github.com/AndreiRudenko/linc_luajit.git`
   - `lib git faxe https://github.com/uhrobots/faxe`
   - `lib git polymod https://github.com/larsiusprime/polymod.git`
   - `lib git extension-webm https://github.com/KadeDev/extension-webm`

### Windows Only Dependinces!
If you are planning to build for Windows, you also need to install **Visual Studio**. While installing it, *don't click on any of the options to install workloads*. Instead, go to the **individual components** tab and choose the following:

-   MSVC v142 - VS 2019 C++ x64/x86 build tools
-   MSVC v141 - VS 2017 C++ x64/x86 build tools
-   Windows SDK (10.0.17763.0)
-   C++ Profiling tools
-   C++ CMake tools for windows
-   C++ ATL for v142 build tools (x86 & x64)

This will install about 7 GB of storage!

### macOS-only dependencies
If you are running macOS, you'll need to install Xcode. You can download it from the macOS App Store or from the [Xcode website](https://developer.apple.com/xcode/).

If you get an error telling you that you need a newer macOS version, you need to download an older version of Xcode from the [More Software Downloads](https://developer.apple.com/download/more/) section of the Apple Developer website. (You can check which version of Xcode you need for your macOS version on [Wikipedia's comparison table (in the `min macOS to run` column)](https://en.wikipedia.org/wiki/Xcode#Version_comparison_table).)

## Cloning the repository
Since you already installed `git` in a previous step, we'll use it to clone the repository.
1. `cd` to where you want to store the source code (i.e. `C:\Users\username\Desktop` or `~/Desktop`)
2. `git clone https://github.com/kadedevteam/Github-Pages-Pro.git`
3. `cd` into the source code: `cd Pages Pro`
4. (optional) If you want to build a specific version of GithubPagesPro, you can use `git checkout` to switch to it (i.e. `git checkout 1.8.3-GP`) (remember that versions 1.6.2 and older cannot build to Linux or HTML5)
- You should **not** do this if you are planning to contribute, as you should always be developing on the latest version.

## Getting Assets
Now We must get out web assets! if you check `/assets/` you will see its empty! with just `assets.rep`!
1. Open `assets.rep` with `git` and the repostory will open!
2. Now go to the top `file > project > clone` this will clone the repostiry into any `assets` files inside of the source!
3. Then in git you want to make sure that the reposrity has been correctly inputed with `git.assetsREP/getSource/assets/` then click save!
4. Now check `/assets/` and loads of files should be there!

## Building Our Site!
Now We are ready to build our site and check it out! 
1. Go into `export/realese/bin/` and open the `lib.git` and click "Create Repostory"
2. After that the `lib.git` file should be gone!
3. Now on the top of file explorer (or any app your using to check out files) you should fine "Files" then inside of it click "Open" then "Open With Powershell"
4. Inside of Powershell type `git build html5 -<target>` replace targert with either `offical` or `demo`. `offical` means it will be realsed with a Jekyll Domain and will be accsesable.
`demo` means that it will be realesed using your web Provider it only be viewable to **YOU** and after closing the tab the domain will be erased.

### Thats all info for installing github pages pro!
### Check out more Guides at the [homepage](https://kadedevteam.github.io/GithubPagesPro/#NECCESARY%20GUDIES!%20(pls%20read))!
