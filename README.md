# awesome-zsh-plugins

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/license/BSD-3-Clause)
![Awesomebot](https://github.com/unixorn/awesome-zsh-plugins/actions/workflows/awesomebot.yml/badge.svg)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers) ⭐ 17,372 | 🐛 5 | 🌐 Shell | 📅 2026-02-03
![Contributors](https://img.shields.io/github/contributors/unixorn/awesome-zsh-plugins.svg)
[![GitHub last commit](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins) ⭐ 17,372 | 🐛 5 | 🌐 Shell | 📅 2026-02-03
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Table of Contents

* [Disclaimer](#disclaimer)
* [Frameworks](#frameworks)
  * [alf](#alf)
  * [ansible-role-zsh](#ansible-role-zsh)
  * [ant-zsh](#ant-zsh)
  * [antibody](#antibody)
  * [antidote](#antidote)
  * [antigen-hs](#antigen-hs)
  * [antigen](#antigen)
  * [awesome-lazy-zsh](#awesome-lazy-zsh)
  * [ax-zsh](#ax-zsh)
  * [deer](#deer)
  * [dotzsh](#dotzsh)
  * [fresh](#fresh)
  * [gh-source](#gh-source)
  * [miniplug](#miniplug)
  * [oh-my-zsh](#oh-my-zsh)
  * [PMS](#pms)
  * [prezto](#prezto)
  * [pumice](#pumice)
  * [rac](#rac)
  * [rat](#rat)
  * [ryzshrc](#ryzshrc)
  * [sheldon](#sheldon)
  * [shplug](#shplug)
  * [TheFly](#thefly)
  * [Toasty](#toasty)
  * [Usepkg](#usepkg)
  * [uz](#uz)
  * [x-cmd](#x-cmd)
  * [yazt](#yazt)
  * [yzsh](#yzsh)
  * [zap](#zap)
  * [zapack](#zapack)
  * [zcomet](#zcomet)
  * [zeesh](#zeesh)
  * [zgem](#zgem)
  * [zgen](#zgen)
  * [zgenom](#zgenom)
  * [zilsh](#zilsh)
  * [zim](#zim)
  * [Zinit](#zinit)
  * [zinit-4](#zinit-4)
  * [zit](#zit)
  * [zlugin](#zlugin)
  * [znap](#znap)
  * [zoppo](#zoppo)
  * [zpacker](#zpacker)
  * [zpico](#zpico)
  * [zplug](#zplug)
  * [zpm](#zpm)
  * [zr](#zr)
  * [zshing](#zshing)
  * [zsh-dot-plugin](#zsh-dot-plugin)
  * [zsh-mgr](#zsh-mgr)
  * [zsh-unplugged.](#zsh-unplugged)
  * [zshPlug](#zshplug)
  * [ztanesh](#ztanesh)
  * [ztheme](#ztheme)
  * [ztupide](#ztupide)
  * [zulu](#zulu)
  * [zush 🦥 - Mid-Performance ZSH Configuration](#zush-%F0%9F%A6%A5---mid-performance-zsh-configuration)
* [Setups](#setups)
  * [zgenom](#zgenom-1)
  * [zinit](#zinit)
* [Prerequisites](#prerequisites)
* [Tutorials](#tutorials)
  * [Generic ZSH](#generic-zsh)
  * [Antigen](#antigen)
  * [Oh-My-Zsh](#oh-my-zsh)
  * [Prezto](#prezto)
  * [Zgen](#zgen)
  * [Zinit (né zplugin)](#zinit-n%C3%A9-zplugin)
  * [ZSH on Windows](#zsh-on-windows)
    * [superconsole - Windows-only](#superconsole---windows-only)
* [Plugins](#plugins)
* [Completions](#completions)
* [Themes](#themes)
* [Fonts](#fonts)
* [Installation](#installation)
  * [Antigen](#antigen-1)
  * [dotzsh](#dotzsh-1)
  * [Oh-My-Zsh](#oh-my-zsh-1)
  * [Prezto](#prezto-1)
  * [Zgen](#zgen-1)
  * [Zgenom](#zgenom)
  * [zplug](#zplug-1)
  * [zpm](#zpm-1)
* [Writing New Plugins and Themes](#writing-new-plugins-and-themes)
* [Other Resources](#other-resources)
  * [ZSH Tools](#zsh-tools)
  * [Other Useful Lists](#other-useful-lists)
  * [Other References](#other-references)
* [Thanks](#thanks)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](origin/Contributing.md) before contributing.*

## Disclaimer

While I have done my best to not add entries with embedded malicious code, I don't have the time to sift through the source of every entry in the list.

THIS LIST IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Frameworks

These frameworks make customizing your ZSH setup easier.

You can find performance timing comparisons of various frameworks in the following locations.

* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark) ⭐ 122 | 🐛 5 | 🌐 Shell | 📅 2025-02-09 - Contains performance benchmarks for the most popular ZSH frameworks, including both install time and load time.
* [pm-perf-test](https://github.com/z-shell/pm-perf-test) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-12-01 - Tooling for running performance tests on multiple ZSH frameworks.

### [alf](https://github.com/psyrendust/alf) ⭐ 120 | 🐛 3 | 🌐 Shell | 📅 2024-04-24

![GitHub last commit](https://img.shields.io/github/last-commit/psyrendust/alf) ![GitHub Repo stars](https://img.shields.io/github/stars/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24 and [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 while utilizing [Oh-My-Zsh](https://ohmyz.sh) under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh) ⭐ 355 | 🐛 2 | 🌐 Jinja | 📅 2025-10-06

![GitHub last commit](https://img.shields.io/github/last-commit/viasite-ansible/ansible-role-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses [antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 to manage bundles and [oh-my-zsh](origin/ohmyz.sh). Can load bundles conditionally. By default it includes the powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) ⚠️ Archived and [fzf-marks](https://github.com/urbainvaes/fzf-marks) ⭐ 514 | 🐛 18 | 🌐 Shell | 📅 2024-08-15. Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2018-08-03

![GitHub last commit](https://img.shields.io/github/last-commit/anthraxx/ant-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody) ⚠️ Archived

![GitHub last commit](https://img.shields.io/github/last-commit/getantibody/antibody)
![GitHub Repo stars](https://img.shields.io/github/stars/getantibody/antibody)

**Antibody** is a faster and simpler [antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 written in Golang. More details are available at <http://getantibody.github.io/>.

### [antidote](https://getantidote.github.io/)

![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/antidote)
![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/antidote)

**Antidote** is a ZSH plugin manager made from the ground up thinking about performance.

It is fast because it can do things concurrently, and generates an ultra-fast static plugin file that you can include in your ZSH config.

It is written natively in ZSH, is well tested, and picks up where [Antibody](https://github.com/getantibody/antibody) ⚠️ Archived left off.

[use-omz](https://github.com/getantidote/use-omz) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2025-05-20 enables easy use of [Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with antidote.

### [antigen-hs](https://github.com/Tarrasch/antigen-hs) ⭐ 206 | 🐛 3 | 🌐 Haskell | 📅 2024-07-29

![GitHub last commit](https://img.shields.io/github/last-commit/Tarrasch/antigen-hs)
![GitHub Repo stars](https://img.shields.io/github/stars/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for [antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 optimized for a low overhead when starting up a `zsh` session. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18

![GitHub last commit](https://img.shields.io/github/last-commit/zsh-users/antigen)
![GitHub Repo stars](https://img.shields.io/github/stars/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to `vim`. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [awesome-lazy-zsh](https://github.com/AmJaradat01/awesome-lazy-zsh) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-09

![GitHub last commit](https://img.shields.io/github/last-commit/AmJaradat01/awesome-lazy-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/AmJaradat01/awesome-lazy-zsh)

**Awesome-Lazy-ZSH** is a simplified and customizable ZSH setup tool for managing plugins and themes. It streamlines your terminal environment with an easy-to-use CLI interface, allowing you to manage .zshrc configurations effectively.
Features

* Plugin Management: Install and manage plugins easily.
* Theme Customization: Apply a variety of Zsh themes.
* Backup and Restore: Safeguard your .zshrc configurations.
* Interactive CLI: User-friendly setup options.
* Dependency Management: Automatically checks for Git, Node.js, and Homebrew.

### [ax-zsh](https://github.com/alexbarton/ax-zsh) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2026-01-31

![GitHub last commit](https://img.shields.io/github/last-commit/alexbarton/ax-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

**Ax-ZSH** integrates well with [Powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28 and other extensions, including plugins compatible with [oh-my-zsh](https://ohmyz.sh/).

### [deer](https://github.com/ArtixLabs/deer) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2022-11-11

![GitHub last commit](https://img.shields.io/github/last-commit/ArtixLabs/deer)
![GitHub Repo stars](https://img.shields.io/github/stars/ArtixLabs/deer)

A minimalist ZSH plugin manager.

### [dotzsh](https://github.com/dotphiles/dotzsh) ⭐ 230 | 🐛 2 | 🌐 Shell | 📅 2018-05-20

![GitHub last commit](https://img.shields.io/github/last-commit/dotphiles/dotzsh)
![GitHub Repo stars](https://img.shields.io/github/stars/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh) ⭐ 1,212 | 🐛 42 | 🌐 Ruby | 📅 2025-12-16

![GitHub last commit](https://img.shields.io/github/last-commit/freshshell/fresh)
![GitHub Repo stars](https://img.shields.io/github/stars/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as [Bundler](https://bundler.io) for your dot files.

### [gh-source](https://github.com/Yarden-zamir/gh-source) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-09-06

![GitHub last commit](https://img.shields.io/github/last-commit/Yarden-zamir/gh-source) ![GitHub Repo stars](https://img.shields.io/github/stars/Yarden-zamir/gh-source)

**gh-source** is a plugin manager for people who don't like plugin managers. It's a simple shell function that downloads and installs plugins from GitHub as part of the sourcing step. It's designed to be used with `zsh`, but it should work with any shell.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

![GitHub last commit](https://img.shields.io/github/last-commit/yerinalexey/miniplug) ![GitHub Repo stars](https://img.shields.io/github/stars/yerinalexey/miniplug)

**miniplug** is a minimalistic plugin manager for ZSH.

* No crashes or double plugin loading when re-sourcing `.zshrc`
* Unlike other frameworks, Miniplug does not pollute your `$PATH`
* Only does the bare minimum for managing plugins

### [oh-my-zsh](https://ohmyz.sh/)

![GitHub last commit](https://img.shields.io/github/last-commit/ohmyzsh/ohmyzsh) ![GitHub Repo stars](https://img.shields.io/github/stars/ohmyzsh/oh-my-zsh)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, `git`, macOS, `hub`, `capistrano`, `brew`, `ant`, MacPorts, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS](https://github.com/JoshuaEstes/pms) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2025-08-21

![GitHub last commit](https://img.shields.io/github/last-commit/JoshuaEstes/pms)
![GitHub Repo stars](https://img.shields.io/github/stars/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

The PMS framework also allows you to use the same framework in different shells. Use ZSH on your personal laptop, and use `bash` on remote servers. Wanna try `fish`? Go ahead, try out different shells.

### [prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24

![GitHub last commit](https://img.shields.io/github/last-commit/sorin-ionescu/prezto)
![GitHub Repo stars](https://img.shields.io/github/stars/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some [prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24-specific plugins at <https://github.com/belak/prezto-contrib> ⭐ 125 | 🐛 6 | 🌐 Shell | 📅 2022-10-30.

### [pumice](https://github.com/ryutamaki/pumice) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2015-05-10

![GitHub last commit](https://img.shields.io/github/last-commit/ryutamaki/pumice)
![GitHub Repo stars](https://img.shields.io/github/stars/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [rac](https://github.com/lomarco/rac) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-02

![GitHub last commit](https://img.shields.io/github/last-commit/lomarco/rac)
![GitHub Repo stars](https://img.shields.io/github/stars/lomarco/rac)

Most ZSH plugin managers are bloated. They try to do too much - dependency graphs, deferred loading, configuration injection - and in the process, they slow down your shell.

The reality is, most users never use even 80% of these features. `rac` is deliberately minimal. All it does is **download plugins** and **update plugins**.

### [rat](https://github.com/gotokazuki/rat-zsh) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-01-08

![GitHub last commit](https://img.shields.io/github/last-commit/gotokazuki/rat-zsh)
![GitHub Repo stars](https://img.shields.io/github/stars/gotokazuki/rat-zsh)

A lightweight, fast, and reproducible plugin manager for ZSH. Made with 🐭 & 🦀 — no magic, no heavy frameworks.

Features 🐭✨

* 🚀 Simple setup
  * Install with a single curl line
  * Just add one eval line in .zshrc to start using it
* ⚙️ Configurable and reproducible
  * Simple TOML-based configuration
  * Automatic plugin load order control
* 🐙 GitHub integration
  * Fetches plugins from GitHub repositories
  * Supports branches, tags, and commits
  * Handles Git submodules automatically
* ⚡️ Lightweight and fast
  * Parallel plugin sync
  * Built in Rust 🦀
* 🔄 Seamless updates
  * Self-upgrade
    -Plugin sync

### [ryzshrc](https://github.com/ryzshrc/ryzshrc) ⭐ 4 | 🐛 4 | 🌐 Shell | 📅 2025-02-02

![GitHub last commit](https://img.shields.io/github/last-commit/ryzshrc/ryzshrc)
![GitHub Repo stars](https://img.shields.io/github/stars/ryzshrc/ryzshrc)

**ryzshrc** is a smart, innovative plugin manager like [Oh My Zsh](https://ohmyz.sh/), designed to enhance your terminal experience with professional and cool features. It boosts productivity by providing efficient shell management, sleek themes, and powerful plugins. Perfect for developers seeking a modern and intelligent way to work with their terminal

### [sheldon](https://github.com/rossmacarthur/sheldon) ⭐ 1,387 | 🐛 18 | 🌐 Rust | 📅 2025-10-21

![GitHub last commit](https://img.shields.io/github/last-commit/rossmacarthur/sheldon)
![GitHub Repo stars](https://img.shields.io/github/stars/rossmacarthur/sheldon)

**sheldon** is a fast, configurable, shell plugin manager.

* It can manage:
  * Any `git` repository.
    * Branch/tag/commit support.
    * Extra support for GitHub repositories.
    * Extra support for Gists.
  * Arbitrary remote files, simply specify the URL.
  * Local plugins, simply specify the directory path.
* Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
* Super-fast parallel installation.
* Configuration file using [TOML](https://github.com/toml-lang/toml) ⭐ 20,339 | 🐛 14 | 📅 2025-12-24 syntax.
* Uses a lock file for much faster loading of plugins.

### [shplug](https://github.com/dtrugman/shplug) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2022-11-08

![GitHub last commit](https://img.shields.io/github/last-commit/dtrugman/shplug)
![GitHub Repo stars](https://img.shields.io/github/stars/dtrugman/shplug)

**shplug** is an easy solution for managing your shell environments. Works with both `bash` and `zsh`. Makes it easy to sync your environment across multiple machines with a `git` repository.

### [TheFly](https://github.com/joknarf/thefly) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2026-01-11

![GitHub last commit](https://img.shields.io/github/last-commit/joknarf/thefly) ![GitHub Repo stars](https://img.shields.io/github/stars/joknarf/thefly)

**TheFly** is a `bash`/`zsh`/`ksh` plugin manager and env teleporter

Makes your shell env and plugins available everywhere (hosts/users)!

### [Toasty](https://github.com/CosmicToast/toasty-zsh) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2020-04-28

![GitHub last commit](https://img.shields.io/github/last-commit/CosmicToast/toasty-zsh) ![GitHub Repo stars](https://img.shields.io/github/stars/CosmicToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [Usepkg](https://github.com/gynamics/zsh-usepkg) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-31

![GitHub last commit](https://img.shields.io/github/last-commit/gynamics/zsh-usepkg) ![GitHub Repo stars](https://img.shields.io/github/stars/gynamics/zsh-usepkg)

**Usepkg** is a minimal declarative zsh plugin manager.

Supports:

* fetch & load plugin(s) with declared methods
* list, check, reload, update & remove plugin(s) with commands

Dependencies:

* zsh
* gnu coreutils
* git (optional, if you want to clone git repositories from internet)
* curl (optional, if you want to fetch a script file by url)

Pros:

* extremely simple and light, but enough to use.
* compared to similar packages like `zplug`, it has a much simpler configuration grammar.

### [uz](https://github.com/maxrodrigo/uz) ⭐ 16 | 🐛 2 | 🌐 Shell | 📅 2021-09-06

![GitHub last commit](https://img.shields.io/github/last-commit/maxrodrigo/uz)
![GitHub Repo stars](https://img.shields.io/github/stars/maxrodrigo/uz)

**uz** is a micro plugin manager for ZSH

### [x-cmd](https://github.com/x-cmd/x-cmd) ⭐ 3,985 | 🐛 88 | 🌐 Shell | 📅 2026-02-06

![GitHub last commit](https://img.shields.io/github/last-commit/x-cmd/x-cmd)
![GitHub Repo stars](https://img.shields.io/github/stars/x-cmd/x-cmd)

**x-cmd** is a toolset implemented using posix shell and awk.It is very small in size and offers many interesting features. Here is a milestone demo: <https://x-cmd.com/>

Tools Provided by x-cmd:

* [Wrappers for Common Commands (e.g., cd, ip, ps, tar, apt, brew)](https://x-cmd.com/mod/zuz): These wrapped commands are more intelligent and easier to use compared to the native commands.
* [Lightweight Package Management Tool](https://x-cmd.com/pkg/): We have implemented a lightweight package management tool using shell and awk. Through it, you can quickly obtain most common software tools, such as jq, 7za, bat, nvim, python, node, go, etc.
* [CLI for Useful Websites (e.g., github.com, cht.sh)](https://x-cmd.com/mod/cht): We have wrapped their APIs using shell and awk for daily use and to obtain corresponding services in scripts.
* [AI Tools](https://x-cmd.com/mod/openai): We provide CLIs for ChatGPT, Gemini, Jina.ai, etc., and have wrapped corresponding shortcut commands for different application scenarios, such as `@gemini` for chatting with Gemini AI and `@zh` for using AI to translate specified content or command results.

### [yazt](https://github.com/bashelled/yazt) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-04-22

![GitHub last commit](https://img.shields.io/github/last-commit/bashelled/yazt)
![GitHub Repo stars](https://img.shields.io/github/stars/bashelled/yazt)

**Yazt** is a simple ZSH theme manager in maintenance that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes and with a few modifications, you can even use it in `bash`.

### [yzsh](https://github.com/yunielrc/yzsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-03-12

![GitHub last commit](https://img.shields.io/github/last-commit/yunielrc/yzsh)
![GitHub Repo stars](https://img.shields.io/github/stars/yunielrc/yzsh)

**yzsh** is a simple ZSH framework for managing plugins, themes, functions, aliases and environment variables.

### [zap](https://github.com/zap-zsh/zap) ⭐ 1,132 | 🐛 14 | 🌐 Shell | 📅 2025-07-12

![GitHub last commit](https://img.shields.io/github/last-commit/zap-zsh/zap)
![GitHub Repo stars](https://img.shields.io/github/stars/zap-zsh/zap)

**:zap:zap** is a minimal ZSH plugin manager.

### [zapack](https://github.com/aiya000/zsh-zapack) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2020-08-19

![GitHub last commit](https://img.shields.io/github/last-commit/aiya000/zsh-zapack)
![GitHub Repo stars](https://img.shields.io/github/stars/aiya000/zsh-zapack)

**zapack** is a basic fast minimal ZSH plugin loader.

### [zcomet](https://github.com/agkozak/zcomet) ⭐ 230 | 🐛 14 | 🌐 Shell | 📅 2025-02-12

![GitHub last commit](https://img.shields.io/github/last-commit/agkozak/zcomet)
![GitHub Repo stars](https://img.shields.io/github/stars/agkozak/zcomet)

**zcomet** is a minimalistic ZSH plugin manager that gets you to the prompt surprisingly quickly without caching (see the benchmarks). In addition to loading and updating plugins stored in `git` repositories, it supports lazy-loading plugins (further reducing startup time) as well as downloading and sourcing code snippets.

### [zeesh](https://github.com/zeekay/zeesh) ⭐ 48 | 🐛 1 | 🌐 Shell | 📅 2025-09-09

![GitHub last commit](https://img.shields.io/github/last-commit/zeekay/zeesh)
![GitHub Repo stars](https://img.shields.io/github/stars/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem) ⭐ 11 | 🐛 3 | 🌐 Shell | 📅 2024-02-09

![GitHub last commit](https://img.shields.io/github/last-commit/qoomon/zgem)
![GitHub Repo stars](https://img.shields.io/github/stars/qoomon/zgem)

**zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,519 | 🐛 41 | 🌐 Shell | 📅 2021-07-21

![GitHub last commit](https://img.shields.io/github/last-commit/tarjoilija/zgen)
![GitHub Repo stars](https://img.shields.io/github/stars/tarjoilija/zgen)

**Zgen is currently not being actively maintained**. I recommend you use the [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01 fork instead, which is actively maintained and continues to get new features and bug fixes.

**Zgen** is a lightweight plugin manager for ZSH inspired by [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18. The goal is to have minimal overhead when starting up the shell because nobody likes waiting.

### [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01

![GitHub last commit](https://img.shields.io/github/last-commit/jandamm/zgenom)
![GitHub Repo stars](https://img.shields.io/github/stars/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,519 | 🐛 41 | 🌐 Shell | 📅 2021-07-21 and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during every shell session's startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24-compatible plugins and themes, and will automagically `git clone` plugins for you when you add them to your plugin list.

### [zilsh](https://github.com/zilsh/zilsh) ⚠️ Archived

![GitHub last commit](https://img.shields.io/github/last-commit/zilsh/zilsh)
![GitHub Repo stars](https://img.shields.io/github/stars/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw) ⭐ 4,502 | 🐛 26 | 🌐 Shell | 📅 2026-01-08

![GitHub last commit](https://img.shields.io/github/last-commit/zimfw/zimfw)
![GitHub Repo stars](https://img.shields.io/github/stars/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02

![GitHub last commit](https://img.shields.io/github/last-commit/zdharma-continuum/zinit) ![GitHub Repo stars](https://img.shields.io/github/stars/zdharma-continuum/zinit)

**Zinit** is an innovative and probably (because of the Turbo) the fastest plugin manager with support for:

* Turbo mode – 80% faster ZSH startup! for example: instead of 200 ms, it'll be 40 ms
* Completion management (selectively disable and enable completions)
* Snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead)
* Annexes (↔ Zinit extensions)
* Reports (from the plugin loads – plugins are no longer black boxes)
* Plugin unloading (allows e.g.: dynamic theme switching)
* `bindkey` capturing and remapping
* packages
* Clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated)
* Services ↔ a single-instance, background plugins
* Also, in general: all the mechanisms from the ZSH Plugin Standard – Zinit is a reference implementation of the standard.

The project is very active – currently > 3100 commits.

### [zinit-4](https://github.com/psprint/Zinit-4) ⭐ 28 | 🐛 6 | 🌐 Shell | 📅 2023-10-24

![GitHub last commit](https://img.shields.io/github/last-commit/psprint/Zinit-4)
![GitHub Repo stars](https://img.shields.io/github/stars/psprint/Zinit-4)

This is Zinit 4 from the [original author](https://github.com/psprint), who once removed the [Zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 repository from GitHub. This spawned a community-driven [zdharma-continuum](https://github.com/zdharma-continuum) organization that revived all of psprint's ZSH projects. Its main innovations from the @zdharma-continuum fork are:

* AppImage distribution (release link),
* Action complete – press Alt-Shift-A and Alt-Shift-C to complete plugin names and ice modifiers,
* Themes – set $ZITHEME to one of default, blue and gold to set a color set to use for Zinit 4 messages,
* New ice `build` which is equivalent of three other ices: `null`, `configure` and `make install` and simply builds the project from sources, with support for autotools/CMake/Meson/Scons.

These are the most visible changes, but there are more (like e.g.: support for compiling with libraries from previously built projects/`$ZPFX`).

### [zit](https://github.com/thiagokokada/zit) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2020-11-02

![GitHub last commit](https://img.shields.io/github/last-commit/thiagokokada/zit)
![GitHub Repo stars](https://img.shields.io/github/stars/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from `git` repositories (and `git` repositories only, that's why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, `$PATH` manipulation and others.

### [zlugin](https://github.com/DrgnFireYellow/zlugin) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2024-06-15

![GitHub last commit](https://img.shields.io/github/last-commit/DrgnFireYellow/zlugin)
![GitHub Repo stars](https://img.shields.io/github/stars/DrgnFireYellow/zlugin)

**zlugin** is a very lightweight ZSH plugin manager.

### [znap](https://github.com/marlonrichert/zsh-snap) ⭐ 1,485 | 🐛 21 | 🌐 Shell | 📅 2025-08-06

![GitHub last commit](https://img.shields.io/github/last-commit/marlonrichert/zsh-snap) ![GitHub Repo stars](https://img.shields.io/github/stars/marlonrichert/zsh-snap)

**:zap:Znap** is a light-weight plugin manager & `git` repository manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, **Znap** also functions as a general-purpose utility for managing `git` repositories.

Znap can:

* Make any prompt appear instantly. Reduce your startup time from \~200ms to \~40ms with just one command.
* Asynchronously compile your plugins and functions.
* Cache those expensive `eval $(commands)`.
* Clone or pull multiple repos in parallel.
* Re-clone all your repos without you having to re-enter them.
* Multi-repo management
* Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo](https://github.com/zoppo/zoppo) ⭐ 36 | 🐛 4 | 🌐 Shell | 📅 2025-08-27

![GitHub last commit](https://img.shields.io/github/last-commit/zoppo/zoppo)
![GitHub Repo stars](https://img.shields.io/github/stars/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-09-09

![GitHub last commit](https://img.shields.io/github/last-commit/happyslowly/zpacker)
![GitHub Repo stars](https://img.shields.io/github/stars/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-04-02

![GitHub last commit](https://img.shields.io/github/last-commit/thornjad/zpico)
![GitHub Repo stars](https://img.shields.io/github/stars/thornjad/zpico)

**zpico** is a minuscule ZSH package manager. No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.

ZSH package managers are abundant, but most are bloated, slow or have excessive requirements. On top of that, more than a few have been abandoned for years. Zpico does not seek to be the best of the best, rather to balance functionality against a tiny, fast footprint.

### [zplug](https://github.com/zplug/zplug) ⭐ 5,990 | 🐛 150 | 🌐 Shell | 📅 2024-06-12

![GitHub last commit](https://img.shields.io/github/last-commit/zplug/zplug)
![GitHub Repo stars](https://img.shields.io/github/stars/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

* Can manage everything
  * Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24 plugins/themes
  * etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md) ⭐ 5,990 | 🐛 150 | 🌐 Shell | 📅 2024-06-12!)
  * ZSH plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  * Gist files ([gist.github.com](https://gist.github.com/discover))
  * Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  * Local plugins
* Interactive interface ([fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05, [peco](https://github.com/peco/peco) ⭐ 7,855 | 🐛 52 | 🌐 Go | 📅 2025-11-09, [zaw](https://github.com/zsh-users/zaw) ⭐ 581 | 🐛 13 | 🌐 Shell | 📅 2023-08-05, and so on)
* Unlike [antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18, no ZSH plugin files (`*.plugin.zsh`) are required
* Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs) ⭐ 5,990 | 🐛 150 | 🌐 Shell | 📅 2024-06-12
* Super-fast parallel installation/update
* Support for lazy-loading
* Branch/tag/commit support
* Post-update, post-load hooks
* Dependencies between packages

### [zpm](https://github.com/zpm-zsh/zpm) ⭐ 391 | 🐛 5 | 🌐 Shell | 📅 2025-12-21

![GitHub last commit](https://img.shields.io/github/last-commit/zpm-zsh/zpm)
![GitHub Repo stars](https://img.shields.io/github/stars/zpm-zsh/zpm)

**zpm** (ZSH Plugin Manager) is a plugin manager for [ZSH](http://www.zsh.org/) which combines the imperative and declarative approach. At first run, `zpm` will do complex logic and generate a cache, after that will only use the cache, so it makes this framework very fast.

* Fastest plugin manager (Really, after the first run, `zpm` will not be used at all)
* Support for async loading
* Dependencies between packages
* **zpm** runs on Linux, macOS, FreeBSD and Android.
* **zpm** plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr) ⭐ 191 | 🐛 4 | 🌐 Rust | 📅 2025-05-12

![GitHub last commit](https://img.shields.io/github/last-commit/jedahan/zr)
![GitHub Repo stars](https://img.shields.io/github/stars/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2020-09-09

![GitHub last commit](https://img.shields.io/github/last-commit/zakariaGatter/zshing)
![GitHub Repo stars](https://img.shields.io/github/stars/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* Keep track of and configure your plugins right in the `.zshrc`
* Install ZSH plugins
* Update ZSH plugins
* Search by name all available ZSH Plugins
* Clean unused plugins up
* Run the above actions in a *single command*
* Manages the **Source Plugins** of your installed Plugins

### [zsh-dot-plugin](https://github.com/DuckzCantFly/zsh-dot-plugin) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-10-11

![GitHub last commit](https://img.shields.io/github/last-commit/DuckzCantFly/zsh-dot-plugin) ![GitHub Repo stars](https://img.shields.io/github/stars/DuckzCantFly/zsh-dot-plugin)

**zsh-dot-plugin** will customize your `.zshrc` with only \~21 lines of code. Based on [zsh-unplugged](https://github.com/mattmc3/zsh_unplugged) ⭐ 487 | 🐛 0 | 🌐 Shell | 📅 2025-10-09.

### [zsh-mgr](https://github.com/amt911/zsh-mgr) ⭐ 3 | 🐛 5 | 🌐 Rust | 📅 2026-02-03

![GitHub last commit](https://img.shields.io/github/last-commit/amt911/zsh-mgr)
![GitHub Repo stars](https://img.shields.io/github/stars/amt911/zsh-mgr)

A simple plugin manager for zsh. Features:

* Auto-updates all plugins.
* Auto-updates itself.
* Configurable time interval for both auto-updaters.

### [zsh-unplugged](https://github.com/mattmc3/zsh_unplugged) ⭐ 487 | 🐛 0 | 🌐 Shell | 📅 2025-10-09.

![GitHub last commit](https://img.shields.io/github/last-commit/mattmc3/zsh_unplugged)
![GitHub Repo stars](https://img.shields.io/github/stars/mattmc3/zsh_unplugged)

**zsh-unplugged** is a *tiny* plugin manager. TLDR; You don't need a big bloated plugin manager for your ZSH plugins. A simple \~20 line function may be all you need.

### [zshPlug](https://github.com/Atlas34/zshPlug) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-11-08

![GitHub last commit](https://img.shields.io/github/last-commit/Atlas34/zshPlug)
![GitHub Repo stars](https://img.shields.io/github/stars/Atlas34/zshPlug)

**zshPlug** is a minimalist plugin manager heavily based on [zap](https://github.com/zap-zsh/zap) ⭐ 1,132 | 🐛 14 | 🌐 Shell | 📅 2025-07-12.

### [ztanesh](https://github.com/miohtama/ztanesh) ⭐ 270 | 🐛 10 | 🌐 Shell | 📅 2024-09-04

![GitHub last commit](https://img.shields.io/github/last-commit/miohtama/ztanesh)
![GitHub Repo stars](https://img.shields.io/github/stars/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-08-10

![GitHub last commit](https://img.shields.io/github/last-commit/SkyyySi/ztheme)
![GitHub Repo stars](https://img.shields.io/github/stars/SkyyySi/ztheme)

**ztheme** is a small and fast theme engine for ZSH.

### [ztupide](https://github.com/mpostaire/ztupide) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-01-31

![GitHub last commit](https://img.shields.io/github/last-commit/mpostaire/ztupide)
![GitHub Repo stars](https://img.shields.io/github/stars/mpostaire/ztupide)

**ztupide** is a simple and fast ZSH plugin manager. It uses `zcompile` and async loading to speed up your shell startup time.

### [zulu](https://github.com/zulu-zsh/zulu) ⭐ 157 | 🐛 2 | 🌐 Shell | 📅 2019-02-20

![GitHub last commit](https://img.shields.io/github/last-commit/zulu-zsh/zulu)
![GitHub Repo stars](https://img.shields.io/github/stars/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5 or later, which aims to make it easy to manage your shell without writing any code.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
* Install packages, plugins and themes easily, and have them available to you immediately.

### [zush](https://github.com/shyndman/zush) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2026-02-04 🦥 - Mid-Performance ZSH Configuration

![GitHub last commit](https://img.shields.io/github/last-commit/shyndman/zush)
![GitHub Repo stars](https://img.shields.io/github/stars/shyndman/zush)

**zush** is a performance-aware ZSH configuration designed for sub-200ms startup times while maintaining full functionality.

Features:

* Instant Prompts - Basic prompt appears immediately, full prompt loads after \~129ms
* Plugin Management - Simple `zushp user/repo` command to install GitHub plugins
* Lazy Loading - Tools like `nvm`, `pyenv`, `cargo` load only when needed
* Auto-compilation - All ZSH files compiled with `zcompile` for faster loading
* Smart Caching - Environment changes cached for instant startup

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) ⭐ 881 | 🐛 16 | 🌐 Shell | 📅 2025-12-19 - A simple quickstart for using ZSH with [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01. This automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01 to load a curated (but easily customizable) collection of plugins and periodically automatically update itself, the plugins, and the quickstart kit itself.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) ⭐ 219 | 🐛 1 | 🌐 Shell | 📅 2026-01-01 - An extremely powerful custom terminal environment built on top of [Zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 for maximum speed.  A full terminal configuration framework including `zsh`, `tmux`, `fzf`, `vim` and spacemacs configurations.  It includes:

* 12.9k+ tab completions

* 1.9k+ aliases

* 330+ git aliases

* 400+ zpwr subcommands

* 2.8k functions

* 175+ zpwr environment variables

* 175+ perl, python, bash, ZSH scripts

* 2.8k line README.md

* 50k+ LOC

* 1 line install

## Prerequisites

If you're on a Mac, the `zsh` that comes with it is usually pretty stale. You can use `brew install zsh` to update it.

Many of the themes here use special glyphs for things like displaying a branch icon. You'll need to use a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 or a Powerline-compatible font in your terminal program or you'll see ugly broken boxes where the symbols should be.

Here are a few good sources for Nerd Fonts and Powerline-compatible fonts:

* [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 - A collection of over 20 patched fonts (over 1,700 variations) & the fontforge font patcher python script for Powerline, devicons, and vim-devicons: includes Droid Sans, Meslo, AnonymousPro, ProFont, Inconsolta, and many more. These can be installed with `brew` - do `brew tap homebrew/cask-fonts && brew install --cask fontname`
* [Cascadia Code](https://github.com/microsoft/cascadia-code) ⭐ 27,501 | 🐛 153 | 🌐 Python | 📅 2025-03-06 - Microsoft's Cascadia Code
* [Powerline patched font collection](https://github.com/powerline/fonts) ⭐ 26,221 | 🐛 182 | 🌐 Shell | 📅 2024-03-22 - A collection of a dozen or so fonts patched to include Powerline glyphs.
* [Fira Mono](https://github.com/mozilla/Fira) ⭐ 5,157 | 🐛 101 | 🌐 CSS | 📅 2020-12-16 - Mozilla's Fira type family.
* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) ⭐ 2,515 | 🐛 23 | 🌐 Shell | 📅 2024-01-16 - A family of fonts that include some nice monospaced Icons.
* [Spacemono](https://github.com/googlefonts/spacemono) ⭐ 412 | 🐛 9 | 📅 2025-01-17 - Google's new original monospace display typeface family.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) ⭐ 37 | 🐛 1 | 🌐 Shell | 📅 2015-02-20 - A nice monospaced font, patched with Font-Awesome, Octoicons, and Powerline-Glyphs.
* [Commit Mono](https://commitmono.com) - Neutral programming typeface.
* [Hack](http://sourcefoundry.org/hack/) - Another Powerline-compatible font designed for source code and terminal usage.
* [Input Mono](https://input.djr.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes Powerline glyphs.
* [Iosevka](https://be5invis.github.io/Iosevka/) - Iosevka is an open source slender monospace sans-serif and slab-serif typeface inspired by [Pragmata Pro](http://www.fsd.it/fonts/pragmatapro.htm), M+ and [PF DIN Mono](https://www.myfonts.com/fonts/parachute/pf-din-mono/), designed to be the ideal font for programming.
* [Monoid](http://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Mononoki](https://madmalik.github.io/mononoki/) - Mononoki is a typeface by Matthias Tellen, created to enhance code formatting.
* [More Nerd Fonts](https://www.nerdfonts.com/font-downloads) - Another site to download Nerd Fonts.
* [Victor Mono](https://rubjo.github.io/victor-mono/) - Victor Mono is a free programming font with semi-connected cursive italics, symbol ligatures (!=, ->>, =>, ===, <=, >=, ++) and Latin, Cyrillic and Greek characters.

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24, [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) ⭐ 13,394 | 🐛 100 | 🌐 Ruby | 📅 2026-01-25 to make for an extremely productive developer workflow.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans) ⭐ 2,189 | 🐛 42 | 📅 2025-09-21 - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
* [ZSH Unplugged](https://github.com/mattmc3/zsh_unplugged) ⭐ 487 | 🐛 0 | 🌐 Shell | 📅 2025-10-09 - Good resource if you want to eliminate using a framework but still easily use plugins.
* [zephyr](https://github.com/mattmc3/zephyr) ⭐ 210 | 🐛 2 | 🌐 Shell | 📅 2026-02-05 - Zephyr uses built-in Zsh features to set up better default options, completions, keybindings, history, and much more.
* [ZSH Pony](https://github.com/mika/zsh-pony) ⭐ 188 | 🐛 0 | 📅 2011-07-29 - Covers customizing ZSH without a framework.
* [GH](https://github.com/gustavohellwig/gh-zsh) ⭐ 74 | 🐛 0 | 🌐 Shell | 📅 2026-01-14 - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28, [zsh-completions](https://github.com/zsh-users/zsh-completions) ⭐ 7,630 | 🐛 16 | 🌐 Shell | 📅 2026-02-04, [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ⭐ 34,784 | 🐛 196 | 🌐 Shell | 📅 2025-06-24, [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting/) ⭐ 1,597 | 🐛 43 | 🌐 Shell | 📅 2025-07-16, and more.
* [adamnorwood-zsh](https://github.com/adamnorwood/adamnorwood-zsh/) ⭐ 13 | 🐛 3 | 🌐 Shell | 📅 2024-01-16 - A minimalist but readable ZSH setup based on [oh-my-posh](https://ohmyposh.dev/).
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2020-07-31 - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [ZSH Setup by Easy-Cloud-in](https://github.com/Easy-Cloud-in/zsh-setup) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-01-31 - A powerful Zsh environment setup with Oh My Posh themes, essential plugins, and advanced search capabilities. This repository provides scripts to automatically configure your terminal with modern features and aesthetics. Requires a Debian or Ubuntu based system.
* [A Guide to ZSH Completion With Examples](https://thevaluable.dev/zsh-completion-guide-examples/) - Explains ZSH autocompletion configuration with examples.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Profiling ZSH](https://ellie.wtf/notes/profiling-zsh) - Good article about profiling your ZSH setup to optimize startup time.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) ⭐ 207 | 🐛 2 | 🌐 Shell | 📅 2025-10-15 - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [One Key Linux Setup](https://github.com/miracleyoo/one-key-linux-setup) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2026-01-20 - Simple setup (ubuntu-only) of `zsh`, `oh-my-zsh`, `tmux`, `python` support and other packages.
* [How to Install and Configure Z Shell in Ubuntu](https://github.com/profpan396/how-to-install-and-configure-zshell) ⭐ 8 | 🐛 0 | 📅 2024-09-04 - Amar Pan's article will walk you through the process of installing and configuring ZSH, including how to change themes and enable the time-saving autosuggestions plug-in.
* [Configuration to use Hyper.js as a ZSH terminal with a Windows Subsystem Linux on windows 10, with Oh My Zsh and the Powerlevel10k theme](https://github.com/jkergal/hyperjs-wsl-zsh-powerlevel10k-config-on-windows/) ⭐ 6 | 🐛 0 | 📅 2022-04-11 - How-to for getting Oh-My-ZSH running on WSL.
* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [iTerm2 + Oh-My-ZSH: Supercharge Your Mac Terminal](https://catalins.tech/improve-mac-terminal) - Catalin Pit's tutorial on getting started with Oh-My-ZSH on macOS.
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [Speeding Up My ZSH Shell](https://scottspence.com/posts/speeding-up-my-zsh-shell) - A quick guide to speeding up ZSH with OMZ

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) ⭐ 41 | 🐛 1 | 🌐 Shell | 📅 2025-11-08 - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24, and [Zgen](https://github.com/tarjoilija/zgen) ⭐ 1,519 | 🐛 41 | 🌐 Shell | 📅 2021-07-21.

### Zinit (né zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) ⭐ 358 | 🐛 5 | 🌐 Shell | 📅 2025-01-30 - :crystal\_ball: Awesome, customizable Zsh Starter Kit :stars::stars:. Includes powerline, [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 integration, Weather and image viewing in some terminals.
* [zinit-configs](https://github.com/zdharma-continuum/zinit-configs) ⭐ 73 | 🐛 2 | 🌐 Shell | 📅 2023-04-16 - Real-world configuration files (basically a collection of `.zshrc` files) holding [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 invocations.

### ZSH on Windows

#### [superconsole](https://github.com/alexchmykhalo/superconsole) ⭐ 91 | 🐛 0 | 🌐 Shell | 📅 2021-10-14 - Windows-only

* Uses [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 for ZSH theme and config management
* Non-blocking ZSH prompt status updates thanks to [agkozak-zsh-prompt](https://github.com/agkozak/agkozak-zsh-prompt) ⭐ 336 | 🐛 10 | 🌐 Shell | 📅 2025-01-01
* `ConEmu`/`zsh` out-of-the-box configured to restore previously opened tabs and shell working directories after `ConEmu` restart
* Choose between clean and inherited environment when starting new SuperConsole sessions
* Custom colorful scheme, colorful output for various commands
* `MSYS2` included, `zsh` and necessary software preinstalled, uses zsh-grml-config
* Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
* Git-for-Windows repo with proper `git` and `git lfs` support for `MSYS2` environment is configured, `git` client already installed.
* `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
* Command-not-found handler customized for `MSYS2` suggests what package to install
* Sets up `nano` as main editor, enables `nano` syntax highlighting
* Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ⭐ 34,784 | 🐛 196 | 🌐 Shell | 📅 2025-06-24 - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 33,206 | 🐛 151 | 🌐 Rust | 📅 2026-02-02 - A fast alternative to `cd` that learns your habits.
* [zellij (tranzystorek-io)](https://codeberg.org/tranzystorekk/zellij.zsh) - Provides an environment that autostarts [zellij](https://github.com/zellij-org/zellij) ⭐ 28,728 | 🐛 1,477 | 🌐 Rust | 📅 2026-02-06 as your terminal's multiplexer.
* [atuin](https://github.com/ellie/atuin) ⭐ 28,180 | 🐛 439 | 🌐 Rust | 📅 2026-02-06 - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) ⭐ 22,216 | 🐛 205 | 🌐 Shell | 📅 2024-11-21 - Add syntax highlighting to your ZSH prompt. Make sure you load this *before* [zsh-users/zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) ⭐ 2,976 | 🐛 45 | 🌐 Shell | 📅 2026-01-15 or they will both break.
* [autojump](https://github.com/wting/autojump) ⭐ 16,821 | 🐛 225 | 🌐 Python | 📅 2025-02-27 - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [blackbox](https://github.com/StackExchange/blackbox) ⚠️ Archived - Stack Exchange's toolkit for storing keys/credentials securely in a `git` repository.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) ⭐ 6,370 | 🐛 31 | 🌐 Shell | 📅 2025-12-09 - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
* [autoenv](https://github.com/hyperupcall/autoenv) ⭐ 5,998 | 🐛 13 | 🌐 Shell | 📅 2025-11-20 - Directory-based environments.
* [forgit](https://github.com/wfxr/forgit) ⭐ 4,879 | 🐛 14 | 🌐 Shell | 📅 2026-02-06 - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) ⭐ 4,497 | 🐛 93 | 🌐 Shell | 📅 2026-02-03 - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) ⭐ 4,209 | 🐛 118 | 🌐 Shell | 📅 2026-01-14 - 💻 A better and friendly `vi`(`vim`) mode plugin for ZSH.
* [git-secret](https://github.com/sobolevn/git-secret) ⭐ 3,959 | 🐛 109 | 🌐 Shell | 📅 2026-02-02 - A bash tool to store your private data inside a `git` repository.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) ⭐ 3,761 | 🐛 7 | 🌐 Shell | 📅 2026-01-13 - ZSH plugin for `kubectl` that adds current context and namespace.
* [z.lua](https://github.com/skywind3000/z.lua) ⭐ 3,121 | 🐛 71 | 🌐 Lua | 📅 2025-12-24 - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19 with Windows and posix shells support and various improvements. 10x faster than [fasd](https://github.com/whjvenyl/fasd) ⭐ 104 | 🐛 5 | 🌐 Shell | 📅 2025-10-20 and autojump, 3x faster than [z.sh](https://github.com/rupa/z) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19.
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) ⭐ 2,976 | 🐛 45 | 🌐 Shell | 📅 2026-01-15 - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [enhancd](https://github.com/b4b4r07/enhancd) ⭐ 2,675 | 🐛 20 | 🌐 Shell | 📅 2025-01-24 - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) ⭐ 2,413 | 🐛 0 | 🌐 Shell | 📅 2025-12-04 - A CLI interface to `git` that relies heavily on [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [nvm](https://github.com/lukechilds/zsh-nvm) ⭐ 2,387 | 🐛 30 | 🌐 Shell | 📅 2024-07-03 - ZSH plugin for installing, updating and loading `nvm`.
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z) ⭐ 2,333 | 🐛 21 | 🌐 Shell | 📅 2025-05-07 - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
* [ansiweather](https://github.com/fcambus/ansiweather) ⭐ 1,928 | 🐛 2 | 🌐 Shell | 📅 2025-12-29 - Weather in your terminal, with ANSI colors and Unicode symbols.
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) ⭐ 1,839 | 🐛 31 | 🌐 Shell | 📅 2025-12-28 - ZSH plugin that reminds you to use those aliases you defined.
* [k](https://github.com/supercrabtree/k) ⭐ 1,816 | 🐛 39 | 🌐 Shell | 📅 2023-02-04 - Directory listings for ZSH with `git` status decorations.
* [codex](https://github.com/tom-doerr/zsh_codex) ⭐ 1,706 | 🐛 21 | 🌐 Python | 📅 2025-03-22 - Enables you to use OpenAI's powerful Codex AI in the command line.
* [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting) ⭐ 1,597 | 🐛 43 | 🌐 Shell | 📅 2025-07-16 - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
* [ugit](https://github.com/Bhupesh-V/ugit) ⭐ 1,500 | 🐛 8 | 🌐 Shell | 📅 2025-04-13 - Lets you undo your last `git` operation.
* [histdb](https://github.com/larkery/zsh-histdb) ⭐ 1,357 | 🐛 39 | 🌐 Shell | 📅 2024-04-27 - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ⭐ 34,784 | 🐛 196 | 🌐 Shell | 📅 2025-06-24.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) ⭐ 1,127 | 🐛 1 | 🌐 Shell | 📅 2026-02-06 - Extra `git` helper scripts packaged as a plugin.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) ⭐ 1,089 | 🐛 9 | 🌐 Shell | 📅 2024-09-30 - Automates ZSH + [oh-my-zsh](https://ohmyz.sh/) installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [sysadmin-util](https://github.com/skx/sysadmin-util) ⚠️ Archived - Steve Kemp's collection of tool scripts for sysadmins.
* [shellfirm](https://github.com/kaplanelad/shellfirm) ⭐ 879 | 🐛 1 | 🌐 Rust | 📅 2025-09-04 - Shellfirm is a handy utility to help avoid running dangerous commands without an extra step of approval. When risky patterns is detected you will immediately get a small prompt challenge that will verify your action.
* [async](https://github.com/mafredri/zsh-async) ⭐ 810 | 🐛 20 | 🌐 Shell | 📅 2023-11-15 - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [alias-tips](https://github.com/djui/alias-tips) ⭐ 809 | 🐛 18 | 🌐 Python | 📅 2023-06-08 - An [oh-my-zsh](https://ohmyz.sh/) plugin to help remembering those aliases you defined once.
* [abbr](https://github.com/olets/zsh-abbr) ⭐ 734 | 🐛 14 | 🌐 Shell | 📅 2026-02-06 - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by the fish shell.
* [wd](https://github.com/mfaerevaag/wd) ⭐ 732 | 🐛 8 | 🌐 Shell | 📅 2025-11-24 - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [dotbare](https://github.com/kazhala/dotbare) ⭐ 725 | 🐛 11 | 🌐 Shell | 📅 2024-04-28 - Interactive dotfile management with the help of [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) ⭐ 690 | 🐛 11 | 🌐 Shell | 📅 2022-06-28 - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
* [artisan](https://github.com/jessarcher/zsh-artisan) ⭐ 647 | 🐛 10 | 🌐 Shell | 📅 2025-12-08 - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [autopair](https://github.com/hlissner/zsh-autopair) ⭐ 608 | 🐛 7 | 🌐 Shell | 📅 2024-07-14 - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) ⭐ 607 | 🐛 36 | 🌐 Shell | 📅 2026-01-07 - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects [pipenv](https://pypi.org/project/pipenv/) and [poetry](https://python-poetry.org/) projects.
* [kubectl-prompt](https://github.com/superbrothers/zsh-kubectl-prompt) ⭐ 587 | 🐛 1 | 🌐 Shell | 📅 2023-05-15 - Display information about the kubectl current context and namespace in your ZSH prompt. Creates `ZSH_KUBECTL_CONTEXT`, `ZSH_KUBECTL_NAMESPACE`,`ZSH_KUBECTL_PROMPT` and `ZSH_KUBECTL_USER` variables you can use to customize your prompt.
* [zaw](https://github.com/zsh-users/zaw) ⭐ 581 | 🐛 13 | 🌐 Shell | 📅 2023-08-05 - ZSH anything.el-like widget.
* [fz](https://github.com/changyuheng/fz) ⭐ 562 | 🐛 9 | 🌐 Shell | 📅 2024-02-25 - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19's tab completion and lets you easily jump around among directories in your history.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) ⭐ 545 | 🐛 6 | 🌐 Shell | 📅 2023-09-26 - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) ⭐ 514 | 🐛 18 | 🌐 Shell | 📅 2024-08-15 - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) ⭐ 467 | 🐛 31 | 🌐 Shell | 📅 2025-06-23 - Automatically sends out a notification when a long running task has completed.
* [defer](https://github.com/romkatv/zsh-defer) ⭐ 459 | 🐛 2 | 🌐 Shell | 📅 2024-02-10 - Defers execution of a `zsh` command until `zsh` has nothing else to do and is waiting for user input. Its intended purpose is staged `zsh` startup. It works similarly to Turbo mode in [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) ⭐ 451 | 🐛 9 | 🌐 Shell | 📅 2025-11-09 - Replaces `Ctrl+R` with an [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05-driven history search that includes date/times.
* [bd](https://github.com/Tarrasch/zsh-bd) ⭐ 445 | 🐛 7 | 🌐 Shell | 📅 2025-01-09 - Jump back to a specific directory, without doing `cd ../../..`.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) ⭐ 445 | 🐛 15 | 🌐 Shell | 📅 2022-06-28 - :scream: Emoji completion on the command line.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) ⭐ 436 | 🐛 22 | 🌐 Shell | 📅 2017-04-18 - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) ⭐ 428 | 🐛 4 | 🌐 Shell | 📅 2024-03-01 - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/) ⭐ 402 | 🐛 6 | 🌐 Shell | 📅 2025-12-19 - Enables [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 history and file searches.
* [proxy](https://github.com/SukkaW/zsh-proxy) ⭐ 396 | 🐛 7 | 🌐 Shell | 📅 2025-11-19 - Configure proxy settings for some package managers and software.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) ⭐ 385 | 🐛 5 | 🌐 Shell | 📅 2024-02-23 - Adds `git` status in your prompt.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) ⭐ 362 | 🐛 8 | 🌐 Shell | 📅 2025-11-02 - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [jq](https://github.com/reegnz/jq-zsh-plugin) ⭐ 356 | 🐛 2 | 🌐 Shell | 📅 2025-07-23 - Interactively build [jq](https://stedolan.github.io/jq/) expressions. Also supports [gojq](https://github.com/itchyny/gojq) ⭐ 3,686 | 🐛 14 | 🌐 Go | 📅 2026-01-31. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) ⭐ 351 | 🐛 3 | 🌐 Ruby | 📅 2023-03-27 - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
* [per-directory-history](https://github.com/jimhester/per-directory-history) ⭐ 345 | 🐛 24 | 🌐 Shell | 📅 2025-09-04 - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) ⭐ 332 | 🐛 5 | 🌐 Shell | 📅 2022-07-26 - Fish-like interactive tab completion for `cd`.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) ⭐ 310 | 🐛 3 | 🌐 Shell | 📅 2025-01-27 - [oh-my-zsh](https://ohmyz.sh/) doesn't automatically update non-core plugins, this plugin autoupdates `git` repositories in the `$ZSH_CUSTOM` directory.
* [deer](https://github.com/Vifon/deer) ⭐ 304 | 🐛 5 | 🌐 Shell | 📅 2022-07-26 - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) ⭐ 301 | 🐛 1 | 🌐 Shell | 📅 2022-06-28 - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
* [zshmarks](https://github.com/jocelynmallon/zshmarks) ⭐ 281 | 🐛 8 | 🌐 Shell | 📅 2024-02-15 - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for [oh-my-zsh](https://ohmyz.sh).
* [hangul](https://github.com/gomjellie/zsh-hangul) ⭐ 268 | 🐛 3 | 🌐 Shell | 📅 2025-07-31 - Auto correct hangul(한글, korean) to English when it was supposed to be typed in English. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
* [history-sync (wulfgarpro)](https://github.com/wulfgarpro/history-sync) ⭐ 265 | 🐛 1 | 🌐 Shell | 📅 2025-12-18 - An [oh-my-zsh](https://ohmyz.sh/) plugin for [GPG](https://www.gnupg.org/) encrypted, Internet synchronized ZSH history using `git`.
* [evalcache](https://github.com/mroth/evalcache) ⭐ 254 | 🐛 2 | 🌐 Shell | 📅 2025-11-24 - Caches the output of a binary initialization command like `eval "$(hub alias -s)"`, to help lower shell startup time by loading from cache instead of re-running every new shell session.
* [sandboxd](https://github.com/benvan/sandboxd) ⭐ 245 | 🐛 2 | 🌐 Shell | 📅 2021-11-08 - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
* [opp](https://github.com/hchbaw/opp.zsh) ⭐ 234 | 🐛 5 | 🌐 Shell | 📅 2018-06-05 - Vim's text-objects-ish for ZSH.
* [zeno](https://github.com/yuki-yano/zeno.zsh) ⭐ 214 | 🐛 4 | 🌐 TypeScript | 📅 2026-02-07 - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [command-time](https://github.com/popstas/zsh-command-time) ⭐ 206 | 🐛 0 | 🌐 Shell | 📅 2025-07-26 - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived. Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) ⭐ 203 | 🐛 1 | 🌐 Shell | 📅 2025-12-17 - Adds tools for macOS.
* [anyframe](https://github.com/mollifier/anyframe) ⚠️ Archived - A `peco`/`percol`/`fzf` wrapper plugin for ZSH.
* [hist](https://github.com/marlonrichert/zsh-hist) ⭐ 193 | 🐛 2 | 🌐 Shell | 📅 2024-06-05 - Edit your history in ZSH, without ever leaving the command line.
* [shift-select](https://github.com/jirutka/zsh-shift-select) ⭐ 186 | 🐛 9 | 🌐 Shell | 📅 2022-07-28 - Emacs shift-select mode for ZSH - select text in the command line using Shift, as in many text editors, browsers and other GUI programs.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) ⭐ 176 | 🐛 6 | 🌐 Shell | 📅 2025-09-27 - Adds key bindings support for ZLE (ZSH Line Editor) clipboard operations for `vi` emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) ⭐ 174 | 🐛 0 | 🌐 Shell | 📅 2025-01-08 - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) ⭐ 756 | 🐛 8 | 🌐 Perl | 📅 2024-06-21 plugin.
* [revolver](https://github.com/molovo/revolver) ⭐ 161 | 🐛 7 | 🌐 Shell | 📅 2024-07-15 - A progress spinner for ZSH scripts.
* [directory-history](https://github.com/tymm/zsh-directory-history) ⭐ 160 | 🐛 5 | 🌐 Shell | 📅 2020-01-31 - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) ⭐ 159 | 🐛 2 | 🌐 Shell | 📅 2025-02-20 - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) ⭐ 155 | 🐛 0 | 🌐 Shell | 📅 2023-09-14 - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) ⭐ 154 | 🐛 4 | 🌐 Shell | 📅 2024-06-08 - ZSH syntax highlighting with dircolors in realtime.
* [256color](https://github.com/chrissicool/zsh-256color) ⭐ 151 | 🐛 0 | 🌐 Shell | 📅 2022-09-13 - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [lazyload](https://github.com/qoomon/zsh-lazyload) ⭐ 150 | 🐛 0 | 🌐 Shell | 📅 2025-08-06 - Lazy load commands and speed up start up time of ZSH.
* [functional](https://github.com/Tarrasch/zsh-functional) ⭐ 140 | 🐛 10 | 🌐 Perl | 📅 2022-06-17 - ZSH higher order functions.
* [macos-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) ⭐ 137 | 🐛 2 | 🌐 Shell | 📅 2025-12-22 - Configures proxy environment variables based on macOS's system preferences.
* [calc (arzzen)](https://github.com/arzzen/calc.plugin.zsh) ⭐ 136 | 🐛 1 | 🌐 Shell | 📅 2024-07-25 - A calculator for ZSH.
* [peco-history](https://github.com/jimeh/zsh-peco-history) ⭐ 127 | 🐛 2 | 🌐 Shell | 📅 2020-12-24 - Search shell history with Peco when pressing `ctrl+R`.
* [autoquoter](https://github.com/ianthehenry/zsh-autoquoter) ⭐ 126 | 🐛 1 | 🌐 Shell | 📅 2023-09-28 - A `zle` widget ("zsh plugin") that will automatically put quotes around arguments to certain commands.
* [kube-aliases](https://github.com/Dbz/kube-aliases) ⭐ 124 | 🐛 9 | 🌐 Shell | 📅 2023-12-09 - Adds functions and aliases to make working with `kubectl` more pleasant.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) ⭐ 124 | 🐛 9 | 🌐 Shell | 📅 2023-12-09 - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) ⭐ 121 | 🐛 6 | 🌐 Shell | 📅 2024-02-09 - Provides functionality similar to `vim`'s abbreviation expansion.
* [history-search-multi-word](https://github.com/zdharma-continuum/history-search-multi-word) ⭐ 119 | 🐛 6 | 🌐 Shell | 📅 2023-04-24 - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) ⭐ 116 | 🐛 0 | 🌐 Shell | 📅 2022-03-04 - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) ⭐ 115 | 🐛 2 | 🌐 Shell | 📅 2023-12-21 - Enables a number of aliases extending [exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24, the modern replacement for `ls`.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) ⭐ 115 | 🐛 19 | 🌐 Shell | 📅 2023-01-06 - Adds ability to open a folder in your current branch on GitHub.
* [ssh-connect](https://github.com/gko/ssh-connect) ⭐ 115 | 🐛 6 | 🌐 Shell | 📅 2022-06-16 - A simple `ssh` manager.
* [exa (zshell)](https://github.com/z-shell/zsh-exa) ⭐ 111 | 🐛 1 | 🌐 Shell | 📅 2026-01-01 - replace `ls` with [ogham/exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24.
* [eza (z-shell)](https://github.com/z-shell/zsh-eza) ⭐ 111 | 🐛 1 | 🌐 Shell | 📅 2026-01-01 - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2020-12-01 - Adds color for `mysql` tables.
* [exa-ls (zpm-zsh)](https://github.com/zpm-zsh/ls) ⭐ 104 | 🐛 2 | 🌐 Shell | 📅 2025-10-16 - Zsh plugin for ls.
* [ls (zpm-zsh)](https://github.com/zpm-zsh/ls) ⭐ 104 | 🐛 2 | 🌐 Shell | 📅 2025-10-16 - Colorizes the output of `ls`.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) ⭐ 101 | 🐛 5 | 🌐 Shell | 📅 2023-07-09 - Outputs a random hacker quote when you open a terminal.
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer) ⭐ 100 | 🐛 7 | 🌐 TypeScript | 📅 2025-06-03 - Enhances history search with more interaction and a multiline selection menu. Requires Node.js.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) ⭐ 97 | 🐛 2 | 🌐 Shell | 📅 2017-05-06 - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
* [zpy](https://github.com/AndydeCleyre/zpy) ⭐ 96 | 🐛 16 | 🌐 Shell | 📅 2026-02-02 - Manage Python environments, dependencies, and isolated app installations, with a ZSH frontend for [uv](https://github.com/astral-sh/uv) ⭐ 78,744 | 🐛 2,633 | 🌐 Rust | 📅 2026-02-06 or [pip-tools](https://github.com/jazzband/pip-tools) ⭐ 7,991 | 🐛 212 | 🌐 Python | 📅 2026-02-05.
* [almostontop](https://github.com/Valiev/almostontop) ⭐ 95 | 🐛 2 | 🌐 Shell | 📅 2019-09-17 - Clears previous command output every time before new command executed in shell. Inspired by the [alwaysontop](https://github.com/swirepe/alwaysontop) ⭐ 204 | 🐛 4 | 🌐 Shell | 📅 2016-09-22 plugin for `bash`.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) ⭐ 94 | 🐛 6 | 🌐 Shell | 📅 2024-02-12 - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) ⚠️ Archived - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [zsh-vi-man](https://github.com/TunaCuma/zsh-vi-man) ⭐ 93 | 🐛 2 | 🌐 Shell | 📅 2026-01-04 - Smart man page lookup for zsh vi mode. Press `Shift-K` on any command or option to instantly open its man page with smart detection for subcommands, option jumping, combined options, and pipe support.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) ⭐ 92 | 🐛 7 | 🌐 Shell | 📅 2024-04-30 - Automatically `ls` when cding to a new directory.
* [aws-vault](https://github.com/blimmer/zsh-aws-vault) ⭐ 92 | 🐛 3 | 🌐 Shell | 📅 2025-04-11 - Plugin for [aws-vault](https://github.com/99designs/aws-vault) ⭐ 8,953 | 🐛 0 | 🌐 Go | 📅 2025-12-30. Includes tab completions.
* [dwim](https://github.com/oknowton/zsh-dwim) ⭐ 91 | 🐛 0 | 🌐 Shell | 📅 2015-06-12 - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [pnpm (ntnyq)](https://github.com/ntnyq/omz-plugin-pnpm) ⭐ 87 | 🐛 0 | 🌐 Shell | 📅 2025-02-15 - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
* [omz-full-autoupdate](https://github.com/Pilaton/OhMyZsh-full-autoupdate) ⭐ 86 | 🐛 0 | 🌐 Shell | 📅 2026-01-05 - Automatically update [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugins and themes.
* [history](https://github.com/b4b4r07/zsh-history) ⚠️ Archived - Extend history so that it can be queried by SQL.
* [zcolors](https://github.com/marlonrichert/zcolors) ⭐ 83 | 🐛 2 | 🌐 Shell | 📅 2025-12-15 - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) ⭐ 22,216 | 🐛 205 | 🌐 Shell | 📅 2024-11-21.
* [git-aliases (peterhurford)](https://github.com/peterhurford/git-aliases.zsh) ⭐ 82 | 🐛 3 | 🌐 Shell | 📅 2019-12-05 - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [tinted-shell](https://github.com/tinted-theming/tinted-shell) ⭐ 82 | 🐛 2 | 🌐 Shell | 📅 2026-01-18 - Adds a script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [ansimotd](https://github.com/yuhonas/zsh-ansimotd) ⭐ 81 | 🐛 0 | 🌐 Shell | 📅 2023-05-03 - Adds old-school cool ANSI art when a login shell starts.
* [ask](https://github.com/Licheam/zsh-ask) ⭐ 78 | 🐛 1 | 🌐 Shell | 📅 2024-07-12 - Serves as a ChatGPT API frontend, enabling you to interact with ChatGPT directly from the ZSH shell using only `cURL` and `jq`.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) ⭐ 78 | 🐛 1 | 🌐 Shell | 📅 2021-03-25 - A ZSH plugin to `cd` to the `git` repository root directory.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) ⭐ 77 | 🐛 7 | 🌐 Shell | 📅 2024-02-12 - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
* [ai-cmd](https://github.com/kylesnowschwartz/zsh-ai-cmd) ⭐ 76 | 🐛 1 | 🌐 Shell | 📅 2026-01-25 - Natural language to shell commands with ghost text preview. Requires `curl`, [`jq`](https://stedolan.github.io/jq/) and an Anthropic API key.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) ⭐ 74 | 🐛 0 | 🌐 Shell | 📅 2021-01-24 - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [ranger-autojump](https://github.com/fdw/ranger-autojump) ⭐ 73 | 🐛 0 | 🌐 Python | 📅 2024-02-26 - Adds [autojump](https://github.com/wting/autojump) ⭐ 16,821 | 🐛 225 | 🌐 Python | 📅 2025-02-27 support to the [ranger](https://github.com/ranger/ranger) ⭐ 16,840 | 🐛 921 | 🌐 Python | 📅 2026-01-22 console file manager.
* [zhooks](https://github.com/agkozak/zhooks) ⭐ 73 | 🐛 0 | 🌐 Shell | 📅 2025-01-01 - Displays the contents of any ZSH hook arrays and the code of any hook functions that have been defined. Useful for debugging.
* [bat](https://github.com/fdellwing/zsh-bat) ⭐ 71 | 🐛 1 | 🌐 Shell | 📅 2024-11-12 - Adds some helper aliases for [bat](https://github.com/sharkdp/bat) ⭐ 57,011 | 🐛 344 | 🌐 Rust | 📅 2026-02-03 users.
* [hooks](https://github.com/willghatch/zsh-hooks) ⭐ 70 | 🐛 2 | 🌐 Shell | 📅 2021-12-01 - Add missing hooks - for plugins and personal use.
* [q (cal2195)](https://github.com/cal2195/q) ⭐ 70 | 🐛 5 | 🌐 Shell | 📅 2020-04-29 - Add `vim`-like macro registers to your ZSH shell.
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) ⭐ 70 | 🐛 0 | 🌐 Shell | 📅 2026-01-02 - Configures colorization with [grc](https://github.com/garabik/grc) ⭐ 2,127 | 🐛 93 | 🌐 Python | 📅 2024-08-18.
* [crash](https://github.com/molovo/crash) ⭐ 69 | 🐛 1 | 🌐 Shell | 📅 2017-03-28 - Adds proper error handling, exceptions and try/catch for ZSH.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) ⭐ 69 | 🐛 0 | 🌐 Shell | 📅 2024-01-28 - Aliases and functions for the lazy penetration tester.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) ⭐ 68 | 🐛 0 | 🌐 Shell | 📅 2019-04-02 - Colorize `man` pages.
* [zce](https://github.com/hchbaw/zce.zsh) ⭐ 67 | 🐛 0 | 🌐 Shell | 📅 2025-03-15 - Vim's EasyMotion / Emacs's ace-jump-mode for ZSH.
* [gunstage](https://github.com/LucasLarson/gunstage) ⭐ 66 | 🐛 3 | 🌐 Shell | 📅 2026-01-13 - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) ⚠️ Archived - A ZSH plugin to open pull requests from command line.
* [hints](https://github.com/joepvd/zsh-hints) ⭐ 64 | 🐛 0 | 🌐 Shell | 📅 2021-10-12 - Display glob and parameter flags and other non completable info right under your editing buffer.
* [iterm2-shell-integration](https://github.com/gnachman/iterm2-shell-integration) ⭐ 64 | 🐛 5 | 🌐 Shell | 📅 2026-02-06 - Shell integration and utilities for iTerm2.
* [timewarrior (svenXY)](https://github.com/svenXY/timewarrior) ⭐ 62 | 🐛 1 | 🌐 Shell | 📅 2025-06-24 - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) ⭐ 59 | 🐛 0 | 🌐 Shell | 📅 2022-04-08 - Automatically list directories with `colorls`.
* [czhttpd](https://github.com/jsks/czhttpd) ⭐ 59 | 🐛 0 | 🌐 Shell | 📅 2025-10-06 - A simple http server written in 99.9% pure ZSH.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) ⭐ 59 | 🐛 1 | 🌐 Shell | 📅 2020-04-13 - Integrates [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and [fasd](https://github.com/clvv/fasd) ⚠️ Archived --- tab completion of `z` with `fzf`'s fuzzy search!
* [fzy](https://github.com/aperezdc/zsh-fzy) ⭐ 59 | 🐛 5 | 🌐 Shell | 📅 2021-01-15 - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) ⭐ 3,193 | 🐛 55 | 🌐 C | 📅 2025-07-29 for certain fuzzy matching operations.
* [fzf-dir-navigator](https://github.com/KulkarniKaustubh/fzf-dir-navigator) ⭐ 58 | 🐛 3 | 🌐 Shell | 📅 2025-08-30 - This is a cool and user-friendly directory navigation plugin for ZSH using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 that allows the user to switch to any directory from anywhere and to anywhere. It also maintains a history of recently visited directories. Additionally, you can use hotkeys to move back and forth between directories in the shell session.
* [llm-suggestions](https://github.com/stefanheule/zsh-llm-suggestions) ⭐ 58 | 🐛 4 | 🌐 Shell | 📅 2024-05-29 - Type something in English at the prompt, hit a definable key, and it uses LLM to generate a command line for you.
* [titles](https://github.com/jreese/zsh-titles) ⭐ 58 | 🐛 1 | 🌐 Shell | 📅 2023-02-10 - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) ⭐ 56 | 🐛 1 | 🌐 Shell | 📅 2024-03-28 - Enhanced colors for ZSH.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) ⭐ 54 | 🐛 0 | 🌐 Python | 📅 2023-02-06 - A port of [vim-easymotion](https://github.com/easymotion/vim-easymotion) ⭐ 7,717 | 🐛 129 | 🌐 Vim script | 📅 2024-02-05 for ZSH.
* [gitignore (voronkovich)](https://github.com/voronkovich/gitignore.plugin.zsh) ⭐ 54 | 🐛 0 | 🌐 Shell | 📅 2024-04-10 - Plugin for creating `.gitignore` files.
* [git](https://github.com/davidde/git) ⭐ 52 | 🐛 1 | 🌐 PowerShell | 📅 2026-02-02 - Replacement for the stock [oh-my-zsh](https://ohmyz.sh/) `git` plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) ⭐ 52 | 🐛 3 | 🌐 Shell | 📅 2019-08-28 - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
* [pyenv (mattberther)](https://github.com/mattberther/zsh-pyenv) ⭐ 52 | 🐛 1 | 🌐 Shell | 📅 2021-06-24 - Inspired by **zsh-rbenv**. Installs, updates or loads `pyenv`, and adds extra functionality.
* [tab-title (trystan2k)](https://github.com/trystan2k/zsh-tab-title) ⭐ 52 | 🐛 0 | 🌐 Shell | 📅 2026-02-02 - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) ⭐ 51 | 🐛 0 | 🌐 Shell | 📅 2016-02-23 - Show `docker` container status in your prompt.
* [apparix](https://github.com/micans/apparix) ⭐ 50 | 🐛 1 | 🌐 Shell | 📅 2025-09-11 - Command line directory bookmarks with jumping to bookmarks, subdirectory tab completion, distant listing etc.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) ⭐ 50 | 🐛 5 | 🌐 Shell | 📅 2024-09-11 - A zle tweak for emulating `...'==`../..' etc.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) ⭐ 50 | 🐛 0 | 🌐 Shell | 📅 2023-02-26 - Lazy load [pyenv](https://github.com/pyenv/pyenv) ⭐ 44,223 | 🐛 56 | 🌐 Shell | 📅 2026-02-04. The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
* [zabb](https://github.com/Mellbourn/zabb) ⭐ 49 | 🐛 0 | 🌐 Shell | 📅 2023-01-12 - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) ⭐ 33,206 | 🐛 151 | 🌐 Rust | 📅 2026-02-02 to unambiguously jump to that directory.
* [zlong\_alert](https://github.com/kevinywlui/zlong_alert.zsh) ⭐ 49 | 🐛 7 | 🌐 Shell | 📅 2024-02-11 - Uses `notify-send` and rings a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) ⭐ 48 | 🐛 10 | 🌐 Shell | 📅 2024-07-30 - Automatically changes iTerm 2 tab color based on the current working directory.
* [docker-run](https://github.com/rawkode/zsh-docker-run) ⚠️ Archived - Go back to running your commands "naturally", we'll handle the container.
* [listbox](https://github.com/gko/listbox) ⭐ 47 | 🐛 4 | 🌐 Shell | 📅 2022-06-15 - Listbox element for shell.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) ⭐ 46 | 🐛 6 | 🌐 Shell | 📅 2024-12-12 - Extends ZLE `vi` commands to remotely access named registers of the `vim` and `nvim` editors, and system selection and clipboard.
* [git-sync](https://github.com/caarlos0-graveyard/zsh-git-sync) ⚠️ Archived - A ZSH plugin to sync `git` repositories and clean them up.
* [lumberjack](https://github.com/molovo/lumberjack) ⭐ 46 | 🐛 1 | 🌐 Shell | 📅 2016-09-14 - Lumberjack is a logging interface for shell scripts.
* [fastcache](https://github.com/QuarticCat/zsh-fastcache) ⭐ 45 | 🐛 1 | 🌐 Shell | 📅 2025-01-20 - Caches command output to improve shell startup time.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) ⭐ 45 | 🐛 1 | 🌐 Shell | 📅 2023-02-24 - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [smartcache](https://github.com/QuarticCat/zsh-smartcache) ⭐ 45 | 🐛 1 | 🌐 Shell | 📅 2025-01-20 - Caches command output to speed up shell startup time.
* [clipboard](https://github.com/zpm-zsh/clipboard) ⭐ 44 | 🐛 0 | 🌐 Shell | 📅 2025-09-09 - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) ⭐ 44 | 🐛 1 | 🌐 Shell | 📅 2024-01-16 - Makes it easier to colorize text from the CLI. `red foo` just works.
* [ollama](https://github.com/plutowang/zsh-ollama-command) ⭐ 44 | 🐛 3 | 🌐 Shell | 📅 2024-07-23 - Integrates the OLLAMA AI model with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 to provide intelligent command suggestions based on user input requirements.
* [zabrze](https://github.com/Ryooooooga/zabrze) ⭐ 44 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - A ZSH abbreviation expansion plugin.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) ⭐ 43 | 🐛 0 | 🌐 Shell | 📅 2020-04-18 - Adds an up command to `cd` multiple levels up.
* [snippets](https://github.com/willghatch/zsh-snippets) ⭐ 41 | 🐛 3 | 🌐 Shell | 📅 2018-03-09 - Command line snippet expansion.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) ⭐ 41 | 🐛 1 | 🌐 Shell | 📅 2025-10-24 - Edouard Lopez's [Yeoman](http://yeoman.io/) plugin for [oh-my-zsh](https://ohmyz.sh/), compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [bash](https://github.com/chrissicool/zsh-bash) ⭐ 40 | 🐛 1 | 🌐 Shell | 📅 2014-10-30 - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) ⭐ 40 | 🐛 2 | 🌐 Shell | 📅 2021-06-15 - A plugin which displays reminders above every prompt.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) ⭐ 40 | 🐛 0 | 🌐 Shell | 📅 2025-06-30 - Add new motions and text objects including quoted/bracketed text and commands.
* [ai-commands](https://github.com/muePatrick/zsh-ai-commands) ⭐ 39 | 🐛 1 | 🌐 Shell | 📅 2024-06-19 - Asks GPT (gpt-4-turbo-preview) for CLI commands that achieve the described target action.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) ⭐ 39 | 🐛 1 | 🌐 Shell | 📅 2024-09-13 - Adds commands for [jHipster](https://www.jhipster.tech/).
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) ⭐ 39 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 - Adds shortcuts for `sail` commands.
* [pip-app](https://github.com/sharat87/pip-app) ⭐ 39 | 🐛 3 | 🌐 Shell | 📅 2021-09-25 - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2020-01-17 - Maps exit status codes to human readable strings.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) ⭐ 37 | 🐛 1 | 🌐 Shell | 📅 2025-07-29 - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) ⭐ 37 | 🐛 0 | 🌐 Shell | 📅 2021-02-24 - Outputs a random Linus Torvalds rant when opening a terminal.
* [zsh-expand](https://github.com/MenkeTechnologies/zsh-expand) ⭐ 37 | 🐛 1 | 🌐 Shell | 📅 2025-07-29 - Expands regular aliases, global aliases and incorrect spellings and phrases with the spacebar key. Native expansions such as globs, command/process substitution, `=command expansion`, history expansion and `$parameters` are also expanded by default but can be turned off.
* [diractions](https://github.com/AdrieanKhisbe/diractions) ⭐ 36 | 🐛 3 | 🌐 Shell | 📅 2025-10-28 - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [git-prune (diazod)](https://github.com/diazod/git-prune) ⭐ 36 | 🐛 0 | 🌐 Shell | 📅 2025-10-16 - Allows you to delete all branches that are already merged in your local `git` repository and/or that were merged in your remote origin `git` repository.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) ⭐ 36 | 🐛 0 | 🌐 Shell | 📅 2025-10-16 - Plugin that simplifies deleting merged branches in a `git` repository.
* [window-title](https://github.com/olets/zsh-window-title) ⭐ 36 | 🐛 1 | 🌐 Shell | 📅 2024-05-24 - Adds informative tiles to your terminal windows.
* [antidote-use-omz](https://github.com/getantidote/use-omz) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2025-05-20 - Make using [oh-my-zsh](https://ohmyz.sh/) with [antidote](https://getantidote.github.io/) seamless.
* [cmdtime](https://github.com/tom-auger/cmdtime) ⭐ 35 | 🐛 1 | 🌐 Shell | 📅 2021-06-08 - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin.
* [colorize](https://github.com/zpm-zsh/colorize) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2023-12-21 - Colorize the output of various programs.
* [ez-compinit](https://github.com/mattmc3/ez-compinit) ⭐ 35 | 🐛 2 | 🌐 Shell | 📅 2026-01-11 - Wraps `compinit`, queueing up calls to `compdef`, and hooking the real `compinit` call to an event that runs at the end of your `.zshrc`. That way you get all the benefits of calling `compinit` early without any of the downsides.
* [git-worktree (alexiszamanidis)](https://github.com/alexiszamanidis/zsh-git-worktree) ⭐ 35 | 🐛 2 | 🌐 Shell | 📅 2023-01-25 - Wraps some `git worktree` operations for simplicity and productivity. Includes [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 tooling.
* [nlsh](https://github.com/PsychArch/nlsh) ⭐ 35 | 🐛 1 | 🌐 Shell | 📅 2026-02-06 - Allows you to interact with your shell using natural language. Supports multiple LLM providers (OpenAI API compatible). Includes support for X.ai's Grok.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) ⭐ 35 | 🐛 0 | 🌐 Shell | 📅 2016-09-30 - A fork of the virtualenv plugin from upstream [oh-my-zsh](https://ohmyz.sh/). Adds support for customizing the virtualenv prompt in [oh-my-zsh](https://ohmyz.sh) themes.
* [aish](https://github.com/chr15m/aish) ⭐ 34 | 🐛 0 | 🌐 Shell | 📅 2025-10-11 - Instant shell script solutions from OpenAI right in your prompt.
* [careful\_rm](https://github.com/MikeDacre/careful_rm) ⭐ 34 | 🐛 9 | 🌐 Python | 📅 2019-05-27 - A wrapper for `rm` that adds trash/recycling and useful warnings.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) ⭐ 34 | 🐛 2 | 🌐 Shell | 📅 2019-12-20 - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) ⭐ 34 | 🐛 5 | 🌐 Shell | 📅 2021-10-19 - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [lux](https://github.com/pndurette/zsh-lux) ⭐ 34 | 🐛 0 | 🌐 Shell | 📅 2024-01-21 - ZSH plugin to toggle the light & dark modes of macOS, iTerm 2, Visual Studio Code and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes a `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) ⭐ 34 | 🐛 2 | 🌐 Shell | 📅 2016-05-06 - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) ⭐ 33 | 🐛 1 | 🌐 Shell | 📅 2020-05-15 - Copy and paste files in your terminal like you would in a GUI.
* [send](https://github.com/robertzk/send.zsh) ⭐ 33 | 🐛 3 | 🌐 Shell | 📅 2026-01-21 - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sudo (hcgraf)](https://github.com/hcgraf/zsh-sudo) ⭐ 33 | 🐛 2 | 🌐 Shell | 📅 2022-06-09 - The `sudo` plugin from [oh-my-zsh](https://ohmyz.sh/), extracted to a standalone. Toggles `sudo` before the current/previous command by pressing \*ESC-ESC- in emacs-mode or vi-command mode.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) ⭐ 33 | 🐛 1 | 🌐 Shell | 📅 2018-03-16 - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
* [thefuck](https://github.com/laggardkernel/thefuck) ⭐ 32 | 🐛 1 | 🌐 Shell | 📅 2019-05-26 - Loads [thefuck](https://github.com/nvbn/thefuck) ⭐ 95,414 | 🐛 404 | 🌐 Python | 📅 2024-07-19 (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2026-01-25 - An [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 interface for tmux session creation and management for all your projects.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2025-04-07 - Add extra `vi`-like functionality.
* [zman](https://github.com/mattmc3/zman) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2026-01-09 - Use [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 to quickly browse ZSH manuals.
* [diff-so-fancy](https://github.com/z-shell/zsh-diff-so-fancy) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2025-12-15 - Automatically installs [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) ⭐ 17,929 | 🐛 33 | 🌐 Perl | 📅 2025-07-15 and enables its use in ZSH and `git`.
* [dirrc](https://github.com/gmatheu/shell-plugins) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2025-04-03 - Executes `.dirc` when present in a directory you `cd` into.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) ⭐ 30 | 🐛 0 | 🌐 Shell | 📅 2023-01-27 - A collection of `docker` helper scripts.
* [explain-shell (gmatheu)](https://github.com/gmatheu/shell-plugins) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2025-04-03 - Opens commands on [explainshell.com](https://explainshell.com).
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) ⭐ 30 | 🐛 1 | 🌐 Shell | 📅 2021-08-31 - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
* [no-ps2](https://github.com/romkatv/zsh-no-ps2) ⭐ 30 | 🐛 0 | 🌐 Shell | 📅 2024-02-22 - When this plugin is used, Enter inserts a newline if the typed command is incomplete. No PS2!
* [profile-secrets](https://github.com/gmatheu/shell-plugins) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2025-04-03 - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) ⭐ 30 | 🐛 1 | 🌐 Shell | 📅 2023-09-05 - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [vimto](https://github.com/laurenkt/zsh-vimto) ⭐ 30 | 🐛 3 | 🌐 Shell | 📅 2020-05-16 - Improved ZSH `vi` mode (bindkey -v) plugin.
* [activate-py-environment](https://github.com/se-jaeger/zsh-activate-py-environment) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2024-01-27 - Automagically detects and activates your python environments (`poetry`, `virtualenv` and `conda`) while traversing directories.
* [grep2awk](https://github.com/joepvd/grep2awk) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2018-09-23 - ZLE widget to transform `grep` command into `awk` command.
* [uv-env](https://github.com/matthiasha/zsh-uv-env) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2025-10-20 - Automatically uses [uv](https://github.com/astral-sh/uv) ⭐ 78,744 | 🐛 2,633 | 🌐 Rust | 📅 2026-02-06 to activate a virtual environment based on the current directory.
* [communism](https://github.com/victoria-riley-barnett/Communism/) ⭐ 28 | 🐛 0 | 🌐 Shell | 📅 2023-03-04 - Displays a Marx quote of the day.
* [nvim-appname](https://github.com/mehalter/zsh-nvim-appname) ⭐ 28 | 🐛 0 | 🌐 Shell | 📅 2024-04-17 - Maintain multiple Neovim configurations with `NVIM_APPNAME` with full tab completion of available flags, available neovim applications, and neovim arguments/flags. Requires neovim v0.9+
* [tipz](https://github.com/molovo/tipz) ⭐ 28 | 🐛 0 | 🌐 Shell | 📅 2018-05-03 - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips) ⭐ 809 | 🐛 18 | 🌐 Python | 📅 2023-06-08.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) ⭐ 27 | 🐛 2 | 🌐 Shell | 📅 2018-08-09 - [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18 doesn't do automatic updates like [oh-my-zsh](https://ohmyz.sh/). This plugin adds auto updating for `antigen`, both of `antigen` and the bundles loaded in your configuration.
* [bitwarden (game4move78)](https://github.com/Game4Move78/zsh-bitwarden) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2025-03-31 - Adds functions to manage [bitwarden](https://bitwarden.com/) sessions.
* [crystal](https://github.com/veelenga/crystal-zsh) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2020-04-20 - A plugin for [Crystal](https://github.com/crystal-lang/crystal) ⭐ 20,154 | 🐛 1,998 | 🌐 Crystal | 📅 2026-02-05.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2019-11-25 - Keep your dotfiles in sync across multiple machines using `git`.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) ⭐ 27 | 🐛 1 | 🌐 Shell | 📅 2022-08-23 - Adds `m2` function to run magento binary, adds tab completions.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2019-06-07 - Turn your terminal into the matrix.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) ⭐ 27 | 🐛 1 | 🌐 Shell | 📅 2024-11-25 - Add safe-`rm` functionality so that `rm` will put files in your OS' trash instead of permanently deleting them.
* [solarized-man](https://github.com/zlsun/solarized-man) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2019-07-01 - A modified version of [Oh-My-ZSH](https://ohmyz.sh/)'s plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 theme in the terminal.
* [command-not-found (tarrasch)](https://github.com/Tarrasch/zsh-command-not-found) ⭐ 26 | 🐛 0 | 🌐 Shell | 📅 2021-09-05 - A mirror of the [oh-my-zsh](https://ohmyz.sh) [command-not-found](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/command-not-found) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin so you don't have to include all of oh-my-zsh.
* [zfzf](https://github.com/b0o/zfzf) ⚠️ Archived - A [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [cdc](https://github.com/evanthegrayt/cdc) ⭐ 25 | 🐛 14 | 🌐 Shell | 📅 2026-02-01 - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
* [history-sync (vitobotta)](https://github.com/vitobotta/zsh-history-sync/) ⭐ 25 | 🐛 2 | 🌐 Shell | 📅 2023-11-12 - Syncs your ZSH history across computers using a `git` private repository. Uses `openssl` to encrypt the history.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) ⭐ 25 | 🐛 1 | 🌐 Shell | 📅 2024-05-16 - Keeps passwords from entering your command line history.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) ⭐ 25 | 🐛 4 | 🌐 Shell | 📅 2023-12-21 - Automatically sets the title of windows/panes as the current foreground command.
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) ⭐ 25 | 🐛 1 | 🌐 Shell | 📅 2018-07-16 - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2020-08-05 - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of [oh-my-zsh](https://ohmyz.sh).
* [fzf-tools](https://github.com/happycod3r/fzf-tools) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2023-11-23 - Provides functions, aliases and key-bindings for commands such as `alias`, `find`, `ls`, `man`, `printenv` that are designed to enhance your command-line workflow by making them to default to filtering through [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05, allowing you to quickly find files, search & run commands from history, run scripts of many supported types, browse `git` commits, and more.
* [macos (zshzoo)](https://github.com/zshzoo/macos) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2024-10-07 - ZSH goodies for macOS users.
* [ripz](https://github.com/jedahan/ripz) ⚠️ Archived - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 59,624 | 🐛 113 | 🌐 Rust | 📅 2025-12-17.
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2023-02-28 - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
* [vanilli.sh](https://github.com/yous/vanilli.sh) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2023-04-19 - A lightweight start point of shell configuration.
* [gpt](https://github.com/antonjs/zsh-gpt) ⭐ 23 | 🐛 2 | 🌐 Shell | 📅 2023-05-27 - Enable querying ChatGPT from the command line.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2024-05-22 - Print the time it takes for the shell to start up.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2023-11-23 - Add convenience aliases for [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
* [undollar](https://github.com/zpm-zsh/undollar) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2019-07-22 - Strips the dollar sign from the beginning of the terminal prompt.
* [compe](https://github.com/tamago324/compe-zsh) ⚠️ Archived - Add completion for [nvim-compe](https://github.com/hrsh7th/nvim-compe) ⚠️ Archived.
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) ⭐ 22 | 🐛 0 | 🌐 Shell | 📅 2020-05-19 - Cycle through the directory stack.
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) ⭐ 22 | 🐛 1 | 🌐 Shell | 📅 2024-03-10 - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and (optionally) [bat](https://github.com/sharkdp/bat) ⭐ 57,011 | 🐛 344 | 🌐 Rust | 📅 2026-02-03 and [fd](https://github.com/sharkdp/fd) ⭐ 41,492 | 🐛 160 | 🌐 Rust | 📅 2026-02-03. Falls back to `find` and `cat`. Searches in the local tree of subdirectories for files.
* [gitio (denysdovhan)](https://github.com/denysdovhan/gitio-zsh) ⚠️ Archived - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [proxy-plugin (escalate)](https://github.com/escalate/oh-my-zsh-proxy-plugin) ⭐ 22 | 🐛 0 | 🌐 Shell | 📅 2025-05-22 - Quickly enable and disable proxy shell environment settings.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) ⭐ 21 | 🐛 1 | 🌐 Shell | 📅 2024-05-14 - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2024-05-24. Supports specifying `mfa_device` in profile.
* [branch-manager](https://github.com/elstgav/branch-manager) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2025-08-29 - A plugin for managing `git` branches.
* [cd-ls](https://github.com/zshzoo/cd-ls) ⭐ 21 | 🐛 1 | 🌐 Shell | 📅 2024-05-10 - Automatically `ls` after `cd`.
* [dropbox](https://github.com/zpm-zsh/dropbox) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2022-01-06 - A [dropbox](https://www.dropbox.com/) plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2020-11-03 - Provides a quick notes editing experience in ZSH.
* [saneopt](https://github.com/willghatch/zsh-saneopt) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2015-09-10 - Sane defaults for ZSH options, in the spirit of [vim-sensible](https://github.com/tpope/vim-sensible) ⭐ 5,279 | 🐛 8 | 🌐 Vim Script | 📅 2024-06-08.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2016-08-07 - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2014-08-19 - View `vim` plugin manuals (help) like `man` in ZSH.
* [alias-finder](https://github.com/akash329d/zsh-alias-finder) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2022-08-04 - Displays an alias when you use a command you have aliased previously. Helpful for remembering aliases you have defined in the past. Written as a pure ZSH script for speed.
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2025-08-14 - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2019-03-20 - Add [Can I Use](https://caniuse.com) support to ZSH.
* [claude-code-shell](https://github.com/ArielTM/zsh-claude-code-shell) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 - Translates natural language comments into shell commands using [Claude Code](https://claude.ai/claude-code).
* [exa (zap-zsh)](https://github.com/zap-zsh/exa) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2025-09-17 - Overrides common commands to use [ogham/exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24 instead.
* [help](https://github.com/Freed-Wu/zsh-help) ⭐ 20 | 🐛 2 | 🌐 Shell | 📅 2026-01-19 - Colorizes the output of commands run with `--help`.
* [osx](https://github.com/mwilliammyers/plugin-osx) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2015-12-31 - Add some common macOS related aliases and functions.
* [print-alias](https://github.com/brymck/print-alias) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2020-11-05 - Prints commands with aliases expanded whenever you use an alias at the command line.
* [project (gko)](https://github.com/gko/project) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2024-06-12 - Create node/python/ruby projects both locally and on GitHub (private or public repository).
* [recall](https://github.com/mango-tree/zsh-recall) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2020-07-04 - Makes using command history easier.
* [tmux (zpm-zsh)](https://github.com/zpm-zsh/tmux) ⭐ 20 | 🐛 3 | 🌐 Shell | 📅 2023-11-29 - Plugin for [tmux](https://tmux.github.io).
* [alehouse](https://github.com/sticklerm3/alehouse) ⭐ 19 | 🐛 1 | 🌐 Shell | 📅 2024-01-11 - Contains short aliases for [brew](https://brew.sh) commands, inspired by `betterbrew`.
* [cdr](https://github.com/willghatch/zsh-cdr) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2015-09-10 - Easy setup of `cdr` for ZSH.
* [mise](https://github.com/wintermi/zsh-mise) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Plugin for [mise](https://mise.jdx.dev/) (formerly called rtx) a fast polyglot version manager, replacing tools like `nvm`, `nodenv`, `rbenv`, `rvm`, `chruby`, `pyenv`, etc.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) ⚠️ Archived - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
* [smart-cd](https://github.com/dbkaplun/smart-cd) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2015-05-26 - Runs `ls` and `git status` after chpwd.
* [tsm](https://github.com/RobertAudi/tsm) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2023-04-16 - Adds a [tmux](https://tmux.github.io) Session Manager.
* [zbrowse](https://github.com/zdharma-continuum/zbrowse) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2023-05-14 - When doing shell work, it is often the case that `echo $variable` is invoked multiple times, to check the result of a loop, etc. With ZBrowse, you just need to press `Ctrl-B`, which invokes the ZBrowse – Zshell variable browser.
* [autodotenv](https://github.com/nocttuam/autodotenv) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-04-25 - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
* [direnv](https://github.com/ptavares/zsh-direnv) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2022-07-17 - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git) ⭐ 14,628 | 🐛 418 | 🌐 Go | 📅 2026-01-26. Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) ⭐ 52 | 🐛 1 | 🌐 Shell | 📅 2021-06-24.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-06-03 - Adds aliases for [exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24, a modern replacement for `ls`.
* [igit](https://github.com/ytakahashi/igit) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-03-17 - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [magic-enter](https://github.com/zshzoo/magic-enter) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2023-06-21 - Make your enter key magical by binding a ZSH command to it.
* [nvm-auto-use (tomsquest)](https://github.com/tomsquest/nvm-auto-use.zsh) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2023-07-11 - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2019-08-13 - Automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) ⭐ 18 | 🐛 1 | 🌐 Shell | 📅 2016-01-21 - Plugin for [Visual Studio Code](https://code.visualstudio.com/download), a text editor for macOS, Windows, and Linux.
* [watch](https://github.com/enrico9034/zsh-watch-plugin) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-03-19 - Easily prefix your current or previous commands with watch by pressing `CTRL + W`.
* [zinsults](https://github.com/ahmubashshir/zinsults) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2024-06-10 - Prints insults if a command fails.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2016-04-18 - Lets you open any commit in your browser from the command line.
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2016-12-22 - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Colorizes `man` output.
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) ⭐ 17 | 🐛 4 | 🌐 Shell | 📅 2020-11-19 - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm) ⭐ 1,001 | 🐛 52 | 🌐 Go | 📅 2022-01-31.
* [ipip](https://github.com/SukkaW/zsh-ipip) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2019-05-19 - Plugin for [IPIP](https://en.ipip.net).
* [laravel (crazybooot)](https://github.com/crazybooot/laravel-zsh-plugin) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2019-03-14 - Add shortcuts for [Laravel](https://laravel.com/) 5, 5.1, 5.2 & 5.3.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2022-10-01 - Adds some functions for dealing with `mysql`.
* [ros2-env](https://github.com/Butakus/ros2-env) ⭐ 17 | 🐛 2 | 🌐 Shell | 📅 2025-10-16 - Manage [ROS 2](https://github.com/ros2) environment and workspaces.
* [yazi-zoxide](https://github.com/fdw/yazi-zoxide-zsh) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2025-08-31 - This plugin for [zsh](https://www.zsh.org) adds just one shortcut, but unfolds the magic of both [Zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 33,206 | 🐛 151 | 🌐 Rust | 📅 2026-02-02 and [yazi](https://github.com/sxyazi/yazi/) ⭐ 32,282 | 🐛 70 | 🌐 Rust | 📅 2026-02-06. Without arguments, `y` just opens yazi. If you supply an argument that is a directory, `yazi` is opened in that directory. But if you supply anything else as an argument, `zoxide` is called with the argument and `yazi` is opened there.
* [zui](https://github.com/zdharma-continuum/zui) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2023-04-16 - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.)
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) ⭐ 16 | 🐛 1 | 🌐 Ruby | 📅 2017-07-29 - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [cdbk](https://github.com/MikeDacre/cdbk) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2018-03-25 - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2017-06-23 - Adds numerous ASCII art emojis to your environment in convenient variables.
* [fnm (dominik-schwabe)](https://github.com/dominik-schwabe/zsh-fnm) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2025-10-13 - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) ⭐ 23,769 | 🐛 364 | 🌐 Rust | 📅 2026-02-05 if it is missing.
* [printc](https://github.com/philFernandez/printc) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2020-10-29 - Allows you to print in any color in the RGB space via a simple `printc` call.
* [zero](https://github.com/arlimus/zero.zsh) ⭐ 16 | 🐛 2 | 🌐 Shell | 📅 2024-07-20 - Zero is both a plugin and a theme. See the GitHub page for installation details. Includes `git` and `hg` status decorators.
* [zinit-console](https://github.com/z-shell/zinit-console) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2022-02-26 - A semigraphical (curses) consolette for the [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 plugin manager.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2024-04-30 - Display reminders when `cd`-ing into specified directories.
* [conda (themysciradata)](https://github.com/ThemysciraData/conda.plugin.zsh) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2022-02-03 - Adds function to provide a prompt segment for [conda](https://conda.io) and aliases for some base functions.
* [fast-alias-tips](https://github.com/decayofmind/zsh-fast-alias-tips) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2025-01-04 - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips) ⭐ 809 | 🐛 18 | 🌐 Python | 📅 2023-06-08. Active fork of [sei40kr/zsh-fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips) ⭐ 59 | 🐛 16 | 🌐 Rust | 📅 2025-12-07.
* [figures](https://github.com/zpm-zsh/figures) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2019-11-08 - Unicode symbols for ZSH.
* [fzf-tab-widgets](https://github.com/tom-power/fzf-tab-widgets) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2025-11-01 - Adds widgets for [fzf-tab](https://github.com/Aloxaf/fzf-tab) ⭐ 4,497 | 🐛 93 | 🌐 Shell | 📅 2026-02-03.
* [git-to-jj](https://github.com/elithrar/zsh-git-to-jj) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2026-01-01 - Helps you progressively learn [Jujutsu](https://github.com/jj-vcs/jj) ⭐ 25,541 | 🐛 1,003 | 🌐 Rust | 📅 2026-02-07 (aka `jj`) porcelain as you use `git` commands.
* [git-worktrees](https://github.com/egyptianbman/zsh-git-worktrees) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2023-02-05 - Makes `git` worktrees more functional. Includes tab completions.
* [lsd (z-shell)](https://github.com/z-shell/zsh-lsd) ⭐ 15 | 🐛 3 | 🌐 Shell | 📅 2025-11-24 - Replaces `ls` with [lsd](https://github.com/Peltoche/lsd) ⭐ 15,413 | 🐛 186 | 🌐 Rust | 📅 2025-12-09.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2020-04-24 -  Generates file from template.
* [select](https://github.com/z-shell/zsh-select) ⭐ 15 | 🐛 3 | 🌐 Shell | 📅 2025-09-05 - Multi-term searched selection list with approximate matching and uniq mode.
* [sudo (none9632)](https://github.com/none9632/zsh-sudo/) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2023-10-12 - Adds `sudo` as a prefix to the current command by typing `ESC`-`ESC`.
* [viexchange](https://github.com/okapia/zsh-viexchange) ⭐ 15 | 🐛 1 | 🌐 Shell | 📅 2020-06-24 - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [zsh-select](https://github.com/z-shell/zsh-select) ⭐ 15 | 🐛 3 | 🌐 Shell | 📅 2025-09-05 - Displays a selection list. It is similar to `selecta`, but uses the curses library to do display, and when compared to [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05, the main difference is approximate matching instead of fuzzy matching.
* [ansible](https://github.com/sparsick/ansible-zsh) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2018-10-19 - A plugin for [Ansible](https://www.ansible.com/).
* [asdf (kiurchv)](https://github.com/kiurchv/asdf.plugin.zsh) ⭐ 14 | 🐛 2 | 🌐 Shell | 📅 2020-10-29 - Integration and completions for [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,040 | 🐛 176 | 🌐 Go | 📅 2026-02-01, the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [bitwarden (kalsowerus)](https://github.com/kalsowerus/zsh-bitwarden) ⭐ 14 | 🐛 1 | 🌐 Shell | 📅 2022-06-08 - Opens a [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 widget containing your [Bitwarden](https://bitwarden.com/) vault items. Upon selecting an item either the username or password will be either written into the shell or copied into the clipboard. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05, `jq` and `bitwarden`.
* [cheatsheet](https://github.com/0b10/cheatsheet) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2019-11-21 - Plugin to easily view, create, and edit cheatsheets.
* [command-execution-timer](https://github.com/olets/command-execution-timer) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2025-10-16 - Displays the time an interactive shell command takes to execute.
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) ⭐ 14 | 🐛 1 | 🌐 Shell | 📅 2017-03-10 - Expand specific aliases with space.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) ⚠️ Archived - Easily add the upstream remote to your `git` fork.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2017-11-01 - [Metasploit](https://www.metasploit.com/) handler plugin for starting handlers easily.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2015-12-05 - This plugin adds some commands for maintaining various server programs on a macOS install.
* [quiet-accept-zle](https://github.com/AdrieanKhisbe/zsh-quiet-accept-line) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2025-11-03 - Enables you to run a typed ZSH command without triggering new prompt, history entry, or having output being outputed.
* [rose-pine-man](https://github.com/const-void/rose-pine-man) ⭐ 14 | 🐛 1 | 🌐 Shell | 📅 2024-10-13 - Colorizes `man` pages.
* [selector](https://github.com/joknarf/selector) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Make it easy to create selection menus.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2017-11-01 - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [terminal-app](https://github.com/the8/terminal-app.zsh) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2021-01-26 - A plugin for integrating with the new macOS El Capitan Terminal.app features.
* [zload](https://github.com/mollifier/zload) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2015-03-24 - Hot Reload for ZSH functions. Enables rapid development.
* [alias-maker](https://github.com/MefitHp/alias-maker) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2023-05-03 - Allows you to easily create and manage aliases from the command line.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2018-09-12 - Record complex commands and comment on them.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2020-08-12 - Adds extra `git` commands to make some common `git` usages more efficient.
* [hipchat](https://github.com/robertzk/hipchat.zsh) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2015-10-06 - Send hipchat messages from the shell.
* [hitokoto](https://github.com/derry96/hitokoto) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2023-07-05 - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [jj](https://github.com/rkh/zsh-jj) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2025-03-31 - Add support for [jujitsu](https://github.com/jj-vcs/jj) ⭐ 25,541 | 🐛 1,003 | 🌐 Rust | 📅 2026-02-07 VCS.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2019-10-16 - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [navigation-tools](https://github.com/zdharma-continuum/zsh-navigation-tools) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2023-04-15 - Adds `htop`-like kill, directory bookmarks browser, a multi-word incremental history searcher and more.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2020-07-02 - Inspired by [terminal\_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) ⭐ 13 | 🐛 8 | 🌐 Makefile | 📅 2026-01-13 - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
* [plugin](https://github.com/darrenbutcher/plugin) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2021-05-27 - Creates custom [oh-my-zsh](https://ohmyz.sh) plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins may need editing to work with other frameworks.
* [safe-paste](https://github.com/oz/safe-paste) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2015-01-22 - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2021-02-28 - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [asdf (zimfw)](https://github.com/zimfw/asdf) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2026-01-30 - Initializes [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,040 | 🐛 176 | 🌐 Go | 📅 2026-02-01, installing it using `git` if not installed yet. Also, bypasses the shims if you're using the [direnv](https://github.com/asdf-community/asdf-direnv) ⭐ 575 | 🐛 0 | 🌐 Shell | 📅 2025-11-21 plugin, as suggested by the plugin [pro-tips](https://github.com/asdf-community/asdf-direnv/#pro-tips) ⭐ 575 | 🐛 0 | 🌐 Shell | 📅 2025-11-21.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2024-02-09 - Integration and completions for [asdf](https://github.com/asdf-vm/asdf) ⭐ 25,040 | 🐛 176 | 🌐 Go | 📅 2026-02-01 and [direnv](https://github.com/asdf-community/asdf-direnv) ⭐ 575 | 🐛 0 | 🌐 Shell | 📅 2025-11-21.
* [brew-switcher](https://github.com/fielding/zsh-brew-switcher) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2023-10-06 - Automatically switch between Homebrew installations based on the current active arch, arm64 or x86\_64, on Apple Silicon Macs.
* [def](https://github.com/thevinter/def) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2022-10-28 - Allows you to specify and run a default command in any directory of your choice.
* [gitgo](https://github.com/ltj/gitgo) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2019-06-27 - Open a GitHub/GitLab repository in your browser from the command line (macOS only).
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) ⚠️ Archived - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [hbt](https://github.com/lzambarda/hbt) ⭐ 12 | 🐛 2 | 🌐 Go | 📅 2025-06-05 - Heuristic ZSH suggestion system based on past command usage.
* [jdk-switch](https://github.com/LockonS/jdk-switch) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2025-05-26 - Switches between jdk versions. Works on macOS and Linux.
* [nodo](https://github.com/nicolodiamante/nodo) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2024-01-21 - This plugin helps you prevent `node_modules` directories from filling your iCloud storage by un-syncing the directory or can save even more space by removing all `node_modules` directories within the chosen root directory. This is particularly useful for cleaning up a project that has multiple `node_modules` trees
* [opt-path](https://github.com/jreese/zsh-opt-path) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2022-08-24 - Automatically add `~/opt` subpaths to your `$PATH`.
* [path-ethic](https://github.com/sha1n/path-ethic) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2026-01-30 - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
* [ph-marks](https://github.com/lainiwa/ph-marks) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2022-06-26 - Bookmark pornhub videos from your terminal.
* [redo](https://github.com/joknarf/redo) ⭐ 12 | 🐛 0 | 📅 2026-02-03 - Adds an interactive history menu to replace `Ctrl-R` and `ESC+/`.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) ⚠️ Archived - Add support for [saml2aws](https://github.com/Versent/saml2aws) ⭐ 2,199 | 🐛 271 | 🌐 Go | 📅 2025-11-20.
* [vivid](https://github.com/ryanccn/vivid-zsh) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2024-08-14 - Make it easier to use `LSCOLORS` with [vivid](https://github.com/sharkdp/vivid) ⭐ 2,138 | 🐛 24 | 🌐 Rust | 📅 2026-01-28.
* [airpods-battery](https://github.com/louis-thevenet/zsh-airpods-battery/) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2025-05-15 - Looks for AirPods via Bluetooth and puts their battery charge state into `$RPROMPT`.
* [alacritty](https://github.com/casonadams/alacritty-shell) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2023-03-10 - Control [alacritty](https://github.com/alacritty/alacritty/wiki/Color-schemes) ⭐ 62,307 | 🐛 331 | 🌐 Rust | 📅 2026-01-29 color schemes.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2018-02-01 - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [command-not-found (freed-wu)](https://github.com/Freed-Wu/zsh-command-not-found) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2023-12-24 - Uses the `command-not-found` package for ZSH to provide suggested packages to be installed if a command cannot be found.
* [declare-zsh](https://github.com/z-shell/declare-zsh) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2025-03-26 - A parser for [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 commands in `.zshrc`. It allows you to perform the following actions on `.zshrc` from the command-line - enable and disable plugins add or remove snippets.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2020-10-19 - Random Dune quote generator plugin.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2018-04-10 - List EC2 instances and `ssh` login to the instances easily.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) ⭐ 11 | 🐛 3 | 🌐 Shell | 📅 2023-06-16 - Installs and loads [exa](https://github.com/ogham/exa.git) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24.
* [extend-history](https://github.com/xav-b/zsh-extend-history) ⭐ 11 | 🐛 3 | 🌐 Shell | 📅 2024-02-15 - Extends command history by adding the exit code for each command in the history.
* [gcloud-project](https://github.com/avivl/gcloud-project) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2019-03-17 - Easy selection of Google Cloud Projects.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2025-03-03 - Automatically `cd` to a `git` working directory after cloning it.
* [hab](https://github.com/alexdesousa/hab) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2020-03-19 - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [mylocation](https://github.com/fALKENdk/mylocation) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2022-04-01 - A plugin to show your current location based on your IP address.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) ⭐ 11 | 🐛 2 | 🌐 Shell | 📅 2020-11-27 - Background notifications for long running commands. Supports Elementary OS Freya.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2023-12-19 - Adds function to quickly reload your `.zshrc`.
* [sealion](https://github.com/xyproto/sealion) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2024-10-10 - Allows you to set reminders that will appear in your terminal when your prompt is refreshed.
* [systemd](https://github.com/le0me55i/zsh-systemd) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2021-06-01 - Adds many aliases for `systemd`.
* [terminal-aliases](https://github.com/dvir-levy/terminal-aliases) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2024-01-04 - Adds convenience aliases for `terraform`, `git` and more.
* [unwrap](https://github.com/foxleigh81/unwrap-zsh-plugin) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2025-01-29 - Allows you to remove a directory without removing the contents - it puts them in the directory's parent directory.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2022-01-19 - Add `vim`-like increment/decrement operations.
* [zjump](https://github.com/qoomon/zjump) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2025-08-06 - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [archlinux (junker)](https://github.com/Junker/zsh-archlinux) ⭐ 10 | 🐛 1 | 🌐 Shell | 📅 2023-04-18 - Based on the oh-my-zsh [archlinux](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/archlinux) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin. Defines helper functions and aliases.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2019-11-13 - Adds some convenience aliases for `git`.
* [colorls](https://github.com/Kallahan23/zsh-colorls) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2020-07-17 - Defines a few helpful shortcuts to some colorls functions.
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2019-07-02 - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived segment with the current bitcoin price.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2024-09-30 - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf) ⭐ 43 | 🐛 4 | 🌐 Python | 📅 2025-04-01. It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli) ⭐ 445 | 🐛 15 | 🌐 Shell | 📅 2022-06-28.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2015-08-05 - A plugin for [exercism.io](http://exercism.io/).
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-02-07 - Makes a shortcuts toolbar using `F1` to `F12` keys.
* [fd-plugin](https://github.com/MohamedElashri/fd-zsh) ⭐ 10 | 🐛 1 | 🌐 Shell | 📅 2024-06-07 - Adds aliases for [fd](https://github.com/sharkdp/fd) ⭐ 41,492 | 🐛 160 | 🌐 Rust | 📅 2026-02-03, a modern replacement for `find`.
* [git-branches](https://github.com/Schroefdop/git-branches) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2025-08-19 - Makes a menu of `git` branches you can switch to without having to type long branch names.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2017-12-25 - ZSH plugin to encrypt and decrypt files or directories in place.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2020-02-23 - Packs iTerm 2's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
* [n](https://github.com/gretzky/n.zsh) ⭐ 10 | 🐛 1 | 🌐 Shell | 📅 2018-08-21 - Auto-switches node versions based on project environment using [n](https://github.com/tj/n) ⭐ 19,491 | 🐛 3 | 🌐 Shell | 📅 2025-11-27.
* [npms](https://github.com/torifat/npms) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2020-03-05 - Utility powered by [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 for using npm scripts interactively. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and [jq](https://stedolan.github.io/jq/).
* [pnpm (baliestri)](https://github.com/baliestri/pnpm.plugin.zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - Adds useful aliases for many common [pnpm](https://pnpm.io/) commands. Includes tab-completions.
* [rust (wintermi)](https://github.com/wintermi/zsh-rust) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Plugin for the [rust](https://www.rust-lang.org/) toolchain.
* [select-with-lf](https://github.com/chmouel/zsh-select-with-lf) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2023-11-29 - Lets user select files or a directory using [lf](https://github.com/gokcehan/lf) ⭐ 9,030 | 🐛 67 | 🌐 Go | 📅 2026-02-04.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2021-11-05 - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [virtualz](https://github.com/aperezdc/virtualz) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2024-04-03 - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) ⭐ 1,090 | 🐛 24 | 🌐 Shell | 📅 2024-11-27 for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [ztrace](https://github.com/zdharma-continuum/ztrace) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2024-05-06 - Catches output of commands, allows to reuse that output, glue it with history content.
* [alt-and-select](https://github.com/raisty/alt-and-select) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2022-11-04 - Binds the `alt-c` (copy), `alt-`v (paste), `alt-x` (cut) keyboard shortcut to commands: `copy-region-as-kill`, `yank` and `kill-region`. Remaps the execute command to `alt-shift-X`.
* [apt](https://github.com/GeoLMg/apt-zsh-plugin) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2024-11-06 - For distros with `apt` package manager. Offers to install missing programs for you.
* [banner](https://github.com/drkhsh/zsh-banner) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2025-07-31 - Displays ANSI/ASCII art on session startup.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) ⚠️ Archived - Collection of useful and fun commands to improve workflow and quality of life.
* [dietpi](https://github.com/unixorn/dietpi.plugin.zsh) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2025-11-25 - Adds utilities for [dietpi](https://dietpi.com) to your `$PATH` (and includes aliases to automagically run them with `sudo`) when you log into a machine running  [dietpi](https://dietpi.com).
* [docker-aliases](https://github.com/webyneter/docker-aliases) ⭐ 9 | 🐛 9 | 🌐 Shell | 📅 2020-06-08 - `Docker` aliases for everyday use.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2017-08-19 - Fast jumps to your favorite directories.
* [fd](https://github.com/aubreypwd/zsh-plugin-fd) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2024-05-02 - Use [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 to browse directories.
* [firebase (seqi)](https://github.com/Seqi/firebase-zsh) ⭐ 9 | 🐛 2 | 🌐 Shell | 📅 2021-08-26 - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2022-06-15 - Adds prompt reminders for `git` user.email.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2015-03-17 - Updated fork of the [oh-my-zsh](https://ohmyz.sh/) `gitfast` plugin.
* [history-here](https://github.com/leonjza/history-here) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2026-01-12 - Binds `^G` to quickly toggle the current shell history file location.
* [homebrew](https://github.com/digitalraven/omz-homebrew) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-10-11 - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh and can safely run with it enabled.
* [hub](https://github.com/soraliu/zsh-hub) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-07-12 - ZSH plugin for forking model.
* [kubecolor (devopstales)](https://github.com/devopstales/zsh-kubecolor) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2025-08-25 - Adds aliases for the `kubecolor` command.
* [kubeconfig-mgr](https://github.com/yhlooo/zsh-kubeconfig-mgr) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2023-12-09 - Makes managing multiple kubeconfig files easier.
* [nohup](https://github.com/micrenda/zsh-nohup) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2017-05-04 - Add `nohup` to the current command pressing `Ctrl-H`.
* [oath](https://github.com/alexdesousa/oath) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2020-06-19 - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [percol](https://github.com/robturtle/percol.plugin.zsh) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2021-08-24 - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol) ⭐ 3,332 | 🐛 51 | 🌐 Python | 📅 2023-12-30.
* [pipx](https://github.com/thuandt/zsh-pipx) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-05-22 - Autocompletions for [pipx](https://github.com/pypa/pipx) ⭐ 12,508 | 🐛 167 | 🌐 Python | 📅 2026-02-02.
* [quoter](https://github.com/pxgamer/quoter-zsh) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2020-07-07 - Display a random quote when opening a new terminal session.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-07-20 - Converts `...` to `../..`
* [rockz](https://github.com/aperezdc/rockz) ⭐ 9 | 🐛 2 | 🌐 Shell | 📅 2025-07-14 - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) ⭐ 9 | 🐛 2 | 🌐 Shell | 📅 2023-12-24 - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-05-18 - Seamlessly install and configure the [Volta](https://volta.sh) Node.js toolchain manager.
* [yadm](https://github.com/juanrgon/yadm-zsh) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2018-07-16 - Displays a warning if there are local `yadm` configuration changes.
* [asdf-prompt](https://github.com/CurryEleison/zsh-asdf-prompt) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2022-08-08 - Provides a function usable in prompts that displays version information for your current tool versions.
* [battery\_state](https://github.com/Jactry/zsh_battery_state) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2012-03-10 - Show battery state in right-prompt.
* [bol](https://github.com/ikhurramraza/bol) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2023-01-09 - Prints a random quote when you open a terminal window.
* [cdhist](https://github.com/joknarf/cdhist) ⭐ 8 | 🐛 0 | 📅 2024-09-10 - cd history/subdir/locatedir navigation. simple cd history, alias builtin `cd` to add `cd` history, rapidily swich to already visited directories, can use `locate`, `mlocate` or `plocate` to rapidly cd to any directory
* [change-case](https://github.com/mtxr/zsh-change-case) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2017-12-04 - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [colorize-functions](https://github.com/Freed-Wu/zsh-colorize-functions) ⭐ 8 | 🐛 1 | 🌐 Shell | 📅 2026-01-19 - Colorizes functions for ZSH.
* [confer](https://github.com/SleepyBag/zsh-confer) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2023-02-25 - Tries to find program configuration files automatically so you can do things like `conf vim` to edit your `vim` configuration files.
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2021-07-21 - Adds aliases to make using [exa](https://github.com/ogham/exa.git) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24 easier.
* [eza (mohamedelashri)](https://github.com/MohamedElashri/eza-zsh) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-11-03 - Adds aliases for [eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01, a modern replacement for `ls`.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-11-10 - Set colors and titles of iTerm 2 tabs.
* [k3d](https://github.com/dwaynebradley/k3d-oh-my-zsh-plugin) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2021-11-11 - Adds aliases and tab completions for [k3d](https://k3d.io/).
* [kill-node](https://github.com/vmattos/kill-node) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2017-09-14 - ZSH plugin for murdering `node` process families.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) ⭐ 8 | 🐛 2 | 🌐 Shell | 📅 2019-06-27 - Simplify and colorize the output of `kubectl get events -w`
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2023-03-06 - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2019-11-03 - Adds aliases for [Laravel](https://laravel.com/) 6.
* [last-working-directory](https://github.com/mdumitru/last-working-dir) ⭐ 8 | 🐛 1 | 🌐 Shell | 📅 2023-12-24 - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
* [markedit](https://github.com/zakariaGatter/MarkEdit) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2019-12-06 - Mark files and edit them with autocompletion for existing marks.
* [mfunc](https://github.com/hlohm/mfunc) ⭐ 8 | 🐛 2 | 🌐 Shell | 📅 2024-07-12 - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [pctl](https://github.com/ytet5uy4/pctl) ⚠️ Archived - Toggle the environment variables for proxying.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-03-06 - Plugin for [PHPUnit](https://phpunit.de/).
* [quotify](https://github.com/dpretet/zsh-quotify) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2022-06-05 - Displays inspiring coding quotes from our pairs when starting up.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-04-28 - Displays random quotes or facts.
* [ranger-zoxide](https://github.com/fdw/ranger-zoxide) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2022-01-08 - Adds [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 33,206 | 🐛 151 | 🌐 Rust | 📅 2026-02-02 support to the [ranger](https://github.com/ranger/ranger) ⭐ 16,840 | 🐛 921 | 🌐 Python | 📅 2026-01-22 console file manager.
* [setenv](https://github.com/kalpakrg/setenv) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2022-07-20 - Runs a script when you change directories.
* [shell-ng](https://github.com/joknarf/shell-ng) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Combines several of [joknarf](https://github.com/joknarf/)'s other plugins - [selector](https://github.com/joknarf/selector) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2026-02-03, [nerdp](https://github.com/joknarf/nerdp) ⭐ 5 | 🐛 0 | 📅 2026-02-03, [redo](https://github.com/joknarf/redo) ⭐ 12 | 🐛 0 | 📅 2026-02-03, [seedee](https://github.com/joknarf/seedee) ⭐ 7 | 🐛 0 | 📅 2026-02-03 and [complete-ng](https://github.com/joknarf/complete-ng) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-02-03.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2021-04-18 - Will update your `known_hosts` file when you `ssh` into a server.
* [timewarrior (ianmkenney)](https://github.com/ianmkenney/timewarrior_zsh_completion) ⭐ 8 | 🐛 0 | 📅 2025-10-08 - Tab completions for the [timewarrior](https://timewarrior.net/) time-tracking application.
* [unique-id](https://github.com/z-shell/zsh-unique-id) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2025-07-19 - Provides a unique number that identifies a running Zshell session, in its shell variable `$ZUID_ID`. Besides this unique number, also a unique codename is provided, in shell variable `$ZUID_CODENAME`. An example use case is to hold logs in files `.../mylog-${ZUID_CODENAME}.log`, so that two different Zshells will not write to the same file at the same time.
* [valet (NasirNobin)](https://github.com/NasirNobin/zsh-valet/) ⭐ 8 | 🐛 3 | 🌐 Shell | 📅 2023-02-24 - Reads `.valetphprc` from the project root and will switch to that PHP version automatically.
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2016-01-30 - An [oh-my-zsh](https://ohmyz.sh/) plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [zed](https://github.com/eendroroy/zed-zsh) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-04-17 - A simple wrapper for [z](https://github.com/rupa/z) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19 to install it via a ZSH plugin.
* [zinit-annex-bin-gem-node](https://github.com/zdharma-continuum/zinit-annex-bin-gem-node) ⭐ 8 | 🐛 8 | 🌐 Shell | 📅 2025-10-05 - [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
* [assume-role](https://github.com/weizard/assume-role) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2019-01-30 - Allows you to assume AWS IAM roles easily. Includes completions.
* [autovenv (linnnus)](https://github.com/linnnus/autovenv) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-03-17 - Automatically activates Python virtual environments when entering their parent directory.
* [bash-quote](https://github.com/jtprog/bash-quote) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2023-02-02 - Get random quote from Bash.im.
* [cycle-jobs](https://github.com/aemonge/zsh-cycle-jobs) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2026-01-19 - The ZSH Cycle Jobs Plugin is a simple yet powerful tool that enhances your terminal workflow by allowing you to cycle through background jobs using a single keyboard shortcut. This plugin is particularly useful for developers and system administrators who frequently work with multiple background processes.
* [delete-prompt](https://github.com/aoyama-val/zsh-delete-prompt) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-05-09 - ZSH widget to delete the prompt texts within the current line. It is useful when executing pasted commands from the web or a README. A leading non-alphanumeric character + space is detected as a prompt.
* [dot-up](https://github.com/toku-sa-n/zsh-dot-up) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2026-01-23 - Converts `...`, `....`, `.....`, etc., into `cd` commands to navigate parent directories.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-03-27 - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [explain-shell (brokentoaster)](https://github.com/brokentoaster/zsh-explainshell) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-05-11 - Uses [lynx](https://lynx.browser.org/) to look up the current command line on [explainshell.com](https://explainshell.com).
* [eza (twopizza9621536)](https://github.com/twopizza9621536/zsh-eza) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2025-08-25 - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01.
* [fzf-it](https://github.com/micakce/fzf-it) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2023-07-08 - Make any command interactive wrapping it with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 functionality.
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2022-05-24 - Better handling of passwords using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and [pass](https://www.passwordstore.org/).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-10-15 - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 has been installed and enables its auto-completion and key-bindings. This plugin works as a Prezto `zstyle` configuration option.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) ⭐ 7 | 🐛 3 | 🌐 Shell | 📅 2025-03-25 - Adds short aliases for the `git-flow` commands.
* [git-plugin (rcruzper)](https://github.com/rcruzper/zsh-git-plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2019-03-03 - Adds some functions for `git`.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2012-08-03 - Add autocompletion for `grunt`.
* [guish](https://github.com/gcarrarom/oh-my-guish) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-06-03 - Collection of utility functions and aliases.
* [hanami](https://github.com/davydovanton/hanami-zsh) ⭐ 7 | 🐛 1 | 📅 2017-08-18 - ZSH plugin for [hanami](http://hanamirb.org) projects.
* [host-switch](https://github.com/LockonS/host-switch) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2016-08-04 - Make it easier to switch in different `/etc/hosts` files during development.
* [javaVersions](https://github.com/miguefl/javaVersions) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2018-12-04 - Change between different java versions with a single command.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2018-10-29 - A ZSH plugin for lazy loading of jEnv.
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) ⭐ 7 | 🐛 0 | 📅 2017-05-17 - ZSH plugin for managing `kubectl`.
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2022-10-20 - Automatically installs [kubectx](https://github.com/ahmetb/kubectx) ⭐ 19,444 | 🐛 75 | 🌐 Go | 📅 2025-01-22 and `kubens`.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2024-07-11 - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
* [markgate](https://github.com/zakariaGatter/MarkGate) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2023-02-16 - Allows you to mark directories so you can jump directly to them.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2022-04-16 - Generates custom themes. Some generated themes require powerline-compatible fonts.
* [sdkman](https://github.com/ptavares/zsh-sdkman) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-10-10 - Installs [sdkman](https://github.com/sdkman) and adds completions and aliases for it.
* [seedee](https://github.com/joknarf/seedee) ⭐ 7 | 🐛 0 | 📅 2026-02-03 - Navigate interactively through directories / history of visited directories using arrow keys from command line.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-03-07 - Adds many `git` aliases and helper shell functions.
* [shortcuts](https://github.com/fairy-root/Zsh-Shortcuts-Plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-07-04 - Enhance your terminal productivity with the Shortcuts plugin for [oh-my-zsh](https://ohmyz.sh/). Easily manage command shortcuts with robust features.
* [smart-files](https://github.com/vxfemboy/zsh-smart-files) ⭐ 7 | 🐛 2 | 🌐 Shell | 📅 2025-02-21 - Enhances CLI by providing visual feedback for file paths and automatically creating directories when needed. It highlights paths in different colors based on their status (existing, new, or permission-denied) and handles directory creation automatically.
* [title](https://github.com/zpm-zsh/title) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2020-03-14 - Allows you to set a terminal window title.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-01-20 - Updates custom [oh-my-zsh](https://ohmyz.sh/) plugins. Only works with the oh-my-zsh framework.
* [valet (A909M)](https://github.com/A909M/valet-zsh-plugin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-09-09 - Works with both [Laravel Valet](https://laravel.com/docs/valet) and [Valet Linux](https://cpriego.github.io/valet-linux/) on Debian/Ubuntu. Provides intelligent autocompletion, helpful aliases, and utility functions to streamline your local development workflow.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-01-06 - Add an operation which quotes or unquotes a motion.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2019-06-06 - Simple utility for jumping between projects.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-06-03 - Adds `yt` aliases to download videos from YouTube.
* [zinit-annex-submods](https://github.com/z-shell/z-a-submods) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2023-02-05 - [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that allows installing and managing additional submodules within a plugin or snippet.
* [zsh-watch](https://github.com/Thearas/zsh-watch) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2023-06-05 - Simple `watch` that supports alias and completion.
* [zshrc](https://github.com/freak2geek/zshrc) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2019-05-08 - Load local `.zshrc` files from your project scopes.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2019-10-04 - Antigen/ZSH script to aid with `git` rebasing.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2016-07-03 - Adds aliases and functions for managing Apache2.
* [arc](https://github.com/anton-rudeshko/zsh-arc) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-06-11 - Adds aliases for Yandex version control system.
* [arduino](https://github.com/raghur/zsh-arduino) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2024-01-09 - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2018-03-06 - A plugin for AsciiDoctor.
* [ash](https://github.com/NotNanook/Ash) ⭐ 6 | 🐛 0 | 🌐 D | 📅 2026-01-31 - A no-bullshit, seamless way to use LLMs right inside your shell (`bash`, `zsh`). Supports OpenAI, Ollama and OpenRouter.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2021-09-25 - Automatically runs `ls` or `color-ls` if available on `cd`.
* [auto-venv (skylor0tang)](https://github.com/Skylor-Tang/auto-venv) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-11-30 - Automatically activates the Python virtual environment in the current directory or its parent directories.
* [brew (wintermi)](https://github.com/wintermi/zsh-brew) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-10-06 - Simple plugin for the [Homebrew](https://brew.sh/) package manager.
* [bw](https://github.com/begris/bw-zsh-plugin) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2024-11-19 - Provides formatting options and easy access to credentials stored in [Bitwarden](https://bitwarden.com) via the Bitwarden [CLI](https://bitwarden.com/download/). The plugin tries to retrieve a valid session before each action, therefore an explicit login is not nescessary beforehand.
* [calc (sam-programs)](https://github.com/Sam-programs/zsh-calc) ⭐ 6 | 🐛 5 | 🌐 Shell | 📅 2025-03-29 - Allows you to run math calculations with no prefixes.
* [containers](https://github.com/redxtech/zsh-containers) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2024-01-04 - Provides aliases and better interoperability between [podman](https://podman.io) and [docker](https://docker.com) commands based on which you have installed.
* [doas (anatolykopyl)](https://github.com/anatolykopyl/doas-zsh-plugin) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2020-08-17 - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2014-03-25 - Dogification plugin.
* [fzfsh](https://github.com/ethan605/fzfsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-05-14 - Add [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 plugins for `chezmoi`, `docker`, `git`, `kubectl` and `pass`.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2021-07-30 - Take the current command line as the commit message and then run `git pull`, `git add`, `git commit` and `git push` with one keystroke.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) ⚠️ Archived - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2018-08-25 - A `gvm` (Go version manager) plugin for ZSH.
* [histree](https://github.com/fuba/histree-zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-12-25 - Integrates with [histree-core](https://github.com/fuba/histree-core) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2026-02-06 to provide enhanced command history logging with directory awareness.
* [incsearch](https://github.com/aoyama-val/zsh-incsearch) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2023-11-06 - Friendlier `vim` mode for ZSH. Moves cursor with incremental search within current line.
* [jenkins](https://github.com/tomplex/jenkins-zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2017-02-21 - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2015-01-17 - Create JIRA tickets from the command line.
* [jumper](https://github.com/thestuckster/jumper) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-07-31 - Saves your current path and allows you to quickly jump to others.
* [lsd (wintermi)](https://github.com/wintermi/zsh-lsd) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Override `ls` and `tree` commands with [lsd](https://github.com/Peltoche/lsd) ⭐ 15,413 | 🐛 186 | 🌐 Rust | 📅 2025-12-09.
* [mkarch](https://github.com/0xRZ/mkarch) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-09-15 - ZSH plugin that allows you to create archives using multiple different compression formats.
* [navi](https://github.com/icatalina/zsh-navi-plugin/) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2021-07-06 - Plugin for [navi](https://github.com/denisidoro/navi) ⭐ 16,704 | 🐛 102 | 🌐 Rust | 📅 2025-10-14.
* [node-path](https://github.com/andyrichardson/zsh-node-path) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2019-09-19 - Automatically adds the `npm` bin of your current directory to your `$PATH`.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-05-16 - Plugin for lazy loading of oh-my-zsh's \**nvm*- plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
* [omz-themes-standalone](https://github.com/zshzoo/omz-themes-standalone) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2022-03-07 - Gives you the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes without requiring everything else that comes with [Oh-My-ZSH](https://ohmyz.sh/).
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2022-04-05 - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) ⭐ 680 | 🐛 4 | 🌐 Shell | 📅 2020-11-13 if an rc-file is present in a directory.
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-08-06 - Plugin for managing projects.
* [pwp](https://github.com/ttkalcevic/pwp) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-09-05 - Provides a convenient way to display the present working path in the terminal prompt and lists the current working directory along with its parent directories. Additionally, it includes a custom command .. to navigate to parent directories easily.
* [ranger (rc2dev)](https://github.com/rc2dev/ranger-zshz) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-03-28 - Integrates [zsh-z](https://github.com/agkozak/zsh-z) ⭐ 2,333 | 🐛 21 | 🌐 Shell | 📅 2025-05-07 into [ranger](https://github.com/ranger/ranger) ⭐ 16,840 | 🐛 921 | 🌐 Python | 📅 2026-01-22.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2016-04-04 - Plugin that re-enters working directory if it has been removed and re-created.
* [run-scripts](https://github.com/Aireck2/zsh-run-scripts) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-11-05 - Runs scripts from `package.json`.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2020-06-27 - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
* [shellcolor](https://github.com/SaltedBlowfish/zsh-shellcolor) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-03-23 - Changes the terminal background color based on the presence of a `.shellcolor` in the current directory.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2018-04-27 - Plugin for `ssh`.
* [stashy](https://github.com/MisterRios/stashy) ⭐ 6 | 🐛 2 | 🌐 Shell | 📅 2024-03-19 - Plugin that simplifies using `git stash`.
* [sublime](https://github.com/valentinocossar/sublime) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2018-02-01 - Same as the official [Sublime](https://www.sublimetext.com/) plugin for [Oh My Zsh](https://ohmyz.sh/), but this opens files in the current Sublime window, if there is one already open.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-08-06 - ZSH plugin for [Symfony](https://symfony.com/).
* [tm](https://github.com/kjhaber/tm.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-05-25 - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2016-11-30 - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
* [watson.zsh](https://github.com/bcho/Watson.zsh) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2015-10-25 - A plugin for the [watson](https://github.com/TailorDev/Watson) ⭐ 2,512 | 🐛 139 | 🌐 Python | 📅 2025-12-15 time management system.
* [web-search (anant-mishra1729)](https://github.com/Anant-mishra1729/web-search/) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-05-12 - Adds aliases for searching with Google, Bing, Wiki, YouTube, Yahoo, Duck Duck Go, GitHub, Stack Overflow and other services straight from the command line.
* [welcome-banner](https://github.com/joshuadanpeterson/zsh-welcome-banner) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-08-13 - Displays a login banner with a random quote.
* [zellij (jaeheonji)](https://github.com/jaeheonji/zsh-zellij-plugin) ⚠️ Archived - Provides an environment that uses [zellij](https://github.com/zellij-org/zellij) ⭐ 28,728 | 🐛 1,477 | 🌐 Rust | 📅 2026-02-06. Requires [tmux](https://github.com/tmux/tmux) ⭐ 41,448 | 🐛 37 | 🌐 C | 📅 2026-02-02. Deprecated by author, now [supported natively](https://zellij.dev/documentation/integration.html#autostart-on-shell-creation).
* [zinit-annex-meta-plugins](https://github.com/zdharma-continuum/zinit-annex-meta-plugins) ⭐ 6 | 🐛 2 | 🌐 Shell | 📅 2023-04-16 - Install groups of plugins with a single label ([zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 only).
* [zinit-annex-readurl](https://github.com/zdharma-continuum/zinit-annex-readurl) ⭐ 6 | 🐛 3 | 🌐 Shell | 📅 2024-06-21 - Adds function to automatically download the newest version of a file to which URL is hosted on a webpage.
* [zlitefetch](https://github.com/ippee/zlitefetch) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-12-19 - Lightweight system information plugin.
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) ⚠️ Archived - Based on the [Sublime](https://github.com/valentinocossar/sublime) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2018-02-01 plugin, lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
* [cmd-time](https://github.com/TomfromBerlin/zsh-cmd-time) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Collects the execution time of commands and exports the result to a variable that can be used elsewhere. It is similar to the built-in [REPORTTIME](http://zsh.sourceforge.net/Doc/Release/Parameters.html) function, but it is also slightly different. Unlike when you set `REPORTTIME`, it considers user and sytem time, not just CPU time.
* [deja-vu](https://github.com/justyntemme/zsh-deja-vu) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2025-11-14 - Logs and retrieves command history based on the directory it was run in. Never forget that complex `docker` or `git` command you ran in a project folder weeks ago.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-12-30 - Provides a lightweight version of Shopify's internal dev tool
* [doas (senderman)](https://github.com/Senderman/doas-zsh-plugin) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-06-26 - Easily prefix your current or previous commands with `doas` by pressing `ESC` twice.
* [download](https://github.com/aubreypwd/zsh-plugin-download) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-08-11 - Helper to download files with `aria2c`.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-05-13 - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a `ssh` connection, or X frames opened on the same host.
* [expander](https://github.com/ianthehenry/zsh-expander) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-01-25 - A `zle` widget that allows you to write custom expanders and select them with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [fav](https://github.com/ddnexus/fav) ⚠️ Archived - ZSH/[fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 plugin that makes it really easy to add and recall named favorites of your important directories.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2017-10-05 - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
* [fzf-copyq-clipboard](https://github.com/magidc/fzf-copyq-clipboard-zsh-plugin) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-12-12 - Add [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 support for [CopyQ](https://hluk.github.io/CopyQ/).
* [gcloud](https://github.com/wintermi/zsh-gcloud) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2024-09-28 - Finds the installed gcloud sdk and sources the zsh file there, along with the zsh completions file.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-12-27 - Adds some aliases and functions to work with Gentoo Linux.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-08-03 - Adds command to `git clone` a repository and `cd` into the resulting directory.
* [gitsync](https://github.com/washtubs/gitsync) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2016-01-18 - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
* [golang](https://github.com/wintermi/zsh-golang) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2024-09-28 - Adds tooling for the Go programming language toolchain.
* [history-on-success](https://github.com/nyoungstudios/zsh-history-on-success) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-04-17 - Save yourself from repeating the same mistakes by filtering out your unsuccessful commands from your zsh history file. Based on a [blog post](https://scarff.id.au/blog/2019/zsh-history-conditional-on-command-success/) by Dean Scarff.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-11-28 - Activate a REPL for any command in your current ZSH session.
* [jabba](https://github.com/2m/zsh-jabba) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-09-19 - Adds shell integration code and completions for the [jabba](https://github.com/shyiko/jabba) ⭐ 3,367 | 🐛 150 | 🌐 Go | 📅 2024-03-14 Java version manager.
* [mkcd](https://github.com/azizoid/zsh-mkcd) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-12-31 - Provides a `mkcd` command, the canonical `mkdir` && `cd` helper.
* [node](https://github.com/srijanshetty/node.plugin.zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2015-04-22 - Srijan Shetty's Node.js plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [oh-my-posh-manager](https://github.com/wintermi/zsh-oh-my-posh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-09-10 - Manages the oh-my-posh theme engine, along with providing a default powerline-like theme.
* [pins](https://github.com/mehalter/zsh-pins) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-03-06 - ZSH plugin for pinning directories. Like a CLI folder bookmark manager with tab completions.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-02-27 - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a `pipenv` project.
* [pnpm (leizhenpeng)](https://github.com/Leizhenpeng/zsh-plugin-pnpm) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-02-10 - Adds useful aliases for common [pnpm](https://pnpm.io/) commands.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-10-24 - Enables poetry `$PATH` and autocompletions.
* [popman](https://github.com/jdsee/popman) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-11-01 - Ever found yourself in the middle of composing a long command and needing to check a man page? Popman lets you instantly pop open a man page for any command you're typing and jump right back to where you left off, making your command-line experience smoother and more efficient.
* [portal](https://github.com/anasouardini/portal/) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-05-06 - A very basic script for jumping to/from paths without having to do write the whole path, open multiple terminal sessions or do a file system search using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. Heavily inspired by [Z](https://github.com/rupa/z) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19.
* [prettyping](https://github.com/unixorn/prettyping) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2023-12-25 - Adds a wrapper around the standard ping tool with the objective of making the output prettier, more colorful, more compact, and easier to read.
* [purge-history-secrets](https://github.com/jotasixto/purge-history-secrets) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-06-01 - Uses [gitleaks](https://github.com/gitleaks/gitleaks) ⭐ 24,797 | 🐛 344 | 🌐 Go | 📅 2026-01-08 to periodically scan your ZSH history for secrets and purge them if found. Requires [jq](https://jqlang.github.io/jq/).
* [redis](https://github.com/z-shell/redis) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-10-30 - Will run [redis-server](https://redis.io/) pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis](https://github.com/z-shell/zredis) ⭐ 7 | 🐛 2 | 🌐 C | 📅 2025-11-21 plugin to share variables between shells.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2020-01-16 - Add some safety when running [kubectl](https://kubernetes.io/docs/reference/kubectl/) by warning what context you're in after a definable number of seconds since the last `kubectl` command.
* [shellsense](https://github.com/venopyX/shellsense) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-01-21 - AI-powered ZSH plugin designed to enhance your terminal experience with powerful features and AI-powered capabilities. Developed using Python, ShellSense offers a streamlined workflow for various tasks, making your terminal more efficient and user-friendly.
* [slugify](https://github.com/lashoun/slugify) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-03-30 - Converts filenames and directories to a web friendly format.
* [smart-insert](https://github.com/lgdevlop/zsh-smart-insert) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-20 - provides interactive widgets to search for files and content using [`fd`](https://github.com/sharkdp/fd) ⭐ 41,492 | 🐛 160 | 🌐 Rust | 📅 2026-02-03, [`rg`](https://github.com/BurntSushi/ripgrep) ⭐ 59,624 | 🐛 113 | 🌐 Rust | 📅 2025-12-17, and [`fzf`](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. It inserts the result directly into your shell with optional command prefixes.
* [smile](https://github.com/fundor333/smile) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-01-12 - Adds function to display random smileys.
* [ssh-host](https://github.com/obolientsev/ssh-host) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-01-13 - Manage ssh with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [statify](https://github.com/vladmrnv/statify) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2016-01-28 - Plugin that does basic statistical analysis.
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) ⚠️ Archived - Rewrite of the stock [oh-my-zsh](https://ohmyz.sh/) [svn](https://subversion.apache.org/) plugin.
* [termux](https://github.com/zpm-zsh/termux) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-04-18 - Adds compatibility for [Termux](https://termux.com/).
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-10-25 - Extends the original [oh-my-zsh](https://ohmyz.sh/) plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) ⚠️ Archived - Plugin for [Terragrunt](https://github.com/gruntwork-io/terragrunt) ⭐ 9,280 | 🐛 249 | 🌐 Go | 📅 2026-02-06, a thin wrapper for [Terraform](https://terraform.io/) that provides extra tools.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) ⚠️ Archived - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2017-07-27 - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2019-04-26 - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [velocity](https://github.com/rahulsalvi/velocity-python) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2019-11-15 - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) ⚠️ Archived - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) ⭐ 44,223 | 🐛 56 | 🌐 Shell | 📅 2026-02-04 (though you don't \*have- to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
* [worktree](https://github.com/jspears/worktree) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2021-06-23 - Adds functions that wrap `git worktree`.
* [xxh (roman-geraskin)](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2020-08-14 - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) ⭐ 39 | 🐛 6 | 🌐 Shell | 📅 2025-04-03 that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) ⭐ 39 | 🐛 6 | 🌐 Shell | 📅 2025-04-03.
* [zconvey](https://github.com/zdharma-continuum/zconvey) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2024-05-12 - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active ZSH sessions, for example.
* [zi-rbenv](https://github.com/z-shell/zi-rbenv) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-02-04 - Fast `rbenv` loads if you're using [zi](https://github.com/z-shell/zi/) ⭐ 879 | 🐛 11 | 🌐 Shell | 📅 2026-01-19.
* [zinit-annex-man](https://github.com/zdharma-continuum/zinit-annex-man) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-04-16 - [Zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that generates man pages for all plugins and snippets
* [zinit-annex-rust](https://github.com/zdharma-continuum/zinit-annex-rust) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2025-04-12 - [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that that installs rust and cargo packages inside plugin directories.
* [zredis-cmd](https://github.com/z-shell/zredis-cmd) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2022-05-03 - Utilizes variable sharing done by [zredis](https://github.com/zdharma-continuum/zredis) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2023-04-16 plugin to implement remote command execution.
* [zsh-llm-assist](https://github.com/championswimmer/zsh-llm-assist) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Plain english to shell command suggestions as well as shell command to plain english explanation using Gemini CLI, Codex, Claude Code or OpenCode
* [1password](https://github.com/agpenton/1password-zsh-plugin) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-07-31 - Adds [1Password](https://1password.com/) functionality including a `opswd` command that wraps the `op` command. It takes a service name as an argument and copies the password for that service to the clipboard.
* [actiona](https://github.com/matthieusb/act) ⭐ 4 | 🐛 2 | 🌐 Shell | 📅 2018-11-18 - Make it easier to call [actiona](https://github.com/Jmgr/actiona) ⭐ 661 | 🐛 63 | 🌐 C++ | 📅 2025-11-15 scripts from your command line. Includes tab completions.
* [allclear](https://github.com/givensuman/zsh-allclear) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-07-10 - Clears the terminal when you `cd` into `$HOME`.
* [auto-pnpm-use](https://github.com/brunomacedo/zsh-auto-pnpm-use) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-01-08 - Automatically loads the node version specified in `.nvmrc` or `.npmrc`.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2018-12-11 - Plugin for using AWS MFA.
* [awsssh](https://github.com/raisedadead/zsh-awsssh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-03-24 - List, select and `ssh` into EC2 instances.
* [bitwarden (casonadams)](https://github.com/casonadams/bitwarden-cli) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-06-27 - A [Bitwarden](https://bitwarden.com/download/) CLI fuzzy finder using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. Requires [jq](https://stedolan.github.io/jq/).
* [bob](https://github.com/wintermi/zsh-bob) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Plugin for [bob](https://github.com/MordechaiHadad/bob) ⭐ 1,992 | 🐛 27 | 🌐 Rust | 📅 2026-01-26 a cross-platform and easy-to-use Neovim version manager.
* [bofh](https://github.com/fundor333/bofh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-01-12 - Adds functions to display random bofh fortunes.
* [c](https://github.com/sebastiangraz/c) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-06-09 - Adds some `git` shortcuts.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-06-15 - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw](https://github.com/zsh-users/zaw) ⭐ 581 | 🐛 13 | 🌐 Shell | 📅 2023-08-05
* [case](https://github.com/rtuin/zsh-case) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-01-12 - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
* [check-deps](https://github.com/zpm-zsh/check-deps) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-07-22 - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Node.js and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) ⭐ 391 | 🐛 5 | 🌐 Shell | 📅 2025-12-21 framework.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2021-04-19 - Reports the status of commands including return code and duration.
* [code-review](https://github.com/xorkevin/code-review-zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2019-07-21 - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
* [cowsay](https://github.com/phucisstupid/cowsay.zsh) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2026-02-07 - Displays a joke with `cowsay` and `lolcat` every time you open a terminal.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-07-01 - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-11-27 - Enables numpad keys of Apple keyboards to be recognized in ZSH.
* [flow-cli](https://github.com/Data-Wise/flow-cli) ⭐ 4 | 🐛 6 | 🌐 Shell | 📅 2026-02-06 - ADHD-friendly ZSH workflow tools. Start working in 10 seconds with `work`, track wins for dopamine with `win`, stay oriented with `dash`. Includes smart dispatchers for git, R, Quarto, and Claude Code.
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-06-21 - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-04-10 - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2020-09-23 - Adds short aliases for the `git-lfs` commands.
* [git-status](https://github.com/AyoubMounim/zsh-git-status/) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-05-17 - Exposes functions with information about the current `git` repository.
* [gitio (nicolodiamante)](https://github.com/nicolodiamante/gitio) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-01-20 - Uses [git.io](https://git.io/) to shorten `git` urls.
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2020-06-07 - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli) ⭐ 514 | 🐛 52 | 🌐 Python | 📅 2026-01-08. and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
* [ing](https://github.com/rummik/zsh-ing) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2018-10-12 - Streamlined `ping` output.
* [iosctl](https://github.com/obayer/iosctl) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-10-14 - Quickly access App, Data, and Log of the running simulator.
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2019-04-18 - Manage your iTerm 2's color scheme from the command line.
* [iwd](https://github.com/zshzoo/iwd) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-12-12 - Similar in concept to `$PWD`, this ZSH plugin saves your initial working directory in `$IWD` for easy returns to the starting point of your session.
* [kctl](https://github.com/yzdann/kctl) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-08-05 - Add helper aliases for `kubectl`.
* [kubecolor (trejo08)](https://github.com/trejo08/kubecolor-zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-02-17 - Prints colorized outputs from  `kubectl`. Includes helper functions.
* [mkcd](https://github.com/marvinroman/oh-my-zsh-mkcd-plugin) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-06-09 - Allows user to create a directory and if successful, `cd` into it afterward.
* [namelink](https://github.com/jthat/zsh-namelink) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-07-14 - Provides an automatically synchronized mapping of filesystem entries (typically symbolic links) in a set of directories to their counterparts in the named directory hash.
* [nnvm](https://github.com/torifat/nnvm) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-03-05 - auto-switches node versions based on `.nvmrc`. Requires [n](https://github.com/tj/n) ⭐ 19,491 | 🐛 3 | 🌐 Shell | 📅 2025-11-27.
* [nobility](https://github.com/Twilight4/nobility) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-01-19 - An organized colletion of shell modules designed to streamline your pentesting workflow by leveraging shell integrations such as autocompletion and prefilling, optimizing the productivity of your work and liberatating you from the hassle of juggling notes, endless copying and pasting, and tedious command editing.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) ⚠️ Archived - Auto-load `nodenv` and its completions into the shell.
* [notenote](https://github.com/DrgnFireYellow/notenote/) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-09-14 - Makes it easy to take notes.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-11-05 - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [qwy](https://github.com/Ryooooooga/qwy) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2025-11-25 - ZSH fuzzy completion plugin.
* [randeme](https://github.com/ex-surreal/randeme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-09-25 - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-12-17 - Change the color of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (elliottcable)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) ⭐ 4 | 🐛 2 | 🌐 Shell | 📅 2022-01-17 - A faster fork of the `rbenv` plugin from [oh-my-zsh](https://ohmyz.sh/).
* [rc-files](https://github.com/0b10/rc-files) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2020-02-23 - Adds shortcut functions for editing various rc files.
* [require](https://github.com/aubreypwd/zsh-plugin-require) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-04-07 - Adds ability to `require commandname` and then (if [brew](https://brew.sh) is installed) automatically `brew install commandname` if it isn't already installed.
* [scad](https://github.com/MicahElliott/scad) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-01-07 - Shell Colorized Aliases for Docker/Podman (SCAD). Defines [docker](https://www.docker.com/) / [podman](https://podman.io) aliases and functions. These aliases adhere to the newer style of organizing and invoking `docker` with management commands rather than the notoriously confusing “random solo commands”. Requires [GRC](https://github.com/garabik/grc) ⭐ 2,127 | 🐛 93 | 🌐 Python | 📅 2024-08-18 and [jq](https://github.com/jqlang/jq) ⭐ 33,491 | 🐛 451 | 🌐 C | 📅 2026-02-01.
* [shell-fns](https://github.com/Hdoc1509/shell-fns) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-09-30 - Includes `git`, `neovim`, `npm`, `pip` extended functionality.
* [show-git-user](https://github.com/luisprgr/zsh-show-git-user) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-06-04 - When you need to work with multiple `git` users on the same machine this plugin will show which `git` user name is active in your prompt.
* [ssh-agent](https://github.com/sdiebolt/zsh-ssh-agent) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-11-13 - Automatically launches `ssh-agent` if it isn't already running.
* [startify](https://github.com/NorthIsMirror/zsh-startify) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-11-05 - Shows recently used `vim` files, shell-util files, active `tmux` sessions, recently-run `git` commands and more.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-09-22 - Directly open files in the shell using ZSH's suffix aliases.
* [take](https://github.com/amyreese/zsh-take) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-04-29 - Replicates `take` from [oh-my-zsh](https://ohmyz.sh/).
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) ⚠️ Archived - Adds a `set-term-title` function you can use to title terminal windows.
* [terraform (ptavares)](https://github.com/ptavares/zsh-terraform) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-03-19 - Adds aliases, functions and tab completions. Also installs [terraform-docs](https://github.com/terraform-docs/terraform-docs) ⭐ 4,687 | 🐛 184 | 🌐 Go | 📅 2025-12-18, [tfsec](https://github.com/aquasecurity/tfsec) ⭐ 6,950 | 🐛 14 | 🌐 Go | 📅 2025-11-10 and [tflint](https://github.com/terraform-linters/tflint) ⭐ 5,601 | 🐛 28 | 🌐 Go | 📅 2026-02-02.
* [tmux-ssh-syncing](https://github.com/alberti42/tmux-ssh-syncing) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-09-09 - Synchronize your `tmux` window names with active `ssh` sessions. This plugin dynamically updates the [`tmux`](https://tmux.github.io) window name to reflect the remote hosts of active `ssh` sessions in the same window. It also restores the original window name when all `ssh` sessions are closed.
* [touchplus](https://github.com/raisedadead/zsh-touchplus) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-05-05 - Create files with `touch` including the path.
* [travis](https://github.com/denolfe/zsh-travis) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-08-11 - Opens the [Travis CI](https://www.travis-ci.com/) page for the current repo if one exists.
* [up (cjayross)](https://github.com/cjayross/up) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-12-06 - A simple way to navigate up through directories.
* [visit](https://github.com/justinpchang/visit) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2018-08-24 - Custom plugin for faster navigation.
* [web-search (sinetoami)](https://github.com/sinetoami/web-search) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-02-15 - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [windows-title](https://github.com/mdarocha/zsh-windows-title) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-03-26 - Dynamically updates terminal window title with current directory and the last command run.
* [zenplash](https://github.com/Chivier/zenplash) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2023-11-08 - Creates files from templates stored in a user directory.
* [zeza](https://github.com/duggum/zeza) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-02-01 - Manages and customizes [eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01, the very colorful `ls` replacement.
* [zflai](https://github.com/zdharma-continuum/zflai) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-04-16 - A fast logging framework for ZSH.
* [zgenom-ext-eval](https://github.com/jandamm/zgenom-ext-eval/) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-05-04 - [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01 extension for creating plugins inline.
* [zledit](https://github.com/Piotr1215/zledit) ⭐ 4 | 🐛 3 | 🌐 Shell | 📅 2026-02-01 - Fuzzy jump to any token on ZSH command line with overlay hints, preview panel, and in-place editing. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [zredis](https://github.com/zdharma-continuum/zredis) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2023-04-16 - Adds [Redis](https://redis.io/) database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zservice-py3http](https://github.com/z-shell/zservice-py3http) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-12-01 - Serve a given directory with Python 3's http server from the standard library.
* [zshcp](https://github.com/michaelsousajr/zshcp) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-03-04 - A lightweight and intuitive clipboard management plugin for Zsh that enhances your command-line workflow with easy copy-paste operations.
* [zshrc-sync](https://github.com/Skylor-Tang/zshrc-sync) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-05-06 - Detects changes to `.zshrc` and pushes them to github when `zsh` exits.
* [zsnapshot](https://github.com/zdharma-continuum/zsnapshot) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-04-16 - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [ai-cmd](https://github.com/shanemcd/ai-cmd) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-12-12 - Generate shell commands from natural language using LLMs via [Claude Code](https://docs.anthropic.com/en/docs/claude-code) or [Ollama](https://ollama.ai/).
* [allergen](https://github.com/stanislas/allergen) ⭐ 3 | 🐛 2 | 🌐 Emacs Lisp | 📅 2024-03-12 - A collection of custom ZSH plugins to use with Antigen.
* [autodark (cravend)](https://github.com/cravend/autodark) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-09-17 - Switches between user-specified light and dark themes. Only works on macOS.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-02-10 - Adds helper functions for `aws` command. Includes mfa and `assume-role` helpers.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-06-18 - Boost your productivity with `aws-upload`.
* [aws](https://github.com/apachler/zsh-aws) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-12-09 - Forked from the original [oh-my-zsh](https://ohmyz.sh/) [aws](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes completions for `awscli` and a few utilities for managing AWS profiles and displaying them in your prompt.
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-01-23 - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [azure-subscription](https://github.com/dmakeienko/azure-subscription-prompt) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-09-26 - Displays information about the Azure current Subscription and tenant.
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-11-03 - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [bws](https://github.com/elogiclab/zsh-bws) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-10-04 - Simplify and improve the retrieval of secrets from the [Bitwarden](https://bitwarden.com) Secret Manager.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-09-11 - `ssh` to a server when you accidentally `cd` to it.
* [cdh](https://github.com/johncassol/cdh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-01-09 - Allows users to manage and navigate through a history of directories they have visited. It maintains a history file of directories and provides several commands to interact with this history.
* [color-logging](https://github.com/p1r473/zsh-color-logging) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-11-03 - provides a really easy to use logging library with notifications for pushbullet and pushover, colorizes tools like `cat` and `ls` and provides a color library.
* [cycle-fav-dirs](https://github.com/cibinmathew/cycle-fav-dirs) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2023-12-29 - A plugin to cycle through your favourite directories.
* [dirbrowse](https://github.com/giovannilupi/dirbrowse/) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-04-06 - Customized version of the [dirbrowse](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/dircycle) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin in [oh-my-zsh](https://ohmyz.sh).
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2015-04-29 - Plugin for displaying the dirstack info on a single line.
* [diskfree](https://github.com/alex-crouch/zsh-diskfree/) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-04-09 - Displays the free space on your disk in your prompt.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-04-28 - A docker-machine plugin for ZSH.
* [env-secrets](https://github.com/singular0/zsh-env-secrets) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-07-02 - Automatically retrieves secrets from secure storage backends and exports them as environment variables during shell initialization. This eliminates the need to store sensitive information in plain text configuration files. Works with `pass` and the macOS keychain.
* [exa-ls](https://github.com/birdhackor/zsh-exa-ls-plugin) ⚠️ Archived - Adds aliases so that you can use [exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24 as a drop-in replacement for `ls` and `tree`.
* [fnm (wintermi)](https://github.com/wintermi/zsh-fnm) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Helper plugin for the fast and simple Node.js version manager [fnm](https://github.com/Schniz/fnm) ⭐ 23,769 | 🐛 364 | 🌐 Rust | 📅 2026-02-05.
* [fuzzy-wd](https://github.com/spodin/zsh-fuzzy-wd) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-23 - Adds fuzzy search for directories warped with the [WD](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/wd) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-01-09 - [Geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-10-05 - [Geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [git-clean-branch](https://github.com/gobriansteele/git-clean-branch) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-05-18 - Cleans up dead `git` branches.
* [git-commit-shortcuts](https://github.com/ashsajal1/git-commit-shortcuts) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-11-03 - Provides shortcuts for creating standardized `git` commit messages with emoji prefixes and consistent formatting.
* [git-is-clean](https://github.com/aubreypwd/zsh-plugin-git-is-clean) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-04-19 - This function will return true or false depending on if it finds out your `git` repo is dirty or not.
* [git-prompt-enhanced](https://github.com/LFabre/zsh-git-prompt-enhanced) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-12-03 - Provides a more granular information about a `git` repository.
* [going\_places](https://github.com/or17191/going_places) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-05-12 - A plugin that helps to use, create and maintain a list of shell locations.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-12-02 - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/).
* [haiku](https://github.com/alesr/oh-my-zsh-haiku-plugin) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-03-29 - Prints a haiku promoting work-life balance and stress management once every 24 hours when the terminal is open.
* [hist-delete](https://github.com/p1r473/zsh-hist-delete-fzf/) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2025-04-14 - Delete history items from zsh's [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 Ctrl+R history search.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2019-12-02 - Captures the `PageUp` key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
* [journal](https://github.com/onurhanak/zsh-journal) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-06-08 - Lets you attach notes to shell commands you have run. Handy for remembering what a oneliner was actually doing when you look back at it later.
* [kubectl-config-switcher](https://github.com/chmouel/kubectl-config-switcher/) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-10-18 - Switch between config files in `~/.kube` via the `KUBECTL` environment variable.
* [lazy-load](https://github.com/goarano/zsh-lazy-load) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-08-06 - Lazy load tab completions only when you actually need them.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) ⭐ 3 | 🐛 4 | 🌐 Python | 📅 2026-01-08 - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) ⭐ 2,224 | 🐛 84 | 🌐 Java | 📅 2026-02-07 development.
* [macos (joow)](https://github.com/joow/macos) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-09-05 - A ZSH plugin for macOS.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-10-08 - A ZSH plugin for switching command line between normal mode and `vi` mode.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2017-01-08 - ZSH plugin for monorepo management.
* [more-hooks-for-git](https://github.com/capsulescodes/more-hooks-for-git) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-04-14 - Adds extra hooks for `git add`, `git diff` and `git status`.
* [mouse-status](https://github.com/gryffyn/mouse-status) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2020-02-27 - Changes mouse color based on status code, uses libratbag.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-08-26 - Allows fast switching between `maven` configurations.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-03-11 - Open/Create projects in Jetbrains.
* [packer](https://github.com/BreakingPitt/zsh-packer) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-08-24 - Adds aliases and auto-completes for Hashicorp [packer](https://www.packer.io/).
* [pgconnect](https://github.com/ruslan-korneev/pgconnect-zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-08-10 - Provides an easy way to manage and connect to PostgreSQL databases using `pgcli` and [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 for a seamless command-line experience.
* [pnpm (mat2ja)](https://github.com/mat2ja/pnpm.plugin.zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-01-24 - Better [pnpm](https://pnpm.io/) aliases.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-01-09 - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks) ⭐ 281 | 🐛 8 | 🌐 Shell | 📅 2024-02-15.
* [pr-return](https://github.com/zpm-zsh/pr-return) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-05-02 - Plugin for ZSH which displays the exit status of the last command run.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-02-03 - Plugin for lazy-loading `pyenv` in ZSH.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2020-08-14 - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) ⭐ 345 | 🐛 24 | 🌐 Shell | 📅 2025-09-04 plugin.
* [shelf](https://github.com/ecmma/shelf) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-10-17 - Utility which can be used to bookmark and access directly any file using mnemonics.
* [skim (hackerchai)](https://github.com/hackerchai/skim-zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-05-24 - Adds support for [skim](https://github.com/lotabout/skim) ⭐ 6,533 | 🐛 29 | 🌐 Rust | 📅 2026-02-06
* [sops-crypt](https://github.com/chaosimpact/sops-crypt) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-09-24 - Plugin for Mozilla SOPS that provides one-click encryption and decryption of files in the current directory and subdirectories.
* [tailf](https://github.com/rummik/zsh-tailf) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-12-01 - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2016-07-27 - A plugin that calculates and displays how many commands have been run via terminal.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-03-28 - Adds convenience aliases for [terraform](https://terraform.io/), along with completions for `terraform` and `terragrunt`.
* [tfenv](https://github.com/CDA0/zsh-tfenv) ⭐ 3 | 🐛 2 | 🌐 Shell | 📅 2024-04-16 - Installs, updates, and loads `tfenv` inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv) ⭐ 52 | 🐛 1 | 🌐 Shell | 📅 2021-06-24
* [tmux-sessionizer](https://github.com/nikevsoft/tmux-sessionizer) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-01-15 - [tmux](https://tmux.github.io) sessionizer as seen on ThePrimeagen.
* [unraid](https://github.com/donbuehl/zsh-unraid) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-09-13 - Adds convenient aliases and functions for managing your Unraid server directly from the command line.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-08-28 - Extends the functionality of the original [oh-my-zsh](https://ohmyz.sh/) `venv` module.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-04-29 - Provides ZSH functions to ease the management of your virtual environments using `venv`.
* [volta](https://github.com/ri7nz/zsh-volta) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2021-06-29 - Installs and loads [Volta: JS Toolchains as Code](https://github.com/volta-cli/volta) ⭐ 12,773 | 🐛 334 | 🌐 Rust | 📅 2025-11-15.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-01-26 - Plugin for [Visual Studio Code](https://code.visualstudio.com/) on macOS.
* [wordle](https://github.com/zechris/zwordle) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-05-01 - Wordle for ZSH, with tab-completions.
* [zapmarks](https://github.com/iliutaadrian/zapmarks) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-01 - Provides quick access to your most used command-line bookmarks. It allows you to save, search, and execute complex commands with ease.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2015-06-16 - Make `compinit` run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,519 | 🐛 41 | 🌐 Shell | 📅 2021-07-21.
* [zinit-annex-default-ice](https://github.com/zdharma-continuum/zinit-annex-default-ice) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2023-04-16 - Allows user to define ices active for multiple zinit commands.
* [zinit-annex-patch-dl](https://github.com/zdharma-continuum/zinit-annex-patch-dl) ⭐ 3 | 🐛 2 | 🌐 Shell | 📅 2025-02-15 - [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that downloads files and applies patches through the provided `dl` and `patch` zinit ices.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-06-30 - Provides a function that automatically shames the user for forgetting they weren't in `vim`.
* [ztouch](https://github.com/mjrafferty/ztouch) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2021-11-01 - Adds touchbar controls for recent history commands, directory stack, cycling between modes and user-mappable commands to the touchbar on macOS.
* [abbr-preview](https://github.com/cohml/zsh-abbr-preview) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-19 - Previews [abbr](https://github.com/olets/zsh-abbr) ⭐ 734 | 🐛 14 | 🌐 Shell | 📅 2026-02-06 abbreviations as you type.
* [arc-search](https://github.com/michaelsousajr/zsh-arc-search) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-01-29 - Enables quick searches using Arc browser directly from your terminal. Features URL encoding for search terms.
* [ask-opencode](https://github.com/andreacasarin/zsh-ask-opencode) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-31 - Integrates OpenCode AI with your shell, allowing you to generate shell commands using natural language. Press `Ctrl+O` to transform any text in your command line into optimized shell commands.
* [aur-install](https://github.com/redxtech/zsh-aur-install) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-06-18 - Small plugin to install packages from the AUR.
* [awsume](https://github.com/Sordie/AWSume) ⚠️ Archived - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) ⭐ 21 | 🐛 39 | 🌐 Python | 📅 2026-01-21 profile.
* [azcli](https://github.com/dmakeienko/azcli) ⚠️ Archived - Helper for using the Azure cli tools.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) ⚠️ Archived - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-05-26 - A plugin to toggle prepending `optirun` in the command line.
* [caper-bush](https://github.com/kobylinski/caper-bush) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-12-03 - Enhances Git's tab autocomplete by using AI to generate concise, context-aware summaries of staged changes for thoughtful commit messages. Requires and OpenAI key, `jq` and `yq`.
* [ccusage](https://github.com/hydai/zsh-ccusage) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-08-14 - Displays real-time AI usage costs from the `ccusage` CLI tool directly in your terminal prompt.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-10-13 - A ZSH plugin to `cd` to the current repository checkout's root directory.
* [clean-history](https://github.com/Automaat/zsh-clean-history) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-02-03 - Smart ZSH history cleanup plugin that automatically removes typos and failed commands based on similarity analysis. Removes failed commands similar to successful ones, finds rare commands similar to common variants, automatically captures command success/failure, adjusts similarity thresholds and behavior & creates backups before cleaning.
* [coffee-time](https://github.com/gakimball/zsh-coffee-time) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-05-29 - Adds the `caf` alias, which runs `caffeinate -dims`. The extra flags keep everything awake: the system, the drive, and the display.
* [conda-init](https://github.com/commiyou/conda-init-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-08-01 - Cleans up environment variables so [conda](https://conda.io) doesn't mess up `tmux`.
* [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-02-14 - Provides a `condaenv_prompt_info` function which returns the current `conda` environment name.
* [cvideo](https://github.com/aubreypwd/zsh-plugin-cvideo) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-08-11 - Quickly compress video with `ffmpeg`.
* [databricks](https://github.com/SlavaYakovenko/zsh-databricks) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-09-13 - Enhanced Databricks CLI integration for Zsh with convenient aliases and profile management.
* [ddev](https://github.com/voronkovich/ddev.plugin.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-04-03 - A ZSH plugin for the [ddev](https://github.com/drud/ddev) ⭐ 3,480 | 🐛 142 | 🌐 Go | 📅 2026-02-07 tool for setting up PHP development environments.
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-08-29 - Simple [oh-my-zsh](https://ohmyz.sh/) plugin for installing the chromium depot\_tools. Installing this plugin will add all of the chromium depot\_tools to your `$PATH` automatically.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-10 - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized) ⭐ 2,868 | 🐛 1 | 🌐 Makefile | 📅 2025-09-22.
* [editing-workbench](https://github.com/commiyou/zsh-editing-workbench) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-11-02 - Adds sane, complex command line editing (e.g. incremental history word completion).
* [ez-cmd](https://github.com/akgarhwal/ez-cmd) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-03-04 - Simplifies and streamlines common command-line tasks by providing easy-to-use shortcuts and aliases.
* [fnm (sukkaw)](https://github.com/SukkaW/zsh-fnm) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-31 - Provides enhancement to the Node.js version manager [`fnm`](https://fnm.vercel.app).
* [fzf (scaryrawr)](https://github.com/scaryrawr/fzf.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-12 - Adds keybindings for [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 inspired by [PatrickF1/fzf.fish](https://github.com/PatrickF1/fzf.fish) ⭐ 2,521 | 🐛 2 | 🌐 Shell | 📅 2025-11-20.
* [fzf-git-worktree](https://github.com/banyan/zsh-fzf-git-worktree) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-07-18 - Manage `git` worktrees with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 integration.
* [fzf-packagemanager](https://github.com/goarano/zsh-fzf-packagemanager) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-10-01 - Adds commands for installing tools via various package managers using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. Supports `apt`, `brew` & `dnf`.
* [fzf-plugin](https://github.com/Atlas34/fzf-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-01-07 - [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02's [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 plugin extracted so it can be used easily with other plugin managers.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-10-17 - [Geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-10-05 - [Geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 plugin to display the current folder's npm package version.
* [ghost-zeus](https://github.com/fontno/ghost_zeus) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2014-10-03 - Lets you use [zeus](https://github.com/burke/zeus) ⭐ 3,323 | 🐛 103 | 🌐 Go | 📅 2024-09-11 with normal rails commands.
* [gimbo-git](https://github.com/gimbo/gimbo-git.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-17 - A subset of the [oh-my-zsh](https://ohmyz.sh/) [git plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/git/git.plugin.zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 aliases, plus some new aliases, plus a few handy functions.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) ⚠️ Archived - Manage [Go](https://golang.org/) installations with [gimme](https://github.com/travis-ci/gimme/) ⭐ 711 | 🐛 36 | 🌐 Shell | 📅 2024-09-06.
* [github](https://github.com/shakir-abdo/zsh-github-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-09-12 - Fork of the original [GitHub plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/github) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 embedded in [oh-my-zsh](https://ohmyz.sh/).
* [hebzsh](https://github.com/admons/hebzsh) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2025-08-26 - If a command is not found as typed in Hebrew, translates the command as if it was typed on a keyboard with a US English layout and tries again.
* [jap](https://github.com/philipstuessel/jap) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-17 - Terminal automation framework.
* [kittyback](https://github.com/pickle-slime/kittyback) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-04-10 - Automatically updates and modifies the background image for the `kitty` terminal emulator.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2016-06-22 - Toggle konsole theme from ZSH.
* [lacrimae](https://github.com/caIamity/lacrimae) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-02-28 - Prints a line from a collection of chants.
* [life-progress](https://github.com/bGZo/life-progress) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-01-11 - Shows your life progress in days, weeks, months, and age.
* [line-bisect](https://github.com/Hoid/line-bisect) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-11-06 - Allows you to move your cursor in your terminal by bisecting the current command left or right with a single keystroke.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-09-24 - Add shortcuts to your favorite directories.
* [lsd (tankeryang)](https://github.com/tankeryang/zsh-lsd) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-06-12 - Replaces `ls` and `tree` commands with [lsd](https://github.com/Peltoche/lsd) ⭐ 15,413 | 🐛 186 | 🌐 Rust | 📅 2025-12-09.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-04-28 - Extracted from [oh-my-zsh](https://ohmyz.sh) so you can use it without the rest of oh-my-zsh.
* [mycli](https://github.com/remino/omz-plugin-mycli-alias) ⚠️ Archived - Add alias for [`mycli`](https://www.mycli.net) with login path.
* [myservice](https://github.com/jarlor/zsh-myservice) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-07-28 - Designed to help you manage custom systemd services and Docker containers more conveniently. This plugin provides user-friendly commands to list and check the status of your custom services and Docker containers straight from your command line.
* [newvwp](https://github.com/aubreypwd/zsh-plugin-newvwp) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-07-13 - Spins up a new WordPress site using Valet.
* [nhl-schedule](https://github.com/Matt561/zsh-nhl-schedule) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-04-18 - Retrieves and displays the NHL schedule.
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-03-25 - Uses `nvm` to install new versions and modules for the current project.
* [nodenv (mattberther)](https://github.com/mattberther/zsh-nodenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-03-31 - Installs, updates and loads `nodenv`. Inspired by [zsh-rbenv](https://github.com/Meroje/zsh-rbenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-02-18.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-11-17 - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin.
* [oh-my-gpt](https://github.com/vicotrbb/oh-my-gpt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-09-25 - Provides an easy-to-use interface for interacting with OpenAI's GPT models directly from your terminal. It allows you to send queries, analyze files, and get AI-powered assistance for various tasks.
* [omz-git](https://github.com/aeons/omz-git) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-04-11 - [Oh-My-ZSH](https://ohmyz.sh/)'s [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin re-packaged to be standalone.
* [paci](https://github.com/iloginow/zsh-paci) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-01-19 - Plugin for arch linux package managers.
* [penmux](https://github.com/mfulz/zsh-penmux) ⚠️ Archived - A session manager plugin meant to be used for penetration testing sessions and tracking the terminal sessions to be used in reports.
* [pew](https://github.com/shosca/zsh-pew) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2019-08-07 - Sets up and manages Python virtualenvs using [pew](https://github.com/berdario/pew) ⭐ 1,164 | 🐛 53 | 🌐 Python | 📅 2024-05-28 and automatically switches virtualenvs as you move directories.
* [php-version-switcher](https://github.com/Akollade/php-version-switcher.plugin.zsh) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2025-02-26 - Changes php versions if a `.php-version` file is found.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2017-05-07 - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer) ⭐ 10,791 | 🐛 269 | 🌐 PHP | 📅 2024-04-01.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2015-02-17 - ZSH plugin for Rails.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-08-02 - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-11-26 - Creates a global variable with `git` status information that can be displayed in prompts.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-02-28 - Converts raw seconds into human-readable strings.
* [pyenv (xlshiz)](https://github.com/xlshiz/pyenv-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-02-26 - Loads [pyenv](https://github.com/pyenv/pyenv) ⭐ 44,223 | 🐛 56 | 🌐 Shell | 📅 2026-02-04 into the current shell and provides prompt info via the `pyenv_prompt_info` function. Also loads [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) ⭐ 6,716 | 🐛 101 | 🌐 Shell | 📅 2025-12-18 if available.
* [pyvenv-fast](https://github.com/ACmyles/pyvenv-fast) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-02-19 - Launch a Python `venv` with one command. Designed for use with [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-03-27.
* [qiime2](https://github.com/misialq/zsh-qiime2) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-12-09 - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
* [rbenv (meroje)](https://github.com/Meroje/zsh-rbenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-02-18 - Inspired by <https://github.com/lukechilds/zsh-nvm/> ⭐ 2,387 | 🐛 30 | 🌐 Shell | 📅 2024-07-03, makes it easier to work with ruby `rbenv` environments.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-07-17 - Displays random riddles.
* [robo](https://github.com/shengyou/robo-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-02-05 - A ZSH plugin for [Robo](https://github.com/consolidation/robo/) ⭐ 2,705 | 🐛 182 | 🌐 PHP | 📅 2025-11-14.
* [rvm](https://github.com/johnhamelink/rvm-zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2013-04-27 - Initiates [rvm](https://github.com/rvm/rvm) ⭐ 5,189 | 🐛 552 | 🌐 Shell | 📅 2026-02-03 and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [show-path](https://github.com/redxtech/zsh-show-path) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-06-22 - Provides a function shows the `$PATH` line by line.
* [skim (casonadams)](https://github.com/casonadams/skim.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-02-19 - Tries to determine where [skim](https://github.com/lotabout/skim) ⭐ 6,533 | 🐛 29 | 🌐 Rust | 📅 2026-02-06 is installed, then enables its fuzzy auto-completion and key bindings.
* [spaceship-ocm](https://github.com/iamkirkbater/spaceship-ocm-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-09-28 - Queries your OpenShift Cluster Manager (ocm) configuration to show which environment you're connected to. Requires [NerdFont](https://www.nerdfonts.com/font-downloads) in your terminal.
* [spack](https://github.com/Game4Move78/zsh-spack) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-11-06 - Includes some useful aliases and functions for loading/unloading [Spack](https://github.com/spack/spack) ⭐ 4,947 | 🐛 1,726 | 🌐 Python | 📅 2026-02-06-generated modules. As it makes use of the `module` command it is much more efficient than `spack load`.
* [ssh-quickconnect](https://github.com/breda/zsh-ssh-quickconnect) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-05-02 - Simple utility to quickly connect to hosts from your `ssh` config & `known_hosts` file.
* [switch-git](https://github.com/robin-mbg/switch-git) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-04-23 - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
* [t32](https://github.com/chrissicool/zsh-t32) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2014-06-01 - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title (p1r473)](https://github.com/p1r473/tab-title/) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-05-24 - Rename [tmux](https://github.com/tmux/tmux/wiki) ⭐ 41,448 | 🐛 37 | 🌐 C | 📅 2026-02-02 and [screen](https://www.gnu.org/software/screen/manual/screen.html) panes and windows.
* [tasko](https://github.com/knid/tasko) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-07-24 - Allows you to annotate [TaskWarrior](https://github.com/GothenburgBitFactory/taskwarrior) ⭐ 5,521 | 🐛 438 | 🌐 C++ | 📅 2026-02-06 tasks.
* [tempit](https://github.com/idirxv/tempit) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-01-07 - Helps you create, manage, and navigate temporary directories with ease. It provides a persistent tracking system so your temporary directories won't get lost.
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-07-17 - Installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher) ⭐ 1,453 | 🐛 9 | 🌐 Go | 📅 2026-02-06.
* [todotxt](https://github.com/Neluji/omz-todotxt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-04-17 - Adds aliases for [todo.sh](https://github.com/benignoc/alfred-todotxt/) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2013-09-22.
* [traista](https://github.com/exaluc/traista) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-03-13 - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-06-19 - Ubuntu 16 aliases.
* [uncloudium](https://github.com/Talon1024/omz-uncloudium) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-01-03 - Adds helper script to download crx files from the Google Chrome web store.
* [up-dir](https://github.com/sgpthomas/zsh-up-dir) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-04-01 - Binds `ctrl-h` to navigating up a directory. This makes it very easy to go up a few directories without having to type any commands.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) ⭐ 2 | 🐛 2 | 🌐 Shell | 📅 2021-04-13 - A wrapper plugin for [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-01-24 - A modified virtualenv ZSH plugin for [oh-my-zsh](https://ohmyz.sh).
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-04-13 - Simple plugin to open [Visual Studio Code](https://code.visualstudio.com/) a little more easily across systems.
* [vscode-shell-integration](https://github.com/tolkonepiu/vscode-shell-integration-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-08-05 - automatically activates [VS Code shell integration](https://code.visualstudio.com/docs/terminal/shell-integration) when working in VS Code terminals.
* [warrior](https://github.com/OfferPi/zsh-warrior) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-06-05 - Uses a local large language model ([Ollama](https://ollama.com/)) to translate natural-language into ZSH commands.
* [web-search (yabanahano)](https://github.com/Yabanahano/web-search) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-12-05 - Adds aliases for searching with Google, Wiki, Bing, YouTube and other popular services.
* [wsl](https://github.com/florentinl/omz-wsl) ⚠️ Archived - Adds helper functions to make it easier to work in ZSH when running inside WSL.
* [xdg-basedirs](https://github.com/krahlos/xdg-basedirs) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-10 - sets up the XDG base directories according to the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/). This plugin ensures that your environment is configured properly for storing user data, cache,and configuration files.
* [youtube-dl](https://github.com/joow/youtube-dl) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-03-07 - Simple plugin for [youtube-dl](https://youtube-dl.org/).
* [zenv](https://github.com/janitha/zenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-08-22 - Isolated working shell enviornments per directory (like `direnv`, but uses a new shell instance to provide cleaner isolation).
* [zinit-annex-unscope](https://github.com/zdharma-continuum/zinit-annex-unscope) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2023-04-16 - Allows installing plugins for [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 without specifying the user name by querying the Github API.
* [zshrpg](https://github.com/aliervo/zshrpg) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-02-22 - A wrapper that fully integrates [rpg-cli](https://github.com/facundoolano/rpg-cli/) ⭐ 1,666 | 🐛 6 | 🌐 Rust | 📅 2025-05-03 with ZSH!
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-12-11 - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [adguard-helper](https://github.com/MohamedElashri/adguard-helper) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-11-19 - Simplies interaction with the [AdGuard VPN CLI](https://github.com/AdguardTeam/AdGuardVPNCLI) ⭐ 151 | 🐛 44 | 🌐 Shell | 📅 2026-01-29. It provides user-friendly commands that reduce the need to remember complex flags and commands by offering a more intuitive interface.
* [archlinux (fourdim)](https://github.com/fourdim/zsh-archlinux) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-19 - Defines helper functions for `pacman` on Arch Linux.
* [aws-vault-profiles](https://github.com/jonscheiding/zsh-plugin-aws-vault-profiles) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-08-15 - Plugin that integrates usage of [aws-vault](https://github.com/99designs/aws-vault) ⭐ 8,953 | 🐛 0 | 🌐 Go | 📅 2025-12-30 with the `$AWS_PROFILE` environment variable.
* [awsp](https://github.com/suonto/awsp-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-12-03 - AWS profile management for ZSH. Inspired by oh-my-zsh's [aws](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/aws/aws.plugin.zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin. Shows details of currently active AWS profile.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-11-07 Remaps vi-mode for the French [bépo](http://bepo.fr/wiki/Accueil) keyboard.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-06-11 - Manages `docker` on macOS.
* [brave](https://github.com/troykelly/oh-my-zsh-brave) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-23 - Manages [Brave](https://brave.com) profiles. With this plugin, you can start the Brave Browser with a specific user profile by using the brave command followed by the profile's name. The plugin also implements autocompletion for the profile names so you won't have to type the entire profile name manually.
* [brew-install](https://github.com/marceloclp/zsh-brew-install) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-12 - Installs and loads [brew](https://brew.sh) on WSL.
* [claude](https://github.com/HundredAcreStudio/zsh-claude) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-17 - AI-powered command suggestions and explanations for ZSH using Claude AI. Get intelligent shell command help with simple keybindings. Transform natural language into executable shell commands, or get detailed explanations of complex commands - all directly in your terminal with Claude AI integration.
* [conda (wardhanisukoco)](https://github.com/wardhanisukoco/zsh-plugin-conda/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-06-01 - Automatically loads `conda` and provides functions for detecting `conda` versions for use in themes.
* [cordova](https://github.com/andredestro/cordova-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-26 - Provides handy aliases for [Apache Cordova](https://cordova.apache.org/) commands, inspired by git-style shortcuts (gco, gcb, etc).
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh) ⚠️ Archived - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
* [deno (cowboyd)](https://github.com/cowboyd/zsh-deno) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-06-15 - Useful [deno](https://deno.land/) aliases and settings.
* [ding](https://github.com/jessetipton/ding) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-17 - Plays notification sounds when a long-running shell command completes.
* [disk-guard](https://github.com/TomfromBerlin/Zsh-Disk-Guard) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Warns you when you try to copy/move/rsync files and are running low on local disk space, and provides useful information and a nice progress bar for `cp` and `mv`.
* [drupal](https://github.com/yhaefliger/zsh-drupal) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-02-02 - Adds aliases for common tasks and also tab-completion for `drush`. Inspired by [Artisan](https://github.com/jessarcher/zsh-artisan) ⭐ 647 | 🐛 10 | 🌐 Shell | 📅 2025-12-08.
* [duration](https://github.com/rtakasuke/zsh-duration) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-10-09 - Displays command duration if it exceeds a user-settable run time.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-02-24 - Quickly insert escaped backticks when double-tapping "\`".
* [exa (todie)](https://github.com/todie/exa.plugin.zsh) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2022-09-22 - Integration and completions for [exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24, a modern replacement for `ls`.
* [eza-ls](https://github.com/birdhackor/zsh-eza-ls-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-17 - Adds aliases allowing [eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01, to act as a drop-in replacement for `ls` and `tree`.
* [ffexport](https://github.com/Pakrohk/ffexport.plugin.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-08 - Lightweight, ZSH-native video export manager — profile-driven [FFmpeg](https://www.ffmpeg.org) exports, persistent ZSH tab completion, profile import/export, and safe defaults for Instagram & YouTube workflows.
* [fzf (gimbo)](https://github.com/gimbo/fzf.zsh) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2025-11-26 - Helpers for using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 in ZSH. Requires [brew.sh](https://brew.sh).
* [fzf-nav](https://github.com/ivomac/zsh-fzf-nav) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-07 - Defines an interactive file/directory navigator using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. Offers multiple navigation modes, git integration, and customizable actions.
* [gdbm](https://github.com/zdharma-continuum/zgdbm) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2023-04-16 - Adds GDBM as a plugin.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) ⚠️ Archived - Plugin for fast downloading the jQuery library from [code.jquery.com](https://code.jquery.com).
* [git-arc](https://github.com/jlduran/git-arc-oh-my-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - Adds aliases and functions for [git-arc](https://github.com/freebsd/freebsd-src/tree/main/tools/tools/git) ⭐ 8,800 | 🐛 86 | 🌐 C | 📅 2026-02-07, a FreeBSD development tool.
* [git-commit-prefixer](https://github.com/dvigo/git-commit-prefixer) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-26 - Adds configurable prefixes and optional icons to `git` commit messages (supports styles, icon themes, and interactive selection)
* [git-gen](https://github.com/sharif3271/git-gen) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-05 - Handle `git` bulk branch delete and create operations.
* [git-graph](https://github.com/Maks0u/git-graph) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-06 - Adds a pretty `git` graph.
* [git-patch](https://github.com/marvinroman/oh-my-zsh-git-patch-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-06-09 - Adds custom functions and aliases to the oh-my-zsh `git` plugin.
* [git-plugin-cheatsheet](https://github.com/rhorno/oh-my-zsh-git-plugin-cheatsheet) ⭐ 1 | 🐛 2 | 🌐 Shell | 📅 2025-07-01 - Displays the aliases and functions available from the `git` oh-my-zsh plugin.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-10-06 - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-smart-commends-wrapper](https://github.com/jelek21/omz-git-smart-commands) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-03-02 - Wraps [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2020-08-12 to make it compatible with the [oh-my-zsh](https://ohmyz.sh) plugins system.
* [git-switch-branch-skim](https://github.com/okhiroyuki/zsh-git-switch-branch-skim) ⚠️ Archived - Allows you to switch `git` branches with [skim](https://github.com/lotabout/skim) ⭐ 6,533 | 🐛 29 | 🌐 Rust | 📅 2026-02-06
* [git-worktree (trthomps)](https://github.com/trthomps/git-worktree-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-20 - Enhanced `git worktree` management with bare repository support. This plugin provides convenient commands for working with `git` worktrees, making it easy to work on multiple branches simultaneously.
* [github-folders](https://github.com/buzuloiu/zsh-github-folders) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-03-09 - Organizes your GitHub checkouts for you.
* [goenv (cda0)](https://github.com/CDA0/zsh-goenv/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-01-26 - Plugin for installing, updating and loading `goenv`.
* [goenv (heyvito)](https://github.com/heyvito/goenv.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-05-29 - Automatically reads `.goenv` files in the current directory and sets `GOPRIVATE` environment variables.
* [golinks](https://github.com/slessans/oh-my-zsh-golinks-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-10-14 - Launch golinks from your terminal.
* [gpg](https://github.com/marvinroman/oh-my-zsh-gpg-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-06-09 - Adds helpful aliases for using `gpg`.
* [gsh](https://github.com/cjayross/gsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-18 - Collection of helper functions for `git`
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) ⭐ 1 | 🐛 1 | 📅 2013-08-09 - Provides autocompletion for `gvm` (Groovy enVironment Manager).
* [historikeeper](https://github.com/stiliajohny/historikeeper) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-11-22 - Captures history in a database.
* [hypnosnek](https://github.com/josephcourtney/hypnosnek) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-14 - Simple utilities with p10k integration for managing `python` environments.
* [ipnav](https://github.com/clebertmarctyson/oh-my-zsh-ipnav) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-23 - Provides convenient aliases and completions for IP address operations [ip-navigator-cli](https://github.com/clebertmarctyson/ip-navigator-cli) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-08.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) ⭐ 1 | 🐛 3 | 🌐 Shell | 📅 2020-08-06 - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-02 - KitsuneBook plugin for [oh-my-zsh](https://ohmyz.sh).
* [kubectlenv](https://github.com/rafalmasiarek/oh-my-zsh-kubectlenv-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-30 - Easily switch between multiple `kubectl` versions.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-07-17 - Installs and loads [kubectx](https://github.com/ahmetb/kubectx) ⭐ 19,444 | 🐛 75 | 🌐 Go | 📅 2025-01-22.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) ⚠️ Archived - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-08-22 - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-08-06 - Keeps track of the last used working directory globally and per [tmux](https://github.com/tmux/tmux) ⭐ 41,448 | 🐛 37 | 🌐 C | 📅 2026-02-02 session and automatically jumps into it for new shells.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-07-26 - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [mac-packaging](https://github.com/Temikus/mac-packaging) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-11-28 - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) ⚠️ Archived - A fork of the [oh-my-zsh](https://ohmyz.sh/) maven plugin.
* [media-sync](https://github.com/redxtech/zsh-media-sync) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-07-20 - A plugin to facilitate copying media between two `rclone` locations.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-02-12 - Renames month names to numbers in filenames.
* [nerd-font-check](https://github.com/delorenj/nerd-font-check) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-30 - Offers to install [Nerd Fonts](https://www.nerdfonts.com/font-downloads) with [brew](https://brew.sh/) if not present.
* [npm (zfben)](https://github.com/zfben/zsh-npm) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-02-20 - Use `n` as `npm` aliases with `noglob` prefix and more. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin.
* [nvm-auto-use (jrr997)](https://github.com/jrr997/zsh-nvm-auto-use) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-06-13 - Automatically manages your Node.js versions with [nvm](https://github.com/nvm-sh/nvm) ⭐ 91,514 | 🐛 372 | 🌐 Shell | 📅 2026-01-29 based on your current directory.
* [nvm-pnpm-auto-switch](https://github.com/spencerbeggs/zsh-nvm-pnpm-auto-switch) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-08 - Automatically switches Node.js versions (using `nvm`) and manages pnpm package manager versions (using `corepack`) when changing directories.
* [opencode](https://github.com/verlihirsh/zsh-opencode-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-20 - Stop googling shell commands. Just describe what you want in plain English, press Tab, and get the exact command you need.
* [org-hopper](https://github.com/hjdarnel/org-hopper/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-02 - Wraps the GitHub CLI with [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05. It allows you to quickly jump between repositories a given GitHub organization, cloning it to a predefined location if the local copy doesn't already exist.
* [pack](https://github.com/fourdim/zsh-pack/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-05-13 - Pack your source code with ZSH.
* [penv](https://github.com/Nhqml/penv-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-07 - Manages `uv` Python virtual environments stored in `~/.local/share/py-venv/`. Supports subcommands for listing, activating (shell and directory level), creating, deleting and explaining why an env is activated. Makes it easier to replace `pyenv` and `poetry` with `uv`.
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2021-07-07 - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pipe](https://github.com/pipe-felipe/zsh-pipe-plugin) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2025-12-31 - A powerful ZSH plugin featuring **cross-distro system updates** and **cleanup** (supports `apt`, `dnf`, `pacman`, `zypper`, `homebrew`, and more), Docker container/volume management, and development environment enhancements. Simplifies system maintenance across multiple Linux distributions with intuitive commands. Extensible through a simple configuration system - see project README for details.
* [pkenv](https://github.com/ptavares/zsh-pkenv) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-07-17 - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git) ⭐ 68 | 🐛 2 | 🌐 Shell | 📅 2023-05-31.
* [plenv](https://github.com/TwoPizza9621536/zsh-plenv) ⚠️ Archived - Plugin for the perl [plenv](https://github.com/tokuhirom/plenv) ⭐ 530 | 🐛 30 | 🌐 Shell | 📅 2025-08-19 version manager based on jenv.
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2013-10-07 - Adds ibtool shortcuts to generate localized XIB files.
* [ppsmon](https://github.com/mzpqnxow/ppsmon) ⭐ 1 | 🐛 0 | 🌐 Makefile | 📅 2020-08-29 - Reads `/sys/class/net/$interface/` to keep track of packet transmission rates. It stores the current rate to a file in the RAM backed filesystem where it can be easily accessed for display in a shell-prompt. Linux-only due to use of `/sys`.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-11-15 - Creates an environment variable which can be used to display background job information in a custom prompt.
* [pr-user](https://github.com/zpm-zsh/pr-user) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-08-02 - Creates a global variable that can be used in prompts.
* [printdocker](https://github.com/elvitin/printdocker-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-06-23 - Pretty print [docker](https://docker.com) objects.
* [prompt-dir-perms](https://github.com/xPMo/zsh-prompt-dir-perms) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-11-07 - Creates a segment displaying the permissions of the current directory you can use in your ZSH prompt.
* [proxy-plugin (xooooooooox)](https://github.com/xooooooooox/zsh-proxy) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-27 - Helps manage proxy settings in your shell environment.
* [psgrep](https://github.com/voidzero/omz-plugin-psgrep/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-12-23 - Makes `ps grep` hide its own process from the results of a `ps aux | grep`.
* [pycalc (alalik)](https://github.com/alalik/pycalc) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-22 - Turns the `=` key into a powerful, Python‑backed calculator in your ZSH shell.
* [pycalc (peibozhao)](https://github.com/peibozhao/pycalc) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-29 - ZSH calculator that uses Python syntax.
* [rura](https://github.com/kiki-ki/rura) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-12-06 - A simple ZSH plugin to save and jump to directories.
* [rust (betterfetch)](https://github.com/betterfetch/zsh-plugin-rust) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-09-04 - Provides convenient aliases for working with Rust's Cargo, Rustc, and Rustup tools.
* [rust (cowboyd)](https://github.com/cowboyd/zsh-rust) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-01-29 - Configure your [rust](https://www.rust-lang.org/) toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2016-12-14 - Show current `chroot` name in your prompt.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-01-28 - Adds keybindings to do global search and replace on current command line.
* [select-history-skim](https://github.com/okhiroyuki/zsh-select-history-skim) ⚠️ Archived Rummage through your history with [skim](https://github.com/lotabout/skim) ⭐ 6,533 | 🐛 29 | 🌐 Rust | 📅 2026-02-06.
* [setpath](https://github.com/mys721tx/set_path) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-26 - Adds some local paths to your `fpath` and `$PATH`.
* [shell-proxy](https://github.com/caesar0301/zsh-shell-proxy) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-05-07 - This a pure user-space program, shell-proxy setter, written in Python3 and `zsh`.
* [skaffold](https://github.com/todie/skaffold.plugin.zsh) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2022-07-30 - ZSH integration and completions for [skaffold](https://skaffold.dev) local kubernetes development environment.
* [snr](https://github.com/raisedadead/zsh-snr) ⚠️ Archived - Passes the selected output of the first command to the next.
* [some-peco](https://github.com/MoeBensu/zsh-some-peco/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-11-26 - Enhances your command-line experience with [peco](https://github.com/peco/peco) ⭐ 7,855 | 🐛 52 | 🌐 Go | 📅 2025-11-09 i.e. providing quick directory navigation and history search.
* [sshinfo](https://github.com/SckyzO/zsh-sshinfo) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2026-01-15 - displays resolved SSH connection details (like the final hostname, port, user, and proxies) before connecting. This is useful for verifying your SSH configuration, especially when dealing with complex setups involving aliases, proxies, or multiple configuration files.
* [sshpky](https://github.com/jeffzhangc/sshpky_zsh_plugin) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-09 - Auto updates git-repositories in the `$ZSH_CUSTOM` folder.
* [sudo-previous-current](https://github.com/chmouel/zsh-sudo-previous-current) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-09-15 - Add a `sudo` to the current line or to the previous command. It tries hard to keep the current cursor position so your flow doesn't get disturbed.
* [system-update](https://github.com/cnlee1702/zsh-system-update) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-26 - A smart, efficient system update plugin for [oh-my-zsh](https://ohmyz.sh/) that handles APT packages, Conda environments, and pip installations with intelligent caching to minimize update times.
* [telepresence](https://github.com/alexgervais/telepresence-ps1) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-10-04 - Add the current [Telepresence](https://www.telepresence.io/) connection status and context to your ZSH prompt.
* [tfaws](https://github.com/jmischler72/tfaws) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-08 - Simplifies context switching between AWS and Terraform. Offers automatic AWS SSO login, automatic profile switching using a `.awsprofile` file, and links terraform workspace/folders to profiles.
* [tgenv](https://github.com/ptavares/zsh-tgenv) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-12 - Installs and loads [tgenv](https://github.com/cunymatthieu/tgenv.git) ⭐ 232 | 🐛 32 | 🌐 Shell | 📅 2023-10-08. Includes a function to manually update `tgenv`.
* [tgswitch](https://github.com/ptavares/zsh-tgswitch) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-07-17 - Installs and loads [tgswitch](https://github.com/warrensbox/tgswitch) ⭐ 161 | 🐛 22 | 🌐 Go | 📅 2024-04-19.
* [tig](https://github.com/MenkeTechnologies/zsh-tig-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-11-04 - Adds a few advanced bindings for [tig](https://github.com/jonas/tig) ⭐ 13,091 | 🐛 205 | 🌐 C | 📅 2025-12-06 and also provides a `tig-pick` script.
* [time-tracker](https://github.com/mike-fam/time-tracker-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-12-04 - Automatically tracks time spent on `git` branches across multiple repositories. Perfect for developers who want to understand their time allocation across different projects and branches.
* [tmux (zsh-contrib)](https://github.com/zsh-contrib/zsh-tmux) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-12-18 - Plugin for [tmux](https://tmux.github.io). Includes automatic window title updates based on running command, command name display during execution, job reference resolution (fg, %1) to actual command names and automatic title truncation (max 20 characters).
* [toolbox](https://github.com/paxcoder/zsh-toolbox) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2023-06-11 - Automagically updates [homebrew](https://brew.sh) plugins. Allows enabling/disabling notice during startup and alias setup.
* [tre](https://github.com/redxtech/zsh-tre) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-07-06 - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) ⭐ 1,162 | 🐛 20 | 🌐 Rust | 📅 2024-09-03 easier.
* [unix-simple](https://github.com/redxtech/zsh-unix-simple) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-06-17 - A command that shows a graphic about the simplicity of unix.
* [venvs](https://github.com/pawnhearts/venvs) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-04-29 - Automatically switches Python virtualenvs. Supports both venvs in project folder(`~/myproject/venv`) and in global folder (like `~/.virtualenvs`)
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) ⚠️ Archived - An [oh-my-zsh](https://ohmyz.sh/) plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [vivi](https://github.com/rufevean/vivi) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-10 - Integrates Google's [Gemini](https://gemini.google.com) language model (LLM) capabilities directly into your terminal. It allows you to send queries to the language model and receive AI-generated solutions, all within your terminal. The plugin supports session context and can dynamically execute received commands.
* [vtex](https://github.com/xdigu/zsh-vtex) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-12-07 - Adds helper aliases for [vtex](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-command-reference#default-commands) cli commands.
* [westchange](https://github.com/TomiVidal99/westchange) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-18 - Allows you to quickly change between directories. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [whisp](https://github.com/jaacob/whisp) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-21 - Adds idempotency and convenience features to OpenAI's Whisper CLI tool. It helps you efficiently transcribe audio files without duplicating work.
* [wpm](https://github.com/btror/wpm) ⭐ 1 | 🐛 12 | 🌐 Shell | 📅 2024-11-17 - Lets you test your typing speed in a terminal, track WPM, accuracy, and more. Results are saved in a handy JSON format for easy tracking.
* [wsl2-ssh-pageant](https://github.com/antoinemartin/wsl2-ssh-pageant-oh-my-zsh-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-28 - Use your Yubikey stored GPG keys from WSL. This packages the instructions from [wsl2-ssh-pageant repo](https://github.com/BlackReloaded/wsl2-ssh-pageant) ⚠️ Archived as a ZSH plugin.
* [zinfo\_line](https://github.com/kmhjs/zinfo_line) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-02-14 - Makes more information available to ZSH themes.
* [znotify](https://github.com/rudeigerc/znotify) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-09-07 - A simple plugin for sending notifications to other services.
* [znvm](https://github.com/Ajnasz/znvm) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-07-22 - A [Node.js](https://nodejs.org) version manager for ZSH similar to [nvm.sh](https://github.com/nvm-sh/nvm) ⭐ 91,514 | 🐛 372 | 🌐 Shell | 📅 2026-01-29 but faster.
* [zoc](https://github.com/TomerG2/zoc) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-10-29 - Speeds up OpenShift `oc` logins and token renewal.
* [zplug-blame](https://github.com/jkcdarunday/zplug-blame) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-08-06 - A [zplug](https://github.com/zplug/zplug) ⭐ 5,990 | 🐛 150 | 🌐 Shell | 📅 2024-06-12-specific plugin that displays how long each of your plugins took to load.
* [zwirl](https://github.com/chordflower/zwirl) ⭐ 1 | 🐛 0 | 🌐 Roff | 📅 2025-12-01 - Adds aliases for `git` and `eza`.
* [zypper-short](https://github.com/justanotherinternetguy/zypper-short) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-27 - Plugin for OpenSuse Tumbleweed's package manager, `zypper`.
* [adonisjs](https://github.com/baliestri/adonisjs.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - Plugin for skipping the `node` part of the `ace` command.
* [auto-cenv](https://github.com/El3ssar/zsh-auto-cenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-01 - Automatically activates the conda environment when entering the project folder.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) ⚠️ Archived - Automatically switches to the node version specified in a given directory.
* [autodark (vbwx)](https://github.com/vbwx/zsh-autodark) ⚠️ Archived - Switches to another Terminal profile if dark mode is enabled (macOS-only).
* [autosuggestions-plugin](https://github.com/jumbojett/zsh-autosuggestions-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-20 - 🐟 [Fish](https://fishshell.com/)-style auto-suggestions in ZSH.
* [autoupdate-antibody](https://github.com/spikespaz/autoupdate-antibody-zsh) ⚠️ Archived - A fork of [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) ⭐ 27 | 🐛 2 | 🌐 Shell | 📅 2018-08-09 for the [Antibody](https://getantibody.github.io) plugin manager, with the added ability to cooperate with static loading.
* [autovenv (snovra-dev)](https://github.com/snovra-dev/zsh-autovenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-11-23 - Automatically activates Python virtual environments when entering their parent directory.
* [azure-keyvault](https://github.com/milespossing/Azure-Keyvault-Zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-02-04 - Makes using Azure keyvaults less verbose from the cli.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-09-06 - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-01-13 - Clone of `chruby` modified to make it easy to switch between multiple Go versions.
* [cleanzip](https://github.com/Xeferis/cleanzip) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-02 - Helps create zip files that don't have data that shouldn't be in there.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) ⭐ 0 | 🐛 0 | 📅 2013-11-21 - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [cwebp](https://github.com/adi-li/zsh-cwebpb) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-22 - Converts common image formats (JPG, PNG, GIF, BMP, TIFF) to WebP format using Google's `cwebp` tool in batch mode.
* [dce](https://github.com/Onnokh/zsh-dce) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-07 - Helps you quickly navigate to your docker containers without losing the current folder context.
* [deno (tricked-dev)](https://github.com/Tricked-dev/deno-zsh-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-06 - Automatically installs [deno](https://deno.land/) to `$HOME/.deno` on startup if deno is not already installed.
* [doppler](https://github.com/lsdcapital/zsh-doppler) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-13 - Displays your current [Doppler](https://doppler.com) project and configuration in your shell prompt from environment variables.
* [edward cli](https://github.com/matthieusb/zsh-edward) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2020-03-14 - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward) ⚠️ Archived.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-01-02 - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
* [ensure-kube-context](https://github.com/do-i-need-a-username/ensure-kube-context) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-09 - Ensures that the `--context` flag is passed to various Kubernetes commands like `kubectl`, `cilium`, `stern`, and more.
* [exa (zplugin)](https://github.com/zplugin/zsh-exa) ⭐ 0 | 🐛 0 | 📅 2023-02-25 - replace `ls` with [ogham/exa](https://github.com/ogham/exa) ⭐ 24,296 | 🐛 214 | 🌐 Rust | 📅 2024-09-24.
* [eza (clavelm)](https://github.com/clavelm/eza-omz-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-12 - Replaces `ls` with [eza-community/eza](https://github.com/eza-community/eza) ⭐ 19,829 | 🐛 323 | 🌐 Rust | 📅 2026-02-01.
* [fishysave](https://github.com/dariogliendo/fishysave.zsh) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-11-09 - Save and update functions and aliases directly from your terminal session.
* [flutter-zsh-shortcuts](https://github.com/dizzpy/flutter-zsh-shortcuts) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-06-17 - Adds clean aliases for flutter commands.
* [fuckmit](https://github.com/mingeme/zsh-fuckmit) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-13 - Provides useful aliases and functions for the [fuckmit](https://github.com/mingeme/fuckmit) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-11-11 command-line tool, an AI-powered `git` commit message generator.
* [git-aliases (remino)](https://github.com/remino/omz-plugin-git-aliases) ⚠️ Archived - Aliases all `git xyz` commands to `gxyz`. Also aliases `g` to `git`.
* [git-cleanbranches](https://github.com/wu9o/ohmyzsh-cleanbranches) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-22 - A powerful unified clean up tool for `git` branches that uses [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 to find all branches that are safe to delete.
* [git-plugin (dark-kitt)](https://github.com/dark-kitt/zsh-git-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-04-27 - `git` integration that displays the current directory and `git` branch.
* [git-wt](https://github.com/fingergohappy/git-wt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-25 - A ZSH-native `git` worktree workflow plugin.
* [gitignore (valerius21)](https://github.com/valerius21/omz-gitignore) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-22 - [oh-my-zsh](https://ohmyz.sh)'s gitignore plugin extracted to be standalone
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-05-14 - Allows fast tagging of a release in `git` using the tag name \**release-YYYY-MM-DD-HH-MM*- and headline **Release YYYY-MM-DD HH:MM**.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2015-09-18 - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [iterm-tmux-color-tabs](https://github.com/remino/omz-plugin-iterm2-tmux-color-tabs) ⚠️ Archived - Every new `tmux` tab opened in iTerm2 will have the next colour from the default or specified palette.
* [jrgit](https://github.com/jrocha-dev/ohmyzsh-plugin-jrgit) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2024-05-19 - Provides a suite of functions to streamline the Git user experience. It includes features for installing and configuring `git`, handling large files with Git LFS, improving diff outputs, and managing credentials and keys securely.
* [kiwi](https://github.com/fruitydog/kiwi.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-05 - Dog-themed, includes `git` status and last command exit status decorators.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-08-22 - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
* [laravel (baliestri)](https://github.com/baliestri/laravel.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - Plugin for skiping the `php` command when running `artisan` commands and `./sail` or `./vendor/bin/sail` when running `sail` commands.
* [lesaint-git](https://github.com/lesaint/lesaint-git) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-27 - Replacement `git` plugin for [oh-my-zsh](https://ohmyz.sh)-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2015-04-15 - Maven plugins for [oh-my-zsh](https://ohmyz.sh).
* [logout-user](https://github.com/pressdarling/logout-user) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-05-26 - Provides a function to log out another macOS user session.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-03-06 - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
* [ls (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-ls) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2023-09-09 - Adds some more aliases for `ls`.
* [macos-theme](https://github.com/gakimball/zsh-macos-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-05-29 - Adds the theme command, which toggles between light and dark mode in macOS. Requires [lux](https://github.com/pndurette/zsh-lux) ⭐ 34 | 🐛 0 | 🌐 Shell | 📅 2024-01-21 plugin.
* [multi-evalcache](https://github.com/rwwiv/multi-evalcache) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-01-18 - Cache multiple eval loads to improve startup time, inspired by [mroth/evalcache](https://github.com/mroth/evalcache) ⭐ 254 | 🐛 2 | 🌐 Shell | 📅 2025-11-24.
* [mysql-login](https://github.com/remino/omz-plugin-mysql-alias) ⚠️ Archived - Adds alias for MySQL with login path.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-12-19 - Looks for `nodenv` in your working directory and loads it when found.
* [nota](https://github.com/0x61nas/nota.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-09 - Simple plugin to manage a list of notes.
* [nvim-switcher](https://github.com/dacarey/zsh-nvim-switcher) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-02- Manages switching between `nvim` distributinons such as [Lazyvim](https://www.lazyvim.org/), [kickstart](https://github.com/nvim-lua/kickstart.nvim) ⭐ 29,335 | 🐛 55 | 🌐 Lua | 📅 2026-01-27 or a home made configuration.
* [nvm-auto-use (martvdmoosdijk)](https://github.com/martvdmoosdijk/zsh-nvm-auto-use) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-07 - Automatically switches node version with `nvm use` when a `.nvmrc` is detected.
* [nvm-deferred](https://github.com/davidparsson/zsh-nvm-deferred) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-09-06 - Defers loading of the `nvm` oh-my-zsh plugin using [zsh-defer](https://github.com/romkatv/zsh-defer) ⭐ 459 | 🐛 2 | 🌐 Shell | 📅 2024-02-10 to speed up shell startup.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2017-12-16 - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-gx](https://github.com/troykelly/oh-my-zsh-opera-gx) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-24 - Enables starting Opera GX with a specific user profile by using the `opgx` command followed by the profile's name. The plugin also implements autocompletion for profile names.
* [package-any-node](https://github.com/zdharma-continuum/zsh-package-any-node) ⚠️ Archived - Easy installing of any Node modules inside the plugin directory, exposing their binaries via shims (i.e.: forwarder scripts) created automatically by [Bin-Gem-Node](https://github.com/zdharma-continuum/z-a-bin-gem-node) ⭐ 8 | 🐛 8 | 🌐 Shell | 📅 2025-10-05 annex.
* [pipenv (sudosubin)](https://github.com/sudosubin/zsh-pipenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-07-25 - Enables `pipenv`'s `$PATH` and adds completions.
* [poetry (murku)](https://github.com/murku/omz_poetry_plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-11 - Adds aliases for frequently used [Poetry](https://poetry.eustace.io/) commands
* [pr-eol](https://github.com/zpm-zsh/pr-eol) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-03-29 - Displays an EOL symbol which can be embedded in the prompt.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-02 - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-node](https://github.com/zpm-zsh/pr-node) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-11-26 - Sets an environment variable which can be used to display Node.js information in a custom prompt.
* [prezto-last-working-dir](https://github.com/JoniVanderheijden/prezto-last-working-dir) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-01-28 - Keeps track of the last used working directory and automatically jumps into it for new shells, unless the starting directory is not `$HOME`. Includes a `lwd` alias.
* [proj-jumper](https://github.com/Kikolator/proj-jumper) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-02 - A lightweight ZSH plugin that lets you jump straight into any project folder under a single development root -- perfect when that root lives on a removable drive.
* [project-aliases](https://github.com/dvigo/project-aliases) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-19 — Zsh plugin to automatically load and unload per-project aliases.
* [projen](https://github.com/p6m7g8/p6-zsh-projen-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-11 - Adds aliases for [projen](https://github.com/projen/projen) ⭐ 2,902 | 🐛 249 | 🌐 TypeScript | 📅 2026-02-06.
* [prompt-watcher](https://github.com/shields/git-prompt-watcher) ⭐ 0 | 🐛 13 | 🌐 Rust | 📅 2026-02-05 - Automatically updates your prompt when git status changes, using fswatch to monitor repository files in real-time.
* [pump](https://github.com/fab1o/pump-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-06 - provides a configurable set of aliases, functions, and themes to supercharge your terminal workflow. Requires [jq](https://stedolan.github.io/jq/), [gum](https://github.com/charmbracelet/gum) ⭐ 22,541 | 🐛 143 | 🌐 Go | 📅 2026-01-21, [glow](https://github.com/charmbracelet/glow) ⭐ 22,638 | 🐛 157 | 🌐 Go | 📅 2026-01-12 and the [GitHub CLI](https://cli.github.com/).
* [pyenv (twopizza9621536)](https://github.com/TwoPizza9621536/zsh-pyenv) ⚠️ Archived - Based on the oh-my-zsh [pyenv](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/pyenv) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin with modifications from the rbenv and jenv plugins.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-10-15 - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q) ⭐ 1,552 | 🐛 1 | 🌐 Go | 📅 2025-09-04, the Dirty Debugging Tool.
* [ranger (niziL)](https://github.com/NiziL/ranger.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-10 - provide prompt element for [ranger](https://github.com/ranger/ranger) ⭐ 16,840 | 🐛 921 | 🌐 Python | 📅 2026-01-22. Shows current `RANGER_LEVEL`, displaying nothing when the environment variable is unset, something when it is equals to 1, and something else when it is greater than 1.
* [raspberry-temp](https://github.com/cfunkz/zsh-raspberry-temp-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-12 - Measures temperature for a Raspberry pi via `rpi-temp` alias.
* [raspberryPi4Temperature](https://github.com/KidesLeo/RaspberryPi4TemperaturePromptPlugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-11-14 - Puts the Raspberry Pi temperature into a spaceship prompt segment
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) ⚠️ Archived - Variant based on the original [oh-my-zsh](https://ohmyz.sh/) `rbenv` plugin.
* [release-fetcher](https://github.com/Game4Move78/zsh-release-fetcher) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-12 - Fetches latest release and checks if you trust the identity used to sign the tag.
* [rtm-reminder](https://github.com/aranel616/rtm-reminder-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-29 - Displays urgent [Remember The Milk](https://www.rememberthemilk.com/) tasks after each command execution. Clean, non-intrusive, and terminal-only.
* [rust (juici)](https://github.com/Juici/zsh-rust-completions) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-17 - ZSH completion definitions for rust.
* [sail](https://github.com/Razzaghnoori/Sailor/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-02-03 - Adds convenience aliases for [sail](https://laravel.com/docs/10.x/sail).
* [sb-upgrade](https://github.com/redxtech/zsh-sb-upgrade) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-07-08 - Script to automatically update apps on a seedbox.
* [senv](https://github.com/joepvd/senv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-10-10 - Report presence of sensitive environment variables in the prompt
* [singularityenv](https://github.com/saravanabalagi/zsh-plugin-singularityenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-10-26 - Provides a `singularityenv_prompt_info` function which returns the current singularity environment name
* [slurm](https://github.com/galhar/slurm) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-27 - Provides convenient commands for running interactive [SLURM](https://slurm.schedmd.com) jobs.
* [smart-command-not-found](https://github.com/rami-shalhoub/Smart-command-not-found) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-11-18 - Shows all available options when a command is not found.
* [ssh-warrior](https://github.com/OfferPi/ssh-warrior) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-29 - Automatically changes your terminal background color based on the host you are `ssh`-ing into. Requires a terminal that supports OSC 11 / OSC 111 escape sequences (Kitty, iTerm2, Alacritty, GNOME Terminal, etc. all work great).
* [sussysh](https://github.com/sussynuggetz/sussysh-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-10-22 - Based on xiong-chiamiov.
* [t3-shortcuts](https://github.com/murat-yasar/zsh-t3-shortcuts) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-31 - Shortcuts for working with TYPO3 projects. Provides fast navigation commands to jump around TYPO3 project directories.
* [temperatures](https://github.com/groberth/temperatures-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-23 - A lightweight, zero-dependency plugin that shows your machine’s CPU and (optionally) GPU temperatures directly in your ZSH prompt. Originally designed for Raspberry Pi but works on any Linux system exposing `/sys/class/thermal/`.
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) ⚠️ Archived - Add [terraform](https://www.terraform.io/) workspace to prompt.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) ⚠️ Archived - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia) ⭐ 21,343 | 🐛 1,718 | 🌐 TypeScript | 📅 2026-02-06.
* [usb](https://github.com/NiziL/usb.plugin.zsh) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-09-12 - A tiny plugin to quickly mount and unmount your USB drives.
* [vapor](https://github.com/notf0und/zsh-vapor) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-10-16 - Laravel [vapor](https://github.com/laravel/vapor-cli) ⭐ 312 | 🐛 5 | 🌐 PHP | 📅 2026-01-06 plugin for ZSH to help you to run `vapor` from anywhere in the project tree, with auto-completion!
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-01-29 - Help vcsh users require GitHub repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
* [venv](https://github.com/lucasheartcliff/venv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-04-23 - Run `source venv/bin/activate` automatically every time there's a path to `venv/bin/activate` file in the current directory.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-02-15 - Add more `vi`-like functionality to ZSH.
* [vivid](https://github.com/zsh-contrib/zsh-vivid) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-18 - Plugin for [vivid](https://github.com/sharkdp/vivid) ⭐ 2,138 | 🐛 24 | 🌐 Rust | 📅 2026-01-28 integration that generates and exports `LS_COLORS` with theme support.
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-09-29 - Lets you run `emacs` commands directly from [vterm](https://github.com/vterm/vterm) ⚠️ Archived shell sessions.
* [which-jspm](https://github.com/zkuzmic/which-jspm/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-09-23 - Adds `npm`, `yarn` or `pnpm` to the end of your prompt depending on what lockfile(s) it detects in the current directory.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-12-20 - Highlight where a particular line was last changed in a file using `git blame`.
* [xxh (ninagrosse)](https://github.com/ninagrosse/xxh-plugin-zsh-ohmyzsh) ⚠️ Archived - Plugin for [xxh](https://github.com/xxh/xxh) ⭐ 5,901 | 🐛 30 | 🌐 Python | 📅 2025-09-22 that requires [xxh-plugin-prerun-cli-tools](https://github.com/ninagrosse/xxh-plugin-prerun-cli-tools) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-21.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-04-05 - Automatically activate a directory's `pip` environment if `pipenv` detects the presence of one.
* [yazi-mount](https://github.com/splixx05/zsh-yazi-mount) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-18 - Mount USB partitions via `udisksctl`, open them in [yazi](https://github.com/sxyazi/yazi) ⭐ 32,282 | 🐛 70 | 🌐 Rust | 📅 2026-02-06, and unmount them afterward – safe, clean, and user-friendly.
* [yup](https://github.com/redxtech/zsh-yup) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-07-08 - Adds helper function to upgrade all the dependencies in a `yarn`/`npm` project.
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-30 - Custom extras for [zimfw](https://github.com/zimfw/zimfw) ⭐ 4,502 | 🐛 26 | 🌐 Shell | 📅 2026-01-08, packaged into a zimfw plugin.
* [zinit-annex-test](https://github.com/NorthIsMirror/z-a-test) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-11-05 - [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,388 | 🐛 112 | 🌐 Shell | 📅 2026-02-02 extension that runs tests (via make test, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [zsh-dev-navigator](https://github.com/dvigo/zsh-dev-navigator) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-12 - A minimal ZSH plugin that lets you quickly jump into your development directories with a single command.
* [zsh-hookie-projects](https://github.com/aemonge/zsh-hookie-projects) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-20 - Language-agnostic project detection with smart hooks, PowerLevel10k integration, and intelligent path shortening. Automatically detects 100+ project types, provides customizable on\_project/off\_project hooks, features a smart `cd` command that goes to project root, and includes a beautiful `hookie_dir` segment that shortens paths like `~/projects/my-app` → `~/p/my-app`. Perfect for polyglot developers who want seamless project-aware shell behavior.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2020-12-09 - Installs and loads [z](https://github.com/rupa/z.git) ⭐ 16,912 | 🐛 106 | 🌐 Shell | 📅 2024-06-19.
* [zshange\_directory\_recent](https://github.com/Kjeldgaard/zshange_directory_recent) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-04-25 - Change to a recent directory. Requires [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [zshclean](https://github.com/bepisdev/zshclean) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-27 - Helps you keep your $HOME directory tidy by removing temporary files and common system clutter. It supports both macOS and Linux, safely deleting common cache, history, swap, and log files with a single command.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
* [oh-my-tmux-manager](origin/omt-manager) - Lets you easily manage your tmux configurations.

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [inshellisense](https://github.com/microsoft/inshellisense) ⭐ 9,738 | 🐛 19 | 🌐 TypeScript | 📅 2026-02-04 - Provides IDE style autocomplete for shells. It's a terminal native runtime for autocomplete which has support for 600+ command line tools. inshellisense supports `bash`, `fish`, `zsh` and `pwsh` on the Windows, Linux, & MacOS operating systems.
* [completions (zsh-users)](https://github.com/zsh-users/zsh-completions) ⭐ 7,630 | 🐛 16 | 🌐 Shell | 📅 2026-02-04 - A collection of extra completions for ZSH.
* [mcfly](https://github.com/cantino/mcfly) ⭐ 7,594 | 🐛 129 | 🌐 Rust | 📅 2026-01-11 - Replaces your default ctrl-r shell history search with an intelligent search engine that takes into account your working directory and the context of recently executed commands. McFly's suggestions are prioritized in real time with a small neural network.
* [git-flow](https://github.com/bobthecow/git-flow-completion) ⭐ 2,800 | 🐛 18 | 🌐 Shell | 📅 2022-06-16 - ZSH completion support for [git-flow](http://github.com/nvie/gitflow) ⚠️ Archived.
* [carapace-bin](https://github.com/rsteube/carapace-bin) ⭐ 1,680 | 🐛 89 | 🌐 Go | 📅 2026-02-05 - Multi-shell multi-command argument completer.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) ⭐ 1,095 | 🐛 33 | 🌐 Kotlin | 📅 2026-02-02 - Bash and ZSH completion support for gradle.
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) ⭐ 814 | 🐛 30 | 🌐 Shell | 📅 2026-01-05 - Add tab completion for ZSH, `bash` & applications using GNU Readline.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) ⭐ 588 | 🐛 3 | 🌐 Rust | 📅 2026-01-30 - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.
* [cod](https://github.com/dim-an/cod) ⭐ 542 | 🐛 24 | 🌐 Go | 📅 2023-12-19 - A completion demon for `bash`/`fish`/`zsh` which creates completion functions on the fly when it sees you run something with `--help`.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) ⭐ 496 | 🐛 12 | 🌐 Shell | 📅 2024-10-31 - Better tab completion for `npm`.
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) ⭐ 470 | 🐛 8 | 🌐 Go | 📅 2024-04-23 - Fast and powerful [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05-powered autocompletion for `kubectl`.
* [argc-completions](https://github.com/sigoden/argc-completions) ⭐ 429 | 🐛 1 | 🌐 Shell | 📅 2024-11-27 - Uses [argc](https://github.com/sigoden/argc) ⭐ 1,107 | 🐛 3 | 🌐 Rust | 📅 2025-08-07 and [jq](https://github.com/stedolan/jq) ⭐ 33,491 | 🐛 451 | 🌐 C | 📅 2026-02-01 to add ZSH tab completions.
* [conda](https://github.com/conda-incubator/conda-zsh-completion) ⭐ 401 | 🐛 7 | 🌐 Shell | 📅 2025-10-22 - ZSH tab completion for [conda](http://conda.pydata.org/).
* [click-completion](https://github.com/click-contrib/click-completion) ⭐ 294 | 🐛 18 | 🌐 Python | 📅 2025-03-25 - Add automatic completion support for [Click](http://click.pocoo.org/), including displaying the options and commands help during the tab completion.
* [nix](https://github.com/spwhitt/nix-zsh-completions) ⭐ 278 | 🐛 8 | 🌐 Shell | 📅 2025-12-12 - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) ⚠️ Archived - Add tab completions for `docker`.
* [ssh (sunlei)](https://github.com/sunlei/zsh-ssh) ⭐ 204 | 🐛 14 | 🌐 Shell | 📅 2025-08-31 - Better host completion for `ssh`.
* [mac](https://github.com/scriptingosx/mac-zsh-completions) ⭐ 190 | 🐛 6 | 🌐 Shell | 📅 2025-03-26 - Completions files for macOS specific commands and third party tools.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) ⭐ 169 | 🐛 4 | 🌐 Shell | 📅 2026-01-16 - Fuzzy completions for [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
* [nx](https://github.com/jscutlery/nx-completion) ⭐ 152 | 🐛 5 | 🌐 Shell | 📅 2025-06-12 - Completions for [nx](https://nx.dev). Requires [`jq`](https://stedolan.github.io/jq/).
* [pmy](https://github.com/relastle/pmy) ⭐ 151 | 🐛 3 | 🌐 Go | 📅 2023-02-25 - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [completions (zchee)](https://github.com/zchee/zsh-completions) ⭐ 119 | 🐛 1 | 🌐 Shell | 📅 2025-12-09 - Yet another collection of tab completions.
* [npm-scripts-autocomplete](https://github.com/grigorii-zander/zsh-npm-scripts-autocomplete) ⭐ 110 | 🐛 2 | 🌐 Shell | 📅 2023-10-19 - Shows autocomplete suggestions from scripts found in the current directory's `package.json`. Works with `npm` and `yarn`.
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion) ⭐ 89 | 🐛 8 | 🌐 Shell | 📅 2019-12-30 - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
* [gcloud (littleq0903)](https://github.com/littleq0903/gcloud-zsh-completion) ⭐ 81 | 🐛 5 | 🌐 Python | 📅 2015-02-07 - Add completions for the Google Cloud SDK.
* [fzshell](https://github.com/mnowotnik/fzshell) ⭐ 80 | 🐛 3 | 🌐 Go | 📅 2026-01-06 - Fetches fuzzy completions from sources predefined by a user.
* [completions (clarketm)](https://github.com/clarketm/zsh-completions) ⭐ 75 | 🐛 4 | 🌐 Shell | 📅 2025-03-06 - This includes the zsh-users[completions](https://github.com/zsh-users/zsh-completions) ⭐ 7,630 | 🐛 16 | 🌐 Shell | 📅 2026-02-04, zchee's [completions](https://github.com/zchee/zsh-completions) ⭐ 119 | 🐛 1 | 🌐 Shell | 📅 2025-12-09, nilsonholger's [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) ⭐ 15 | 🐛 1 | 📅 2014-12-12 and various other custom completions.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) ⭐ 68 | 🐛 6 | 🌐 Shell | 📅 2024-01-19 - Support `bash` completions for commands when no native ZSH one is available.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) ⭐ 67 | 🐛 1 | 🌐 Shell | 📅 2026-02-01 - Add tab completions for `docker` and `docker-compose`.
* [kafka](https://github.com/Dabz/kafka-zsh-completions) ⭐ 67 | 🐛 5 | 🌐 Shell | 📅 2022-08-19 - Completions for Apache [kafka](https://kafka.apache.org).
* [xcode](https://github.com/keith/zsh-xcode-completions) ⭐ 63 | 🐛 3 | 🌐 Makefile | 📅 2024-06-19 - Completions for some Xcode command line tools - `genstrings`, `nm`, `plutil`, `xcode-select`, `xcodebuild`, `xcrun`, `simctl`, `strings`, `swift-demangle`, `swift` and `lipo`.
* [sdkman (matthieusb)](https://github.com/matthieusb/zsh-sdkman) ⭐ 61 | 🐛 0 | 🌐 Shell | 📅 2025-01-16 - Add tab completions for [sdkman](https://sdkman.io/).
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) ⭐ 58 | 🐛 0 | 🌐 Shell | 📅 2026-01-20 - Tab completions for Metasploit.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) ⭐ 54 | 🐛 5 | 🌐 Shell | 📅 2021-03-16 - Autocompletion support for `npm run`.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) ⭐ 52 | 🐛 1 | 🌐 Roff | 📅 2025-07-24 - 13500 ZSH compsys completions! Most were generated by python scripts that parsed --help output and man page output. As such they are of varying quality. Architecture prefixed completions are in the `architecture_src` directory.
* [deoplete](https://github.com/zchee/deoplete-zsh) ⭐ 51 | 🐛 1 | 🌐 Shell | 📅 2019-11-10 - ZSH completion for [deoplete.nvim](https://github.com/Shougo/deoplete.nvim) ⭐ 5,920 | 🐛 1 | 🌐 Python | 📅 2024-06-05
* [drush\_zsh\_completion](https://github.com/webflo/drush_zsh_completion) ⭐ 40 | 🐛 1 | 🌐 PHP | 📅 2016-01-29 - Drush autocomplete awesomeness for ZSH.
* [flatpak](https://github.com/bilelmoussaoui/flatpak-zsh-completion) ⭐ 39 | 🐛 2 | 🌐 Shell | 📅 2024-10-03 - Tab completions for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) ⭐ 39 | 🐛 1 | 🌐 Shell | 📅 2025-07-08 - Provides ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [yarn-extra-completion](https://github.com/BuonOmo/yarn-extra-completion) ⭐ 38 | 🐛 1 | 🌐 Shell | 📅 2022-11-10 - Inspired by [lukechilds/zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) ⭐ 496 | 🐛 12 | 🌐 Shell | 📅 2024-10-31.
* [git-fzf](https://github.com/alexiszamanidis/zsh-git-fzf) ⭐ 35 | 🐛 2 | 🌐 Shell | 📅 2023-01-25 - ZSH plugin that wraps `git` operations for simplicity and productivity. It also contains completions and combines support for [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05.
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) ⭐ 34 | 🐛 1 | 🌐 Shell | 📅 2020-01-03 - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) ⭐ 33 | 🐛 3 | 🌐 Shell | 📅 2024-05-25 - All the functionality of the original oh-my-zsh cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) ⭐ 32 | 🐛 4 | 🌐 Shell | 📅 2016-02-05 - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [lazycomplete](https://github.com/rsteube/lazycomplete) ⭐ 30 | 🐛 2 | 🌐 Go | 📅 2022-11-22 - Lazy loading for shell completion scripts.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) ⭐ 26 | 🐛 0 | 🌐 Shell | 📅 2024-08-17 - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) ⭐ 26 | 🐛 0 | 🌐 Shell | 📅 2023-08-13 - Manage `ssh-agent`.
* [ddc](https://github.com/Shougo/ddc-zsh) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2025-09-04 - Adds tab completions for [ddc](https://github.com/Shougo/ddc.vim) ⭐ 733 | 🐛 1 | 🌐 TypeScript | 📅 2026-01-26.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2015-04-22 - Autocompletion plugin for pip.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) ⭐ 22 | 🐛 0 | 🌐 Shell | 📅 2019-12-19 - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
* [completion-sync](https://github.com/BronzeDeer/zsh-completion-sync) ⭐ 21 | 🐛 1 | 🌐 Shell | 📅 2025-09-15 - Automatically loads completions added dynamically to `FPATH` or `XDG_DATA_DIRS`.
* [dropbox](https://github.com/zpm-zsh/dropbox) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2022-01-06 - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) ⭐ 20 | 🐛 2 | 📅 2015-12-11 - Completions for [keybase](https://book.keybase.io/docs/cli).
* [llm](https://github.com/eliyastein/llm-zsh-plugin) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2025-05-28 - Adds tab completions for the [LLM CLI tool](https://llm.datasette.io/).
* [terragrunt](https://github.com/jkavan/terragrunt-oh-my-zsh-plugin) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2023-08-24 - Tab completion for [Terragrunt](https://github.com/gruntwork-io/terragrunt) ⭐ 9,280 | 🐛 249 | 🌐 Go | 📅 2026-02-06.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2015-06-18 - Completion plugin for [homebrew](https://brew.sh) services.
* [haskell](https://github.com/coot/zsh-haskell) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2025-03-02 - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
* [ssh (zpm-zsh)](https://github.com/zpm-zsh/ssh) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2023-12-27 - Add host completion for `ssh`.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2021-08-25 - Adds tab completion for berkshelf.
* [fancy-completions](https://github.com/z-shell/zsh-fancy-completions) ⭐ 17 | 🐛 4 | 🌐 Shell | 📅 2025-12-15 - Provides various completions tools, libraries and integrations.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) ⭐ 16 | 🐛 7 | 📅 2016-10-11 - Allows tab completion for most git-annex commands.
* [tinygo](https://github.com/sago35/tinygo-autocmpl) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2025-01-24 - Add tab completions for [tinygo](https://tinygo.org/).
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2023-11-13 - Add completions for macOS [yabai](https://github.com/koekeishiya/yabai/) ⭐ 28,092 | 🐛 257 | 🌐 C | 📅 2026-01-17 tiling window manager.
* [kubectl-plugin](https://github.com/MartinSimango/kubectl-plugin_completion) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2022-06-07 - Generates `kubectl` completion scripts to extend the `kubectl` auto complete functionality to accomodate for plugin sub-commands.
* [kustomize](https://github.com/ralgozino/oh-my-kustomize) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2025-05-28 - Adds tab completions for [kustomize](https://kustomize.io/)
* [osx-zsh-completions](https://github.com/nilsonholger/osx-zsh-completions) ⭐ 15 | 🐛 1 | 📅 2014-12-12 - Tab completions for some macOS-specific commands like `launchctl`.
* [rustup](https://github.com/pkulev/zsh-rustup-completion) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2019-10-24 - Tab completions for Rustup.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) ⚠️ Archived - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) ⭐ 14 | 🐛 2 | 🌐 Shell | 📅 2019-07-06 - Pandoc completion plugin.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2018-03-15 - Completions for `pipenv`.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2015-09-28 - Adds command completion for the Codeception Testing Framework.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) ⭐ 12 | 🐛 2 | 🌐 Shell | 📅 2024-03-10 - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2015-05-17 - Autocompletion for gulp.
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-06 - Autocomplete plugin for Salesforce [sfdx](https://developer.salesforce.com/tools/salesforcecli).
* [brew-completions](https://github.com/z-shell/brew-completions) ⭐ 10 | 🐛 0 | 📅 2022-06-28 - Brings [Homebrew Shell Completion](https://docs.brew.sh/Shell-Completion) under the control of ZSH & [ZI](https://github.com/z-shell/zi/) ⭐ 879 | 🐛 11 | 🌐 Shell | 📅 2026-01-19.
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) ⭐ 10 | 🐛 0 | 📅 2021-04-06 - Completions for the [Interplanetary File System](https://ipfs.tech).
* [op](https://github.com/sirhc/op.plugin.zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2021-11-20 - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) ⭐ 10 | 🐛 2 | 🌐 Shell | 📅 2022-01-16 - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH.
* [rancher](https://github.com/go/rancher-zsh-completion) ⭐ 10 | 🐛 5 | 🌐 Shell | 📅 2017-04-12 - Add completions for the Rancher CLI.
* [1password-op](https://github.com/unixorn/1password-op.plugin.zsh) ⭐ 9 | 🐛 2 | 🌐 Shell | 📅 2025-11-30 - Loads autocompletions for 1Password's [op](https://developer.1password.com/docs/cli/get-started/) command line tool.
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) ⭐ 9 | 🐛 0 | 📅 2015-11-09 - Completions for autopkg.
* [bio](https://github.com/yamaton/zsh-completions-bio/) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-01-29 - Completions for bioinformatics tools.
* [bosh (thomasmitchell)](https://github.com/thomasmitchell/bosh-complete) ⭐ 9 | 🐛 2 | 🌐 Go | 📅 2022-03-15 - Tab completion for [BOSH](https://github.com/cloudfoundry/bosh) ⭐ 2,070 | 🐛 29 | 🌐 Ruby | 📅 2026-02-07.
* [complete-mac](https://github.com/vitkabele/complete-mac) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2022-09-07 - Add completions for macOS `ioreg`, `lsmp`, `scselect`, `system_profiler` and `tmutil` commands.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) ⭐ 9 | 🐛 0 | 📅 2013-08-03 - Add completions for Parallels desktop.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) ⭐ 9 | 🐛 1 | 📅 2015-11-21 - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [symfony-complete](https://github.com/voronkovich/symfony-complete.plugin.zsh) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2023-12-29 - Universal completion for [Symfony](https://symfony.com/doc/current/components/console.html) based CLI applications: `composer`, `php-cs-fix`, `bin/console`, `artisan`, `php-cs-fixer` and etc. This supports autocompletion for subcommands and GNU-style options (`--help`)
* [tailscale (heroeslament)](https://github.com/HeroesLament/zsh-tailscale-plugin) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2024-08-01 - Tab completion and aliases for [tailscale](https://www.tailscale.com/).
* [yt-dlp](https://github.com/clavelm/yt-dlp-omz-plugin) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2025-06-29 - Tab completions for [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 146,062 | 🐛 2,287 | 🌐 Python | 📅 2026-02-06.
* [chezmoi](https://github.com/mass8326/zsh-chezmoi) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-10-03 - Adds completions and aliases for [chezmoi](https://www.chezmoi.io/). Detects if you have `git` aliases and generates `chezmoi` aliases for them.
* [extract (thetic)](https://github.com/thetic/extract) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2018-07-16 - Fork of the oh-my-zsh extract plugin.
* [kitty](https://github.com/redxtech/zsh-kitty) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2021-07-06 - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
* [mx-honey](https://github.com/mukel/mx-honey) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2020-03-03 - Provides completions for [mx](https://github.com/graalvm/mx) ⭐ 197 | 🐛 40 | 🌐 Python | 📅 2026-01-29; a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) ⭐ 8 | 🐛 1 | 🌐 Shell | 📅 2025-12-16 - Add fast tab completion for rakefile targets.
* [bitbake](https://github.com/antznin/zsh-bitbake) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2025-10-26 - Completions for [bitbake](https://git.openembedded.org/bitbake).
* [ollama](https://github.com/Katrovsky/zsh-ollama-completion) ⭐ 7 | 🐛 0 | 📅 2025-02-02 - Tab command completion for Ollama AI models management.
* [test-kitchen](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) ⭐ 7 | 🐛 0 | 📅 2014-08-09 - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen) ⭐ 1,893 | 🐛 8 | 🌐 Ruby | 📅 2026-02-02).
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) ⭐ 6 | 🐛 2 | 🌐 Perl | 📅 2022-11-21 - Generating completions for Bash and ZSH from YAML specs
* [claude-code-zsh-completion](https://github.com/1160054/claude-code-zsh-completion) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-12-14 - Adds completions for Anthropic's Claude Code CLI with support for 120+ languages. Includes dynamic completion for MCP servers, plugins, and session IDs.
* [github-cli](https://github.com/sudosubin/zsh-github-cli) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-08-18 - Tab completions for the GitHub cli.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) ⭐ 6 | 🐛 4 | 📅 2015-03-27 - Provides auto-complete for nova.
* [racket completion](https://github.com/racket/shell-completion) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2025-11-21 - Completion for [Racket](http://racket-lang.org).
* [aircrack](https://github.com/Doc0x1/Aircrack-Zsh-Completions) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2024-11-22 - Adds completions for `airbase-ng`, `aircrack-ng`, `airdecap-ng`, `airdecloak-ng`, `aireplay-ng`, `airmon-ng`, `airodump-ng`, `airolib-ng`, `airserv-ng`, `airtun-ng`, `airventriloquist-ng`.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2019-07-27 - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
* [claudecode-completion](https://github.com/wbingli/zsh-claudecode-completion) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-02-06 - Minimal and always up-to-date zsh completions for [Claude Code CLI](https://github.com/anthropics/claude-code) ⭐ 64,911 | 🐛 6,414 | 🌐 Shell | 📅 2026-02-06.
* [complete-ng](https://github.com/joknarf/complete-ng) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Replace ZSH completion multiple choices output by interactive selector menu, browse directories inside the menu, view/edit files directly from the menu.
* [gcloud (wintermi)](https://github.com/wintermi/zsh-gcloud) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2024-09-28 - Adds Google Cloud Command Line Interface ([gcloud](https://cloud.google.com/cli) CLI) completions.
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) ⭐ 5 | 🐛 0 | 📅 2022-04-15 - Completions for `node ace`.
* [packer](https://github.com/wakeful/zsh-packer) ⭐ 5 | 🐛 0 | 📅 2021-04-19 - Adds tab completion for [packer](https://packer.io).
* [audogombleed.sh](https://github.com/i-love-coffee-i-love-tea/audogombleed.sh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-11-24 - Makes it easy to generate completion files using a declarative syntax, quickly and without coding.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-12-04 - Tab completions for [ctop](https://github.com/bcicen/ctop) ⭐ 17,571 | 🐛 118 | 🌐 Go | 📅 2024-07-08.
* [elm](https://github.com/kraklin/elm.plugin.zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-08-15 - Tab completion for [elm](https://elm-lang.org/).
* [git-profiles](https://github.com/baliestri/git-profiles.plugin.zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - Manages multiple git users in a single `.gitconfig` file.
* [helmfile](https://github.com/Downager/zsh-helmfile) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-05-07 - Adds autocompletion for `helm`.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-12-04 - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-12-04 - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/).
* [kubectl (chrishrb)](https://github.com/chrishrb/zsh-kubectl) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-10-22 - Automatically loads completions for [kubectl](https://github.com/kubernetes/kubectl) ⭐ 3,223 | 🐛 108 | 🌐 Go | 📅 2026-02-07.
* [mill](https://github.com/carlosedp/mill-zsh-completions) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2025-07-25 - Tab completions for Scala's [Mill](http://mill-build.com/) build tool.
* [oh-my-update](https://github.com/utox39/oh-my-update) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2025-12-10 - Updates plugins in [oh-my-zsh](https://ohmyz.sh/).
* [symfony (Akollade)](https://github.com/Akollade/symfony.plugin.zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-02-26 - Adds completions for [Symfony](https://symfony.com/), including the `bin/console` and `sf` commands.
* [task](https://github.com/targendaz2/taskfile) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-12-30 - Tab completions for [Task](https://taskfile.dev/).
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) ⭐ 4 | 🐛 0 | 📅 2015-04-27 - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) ⭐ 1,445 | 🐛 12 | 🌐 Ruby | 📅 2018-03-11 command.
* [url-httplink](https://github.com/Valodim/zsh-_url-httplink) ⭐ 4 | 🐛 0 | 📅 2013-03-04 - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
* [zoxide](https://github.com/jnooree/zoxide-zsh-completion) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-01-21 - Tab completions for [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 33,206 | 🐛 151 | 🌐 Rust | 📅 2026-02-02.
* [aider](https://github.com/hmgle/aider-zsh-complete) ⭐ 3 | 🐛 0 | 📅 2025-03-23 - Tab completions for [aider](https://aider.chat/).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-05-26 - Completions for [viasite-ansible/ansible-server](https://github.com/viasite-ansible/ansible-server) ⭐ 14 | 🐛 0 | 📅 2020-05-01.
* [autorestic](https://github.com/naegling/zsh-autorestic) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-03-19 - automatically installs [Restic](https://github.com/cupcakearmy/autorestic/) ⭐ 1,782 | 🐛 100 | 🌐 Go | 📅 2026-01-30's completions for you, and keeps them up to date as your autorestic version changes.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-06-01 - Adds completion and useful aliases for NomicLabs Buidler tool.
* [complete-lastf](https://github.com/chougousui/complete-lastf) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-07-23 - Adds a tab completion to select the most recently modified file or directory.
* [efibootmgr](https://github.com/wehlando/efibootmgr-zsh-completion) ⭐ 3 | 🐛 0 | 📅 2021-09-13 - Tab completions for `efibootmgr`.
* [llm-cli-autocomplete-tool](https://github.com/duoyuncloud/zsh-llm-cli-autocomplete-tool) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-11-22 - Advanced AI-powered ZSH plugin with LoRA fine-tuning, navigatable UI, and [Ollama](https://ollama.com) integration.
* [poetry](https://github.com/fourdim/zsh-poetry) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-05-13 - Tab completions for [poetry](https://python-poetry.org/).
* [python-module-completion](https://github.com/UshioA/zsh-python-module-completion) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-10-20 - Intelligent tab completion for python -m commands with hierarchical module navigation and smart project detection.
* [tailscale (hsrzq)](https://github.com/hsrzq/PluginForTailscale) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-03-07 - Tab completions for [tailscale](https://www.tailscale.com/). Only works on macOS.
* [talosctl](https://github.com/RusMephist/talosctl-zsh-plugin) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2024-02-23 - Tab completion for [Talos Linux](https://www.talos.dev/v1.6/introduction/what-is-talos/).
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-08-30 - Auto-completes task numbers for taskbook.
* [web-search](https://github.com/GowayLee/zsh_web_search) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-08 - Runs a search in the specified search engine in your default browser.
* [aws\_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) ⭐ 2 | 🐛 0 | 📅 2016-05-20 - Add completions for the `aws_manager` CLI.
* [bosh (krujos)](https://github.com/krujos/bosh-zsh-autocompletion) ⭐ 2 | 🐛 1 | 📅 2014-12-13 - Adds [BOSH](https://github.com/cloudfoundry/bosh) ⭐ 2,070 | 🐛 29 | 🌐 Ruby | 📅 2026-02-07 autocompletion.
* [bw](https://github.com/CupricReki/zsh-bw-completion) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-06-05 - Adds completion for [Bitwarden](https://bitwarden.com/).
* [codex](https://github.com/pressdarling/codex-zsh-plugin) ⭐ 2 | 🐛 39 | 🌐 Shell | 📅 2026-01-27 - Vibe-coded tab completion for OpenAI's [codex](https://github.com/openai/codex) ⭐ 59,308 | 🐛 1,052 | 🌐 Rust | 📅 2026-02-07 tool. Generates completions in the background so it doesn't slow down shell startup. Includes enhancements for a smooth experience on macOS.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-10-03 - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-05-16 - Dotnet tab completion.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) ⭐ 2 | 🐛 0 | 📅 2015-05-30 - A ZSH plugin for [duell](https://github.com/gameduell/duell) ⭐ 41 | 🐛 2 | 🌐 Haxe | 📅 2017-10-13.
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) ⭐ 2 | 🐛 4 | 📅 2014-09-28 - Adds etcdctl tab completions.
* [fnm](https://github.com/zap-zsh/fnm) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-12-14 - Adds tab completions for Fast Node Manager [fnm](https://github.com/Schniz/fnm) ⭐ 23,769 | 🐛 364 | 🌐 Rust | 📅 2026-02-05.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) ⚠️ Archived - Grid 5000 plugin - adds theme, autocompletions.
* [gstreamer](https://github.com/CraigCarey/gstreamer-tab) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-04-18 - Tab completion for [GStreamer](https://gstreamer.freedesktop.org/).
* [lets-cli](https://github.com/lets-cli/lets-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-06-29 - Add autocompletion for [lets](https://github.com/lets-cli/lets) ⭐ 84 | 🐛 27 | 🌐 Go | 📅 2026-01-09 cli task runner.
* [ngrok](https://github.com/bostonaholic/ngrok.plugin.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-02-24 - Auto-loads [ngrok](https://ngrok.com) and its completions into the shell.
* [openstack](https://github.com/florentinl/openstack-zsh-plugin) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-09-09 - Add functions and aliases for managing [OpenStack](https://www.openstack.org/).
* [rhoas](https://github.com/craicoverflow/rhoas-zsh-plugin) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2021-11-18 - Adds completions for [rhoas](https://developers.redhat.com/products/red-hat-openshift-streams-for-apache-kafka/overview).
* [saml2aws](https://github.com/sirhc/saml2aws.plugin.zsh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-11-20 - Adds completions for [saml2aws](https://github.com/Versent/saml2aws) ⭐ 2,199 | 🐛 271 | 🌐 Go | 📅 2025-11-20.
* [speedtest](https://github.com/Yash-Singh1/zsh-plugin-speedtest) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-06-27 - Tab completions for the speedtest [cli](https://www.speedtest.net/insights/blog/introducing-speedtest-cli/).
* [ssh-agent (twfksh)](https://github.com/twfksh/zsh-ssh-agent) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-02 - A bloat free utility plugin for managing ssh-agent in ZSH. This plugin automatically starts and manages `ssh-agent` whenever a new ternimal session starts. After running zsh-ssh-agent, you only need to `ssh-add` your keys once. The plugin will handle the rest.
* [tshark](https://github.com/Yoswell/zsh_tshark_autocomplete) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-18 - Adds tab completions for [TShark](https://tshark.dev/) that provide deep, protocol-aware, and hierarchical autocompletion for display filters (`-Y`) and extracted fields (`-e`). Unlike traditional shell completions that only suggest flat protocol names or static options, this tool understands the internal structure of TShark fields.
* [alembic](https://github.com/datumbrain/oh-my-zsh-alembic) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-06-05 - Adds completions for [Alembic](https://alembic.sqlalchemy.org/), the database migration tool for SQLAlchemy. Includes helper functions for faster workflow, command aliases and status overview functions.
* [atuin](https://github.com/marcelohmdias/zsh-atuin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-04 - Tab completions for the [Atuin](https://github.com/atuinsh/atuin) ⭐ 28,180 | 🐛 439 | 🌐 Rust | 📅 2026-02-06 shell history system.
* [batect](https://github.com/batect/batect-zsh-completion/) ⚠️ Archived - Adds tab completions for [batect](https://batect.dev/) build system.
* [cabal (ehamberg)](https://github.com/ehamberg/zsh-cabal-completion) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2015-04-29 - Add tab completion for cabal.
* [carthage](https://github.com/squarefrog/zsh-carthage) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-08-15 - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage) ⭐ 15,446 | 🐛 213 | 🌐 Swift | 📅 2025-09-10.
* [cross-compiler](https://github.com/Freed-Wu/zsh-completions-for-cross-compilers) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2026-01-19 - In cross compilations, there are many tools like x86\_64-w64-mingw32-gcc, x86\_64-linux-android32-clang, arm-none-eabi-gcc, etc. This plugin provides ZSH completions for them.
* [dagger](https://github.com/jygastaud/dagger-oh-my-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-07 - Completions for dagger.
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2016-04-18 - Adds autocompletion options for all [Concourse CLI](https://concourse-ci.org/fly.html) commands.
* [fvm](https://github.com/olrtg/zsh-fvm) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-26 - Adds tab completions for the [Flutter Version Manager (FVM)](https://fvm.app/).
* [fzf-rg](https://github.com/ppcamp/zsh-fzf-rg) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-27 - Add some functionalities to terminal using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05, [bat](https://github.com/sharkdp/bat) ⭐ 57,011 | 🐛 344 | 🌐 Rust | 📅 2026-02-03 and [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 59,624 | 🐛 113 | 🌐 Rust | 📅 2025-12-17.
* [git-recent-branches](https://github.com/Zacharyjlo/git-recent-branches) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-22 - Makes it easy to check view and checkout recently checked-out branches.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2018-05-21 - ZSH completion support for gradle.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2018-03-22 - Completions for haxelib.
* [justfile](https://github.com/JBarberU/zsh-justfile) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-06-16 - Adds tab completions for [just](https://github.com/casey/just) ⭐ 31,002 | 🐛 388 | 🌐 Rust | 📅 2026-02-05.
* [kind](https://github.com/TomerFi/zsh-kind) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-04-23- Loads tab completions for [kind](https://kind.sigs.k8s.io/).
* [macos](https://github.com/danydodson/zsh-completions) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-12 - Completions for selected OSX commands. This repository's main purpose is to create quality auto completions, e.g. conditional flag aware presentation and selection of choices, as well as up-to-date and feature-complete auto completions.
* [miniconda](https://github.com/cmuench/zsh-miniconda) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-11-27 - Tab completions for [miniconda](https://docs.conda.io/en/latest/miniconda.html).
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) ⭐ 1 | 🐛 0 | 🌐 Perl | 📅 2019-04-16 - Completion generator for Perl module `MooseX::App`.
* [nestcli](https://github.com/behradkhodayar/nestcli-zsh) ⭐ 1 | 🐛 0 | 📅 2025-06-14 - Tab completion for the [Nest.js CLI](https://github.com/nestjs/nest-cli) ⭐ 2,140 | 🐛 38 | 🌐 TypeScript | 📅 2026-02-07.
* [okta](https://github.com/sirhc/okta.plugin.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-11-20 - Provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) ⚠️ Archived and [okta-awscli](https://github.com/jmhale/okta-awscli) ⭐ 311 | 🐛 41 | 🌐 Python | 📅 2024-08-27 commands.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2018-08-18 - Enables aliases for the most common pipenv commands.
* [pytest-fzf](https://github.com/jszczepaniak/zsh-pytest-fzf) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-04-14 - lets you select pytest tests using [fzf](https://github.com/junegunn/fzf) ⭐ 77,588 | 🐛 322 | 🌐 Go | 📅 2026-02-05 and insert them into your terminal.
* [quickjump](https://github.com/fikovnik/zsh-quickjump) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-05-25 - Adds tab completion support for [skim](https://github.com/lotabout/skim) ⭐ 6,533 | 🐛 29 | 🌐 Rust | 📅 2026-02-06 for recent files and directories using [fasd](https://github.com/whjvenyl/fasd) ⭐ 104 | 🐛 5 | 🌐 Shell | 📅 2025-10-20.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2020-12-19 - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
* [ssh-config-suggestions](https://github.com/yngc0der/zsh-ssh-config-suggestions) ⭐ 1 | 🐛 2 | 🌐 Shell | 📅 2024-01-25- Loads completions for `ssh` from `~/.ssh/config`.
* [supabase](https://github.com/Taimoor-Tariq/zsh-supabase) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-01-13 - Tab completions for the [supabase cli](https://supabase.com/docs/guides/cli/getting-started)
* [tailscale-ssh](https://github.com/Seraphin-/zsh-tailscale-ssh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-03-05 - Provides host completion based off tailscale status. It automatically strips the MagicDNS suffix, if present.
* [umake](https://github.com/zlsun/umake) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-03-05 - Tab completion for Ubuntu umake.
* [uv](https://github.com/lipov3cz3k/zsh-uv) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2024-11-24 - Tab completion for [uv](https://github.com/astral-sh/uv) ⭐ 78,744 | 🐛 2,633 | 🌐 Rust | 📅 2026-02-06.
* [vorpal](https://github.com/VorpalBlade/vorpal-zsh-completions) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-07-18 - Adds completions for some projects whose upstream appears dead, including [duperemove](https://github.com/markfasheh/duperemove) ⭐ 962 | 🐛 55 | 🌐 C | 📅 2025-10-11, [optimus-manager](https://github.com/Askannz/optimus-manager) ⭐ 2,443 | 🐛 2 | 🌐 Python | 📅 2026-02-05 and [pacutils](https://github.com/andrewgregory/pacutils) ⭐ 130 | 🐛 24 | 🌐 C | 📅 2024-09-16.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-01-20 - Adds alias to open web pages. Only works with Ubuntu 20.
* [wsl-notify](https://github.com/masonc15/wsl-notify-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-09-29 - Uses [wsl-notify-send](https://github.com/stuartleeks/wsl-notify-send) ⭐ 168 | 🐛 6 | 🌐 Dockerfile | 📅 2024-07-06 to notify when a command takes longer than 15 seconds. Windows-only.
* [aliyun](https://github.com/thuandt/zsh-aliyun) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-05-22 - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli) ⭐ 912 | 🐛 40 | 🌐 Go | 📅 2026-02-04.
* [antibody](https://github.com/sinetoami/antibody-completion) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-11-24 - This plugin provides completion for the [Antibody](https://github.com/getantibody/antibody) ⚠️ Archived plugin manager.
* [cabal (d12frosted)](https://github.com/d12frosted/cabal.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2014-10-21 - Adds autocompletion for cabal.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) ⚠️ Archived - Tab completions for [comonicon](https://github.com/Roger-luo/Comonicon.jl) ⭐ 291 | 🐛 46 | 🌐 Julia | 📅 2025-12-15.
* [completions (northismirror)](https://github.com/NorthIsMirror/zsh-completions) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-05 - Extra completions for ZSH.
* [copilot](https://github.com/scaryrawr/copilot.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-07 - Adds completions for the [GitHub Copilot CLI](https://github.com/features/copilot/cli/).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2014-03-21 - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [deno](https://github.com/marcelohmdias/zsh-deno) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-06-16 - Tab completions for [deno](https://deno.com/).
* [expressvpn](https://github.com/tk7r/zsh-expressvpn) ⭐ 0 | 🐛 0 | 📅 2021-12-27 - Adds tab completions for the [expressVPN](https://www.expressvpn.com/support/vpn-setup/app-for-linux/) client.
* [fluxcd](https://github.com/l-umaca/omz-fluxcd-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-05-24 - Adds tab completion for the [FluxCD command line](https://fluxcd.io/flux/cmd/) tool, as well as some aliases for the most common flux commands.
* [gardenctl](https://github.com/holgerkoser/gardenctl) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-02-20 - Tab completions for the [Gardener](https://github.com/gardener/gardenctl-v2) ⭐ 32 | 🐛 10 | 🌐 Go | 📅 2026-02-06 command-line interface, as well as some aliases for common gardenctl commands
* [git-user-switch](https://github.com/dipodidae/zsh-plugin-git-user-switch) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-11-06 - Switch between multiple GitHub user accounts. It automatically updates both your SSH configuration and GitHub CLI (gh) authentication..
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) ⭐ 0 | 🐛 0 | 📅 2022-10-06 - ZSH completions for gitlab-ci-multi-runner.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-07-18 - Completions for <https://hashlink.haxe.org/>.
* [jenv](https://github.com/cmuench/zsh-jenv) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-09-17 - Tab completions for [jEnv](https://github.com/jenv/jenv) ⭐ 6,532 | 🐛 77 | 🌐 Shell | 📅 2025-12-24.
* [joe](https://github.com/corvofeng/joe-completion) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2018-09-07 - Adds completions for [joe](https://github.com/karan/joe) ⭐ 2,873 | 🐛 33 | 🌐 Go | 📅 2024-05-30 gitignore editor.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) ⭐ 0 | 🐛 0 | 📅 2017-07-23 - ZSH completions for jtool.
* [jx](https://github.com/haysclark/zsh-jx) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-01-07 - Adds tab completions for the Jenkins-X cli.
* [ls-go](https://github.com/MohamedElashri/ls-go-zsh) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2024-06-03 - Adds some useful aliases for [ls-go](https://github.com/acarl005/ls-go) ⭐ 222 | 🐛 6 | 🌐 Go | 📅 2024-11-16.
* [misc-completions](https://github.com/syohex/zsh-misc-completions) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-23 - Adds completions for more unix and perl commands.
* [myincr](https://github.com/gaojunbin/zsh-myincr/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-06-05 - Speeds up pasting with autosuggest and incr.
* [newman](https://github.com/selop/newman-autocomplete) ⭐ 0 | 🐛 0 | 📅 2016-10-17 - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman) ⭐ 7,181 | 🐛 308 | 🌐 JavaScript | 📅 2026-02-06.
* [pagerduty](https://github.com/jedelson-pagerduty/pagerduty-omz-plugin) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-09-08 - Adds completions for the pagerduty [cli](https://github.com/martindstone/pagerduty-cli) ⭐ 94 | 🐛 17 | 🌐 TypeScript | 📅 2024-10-30
* [prettier](https://github.com/sambergo/zsh-prettier-completion/) ⭐ 0 | 🐛 0 | 📅 2022-09-07 - Tab completion for [prettier](https://prettier.io/.)
* [sdkman (yongxingzhao)](https://github.com/yongxingzhao/zsh-sdkman) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-27 - Add tab completions for [sdkman](https://sdkman.io/).
* [skate-actions](https://github.com/mjmccull0/skate-actions) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-31 - Tab completions for [skate](https://github.com/charmbracelet/skate) ⭐ 1,717 | 🐛 12 | 🌐 Go | 📅 2025-12-22 personal key-value store.
* [tio](https://github.com/JBarberU/zsh-tio) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-06-16 - Add tab completions for tio
* [tofu](https://github.com/marknefedov/oh-my-zsh-tofu) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-09 - Autoloads tab completions for `tofu`.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) ⭐ 0 | 🐛 0 | 📅 2015-12-25 - Provides autocomplete features for the [vertx](https://vertx.io/) command.
* [zenquotes](https://github.com/aminelch/zenquotes) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-18 - Displays a random quote from [zenquotes.io](https://zenquotes.io).
* [zpacman](https://github.com/Yttehs-HDX/zsh-zpacman/) ⭐ 0 | 🐛 0 | 📅 2024-10-24 - Add tab completions for [zpacman](https://github.com/Yttehs-HDX/zpacman.git) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-06-07.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.

## Themes

* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH which uses [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28 - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) ⭐ 20,388 | 🐛 128 | 🌐 Shell | 📅 2025-12-24 - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status decorators.
* [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts) ⭐ 26,221 | 🐛 182 | 🌐 Shell | 📅 2024-03-22. It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24, [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18, and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions) ⚠️ Archived.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous prompt inspired by [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived and [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 that's easily extensible and extremely configurable. It supports async segments using [zsh-async](https://github.com/mafredri/zsh-async) ⭐ 810 | 🐛 20 | 🌐 Shell | 📅 2023-11-15.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) ⭐ 6,300 | 🐛 134 | 🌐 Python | 📅 2024-03-19 - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) ⭐ 6,300 | 🐛 134 | 🌐 Python | 📅 2024-03-19 - A [powerline](https://github.com/Lokaltog/vim-powerline) ⚠️ Archived-like prompt for Bash, ZSH and Fish. Includes decorators for `git`/`svn`/`hg`/`fossil` branch, last command exit status, shortened path to current directory and the current python virtualenv and is easy to customize/extend.
* [liquidprompt](https://github.com/nojhan/liquidprompt) ⭐ 4,628 | 🐛 35 | 🌐 Shell | 📅 2025-12-15 - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) ⭐ 3,696 | 🐛 56 | 🌐 Shell | 📅 2022-06-30 - An opinionated prompt for bash and ZSH.
* [powerline-go](https://github.com/justjanne/powerline-go) ⭐ 2,864 | 🐛 81 | 🌐 Go | 📅 2026-01-14 - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) shell, and is easy to extend.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) ⭐ 2,853 | 🐛 93 | 🌐 Makefile | 📅 2024-07-29 - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt) ⭐ 1,765 | 🐛 59 | 🌐 Haskell | 📅 2023-11-08 - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) ⭐ 1,484 | 🐛 0 | 🌐 Shell | 📅 2025-06-15 - A Minimalistic and Dark ZSH theme.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) ⚠️ Archived - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) ⭐ 1,215 | 🐛 10 | 🌐 Shell | 📅 2022-12-23 - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) ⭐ 1,083 | 🐛 0 | 📅 2018-03-26 - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [typewritten](https://github.com/reobin/typewritten) ⭐ 933 | 🐛 0 | 🌐 Shell | 📅 2025-01-01 - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
* [materialshell](https://github.com/carloscuesta/materialshell) ⭐ 841 | 🐛 0 | 🌐 Shell | 📅 2025-12-12 - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
* [gbt](https://github.com/jtyr/gbt) ⭐ 557 | 🐛 2 | 🌐 Go | 📅 2024-02-22 - Go Bullet Train is a very customizable prompt builder inspired by Bullet Train and [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 that runs much faster. Includes many different status cars. Includes a [prompt-forwarding](https://github.com/jtyr/gbt#prompt-forwarding) ⭐ 557 | 🐛 2 | 🌐 Go | 📅 2024-02-22 feature than enables the user to forward their user-defined prompt to a remote machine and have the same-looking prompt across all machines via SSH but also in Docker, Kubectl, Vagrant, MySQL or in Screen without the need to install anything remotely.
* [jovial](https://github.com/zthxxx/jovial) ⭐ 546 | 🐛 3 | 🌐 Shell | 📅 2025-06-16 - Shows decorators for host, user, path, development environment, `git` branch, and which `python` venv is active.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) ⭐ 539 | 🐛 0 | 📅 2020-10-16 - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [silver](https://github.com/reujab/silver) ⭐ 496 | 🐛 22 | 🌐 Rust | 📅 2024-02-21 - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23. A faster rust port of [bronze](https://github.com/reujab/bronze) ⚠️ Archived. Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Very configurable, includes `git` status decorations.
* [wild-cherry](https://github.com/mashaal/wild-cherry) ⭐ 482 | 🐛 7 | 🌐 Less | 📅 2023-03-18 - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 - A simple ZSH theme, optimized for `git` usage.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) ⭐ 401 | 🐛 12 | 🌐 Shell | 📅 2019-05-27 - Based on [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
* [common](https://github.com/jackharrisonsherlock/common) ⭐ 363 | 🐛 1 | 🌐 Shell | 📅 2026-01-31 - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) ⭐ 360 | 🐛 3 | 🌐 Vim script | 📅 2022-07-26 - A simple, fast & cool prompt.
* [purify (kyoz)](https://github.com/kyoz/purify) ⭐ 360 | 🐛 3 | 🌐 Vim script | 📅 2022-07-26 - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) ⭐ 358 | 🐛 5 | 🌐 Shell | 📅 2025-01-30 - Includes account info, root user, using ssh, directory lotation, write permission, and vcs info decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) ⭐ 344 | 🐛 6 | 🌐 Shell | 📅 2024-06-18 - Includes decorations for current time, `git` status, last command run time in milliseconds, and the exit status of the last command. Requires coreutils on macOS.
* [alien](https://github.com/eendroroy/alien) ⭐ 342 | 🐛 9 | 🌐 Shell | 📅 2025-10-30 - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) ⭐ 336 | 🐛 10 | 🌐 Shell | 📅 2025-01-01 - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
* [headline](https://github.com/Moarram/headline) ⭐ 327 | 🐛 1 | 🌐 Shell | 📅 2025-10-14 - A responsive ZSH theme featuring Git status information and a colored line above the prompt.
* [shellder](https://github.com/simnalamburt/shellder) ⭐ 299 | 🐛 12 | 🌐 Shell | 📅 2022-06-20 - Minimal theme with a `git` branch decorator. Requires a Powerline-compatible font.
* [dracula](https://github.com/dracula/zsh) ⭐ 290 | 🐛 9 | 🌐 Shell | 📅 2024-08-01 - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) ⭐ 288 | 🐛 2 | 🌐 Shell | 📅 2025-12-07 - A fast, customizable, pure-shell, asynchronous `git`-aware prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) ⭐ 1,765 | 🐛 59 | 🌐 Haskell | 📅 2023-11-08 and very similar to the "Informative VCS" prompt of fish shell.
* [minimal (subnixr)](https://github.com/subnixr/minimal) ⭐ 275 | 🐛 1 | 🌐 Shell | 📅 2022-06-16 - Minimal yet feature-rich theme.
* [purs](https://github.com/xcambar/purs) ⭐ 264 | 🐛 8 | 🌐 Rust | 📅 2020-02-15 - A fast [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [agnoster (fcamblor)](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) ⭐ 251 | 🐛 0 | 🌐 Shell | 📅 2018-07-05 - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 terminal.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) ⭐ 231 | 🐛 4 | 🌐 Shell | 📅 2025-03-13 - Shows decorations for username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [bearings](https://github.com/liamg/bearings) ⭐ 202 | 🐛 1 | 🌐 Go | 📅 2022-07-20 - A fast, clean, super-customizable shell prompt. Includes decorators for current directory, `git` status, exit code of last command, duration of last command, background jobs & username.
* [shelby](https://github.com/athul/shelby) ⭐ 194 | 🐛 4 | 🌐 Go | 📅 2022-02-06 - Fast, lightweight and minimal prompt written in pure `golang`. Includes decorations for last command exit status, `git` status and the current working directory.
* [vercel](https://github.com/vercel/zsh-theme) ⭐ 194 | 🐛 1 | 📅 2020-10-05 - Minimalist theme with `git` status decorations.
* [zeit](https://github.com/zeit/zeit.zsh-theme) ⭐ 194 | 🐛 1 | 📅 2020-10-05 - Optimized for dark backgrounds, includes `git` status information.
* [polyglot](https://github.com/agkozak/polyglot) ⭐ 193 | 🐛 5 | 🌐 Shell | 📅 2025-01-01 - a dynamic prompt for `zsh`, `bash`, `ksh93`, `mksh`, `pdksh`, `dash`, and busybox `ash` that uses basic ASCII symbols (and color, when possible) to show username, whether it is a local or remote `ssh` sesssion, abbreviated path, `git` branch and status, exit status of last command if non-zero, any virtual environment created with `virtualenv`, `venv`, `pipenv`, `poetry`, or `conda`.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) ⭐ 171 | 🐛 2 | 🌐 Shell | 📅 2025-08-04 - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) ⭐ 164 | 🐛 3 | 🌐 Shell | 📅 2025-11-21 - A minimalistic theme inspired by old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) ⭐ 159 | 🐛 9 | 🌐 Shell | 📅 2022-05-02 - Prezto prompt with the information you need the moment you need it.
* [lean](https://github.com/miekg/lean) ⭐ 158 | 🐛 0 | 🌐 Shell | 📅 2025-12-19 - Inspired by [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15. Has decorators for `git` status information, exit status of last command run, and the elapsed time of last command.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) ⭐ 151 | 🐛 1 | 🌐 Shell | 📅 2025-04-22 - Minimalist ZSH theme with `git` status displayed.
* [powerline](https://github.com/carlcarl/powerline-zsh) ⭐ 132 | 🐛 0 | 🌐 Python | 📅 2022-07-04 - A [Powerline](https://github.com/Lokaltog/vim-powerline) ⚠️ Archived-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash) ⭐ 15 | 🐛 0 | 📅 2013-01-21. Displays virtualenv, `git` status information and the exit code of the last command run.
* [gruvbox (sbugzu)](https://github.com/sbugzu/gruvbox-zsh) ⭐ 126 | 🐛 1 | 🌐 Shell | 📅 2023-11-13 - Based on [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) ⭐ 15,162 | 🐛 157 | 🌐 Vim Script | 📅 2025-04-20 `vim` plugin.
* [lambda-pure](https://github.com/marszall87/lambda-pure) ⭐ 124 | 🐛 2 | 🌐 Shell | 📅 2022-06-16 - A minimal ZSH theme, based on [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15, with added Node.js version decorator.
* [021011](https://github.com/guesswhozzz/021011.zsh-theme) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Minimalist. Includes a single `git` marker for VS Code.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Minimalist, includes `git` status decorations.
* [ortiz (guezwhoz)](https://github.com/guesswhozzz/guezwhoz-zsh-theme) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Simplified fork of [eriner](https://github.com/zimfw/eriner) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 with `git` status, `kubectl` context and elapsed time decorations.
* [ultima](https://github.com/egorlem/ultima.zsh-theme) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Minimalist, includes `git` status and current directory decorators.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) ⭐ 119 | 🐛 7 | 🌐 Haskell | 📅 2024-01-03 - A [Powerline](https://github.com/powerline/powerline) ⭐ 14,701 | 🐛 239 | 🌐 Python | 📅 2024-09-30 clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) ⭐ 117 | 🐛 1 | 📅 2021-02-23 - Minimalist prompt that includes `git` information.
* [prezto\_powerline](https://github.com/davidjrice/prezto_powerline) ⭐ 117 | 🐛 13 | 📅 2019-12-22 - Powerline for prezto. Shows git information, RVM version.
* [zsh2000](https://github.com/consolemaverick/zsh2000) ⭐ 117 | 🐛 1 | 🌐 Shell | 📅 2023-05-30 - Theme which resembles Powerline and includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [kiss](https://github.com/rileytwo/kiss) ⭐ 112 | 🐛 1 | 🌐 Vim script | 📅 2020-11-27 - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
* [pi](https://github.com/tobyjamesthomas/pi) ⭐ 111 | 🐛 0 | 📅 2019-03-11 - A minimalist theme with `git` status decorations.
* [astro](https://github.com/iplaces/astro-zsh-theme) ⭐ 108 | 🐛 0 | 📅 2020-02-13 - Based on the `ys` and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes.
* [daivasmara](https://github.com/Daivasmara/daivasmara.zsh-theme) ⭐ 88 | 🐛 0 | 📅 2020-07-06 - Chill theme with decorators for current directory (truncated if necessary) and `git` information, including time since last commit.
* [heapbytes](https://github.com/heapbytes/heapbytes-zsh) ⚠️ Archived - Includes decorators for current directory, tun0 ip if on a VPN, wlan ip when not on VPN and `git` information.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) ⭐ 77 | 🐛 1 | 🌐 Shell | 📅 2024-04-13 - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23. Works best with [nerdfonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [powerless](https://github.com/martinrotter/powerless) ⭐ 76 | 🐛 0 | 🌐 Shell | 📅 2020-05-14 - Tiny & simple pure ZSH prompt inspired by powerline.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) ⭐ 74 | 🐛 3 | 🌐 Shell | 📅 2022-07-27 - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
* [odin](https://github.com/tylerreckart/odin) ⭐ 71 | 🐛 0 | 🌐 Makefile | 📅 2018-02-09 - Odin is a `git`-flavored ZSH theme.
* [minimal-terminal](https://github.com/Lissy93/minimal-terminal-prompt) ⭐ 69 | 🐛 1 | 🌐 Shell | 📅 2024-01-17 - Includes decorators for username\@host, current directory, `git` information and the last command's exit code.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) ⭐ 69 | 🐛 0 | 📅 2015-12-10 - oh-my-zsh's Node.js theme, broken out to make it easier to use with other plugin managers.
* [zhiyin](https://github.com/AmyangXYZ/zhiyin-zsh-theme) ⭐ 69 | 🐛 0 | 🌐 Shell | 📅 2024-08-23 - Includes decorators for user @ host, current working directory and `git` status information.
* [statusline](https://github.com/el1t/statusline) ⭐ 68 | 🐛 3 | 🌐 Shell | 📅 2019-08-14 - A responsive ZSH theme that provides informational segments when you need them.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03 - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) ⭐ 67 | 🐛 0 | 📅 2020-04-26 -  Inspired by the [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes `git` status decorations.
* [blox](https://github.com/yardnsm/blox-zsh-theme) ⭐ 60 | 🐛 0 | 🌐 Shell | 📅 2022-11-01 - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets], and you can add blocks by simply creating a function.
* [kali-like](https://github.com/clamy54/kali-like-zsh-theme) ⭐ 60 | 🐛 0 | 🌐 Shell | 📅 2025-10-31 - Inspired by the Kali Linux default ZSH theme. Includes decorators for user\@host, current directory and `git` information.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) ⭐ 59 | 🐛 0 | 🌐 Shell | 📅 2022-12-11 - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt) ⭐ 20,388 | 🐛 128 | 🌐 Shell | 📅 2025-12-24.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) ⭐ 55 | 🐛 0 | 📅 2022-06-15 - Minimal, clean theme with `git` support.
* [gitsome](https://github.com/mtully/gitsome) ⭐ 54 | 🐛 0 | 📅 2013-04-15 - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) ⭐ 621 | 🐛 5 | 📅 2013-04-10 color scheme.
* [slimline](https://github.com/mengelbrecht/slimline) ⭐ 53 | 🐛 1 | 🌐 Shell | 📅 2021-01-02 - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [rafiki](https://github.com/akabiru/rafiki-zsh) ⭐ 52 | 🐛 0 | 📅 2018-09-21 - Adds emojis to your ZSH terminal.
* [bronze](https://github.com/reujab/bronze) ⚠️ Archived - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [kali](https://github.com/h4ck3r0/kali-theme) ⭐ 51 | 🐛 3 | 🌐 Shell | 📅 2026-01-18 - Includes `git` decorations.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) ⭐ 51 | 🐛 2 | 🌐 Shell | 📅 2019-11-24 - Theme optimized for dark terminal themes.
* [roundy](https://github.com/nullxception/roundy) ⭐ 51 | 🐛 0 | 🌐 Shell | 📅 2025-10-28 - Fast, cute and roundy theme. Includes decorators for `git` status, current directory and last command execution time. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 and a unicode-capable terminal application.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) ⭐ 50 | 🐛 4 | 🌐 Shell | 📅 2016-04-28 - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
* [gndx](https://github.com/gndx/gndx-zsh-theme) ⭐ 49 | 🐛 0 | 📅 2023-07-04 - Includes `git` status, hostname, directory and last command exit status decorations.
* [pre](https://github.com/leandromatos/pre-theme) ⭐ 49 | 🐛 3 | 🌐 Shell | 📅 2023-06-05 - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [ducula](https://github.com/janjoswig/Ducula) ⭐ 48 | 🐛 1 | 🌐 Shell | 📅 2025-11-17 - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) ⭐ 48 | 🐛 1 | 📅 2016-09-30 - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2024-01-30 - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme for pentesters which includes the date, time, and IP address for pentest logging.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) ⭐ 46 | 🐛 0 | 📅 2019-06-16 - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) ⭐ 45 | 🐛 1 | 📅 2016-04-21 - Solarized powerline variant.
* [filthy](https://github.com/molovo/filthy) ⭐ 44 | 🐛 0 | 🌐 Shell | 📅 2025-07-10 - A disgustingly clean ZSH prompt. Includes decorators for path to `git` root when in a `git` repository, `git` status, prompt character based on exit status of last command run, and the execution time of the last run command.
* [absolute](https://github.com/NelsonBrandao/absolute) ⭐ 41 | 🐛 0 | 📅 2019-04-08 - Very clean looking theme with decorators for `git` status, `node` version and the exit code from the last command.
* [oh-my-via](https://github.com/badouralix/oh-my-via) ⭐ 41 | 🐛 2 | 🌐 Shell | 📅 2023-11-27 - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [blaze](https://github.com/danieltodor/blaze) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2025-12-03 - Visually similar to powerline. Requires `make` and `g++`. Works best with your terminal set to use a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Includes decorators for current directory, execution time of last command, exit status of last command, `git` status information, date, time, username and host. Can be extended with custom segments.
* [bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 - A clear and informative two-lined prompt. Includes `git` status optimized for large repositories.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) ⭐ 38 | 🐛 0 | 📅 2021-05-23 - Shows active Python version and `git` decorations in the prompt.
* [igeek](https://github.com/Saleh7/igeek-zsh-theme) ⭐ 38 | 🐛 1 | 🌐 Shell | 📅 2022-04-27 - Displays system information when starting a new terminal session.
* [quantum](https://github.com/calebephrem/quantum-zsh) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2026-01-30 - Sleek, dynamic ZSH theme built for speed, style, and shell supremacy. Whether you're deep in Git or just vibing in your terminal, Quantum adapts to your flow.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) ⭐ 38 | 🐛 0 | 📅 2021-05-23 - Includes `git` status decorations and conda/virtualenv status.
* [windows](https://github.com/juliavallina/windows-zsh-theme/) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-09-28 - Inspired by the Windows Command Prompt. Includes a decorator for the current directory.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) ⭐ 38 | 🐛 0 | 📅 2021-05-23 - Includes conda and venv status.
* [aterminal](https://github.com/guiferpa/aterminal) ⭐ 37 | 🐛 3 | 🌐 Shell | 📅 2024-07-08 - Displays Node.js, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) ⭐ 36 | 🐛 0 | 📅 2016-03-12 - Based on the ys theme, with added Node.js version (from NVM plugin).
* [itg](https://github.com/itsthatguy/itg.zsh-theme) ⭐ 35 | 🐛 10 | 🌐 Vim script | 📅 2018-09-18 - itsthatguy's theme.
* [catpuccin](https://github.com/JannoTjarks/catppuccin-zsh) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2026-01-19 - Minimalist theme. Includes decorators for current directory, exit status of last command and `git` status.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) ⭐ 33 | 🐛 0 | 📅 2020-02-26 - A macOS oh-my-zsh shell theme with cute emoji based on the Powerline Vim plugin.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) ⭐ 33 | 🐛 0 | 📅 2020-02-26 - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh) ⭐ 2,853 | 🐛 93 | 🌐 Makefile | 📅 2024-07-29.
* [nothing](https://github.com/eendroroy/nothing) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2023-11-16 - Lightning fast and really simple because it has almost nothing in it.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) ⭐ 32 | 🐛 0 | 🌐 Shell | 📅 2023-03-15 - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or `~` when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) ⭐ 31 | 🐛 5 | 🌐 Shell | 📅 2023-11-12 - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
* [imp](https://github.com/igormp/Imp) ⭐ 30 | 🐛 0 | 🌐 Shell | 📅 2024-11-05 - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) ⭐ 14,930 | 🐛 7 | 🌐 Shell | 📅 2025-10-18 and optimized for dark backgrounds.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) ⭐ 30 | 🐛 0 | 📅 2021-03-13 - Theme for dark terminals, includes `git` decorations in the right-side prompt.
* [cloudy](https://github.com/Huvik/Cloudy) ⭐ 29 | 🐛 0 | 📅 2016-12-22 - Minimal cloudy ZSH theme.
* [zen (cybardev)](https://github.com/cybardev/zen.zsh) ⭐ 29 | 🐛 0 | 🌐 Shell | 📅 2025-03-12 - A minimalist theme for `*NIX` systems. Includes decorators for execution time of last command run, curreent directory and vcs status information.
* [zigbar](https://github.com/dbushell/zigbar) ⭐ 29 | 🐛 0 | 📅 2025-12-01 - Written in zig. Includes decorators for `git` status, current directory. Requires a [Nerd Font](https://www.nerdfonts.com/font-downloads).
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) ⭐ 28 | 🐛 0 | 🌐 Shell | 📅 2025-04-10 - A minimalist variant of [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15. Pure is not clean, clean is not pure.
* [fall](https://github.com/jottenlips/seasonal-zshthemes) ⭐ 28 | 🐛 2 | 🌐 Shell | 📅 2024-12-31 - Minimalist theme with fall icons. Includes `git` status decorations.
* [seashell](https://github.com/jottenlips/seasonal-zshthemes) ⭐ 28 | 🐛 2 | 🌐 Shell | 📅 2024-12-31 - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
* [transient](https://github.com/olets/zsh-transient-prompt) ⭐ 27 | 🐛 0 | 🌐 Shell | 📅 2025-10-16 - Add a transient prompt to your zsh command line — that is, make your current command line's prompt different from past command lines' prompts. For example, past prompts might not need to show as much contextual information. Or you might want to put past commands on their own line, instead of prefixed by a prompt, for easier selecting and copying. More details at [zsh-transient-prompt.olets.dev](https://zsh-transient-prompt.olets.dev/).
* [almel](https://github.com/Ryooooooga/almel) ⚠️ Archived - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, written in Rust. Includes `git` status, user\@host, last command exit status and working directory decorations
* [bliss](https://github.com/joshjon/bliss-zsh) ⭐ 24 | 🐛 0 | 📅 2021-03-07 - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm](https://github.com/joshjon/bliss-iterm) ⭐ 15 | 🐛 0 | 📅 2019-06-12 color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors) ⭐ 73 | 🐛 1 | 📅 2019-06-17. Includes `git` status decorations.
* [guri](https://github.com/victorfsf/guri) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2018-11-17 - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15's design.
* [multiline](https://github.com/jan-auer/zsh-multiline) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2021-11-21 - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23.
* [skull](https://github.com/tahadostifam/skull-zsh) ⭐ 24 | 🐛 0 | 🌐 Shell | 📅 2024-08-10 - Includes `git` status, python virtual environment and ruby `rvm` status decorations.
* [slick](https://github.com/nbari/slick) ⭐ 24 | 🐛 0 | 🌐 Rust | 📅 2026-02-06 - Inspired by the [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15, [purs](https://github.com/xcambar/purs) ⭐ 264 | 🐛 8 | 🌐 Rust | 📅 2020-02-15 and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2018-12-18. Requires `cargo` for installation.
* [archcraft](https://github.com/mrx04programmer/ZshTheme-ArchCraft) ⭐ 23 | 🐛 1 | 🌐 Shell | 📅 2023-04-13 - Greenish theme, optimized for dark backgrounds. Includes `git` status decorations.
* [eriner](https://github.com/zimfw/eriner) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 prompt theme. Includes `git` status decorations.
* [gcloud-prompt](https://github.com/ocadaruma/zsh-gcloud-prompt) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2019-11-23 - Shows the current gcloud configuration in the prompt.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) ⭐ 23 | 🐛 0 | 📅 2025-05-09 - Seasoning for shells. Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, and [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme) ⭐ 2,853 | 🐛 93 | 🌐 Makefile | 📅 2024-07-29.
* [elessar](https://github.com/fjpalacios/elessar-theme) ⭐ 22 | 🐛 1 | 📅 2020-11-21 - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03. Requires a Powerline-compatible font.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) ⚠️ Archived - Clean and effective ZSH theme with git and npm support.
* [macos](https://github.com/alejandromume/macos-zsh-theme) ⭐ 21 | 🐛 1 | 🌐 Shell | 📅 2024-05-21 - Includes `git` status decorations.
* [pentest-report](https://github.com/sikumy/ohmy-pentest-report) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2025-06-09 - Designed for pentesters, offering a clean and efficient prompt to streamline daily tasks during audits and penetration testing. The theme includes decorators for real-time display of the date, time, IP address, current directory, and the result of the last executed command.
* [x](https://github.com/tharindu899/x-theme) ⭐ 21 | 🐛 0 | 🌐 Shell | 📅 2024-10-07 - Includes customizable banners
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) ⭐ 20 | 🐛 11 | 🌐 Shell | 📅 2022-09-11 - Optimized for [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes decorators for status of last command run, user\@hostname, `git` status, working directory, whether running as root, whether background jobs are running, and other information.
* [emoji](https://github.com/meiokubo-zz/emoji.zsh-theme) ⭐ 20 | 🐛 0 | 📅 2021-04-25 - Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) ⭐ 20 | 🐛 1 | 🌐 Ruby | 📅 2019-10-05 - Written in Ruby, uses powerline characters to simulate pills with useful information.
* [starship (wintermi)](https://github.com/wintermi/zsh-starship) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2024-09-28 - A simple plugin to use the Starship prompt, along with a powerline theme.
* [catppuccin-powerlevel10k-themes](https://github.com/tolkonepiu/catppuccin-powerlevel10k-themes) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2025-12-12 - [Powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28 themes inspired by the [**Catppuccin**](https://catppuccin.com/) color palettes. These themes are available in multiple styles and support all four Catppuccin palettes: **🌻 Latte**, **🪴 Frappé**, **🌺 Macchiato**, and **🌿 Mocha**.
* [astral](https://github.com/xwmx/astral) ⭐ 18 | 🐛 0 | 🌐 Shell | 📅 2025-05-19 - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) ⭐ 22,216 | 🐛 205 | 🌐 Shell | 📅 2024-11-21 plugin. Includes decorators for execution time of last command, when it was run, its exit status, machine name, current path, `ssh` status, and `git` status.
* [furio](https://github.com/hectorpalmatellez/furio-theme) ⭐ 17 | 🐛 0 | 📅 2014-09-17 - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 oh-my-zsh theme. with different colors and emojis.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) ⭐ 17 | 🐛 4 | 🌐 CSS | 📅 2018-07-18 - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
* [sm](https://github.com/blyndusk/sm-theme) ⚠️ Archived - A minimalist theme that includes `git` status decorations.
* [fishbone++](https://github.com/EYH0602/Fishbonepp) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2025-11-12 - A theme influenced by [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) ⭐ 11,169 | 🐛 3 | 🌐 Shell | 📅 2025-05-30 theme fishbone and [oh-my-zsh](https://github.com/ohmyzsh) theme [typewritten](https://github.com/reobin/typewritten) ⭐ 933 | 🐛 0 | 🌐 Shell | 📅 2025-01-01. Includes decorators for current directory, `git` status, exit status of last command.
* [lime](https://github.com/yous/lime) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2025-12-09 - Simple and easily customizable ZSH theme.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2018-03-08 - Minimal but easily extensible prompt.
* [nerdps1](https://github.com/joknarf/nerdps1) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 - Reminiscent of powerline. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Includes decorators for user\@hostname, `git` information, truncated current directory, python virtualenv, exit status of last command run and the time.
* [sepshell](https://github.com/sepehr/sepshell) ⚠️ Archived - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
* [termuxer](https://github.com/patrick330602/termuxer) ⚠️ Archived - Theme inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 and linuxer.
* [ykali](https://github.com/JeffreyYAJ/ykali-zsh) ⭐ 16 | 🐛 0 | 🌐 Shell | 📅 2025-06-29 - Prints a modifiable banner for each new ZSH session. Includes decorators for username, hostname, current directory, wlan0 IP and `git` information.
* [zero (arlimus)](https://github.com/arlimus/zero.zsh) ⭐ 16 | 🐛 2 | 🌐 Shell | 📅 2024-07-20 - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
* [0i0](https://github.com/0i0/0i0.zsh-theme) ⭐ 15 | 🐛 0 | 📅 2021-01-19 - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [promptus](https://github.com/willeccles/promptus) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2025-10-20 - Simple, minimalist and configurable shell prompt program in C which can be used to make your prompt the same on any shell. Includes exit code and working directory decorations.
* [skill (asafaeirad)](https://github.com/ASafaeirad/oh-my-zsh-skill-theme) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2022-12-27 - Includes decorations for working directory, `git` working branch, working directory status and tracking branch status.
* [skill (frontendmonster)](https://github.com/frontendmonster/oh-my-zsh-skill-theme) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2022-12-27 - Optimized for a dark terminal, displays `git` status decorations.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) ⭐ 14 | 🐛 0 | 📅 2020-12-25 - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ⭐ 14 | 🐛 0 | 📅 2016-09-23 - Simple, clean, and beautiful theme.
* [parrot](https://github.com/trabdlkarim/parrot-zsh-theme) ⭐ 14 | 🐛 0 | 🌐 Shell | 📅 2023-11-10 - Based on Parrot OS bash theme. Includes decorators for user\@host, `git` information, exit status of last command, time and current directory.
* [purity](https://github.com/petermbenjamin/purity) ⚠️ Archived - Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme and the [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 prompt.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) ⭐ 13 | 🐛 0 | 📅 2016-05-28 - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme, with small changes.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2022-03-05 - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows. Includes `node` and `git` status decorations.
* [dragon (sabertaximi)](https://github.com/sabertazimi/dragon-zsh-theme) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2026-01-28 - Minimalistic, includes `git` status information.
* [git-prompt (awgn)](https://github.com/awgn/git-prompt) ⭐ 13 | 🐛 0 | 🌐 Haskell | 📅 2024-07-05 - A fast `git` prompt for `bash`, `zsh` and `fish`.
* [neon](https://github.com/sahariko/neon) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2020-12-10 - A pretty and minimal ZSH theme with `git` decorations.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) ⭐ 13 | 🐛 1 | 📅 2019-06-17 - Allows display of host information, includes `git` branch decoration.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2016-12-08 - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 theme.
* [smail](https://github.com/nimacpp/themes-zsh) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2024-03-12 - Includes decorators for `git` status, current directory and exit status of last command run.
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) ⭐ 13 | 🐛 1 | 🌐 Shell | 📅 2020-04-07 - Colorful theme with `git` status.
* [zshpower](https://github.com/snakypy/zshpower) ⭐ 13 | 🐛 2 | 🌐 Python | 📅 2022-11-10 - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
* [acenoster](https://github.com/himdek/Acenoster-ZSH-Theme) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2024-05-26 - A multi-purpose theme with very detailed `git` and `mercurial` support. Also includes decorators for AWS profile name, virtual environment name if any, number of background tasks, current directory and previous command's exit code if non-zero.
* [aloy (garethclews)](https://github.com/garethclews/aloy) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2024-05-01 - Fork of [@elenapan's](https://github.com/elenapan/dotfiles) ⭐ 3,865 | 🐛 17 | 🌐 Lua | 📅 2025-09-17 lena theme. Includes magic enter from subnixr's [minimal](https://github.com/subnixr/minimal) ⭐ 275 | 🐛 1 | 🌐 Shell | 📅 2022-06-16 where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
* [aloy (karetsu)](https://github.com/karetsu/aloy) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2024-05-01 - Fork of [@elenapan's](https://github.com/elenapan/dotfiles) ⭐ 3,865 | 🐛 17 | 🌐 Lua | 📅 2025-09-17 lena ZSH theme. extended to give a little more information in it. It also includes the 'magic enter' from subnixr's [minimal](https://github.com/subnixr/minimal) ⭐ 275 | 🐛 1 | 🌐 Shell | 📅 2022-06-16 where hitting enter without any further commands prints out some useful `ls`, `git` and current working directory information.
* [goprompt](https://github.com/NonLogicalDev/shell.async-goprompt) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2025-07-18 - Lightning fast. Includes decorators for truncated current directory, last command duration & exit status, vim-mode indicators, `git` information, datetime and parent process name.
* [minimal2](https://github.com/PatTheMav/minimal2) ⭐ 12 | 🐛 0 | 📅 2019-02-18 - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) ⭐ 275 | 🐛 1 | 🌐 Shell | 📅 2022-06-16 and adapted for [Zimfw](https://github.com/zimfw/zimfw) ⭐ 4,502 | 🐛 26 | 🌐 Shell | 📅 2026-01-08.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2015-03-27 - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [senpai](https://github.com/hiroru/senpai-zsh) ⭐ 12 | 🐛 0 | 📅 2019-08-05 - Clean prompt theme for Devops. Includes decorators for `git` status, the kubernetes context, AWS profile, GCP project and Azure active cloud.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2017-08-31 - Solarized powerline-style theme for ZSH.
* [ultimate](https://github.com/b4b4r07/ultimate) ⚠️ Archived - Minimalist theme with decorators for `git` status, vim mode indicator and shortened path.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) ⭐ 11 | 🐛 0 | 📅 2014-07-03 - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [bruh](https://github.com/haze/bruh) ⭐ 11 | 🐛 0 | 🌐 Zig | 📅 2021-09-14 - Includes `git` status decorations.
* [delta-prompt](https://github.com/cusxio/delta-prompt) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2016-12-05 - A minimal ZSH prompt.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) ⭐ 11 | 🐛 0 | 📅 2015-03-29 - A theme with `git` status and exit code of last command run decorators embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived.
* [igorsilva](https://github.com/igor9silva/igorsilva-zsh-theme) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2024-08-16 - Shows current directory, customizable delimiter, current branch, and `git` status decorators.
* [newt](https://github.com/softmoth/zsh-prompt-newt) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2021-03-31 - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) ⭐ 11 | 🐛 0 | 📅 2015-12-28 - A two-line version of powerline: one for information, one for input.
* [croque](https://github.com/Ryooooooga/croque) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-02-03 - Powerline-inspired theme with decorators for OS, user\@host, `git` information, `git` username, current directory and exit status of last command.
* [fish (raniconduh)](https://github.com/Raniconduh/zshfish) ⭐ 10 | 🐛 1 | 🌐 Shell | 📅 2024-03-22 - ZSH theme reminiscent of the default `fish` shell theme. Includes `git` status decorations.
* [fluent-git](https://github.com/RobertKozak/fluent-git) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2023-11-01 - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [hometown](https://github.com/olets/hometown-prompt) ⭐ 10 | 🐛 3 | 🌐 Shell | 📅 2025-02-06 - A feature rich, high performance `git`-aware ZSH theme with segments for the user, host, time, the current working directory and its parent, and detailed full Git status within a Git repo.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) ⚠️ Archived - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
* [mnml](https://github.com/mnml-theme/prompt) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2023-11-21 - Minimal theme with `git` status decorations.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2016-04-06 - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [nord](https://github.com/TyWR/Nord-zsh) ⭐ 10 | 🐛 0 | 📅 2019-07-25 - Includes `git` status decorations and displays the active conda environment.
* [nox](https://github.com/kbrsh/nox) ⭐ 10 | 🐛 0 | 🌐 Vim script | 📅 2021-07-08 - Dark theme, displays the current working directory and git status.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) ⭐ 10 | 🐛 1 | 📅 2017-04-08 - Based on af-magic and posh-git.
* [susi](https://github.com/carcruz/susi-zsh-iterm) ⭐ 10 | 🐛 0 | 📅 2019-02-07 - Includes `git` status decorations and an accompanying iTerm2 color scheme.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2018-06-27 - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, designed to disclose information contextually, with a powerline aesthetic.
* [bender](https://github.com/specious/bender) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2024-12-30 - Fancy two-line prompt with git integration.
* [capsule](https://github.com/42LM/capsule) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2025-03-21 - A simple single file terminal prompt that is completely customizable. Display is divided into capsules (`TIMER` > `DIR` > `GIT` > `GIT ACTION`).
* [clean (akz92)](https://github.com/akz92/clean) ⭐ 9 | 🐛 0 | 📅 2017-10-26 - Minimalist ZSH theme.
* [dfrx](https://github.com/Dofoerix/Dfrx-Prompt-Theme) ⭐ 9 | 🐛 0 | 📅 2026-01-22 - Oh-My-Posh theme. Includes decorators for current directory, execution time of last command, root status, and the time.
* [gops](https://github.com/noxer/gops) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2023-02-27 - Fast powerline-like prompt. Includes `git` status, current directory, root status decorations.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) ⭐ 9 | 🐛 0 | 📅 2018-10-10 - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2018-04-27 - Minimal theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2019-07-04 - 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2021-04-14 - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) ⭐ 9 | 🐛 0 | 📅 2018-10-10 - Add-on for [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) ⭐ 9 | 🐛 0 | 📅 2020-12-22 - The original [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with a fullpath in the prompt.
* [theta](https://github.com/eendroroy/theta) ⚠️ Archived - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-08-01 - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [git-prompt-kit](https://github.com/olets/git-prompt-kit) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-11-06 - A configurable set of components for creating feature rich, high performance Git-aware zsh prompts (aka themes) with minimal coding.
* [haribo](https://github.com/haribo/omz-haribo-theme) ⭐ 8 | 🐛 0 | 📅 2015-11-14 - Simple `git` status + timestamp in prompt.
* [iay](https://github.com/aaqaishtyaq/iay) ⭐ 8 | 🐛 9 | 🌐 Rust | 📅 2026-02-04 - A `{ba,z}sh` prompt written in Rust. Includes decorations for the current directory and `git` status.
* [lgbtq](https://github.com/PhoenixSmaug/zsh-lgbtq-themes) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2022-11-01 - A collection of lgbtq themes for your terminal.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) ⭐ 8 | 🐛 0 | 📅 2013-03-03 - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, optimized for [solarized](https://github.com/altercation/solarized) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 terminal themes.
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) ⭐ 8 | 🐛 0 | 📅 2022-02-01 - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [shades of purple](https://github.com/nmcc1212/shades-of-purple-windows-terminal/) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2024-06-27 - Purple theme for Windows terminal that is reminiscent of [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) ⚠️ Archived.
* [zshcomrade](https://github.com/landongn/zshcomrade) ⭐ 8 | 🐛 0 | 📅 2012-09-27 - A ZSH theme, comrade! Includes `git` status decorations.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2020-04-16 - Based on [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) ⭐ 6,903 | 🐛 31 | 🌐 Shell | 📅 2025-11-26. Shows detailed information about `git` status.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme) ⭐ 7 | 🐛 0 | 📅 2020-09-05 - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
* [droolscar](https://github.com/isuke/droolscar) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-02-26 - [Powerline](https://github.com/powerline/powerline) ⭐ 14,701 | 🐛 239 | 🌐 Python | 📅 2024-09-30 variant.
* [elsa](https://github.com/faycito/elsa) ⭐ 7 | 🐛 0 | 📅 2021-07-30 - Includes root status, pwd and `git` status decorations.
* [git-kali](https://github.com/Green0wl/zsh-git-kali-prompt) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-09-14 - Based on [An informative `git` prompt for kali](https://github.com/olivierverdier/zsh-git-prompt) ⭐ 1,765 | 🐛 59 | 🌐 Haskell | 📅 2023-11-08. Includes decorators for `git` status, username\@host, and the current directory.
* [gitster (zimfw)](https://github.com/zimfw/gitster) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-01-17 - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03 prompt theme
* [gruvbox (hgaiser)](https://github.com/hgaiser/gruvbox-zsh) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2022-01-14 - Sets colors from the [gruvbox](https://github.com/morhetz/gruvbox) ⭐ 15,162 | 🐛 157 | 🌐 Vim Script | 📅 2025-04-20 `vim` plugin.
* [heart](https://github.com/gko/heart) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2023-09-18 - Heart themed prompt for light backgrounds.
* [ivabus](https://github.com/ivabus/ivabus-zsh-theme) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2023-02-05 - Inspired by the GitHub Codespaces prompt. Includes decorators for `git` status, username and current directory.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) ⚠️ Archived - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user\@machine in `ssh` sessions and docker containers.
* [lighthaus](https://github.com/lighthaus-theme/zsh) ⭐ 7 | 🐛 0 | 📅 2021-03-02 - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) ⭐ 29 | 🐛 0 | 📅 2021-04-08 theme. Shows `git` information, GitHub/GitLab logo and shows changes as and when they occur.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2019-07-22 - Variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
* [ps1.py](https://github.com/jwodder/ps1.py) ⭐ 7 | 🐛 7 | 🌐 Python | 📅 2025-11-24 - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
* [starship2k](https://github.com/2KAbhishek/starship2k) ⭐ 7 | 🐛 0 | 📅 2023-02-16 - Includes powerline support, multiple languages and a multiline prompt. Includes a decorator for `git` status.
* [toledo](https://github.com/mmatongo/toledo) ⚠️ Archived - Quick minimalist theme with `git` status decorations. Works with `zsh`, `bash`, `dash` and `yash`.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) ⭐ 7 | 🐛 0 | 📅 2013-12-12 - Modified from [mgutz](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/mgutz.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Looks great when using with a [Solarized](https://github.com/altercation/solarized) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 color scheme.
* [yazpt](https://github.com/jakshin/yazpt) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2024-03-12 - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2014-09-04 - Customized version of oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with mercurial support and other changes.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) ⭐ 7 | 🐛 0 | 📅 2019-07-14 - Works best on dark backgrounds, includes `git` status decorations.
* [zp](https://github.com/Karitham/zp) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2022-11-17 - Fast prompt, written in `zig`. Includes `git` status and current directory decorators.
* [zunder](https://github.com/Warbacon/zunder-prompt) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-11-23 - Simple and fast ZSH prompt based on [gitstatus](https://github.com/romkatv/gitstatus) ⭐ 1,783 | 🐛 44 | 🌐 C++ | 📅 2025-10-12.
* [1999](https://github.com/DTan13/zsh1999) ⭐ 6 | 🐛 0 | 📅 2021-04-26 - Powerline-esque theme. Includes `git` status decorations, network and battery status.
* [abhiyan](https://github.com/abhiyandhakal/abhiyan.zsh/) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2026-01-19 - Segmented prompt. Includes decorators for `git` branch, staged file count, unstaged file count & untracked file count, username, current working directory and the time. Requires Powerline-compatible fonts.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) ⭐ 6 | 🐛 1 | 🌐 Shell | 📅 2017-12-04 - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 terminal color scheme. Includes `git` status.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2019-03-25 - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2017-05-18 - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) ⚠️ Archived and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) ⭐ 401 | 🐛 12 | 🌐 Shell | 📅 2019-05-27.
* [asciigit](https://github.com/cemsbr/asciigit) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2017-12-19 - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2025-03-18 - Includes `git` status decorations and current directory.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) ⭐ 6 | 🐛 0 | 📅 2016-11-13 - Another `git`-aware theme.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) ⚠️ Archived - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 dark terminal theme.
* [chi](https://github.com/akinjide/chi) ⭐ 6 | 🐛 0 | 📅 2017-04-20 - A ZSH theme optimized for iTerm 2 users on macOS.
* [chill](https://github.com/JKerboeuf/chill.zsh-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-12-10 - Has decorations for the current working directory, last command exit status and `git` status.
* [clarity](https://github.com/nbitmage/clarity.zsh) ⭐ 6 | 🐛 0 | 📅 2020-08-22 - Designed for for simpleness and extensibility.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) ⭐ 6 | 🐛 0 | 📅 2014-03-27 - Displays decorators for `git` info, whether you're logged in via `ssh`, and the return code of last command.
* [collon](https://github.com/lambdalisue/collon.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2019-11-15 - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
* [cramin](https://github.com/FelipeCRamos/craminzsh) ⭐ 6 | 🐛 0 | 📅 2018-12-11 - Minimal interface with support for GitHub plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh) ⭐ 539 | 🐛 0 | 📅 2020-10-16.
* [doom](https://github.com/CMOISDEAD/doom-zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2024-06-15 - Doom-inspired. Looks similar to powerline. Has customizable segments, decorators for `git` status, `rust`, `Node.js`, `python` and `ruby` versions.
* [enlightenment](https://github.com/w33tmaricich/enlightenment) ⭐ 6 | 🐛 0 | 📅 2022-01-14 - Includes decorations for `git` status, `vi`-mode indicator, and the time for last command to execute.
* [linear](https://github.com/MrYazdan/zsh-linear-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-03-11 - Reminiscent of Powerline. Includes segments with `git` status, Pythonvirtualenv, current directory and current time.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2017-11-20 - Minimalist theme used by discerning llamas.
* [mochi](https://github.com/mochidaz/zsh-themes) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2020-11-04 - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [mochi2](https://github.com/mochidaz/zsh-themes) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2020-11-04 - Minimalist theme. Includes `git` and `hg` status decorations.
* [muslim](https://github.com/nksoff/muslim) ⭐ 6 | 🐛 0 | 📅 2016-08-28 - A simple minimal ZSH prompt theme.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) ⭐ 6 | 🐛 1 | 🌐 Makefile | 📅 2020-03-02 - Minimalist theme, includes `git` status decorations and time.
* [operator](https://github.com/nivv/operator-theme) ⭐ 6 | 🐛 0 | 📅 2021-10-14 - Clean and simple theme, works best with [Menlo for Powerline](https://github.com/abertsch/Menlo-for-Powerline) ⭐ 797 | 🐛 8 | 📅 2021-12-21.
* [pastel](https://github.com/iboyperson/pastel) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2018-11-23 - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-01-09. Includes `git` decorations.
* [saturn](https://github.com/gantoreno/saturn-prompt) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2021-06-27 - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
* [shayan](https://github.com/shayanh/shayan-zsh-theme) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2021-03-10 - Simple theme with `git` status decorations.
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) ⭐ 6 | 🐛 0 | 📅 2013-12-25 - A prompt with happy and sad faces.
* [work-line](https://github.com/afnizarnur/work-line) ⭐ 6 | 🐛 0 | 📅 2017-10-26 - Theme with nice emojis.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) ⭐ 6 | 🐛 0 | 📅 2017-01-19 - A dark optimized ZSH theme.
* [zprompts](https://github.com/z-shell/zprompts) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2023-12-04 - Themes (prompts) that use original `zsh` theming subsystem.
* [zsh1999](https://github.com/DTan13/zsh1999) ⭐ 6 | 🐛 0 | 📅 2021-04-26 - Includes network connectivity, battery and `git` status decorations.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2014-05-25 - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2021-02-15 - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
* [bashi](https://github.com/eli-oat/bashi) ⚠️ Archived - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) ⭐ 621 | 🐛 5 | 📅 2013-04-10 theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) ⭐ 73 | 🐛 1 | 🌐 HTML | 📅 2016-05-11 theme.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-12-03 - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2017-11-06 - Cobalt 2 theme with `git` extensions.
* [do-you-even-nix](https://github.com/miche1e/do-you-even-nix) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2025-02-10 - Simple powerline-esque theme designed to increase [nix](https://nixos.org) power. Includes decorators for username\@hostname, current directory, `git` status, whether you're in a nix shell, and whether there is a flake.nix or shell.nix file in the current directory.
* [duckster](https://github.com/ducky/duckster) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-01-26 - A fork of the [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03 ZSH theme that's more ducky fresh.
* [efritas](https://github.com/erikfritas/efritas) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-03-25 - Includes username, hostname, `venv`, `rvm` and `git` status decorations.
* [fishy2](https://github.com/akinjide/fishy2) ⭐ 5 | 🐛 0 | 📅 2020-01-06 - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2019-07-18 - Custom setup for [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived. Includes `git` status decorations.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-03-23 - Originally a fork of [Bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 adds new virtual environments info to the prompt: Kubernetes, virtualenv, rbenv and Java versions. Includes `git` status integration.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) ⭐ 5 | 🐛 0 | 📅 2020-09-30 - Shows command and `git` status decorations.
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-08-23 - Minimalist theme with `git` decorations.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) ⭐ 5 | 🐛 0 | 📅 2021-05-17 - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [magicmace](https://github.com/zimfw/magicmace) ⭐ 5 | 🐛 1 | 🌐 Shell | 📅 2024-12-19 - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2025-12-11. Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme) ⭐ 5 | 🐛 0 | 📅 2020-10-17 - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
* [nerdp](https://github.com/joknarf/nerdp) ⭐ 5 | 🐛 0 | 📅 2026-02-03 - Nerd powerline-style prompt. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Includes decorators for `git` status, username\@hostname, current directory, Python virtualenv, filesystem usage check, 1 minute CPU load, available memory and the time.
* [powerline-train](https://github.com/sherubthakur/powerline-train) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2016-01-20 - A powerline variant.
* [probe](https://github.com/probe2k/probe_zsh) ⭐ 5 | 🐛 0 | 📅 2020-08-18 - Includes `git` status decorations.
* [s1ck94](https://github.com/zimfw/s1ck94) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [savior](https://github.com/Savecoders/Savior-zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-11-26 - Minimalist theme with decorators for current directory, exit status of last command run and `git` status.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-11-26 - Simple and minimalist theme with `git`, `username` and execution status decorations.
* [softblobby](https://github.com/gsalami00/softblobby/) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-12-22 - A theme for people who love unicorns, pink and purple. Includes decorators for `git` information, current directory, time and username.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) ⭐ 5 | 🐛 0 | 📅 2012-07-02 - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) ⭐ 15,968 | 🐛 218 | 🌐 Vim script | 📅 2024-07-11 terminals.
* [steef (zimfw)](https://github.com/zimfw/steeef) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-08-13 - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [wade](https://github.com/wadehammes/wade.zsh-theme) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2017-10-20 - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, with some visual tweaks.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) ⭐ 5 | 🐛 0 | 📅 2016-08-08 - Based on the 0532 theme.
* [za-prompt](https://github.com/babarot/za-prompt) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2025-12-13 - A fast, minimal, and highly customizable theme with vi-mode support and decorators for `git` status, customizable path, and exit code of last command.
* [zemoji](https://github.com/therzka/zemoji) ⭐ 5 | 🐛 0 | 📅 2019-11-24 - Based on [wild-cherry](https://github.com/mashaal/wild-cherry/tree/master/zsh) ⭐ 482 | 🐛 7 | 🌐 Less | 📅 2023-03-18. Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
* [agnoster (fseguin)](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) ⭐ 4 | 🐛 0 | 📅 2014-10-18 - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) ⭐ 4 | 🐛 0 | 📅 2014-10-18 - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [aplos](https://github.com/sunquan1991/aplos) ⭐ 4 | 🐛 0 | 📅 2017-10-16 - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [async](https://github.com/mje-nz/zsh-themes) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-03-20 - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
* [brunty](https://github.com/Brunty/omz-brunty) ⭐ 4 | 🐛 0 | 📅 2018-08-03 - Includes `git` status decorations.
* [cactus](https://github.com/welksonramos/cactus) ⭐ 4 | 🐛 0 | 📅 2019-04-12 - Minimalist theme with `git` status decorations.
* [clover](https://github.com/tzing/clover.zsh-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-06-18 - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) ⭐ 231 | 🐛 4 | 🌐 Shell | 📅 2025-03-13 and [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) ⭐ 4 | 🐛 0 | 📅 2018-03-11 - Brightly colored theme optimized for dark backgrounds.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-09-20 - Comes with custom `LSCOLORS` and `LS_COLORS` settings files, works with both dark and light terminal themes.
* [endless-dog](https://github.com/qwelyt/endless-dog) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2016-12-28 - oh-my-zsh-compatible theme that mimics grml-zsh-config.
* [es6](https://github.com/suissa/oh-my-zsh-theme-es6) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2025-11-02 - Includes decorators for `git` status and truncated path to current directory.
* [excess](https://github.com/davydovanton/excess.zsh-theme) ⭐ 4 | 🐛 0 | 📅 2015-08-18 - Simple ZSH color theme.
* [github](https://github.com/Debdut/github.zsh-theme/) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-07-14 - A GitHub-inspired theme. Shows decorators for (truncated) current directory, hostname and `git` status. Includes both light and dark modes and detects system settings for that on macOS and Linux.
* [home](https://github.com/sheerun/home) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-11-26 - Pretty and short one-line theme that makes you feel at home.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) ⭐ 4 | 🐛 5 | 🌐 Shell | 📅 2017-03-29 - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-01-03 - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
* [lagnoda](https://github.com/jashezan/lagnoda) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-10-14 Inspired by [agnoster](https://gist.github.com/agnoster/3712874) and `lambda` themes. Includes decorators for username\@hostname, current directory, `git`, `hg`, or `bzr` status, current virtualenv, exit status of last command run, and current aws profile.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2022-09-10 - Simple theme based on lambda with `git` status and virtualenv information.
* [lambda-zen](https://github.com/seamile/lambda-zen) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-12-19 - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 with graphical `git` status decorations.
* [light](https://github.com/InfinityUniverse0/light-zsh) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2024-08-23 - Works best on a light background. Includes decorators for username\@hostname, `git` status and the current directory.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2022-01-05 - Includes decorations for kernel, OS version, uptime and `git`.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-11-15 - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) ⭐ 70 | 🐛 2 | 🌐 Shell | 📅 2021-12-01 plugin.
* [mu](https://github.com/seamile/mu-zsh-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-12-19 - Improves display of multiple `git` statuses. Inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24. Requires a powerline-compatible font.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2017-01-01 - A very basic theme which just features an macOS bike icon.
* [ninik](https://github.com/NimaNikfar/ninik-zsh-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-03-22 - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 and [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) ⭐ 31 | 🐛 5 | 🌐 Shell | 📅 2023-11-12. Includes decorators for OS, current directory, python virtualenv and `git` status. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 or Powerline-patched font.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2023-06-15 - A theme for the [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28 prompt that puts an emphasis on simplcity while still getting important information across.
* [pacmandoh](https://github.com/pacmandoh/omz-theme-pacmandoh) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-07-26 - Enhance your command-line with a sleek theme. Includes decorators for `git` integration, permissions feedback, Python environment support, and dynamic prompts, all in one, customizable with a single installation script and selectable styles.
* [pad](https://github.com/eproxus/pad.zsh-theme) ⚠️ Archived - A concise and colorful oh-my-zsh theme.
* [princess](https://github.com/mellypop/princess) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2024-09-10 - Modeled after [abhiyan.zsh](https://github.com/abhiyandhakal/abhiyan.zsh) ⭐ 6 | 🐛 0 | 🌐 Shell | 📅 2026-01-19 with perhaps a bit too much pink and arguably too few emojis. Includes decorators for current directory and `git` status.
* [pure-agnoster](https://github.com/yourfin/pure-agnoster) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2020-03-07 - Mashup of [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 and [agnoster](https://gist.github.com/3712874). Has `git` decorations and works well with both dark and light terminal backgrounds.
* [rb](https://github.com/rberenguel/rb-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2018-10-25 - Powerline-styled theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) ⭐ 4 | 🐛 0 | 📅 2018-05-12 - Includes `git` status decorations, works well on a dark terminal background.
* [shrug](https://github.com/to-var/shrug-zsh-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-11-09 - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme) ⭐ 3 | 🐛 0 | 📅 2014-11-07, includes `git` status and current directory decorations.
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2019-08-09 - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-11-10 - Powerline-inspired simple theme with `git` decorations.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2019-04-01 - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [staples](https://github.com/dersam/staples) ⭐ 4 | 🐛 0 | 📅 2021-08-27 - Based on [bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12, displays `user@host` if connected through SSH.
* [steef (danihodovic)](https://github.com/danihodovic/steeef) ⭐ 4 | 🐛 0 | 📅 2017-10-12 - Oh-my-zsh steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
* [sugar-free](https://github.com/cbrock/sugar-free) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2017-01-09 - Based on the [Pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-06-27 themes.
* [thm](https://github.com/thm-unix/thm-zshtheme) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2023-09-09 - Includes decorators for virtualenv, current directory and `git` status.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2022-07-26 - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
* [zshify](https://github.com/nrjdalal/zshify) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-12-07 - A minimalistic, one command installation to customize your prompt. Requires [npx](https://docs.npmjs.com/getting-started/installing-npm-packages-locally).
* [zskai](https://github.com/dinizgab/zskai-theme) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2022-12-22 - Simple theme based on Monokai. Includes decorators for user\@hostname, time, `git` status and current working directory.
* [a](https://github.com/chammanganti/a-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-03-22 - Simple theme with current directory and `git` status decorations.
* [achab](https://github.com/niotna/antoinechab-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-01 - Includes decorators for the current folder path, the current user and the current `git` branch. Decorator colors are easily customizable.
* [ale](https://github.com/alepimentel/ale-zsh) ⭐ 3 | 🐛 1 | 📅 2020-10-10 - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
* [antoinechab](https://github.com/antoinechab/antoinechab-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-01 - Includes `git` status, username, time and current directory decorations.
* [baddcafe](https://github.com/dimgatz98/Baddcafe_zsh_theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-12-11 - Provides dynamic system information. Includes decorators for `git` status, cpu usage, memory usage, battery level, local and global IP addresses, current time, current directory and the exit status of the last command run.
* [bandit](https://github.com/Holger-Will/zsh_bandit) ⭐ 3 | 🐛 2 | 📅 2020-08-14 - Another Powerline variant.
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-10-01 - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
* [bashlover](https://github.com/Vu0811/bashlover) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-05-19 - Designed for those who appreciate the powerful features of ZSH shell but still prefer a simple, classic interface similar to the `bash` shell. Includes decorators for `git` information, user\@host and the current working directory
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) ⭐ 3 | 🐛 0 | 📅 2014-11-07 - Inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, but with beer icons.
* [bira](https://github.com/zimfw/bira) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-07-12 - Fork of Oh-My-ZSH [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes decorators for working directory, username\@host, `git` status information, Python [venv](https://docs.python.org/3/library/venv.html) and a status code when the last command had an error.
* [birame](https://github.com/maniat1k/birame) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-08 - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [biratime](https://github.com/vemonet/biratime) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-11-06 - Based on the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme, but displays the date instead of the username in the prompt.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2019-03-24 - Minimal theme, displays `git` information.
* [bluelines](https://github.com/apbarrero/bluelines) ⭐ 3 | 🐛 0 | 📅 2021-03-24 - Clear and blue theme.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2025-11-03 - Multiline theme, best on dark backgrounds.
* [bref](https://github.com/mpostaire/bref-zsh-prompt) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-09-18 - A simple prompt. It includes decorators to display `git` status asynchronously, a notification if the `ssh` session is remote, the battery level and the number of background jobs.
* [brs](https://github.com/evenhold/brs-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2019-01-20 - Displays the current song in the prompt with `audtool`.
* [buster](https://github.com/grantbuster/buster_zsh_theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-06-18 - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
* [calma](https://github.com/luislve17/calma) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-07-13 - Minimalist theme that works well on dark backgrounds. Includes decorators for truncated current directory, `git` information, time, and for the exit status of last command.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme) ⭐ 3 | 🐛 0 | 📅 2021-05-27 - Includes `git` decorations. Requires a powerline-compatible terminal font.
* [cleansh](https://github.com/diegoos/cleansh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-11-07 - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-06-15 - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
* [czsh](https://github.com/Cellophan/czsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-01-20 - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 theme in a container.
* [dango](https://github.com/ann-kilzer/annkilzer.zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-03-24 - Includes decorations for current directory and `git` status.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2021-02-06 - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2021-08-23 - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
* [drkat](https://github.com/katrinaalaimo/drkat-zsh-theme) ⭐ 3 | 🐛 1 | 📅 2021-09-30 - Reminiscent of [Powerline](https://github.com/powerline/powerline) ⭐ 14,701 | 🐛 239 | 🌐 Python | 📅 2024-09-30. Includes directory, `git` status, and hostname decorations.
* [dtheme](https://github.com/OlukaDenis/DTheme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2019-12-03 - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2018-10-25 - A colorful two-line theme with support for `git` and `svn`.
* [gal](https://github.com/x6r/gal) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-12-30 - Minimalist theme based on [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) ⭐ 3 | 🐛 0 | 📅 2012-03-07 - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gitneko](https://github.com/gynamics/zsh-gitneko/) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-01-05 - Has a neko `(^>ω<^)` prompt with `git` status information.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) ⭐ 3 | 🐛 4 | 🌐 Shell | 📅 2020-02-07 - Simple yet informative theme that includes `git` decorations and the return status of the last command.
* [hexagon](https://github.com/diogoazevedos/hexagon) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2019-10-19 - Minimalist ZSH theme based on [geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13.
* [horizontal](https://github.com/nuimk/horizontal) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2019-01-26 - Two line prompt with a horizontal separator.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-12-15 - Works well on a dark background.
* [illusion](https://github.com/shabane/illusion) ⭐ 3 | 🐛 0 | 📅 2022-01-10 - Includes username, current working directory, `git` status and last command status decorators.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) ⚠️ Archived - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [kalsowerus](https://github.com/kalsowerus/kalsowerus.zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-26 - Colorful powerline-inspired multi-line theme, includes decorations for `git` status, directory, last command exit status and `nvm` information.
* [kerneldiego](https://github.com/KernelDiego/kerneldiego-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-04-11 - A minimal and informative Zsh theme with a clean box-style layout, Git integration, and colorful prompt indicators for productivity and visual clarity.
* [kindahv](https://github.com/kshnkvn/kindahv-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-06-19 - A clean ZSH theme with command execution time tracking.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2020-11-27 - Based on [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes `kubectl` context. Has time, directory, and `git` status decorations.
* [logico](https://github.com/logico/logico-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2021-01-19 - Has `git` decorations. Shows remote status and indicator for vi-mode.
* [mau](https://github.com/vichargrave/mau) ⭐ 3 | 🐛 0 | 📅 2021-11-25 - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes.
* [minima](https://github.com/Brolly0204/zsh-minima) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-01-20 - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
* [minimal-os](https://github.com/nkurata/zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-01-14 - A minimalist prompt with helpful `git` status and system-specific decorators.
* [nanofish](https://github.com/tweekmonster/nanofish) ⭐ 3 | 🐛 0 | 📅 2016-05-27 - Adds fish-style directory prompt to nanotech theme.
* [niotna](https://github.com/niotna/niotna-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-11-01 - Includes decorators for `git` status and current directory. Customizable colors.
* [ortiz (andres-ortizl)](https://github.com/andres-ortizl/ortiz-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-12-29 - Fork of [eriner](https://github.com/zimfw/eriner) ⭐ 23 | 🐛 0 | 🌐 Shell | 📅 2025-12-11 with decorations for the interval between commands and k8s context.
* [osx2](https://github.com/RizkiIqbal02/zsh-theme-custom) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2024-03-02 - Based on archcraft. Minimalist. Includes decorator for current directory.
* [persi](https://github.com/persiliao/persi-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-12-07 - Includes `git`, hostname and current directory decorations. Works with both light and dark backgrounds.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) ⚠️ Archived - RDM's basic oh-my-zsh custom theme.
* [river](https://github.com/revir/river-zsh-config) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-05-21 - Dark theme with `git` information.
* [rounded](https://github.com/daniilty/rounded-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-01-01 - Includes current directory and `git` status decorations.
* [snowflake](https://github.com/angelina-tsuboi/snowflake-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-03-04 - An elegant, simple, and neat ZSH theme including an aesthetically pleasing cool color palette that harmonizes with dark themes.
* [t2colorful](https://github.com/AmirhosseinAbutalebi/t2colorful-oh.my.zsh) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2023-04-17 - Includes decorators for `git` information, current directory, last command exit status, and current time.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2018-01-07 - Minimal ZSH theme optimized for dark backgrounds.
* [tarcadia](https://github.com/Tarcadia/tarcadia-zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-10-04 - Based on [jonathan](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/jonathan.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for current directory and `git` status.
* [ulyssesys](https://github.com/UlyssesZh/ulyssesys) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-05-26 - Has decorators for full path to current directory, exit code of last command and `git` status.
* [wormwood](https://github.com/ann-kilzer/annkilzer.zsh-theme) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-03-24 - Includes decorators for last command exit status, current directory and `git` status.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) ⭐ 3 | 🐛 0 | 📅 2018-03-10 - Modified version of oh-my-zsh's [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) ⭐ 2 | 🐛 1 | 📅 2021-02-26 - Includes `git`, `virtualenv` and `rvm` status decorations.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-03-06 - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
* [aftermath](https://github.com/schanur/aftermath) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-08-30 - Get a nice summary line after each command you run in your shell.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-05-12 - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) ⭐ 344 | 🐛 6 | 🌐 Shell | 📅 2024-06-18 themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2019-08-27 - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [archie](https://github.com/dcavalcante/archie) ⭐ 2 | 🐛 0 | 📅 2018-08-30 - Arch Linux inspired ZSH theme. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [arctic-glow](https://github.com/Etto48/arcticglow-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-11-25 - Based on [agnoster](https://gist.github.com/3712874). Includes decorators for `git` status, python virtual environment, current directory, username  and operating system.
* [aub](https://github.com/FraSharp/aub) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-03-19 - Includes decorations for `git` and `hg` status and `username` at `host`.
* [backbone](https://github.com/42LM/backbone-zsh-prompt) ⚠️ Archived - A bare minimum single file prompt, fast as a roadrunner MEEP! MEEP. Includes `git` status and current directory decorations.
* [bar (anki-code)](https://github.com/anki-code/shell-prompt-theme-bar) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-04-10 - Minimalist settings for [p10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28.
* [base](https://github.com/Rodr1goTavares/based-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-06-27 - A minimal and functional ZSH theme designed for developers and sysadmins who frequently work on remote servers, VPS, or VPNs. Includes decorators for your public IP address, `git` status and current directory.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-01-17 - Modified version of [gitster](https://github.com/zimfw/gitster) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2024-01-17 theme for [ZIM](https://github.com/zimfw/zimfw) ⭐ 4,502 | 🐛 26 | 🌐 Shell | 📅 2026-01-08.
* [bigshrimp](https://github.com/taksyon/BigShrimp-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-01-26 - A clear and concise theme that includes decorators for username\@host, current directory and `git` status.
* [bigyls](https://github.com/Bigyls/Bigyls-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-10-18 - Based on [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2024-01-30. Includes decorators for date, time, IP address, `git` status, plugins and current directory.
* [blazux](https://github.com/blazux/omz-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-09-08 - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
* [bluo](https://github.com/varunpbardwaj/bluo) ⭐ 2 | 🐛 0 | 📅 2021-09-17 - Colorful prompt segments reminiscent of [bullet-train](https://github.com/caiogondim/bullet-train.zsh) ⭐ 2,853 | 🐛 93 | 🌐 Makefile | 📅 2024-07-29 or [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28. Includes `git` status decorations.
* [bright-catpuccin](https://github.com/Tailung42/bright_catppuccin_zsh_theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-27 - A vibrant, modern ZSH prompt built on the beautiful Catppuccin Mocha palette with bright color vibes. Includes decorators for `git` status, python `venv`, conda env, smart path truncation, command execution time for long-running commands, optional username\@hostname, smart path truncation, background jobs and command exit status.
* [brisa](https://github.com/ambrisolla/oh-my-zsh-brisa-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-06-17 - Multiline theme based on [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorations for username, host, current directory, and `git` status.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) ⭐ 2 | 🐛 0 | 📅 2020-07-04 - Shows timestamp, large line breaks, git branch and status.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) ⭐ 2 | 🐛 0 | 📅 2020-04-03 - minimalist theme with `git`, nix-shell and virtualenv status decorations.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-08-14 - A theme with an emphasis on the right side (hence the name) of the terminal.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) ⭐ 2 | 🐛 1 | 📅 2021-08-24 - Combination of the of [af-magic](https://github.com/andyfleming/oh-my-zsh) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2013-12-10 and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) ⭐ 20 | 🐛 5 | 🌐 Shell | 📅 2026-02-06 themes. Includes `git` and `virtualenv` status decorations.
* [eucalyptus](https://github.com/relastle/eucalyptus) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-02-09 - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 and [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ⚠️ Archived. Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
* [fishy-lite](https://github.com/sudorook/fishy-lite) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-19 - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) ⭐ 2 | 🐛 0 | 📅 2018-01-14 - Includes status of last command, `git` information and current directory.
* [funkydrac](https://github.com/warshanks/funkydrac) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-11-20 - Multiple Dracula-themed omz themes based on [funky](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/funky.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and an [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) ⭐ 21,443 | 🐛 26 | 🌐 Go | 📅 2026-02-06 theme based on [alien](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/aliens.omp.json) ⭐ 21,443 | 🐛 26 | 🌐 Go | 📅 2026-02-06
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) ⚠️ Archived - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) ⭐ 312 | 🐛 0 | 🌐 Shell | 📅 2024-09-09 with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gitbash](https://github.com/eddieantonio/gitbash-zsh-theme/) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-10-11 - Mimics the default prompt from [Git for Windows](https://gitforwindows.org/). Includes `git` status, user\@host and current directory decorators.
* [halil](https://github.com/5m0k3r/zsh-themes) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-01-09 - Fork of oh-my-zsh's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2019-08-08 - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) ⭐ 0 | 🐛 0 | 🌐 CSS | 📅 2018-10-24 theme. Includes `git` status decorations.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) ⭐ 2 | 🐛 0 | 📅 2019-12-21 - Based on oxide, includes `git` status decorations and current user/host information.
* [happy-coding](https://github.com/lexhuismans/happy-coding/) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-04-22 - Stripped down version of [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) ⭐ 344 | 🐛 6 | 🌐 Shell | 📅 2024-06-18. Includes decorators for time, `git` branch, last command execution time and last command exit status.
* [hietan](https://github.com/Hietan/Hietan_ZshTheme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-08-20 - Includes decorators for current directory, date & time, `git` status and the exit value of the last command run. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [htb](https://github.com/ibyf0r3ns1cs/zsh-htb-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-07-30 - Inspired by the pwnbox on a HackTheBox machine. Includes decorators for user\@host, IP address and the current directory.
* [icicle](https://github.com/JamesConlan96/Icicle) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-09-13 - Includes `git` status decorations, and whether running as root.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-10-18 - Includes `git`, `nvm` and `venv` decorations.
* [imranic](https://github.com/alimranahmed/zsh-imranic-themes) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-02-26 - Minimalist theme with decorators for `git` status, python virtualenv, rvm ruby version, conda version, kube status,  and current directory.
* [infinite](https://github.com/The-Infinitys/zsh-infinite) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-01-13 - A highly customizable and dynamic ZSH theme written in Rust. Infinite offers a powerful CLI tool to manage your ZSH prompt's appearance, allowing for dynamic content, sophisticated coloring, and unique visual separators.
* [integral](https://github.com/Readf0x/integral-prompt) ⭐ 2 | 🐛 3 | 🌐 Go | 📅 2025-12-06 - Math-inspired, includes decorators for time, current directory and `git` status.
* [ivy](https://github.com/ivyhjk/ohmyzsh-theme-ivy) ⭐ 2 | 🐛 0 | 📅 2022-01-04 - Works well on dark backgrounds. Includes user\@host, `git` status and time decorators. Based on the [obraun](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#obraun) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2013-08-21 - Loosely based on the `ys` theme.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) ⭐ 2 | 🐛 0 | 📅 2020-11-25 - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
* [karu](https://github.com/zaari/karu) ⭐ 2 | 🐛 0 | 📅 2020-10-07 - Minimalist single line ZSH prompt.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) ⭐ 2 | 🐛 0 | 📅 2018-01-01 - Theme that includes a few features from other themes.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) ⭐ 2 | 🐛 0 | 📅 2018-10-22 - Colorful theme, includes iTerm 2 color schemes.
* [lambda (bluedragon1221)](https://github.com/bluedragon1221/zsh-lambda-prompt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-03-20 - Includes decorators for current directory and `git` status.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) ⭐ 2 | 🐛 1 | 📅 2022-02-09 - A combination of the Lambda and Fishy themes, includes `git` status decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh) ⭐ 2 | 🐛 0 | 📅 2021-07-19 - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
* [linuxer](https://github.com/patrick330602/linuxer) ⚠️ Archived - Inspired by Yaris Alex Gutierrez's [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) ⭐ 55 | 🐛 0 | 📅 2022-06-15, Yad Smood's `ys`, and the [Bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 theme.
* [maivana](https://github.com/nylo-andry/zsh-themes) ⭐ 2 | 🐛 0 | 📅 2019-09-25 - Includes `kubectl` context, `git` status decorations.
* [mdmini](https://github.com/MarioDena/MDmini) ⭐ 2 | 🐛 0 | 📅 2019-10-17 - Includes `git` and `ssh` status decorations.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-05-08 - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) ⭐ 2 | 🐛 1 | 📅 2014-12-15 - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-06-21 - Minimalist. Includes `vcs` status decorations.
* [nescalante](https://github.com/nescalante/zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-03-12 - Optimized for dark terminal backgrounds, includes `git` decorations.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) ⭐ 2 | 🐛 2 | 🌐 Shell | 📅 2024-06-07 - Minimalist ZSH theme with `git` status decorations.
* [nuqle](https://github.com/Nuqlear/nuqlezsh.zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-06-15 - A simple theme for prezto and oh-my-zsh.
* [oblong](https://github.com/Ansimorph/oblong) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-08-23 - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03 and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
* [odra](https://github.com/ErikBenavides/odra.zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-08-04 - Colorful, works well on dark backgrounds. Includes decorators for `git` status, current directory, username and exit status of the last command.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) ⭐ 2 | 🐛 0 | 📅 2019-10-04 - Works well with dark terminal windows. Includes `git` decorations.
* [omszt](https://github.com/MU001999/omszt) ⭐ 2 | 🐛 0 | 📅 2021-11-24 - Minimalist theme with `git` decorations.
* [otter](https://github.com/OtterArkar/otter-zsh/) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-11-25 - Otter-themed theme with `git` status, user\@host and current directory decorators.
* [page](https://github.com/SLIB53/page-zsh-theme) ⚠️ Archived - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [paroape](https://github.com/ParoaPe/ParoaPe-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-10-18 - Based on [lpha3cho](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2024-01-30
* [pog7x](https://github.com/pog7x/pog7x-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-11-25 - Works with unicode. Includes decorators for `git` information, current directory, last command exit status & execution time, time, virtualenv, nvm, rvm, rust, go, kubernetes context, and elixir.
* [prowpt](https://github.com/alpaca-honke/prowpt) ⭐ 2 | 🐛 2 | 🌐 Shell | 📅 2025-06-13 - Simple, lightweight, and customizable Powerline-like prompt, with decorators for `git` information, user, hostname, current directory, time and exit status of the last command.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-02-16 - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
* [quietline](https://github.com/qwreey/quietline) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - A simple theme inspired by the headline theme. Includes decorators for `git` status, user\@host and current directory.
* [random-emoji-robbyrussell](https://github.com/parwatcodes/random-emoji-robbyrussell) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-12-09 - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) ⭐ 2 | 🐛 0 | 📅 2021-06-04 - Minimal prompt, includes `git` status decorations.
* [renanborgez](https://github.com/renanborgez/ohmyzsh-theme-renanborgez) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-05-25 - Works well on dark backgrounds. Includes decorators for `nvm` and `git` information.
* [risbow](https://github.com/waddupp00/risbow) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-03-18 - A [risto](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/risto.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 inspired ZSH theme with a lolcat like rainbow effect.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2021-05-08 - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) ⭐ 2 | 🐛 0 | 📅 2018-08-23 - A dark theme.
* [russtone](https://github.com/russtone/prompt-russtone) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-05-30 - Inspired by [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 and [sorin](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24. Includes `git` status decorations.
* [rzh](https://github.com/patwhatev/rzh) ⭐ 2 | 🐛 0 | 📅 2016-11-05 - Theme with `git` states indicated by emojis.
* [seti\_UX](https://github.com/ginfuru/iTerm-Seti_UX) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2016-11-13 - A simple oh-my-zsh-compatible theme with a corresponding iTerm 2 color scheme.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) ⭐ 2 | 🐛 0 | 📅 2017-06-11 - An evolution of lean prompt which itself is a rewrite of pure.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2021-07-27 - Includes `git` status, directory, host name, username and time decorations.
* [shiko](https://github.com/regarager/shiko-prompt) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-01-28 - Minimalist prompt with decorators for VCS information and current directory.
* [simpalt](https://github.com/m-lima/simpalt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-11-28 - An information-rich small-footprint theme based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23.
* [simple (rkitover)](https://github.com/rkitover/sh-prompt-simple) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-23 - A simple, lightweight, and nice looking prompt that runs quickly even in very slow shells like MSYS2, Cygwin and WSL. It shows decorations for the short name of the current environment (distribution, OS, etc.) the `git` branch when in a `git` checkout, as well as the last command exit status (green checkmark for success and red X mark for non-zero exit).
* [simplezsh](https://github.com/fr0zn/simplezsh) ⭐ 2 | 🐛 0 | 📅 2019-07-03 - Minimal theme with `git` info display.
* [skondrashov](https://github.com/sergkondr/skondrashov-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-03-06 - Minimalist. Includes decorators for `git` status, current kubernetes context and current AWS profile.
* [spyrhoo](https://github.com/FajarKim/spyrhoo-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-05-07 - Includes time, `git` and current directory decorations.
* [starboy](https://github.com/prdpx7/Starboy) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-02-21 - A simple theme.
* [superkolo](https://github.com/Minipada/superkolo) ⭐ 2 | 🐛 0 | 📅 2020-10-11 - Add date and return status to the [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [suprima-asra](https://github.com/mohdismailmatasin/suprima-asra) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-08-09 - A feature-rich minimal theme inspired by [Ultima](https://github.com/egorlem/ultima.zsh-theme) ⭐ 123 | 🐛 0 | 🌐 Shell | 📅 2026-01-24. Includes decorators for battery status, multi-VCS (`git`, `hg` and `svn`), whether or not it's an `ssh` connection, exit status of last command, command timing, current time, `username@host`, active python `venv`, node version, `docker-compose` detection and project context awareness.
* [sy](https://github.com/ttttmr/sy-zsh-theme) ⭐ 2 | 🐛 2 | 📅 2021-05-06 - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes `git` status decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2017-12-17 - Inspired by theunraveler, uses symbols to display `git` status.
* [tq](https://github.com/kitian616/tq-zsh-theme) ⭐ 2 | 🐛 0 | 📅 2017-06-16 - Displays `git` status, time, requires a Powerline-compatible font.
* [tsotra](https://github.com/nylo-andry/zsh-themes) ⭐ 2 | 🐛 0 | 📅 2019-09-25 - Minimalist theme, includes decorators for `git` status, k8s context, and `rvm` status.
* [tvline](https://github.com/thvitt/tvline) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2020-01-04 - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) theme, adds powerline font enhancements.
* [twilight](https://github.com/Henryws/twilight-prompt) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2025-12-14 - Minimalist, but includes last command exit status, `git` status and `user@hostname` decorations.
* [warmblood](https://github.com/D42H5/warmblood) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2023-06-15 - Based on [darkblood](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `git` information, user\@hostname and the current directory.
* [whale](https://github.com/whalesea520/whale-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-04-12 - Fast reimplementation of the whale theme.
* [yindev](https://github.com/menyinch/yindev-zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-07-01 - Variant of `gndx`. Includes decorations for `git` status and current directory.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) ⭐ 2 | 🐛 0 | 📅 2020-01-31 - Zelda-inspired theme. Includes `git` status decorations.
* [zoo](https://github.com/salamantos/zoo_sh) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2022-09-13 - Casual theme with animal emoji. Includes decorators for current directory, time and `git` status.
* [abzt](https://github.com/stentibbing/abzt-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-13 - No nonsense theme with decorators for `git` status and directory information. Requires a nerdfont.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-10-15 - Includes decorators for `git` status, the name of your AWS profile, the name of your Azure Service Principal, kubernetes context, terraform workspace, last command exit status and current working directory.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) ⭐ 1 | 🐛 0 | 📅 2020-10-31 - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2013-12-10 with dynamic path shortening.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-04-20 - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 that includes user\@hostname and `git` status decorations. Works better with a unicode font.
* [akzsh](https://github.com/awkimball/akzsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-01-20 - Works best with a dark terminal theme, includes `git` decorations.
* [al-magic](https://github.com/Alustrat/al-magic/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-04-19 - Clone of the oh-my-zsh [af-magic](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme with the time added at the right of the prompt.
* [alpha](https://github.com/Republic-Of-Lunar/alpha-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-17 - Includes decorators for username\@hostname and current directory.
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-08 - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
* [apple (aramirol)](https://github.com/aramirol/apple-zsh-custom-themes) ⭐ 1 | 🐛 0 | 📅 2021-10-02 - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes `vcs` status decorations. Colors customizable by setting vars in your `.zshrc`.
* [archmocha](https://github.com/mikkurogue/archmocha/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-03 - Some of [catpucchin](https://github.com/JannoTjarks/catppuccin-zsh) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2026-01-19's mocha theming with an Arch Linux twist. Includes decorators for user\@hostname, current directory and `git` status.
* [avoleo](https://github.com/flameleo11/avoleo-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-03-11 - Features a date and time prompt for each command, as well as a command number in history. In addition, it uses special symbols '⠾' and '⡶' to display `git` information if applicable in the current path. It also supports custom colors based on the Gnome-Terminal default color palette.
* [aws](https://github.com/chiemerieezechukwu/aws-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-10 - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, with an extra decorator to show your `$AWS_PROFILE` when it is set.
* [bahman](https://github.com/bahmanworld/bahman-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-08-30 - Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Has `git` status decorator.
* [barion](https://github.com/SEbbaDK/barion) ⭐ 1 | 🐛 2 | 🌐 Crystal | 📅 2021-10-21 - A fast compiled prompt with a compact `git` status overview. Reminiscent of powerline. Requires [Crystal](https://crystal-lang.org/) to build.
* [bearable](https://github.com/JanmanX/bearable-zsh) ⭐ 1 | 🐛 0 | 📅 2019-01-12 - Works well with dark terminal backgrounds.
* [berghain](https://github.com/meshkinyar/berghain.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-05-18 - Minimalist theme. Includes decorators for the exit code of the last command run and for `git` status.
* [bernkastel](https://github.com/JamesLaverack/bernkastel) ⚠️ Archived - Based on [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorations for kubernetes context, current directory, last command exit status and `git` status.
* [birav2](https://github.com/shahid64/birav2-theme) ⭐ 1 | 🐛 0 | 📅 2020-01-24 - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes `git`, `rvm` and `virtualenv` status decorations.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) ⭐ 1 | 🐛 0 | 📅 2016-11-13 - Based on the existing theme [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [boban](https://github.com/TheEdgeOfRage/boban-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-12-30 - A powerline-style file based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23. Includes decorators for user\@hostname, `git` status, current working directory, python venv, AWS profile, `$KUBECONFIG`, the terraform workspace and the exit status of the last command run. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 for symbols to render properly.
* [born-in-the-purple](https://github.com/LeonardMH/born-in-the-purple) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-08-23 - Simple theme with a purple motif. Inspired by [Pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15.
* [braundo](https://github.com/Braundo/braundo-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-03-14 - Straightforward theme with username, current directory, `git` status, and timestamp.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-10 - BTTF color theme. Includes `git` status decorations.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) ⭐ 1 | 🐛 0 | 📅 2018-08-15 - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ⭐ 14 | 🐛 0 | 📅 2016-09-23 ZSH theme, modified to just display time and directory.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) ⭐ 1 | 🐛 0 | 📅 2021-07-15 - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme that adds a Python virtual environment label to the left of the `git` block.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-01-13 - Based on [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes `git` decorations.
* [burn](https://github.com/Xatra1/burn) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-24 - Includes decorators for user\@hostname and current directory.
* [cafeconbits](https://github.com/ricard-ferrero/cafeconbits-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-14 - Simple theme with a coffee cup icon. Includes decorators for `git` status, current directory and the exit status of the last command.
* [celestialorb](https://github.com/celestialorb/zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-08-19 - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
* [chaos](https://github.com/kusamaxi/chaos-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-03 - Inspired by dogenpunk and smt themes, optimized for `git` users and Python developers. Includes decorators for `git` status, python virtual environment, background jobs, error status of last command, user\@hostname and current directory. Requires a font with emoji.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-07-26 - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
* [chello](https://github.com/Abdalla981/chello) ⭐ 1 | 🐛 0 | 📅 2022-06-14 - Works well on dark backgrounds. Depends on [autojump](https://github.com/wting/autojump) ⭐ 16,821 | 🐛 225 | 🌐 Python | 📅 2025-02-27, [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ⭐ 34,784 | 🐛 196 | 🌐 Shell | 📅 2025-06-24 and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) ⭐ 22,216 | 🐛 205 | 🌐 Shell | 📅 2024-11-21.
* [chinipage](https://github.com/andresemartinez/chinipage-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2021-12-28 - Minimalist theme that includes `git` decorations. Requires powerline-compatible fonts and the [git-prompt](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git-prompt) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugin.
* [classic](https://github.com/freakinu/classic-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-02-14 - A classic unix theme with decorators for username, host, current directory and `git` status.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) ⭐ 1 | 🐛 0 | 📅 2020-11-09 - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) ⭐ 55 | 🐛 0 | 📅 2022-06-15. Works better with dark backgrounds. Includes `git` status decorations.
* [coolmelon](https://github.com/omkarpai/coolmelon-zsh-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-04-16 - Includes decorators for user\@host, time, current directory, node version and `git` information.
* [cr](https://github.com/cruzrovira/cr-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-03-01 - Includes directory, time, host name, last command exit status, and `git` status decorations.
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-05-15 - A standalone clone of the original oh-my-zsh theme with date and time added.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) ⭐ 1 | 🐛 0 | 📅 2020-05-29 - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 but includes the active Ruby version.
* [daily-emoji](https://github.com/huytran-wq/zsh-daily-emoji-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-04-25 - Shows random emoji at the beginning of each command depending on the day of the week.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) ⭐ 1 | 🐛 3 | 🌐 Shell | 📅 2024-02-29 - Informative, minimal, and, above all, X-Men themed. Includes decorators for `git` status, working directory, parent directory and `vim` mode.
* [danielparks](https://github.com/danielparks/danielparks-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-01 - Works well on dark backgrounds. Includes decorators for `git` status, user\@host when in an `ssh` session, success/failure of last command, working directory, python virtualenv, execution time of last command and whether running as `root`.
* [dark-modern](https://github.com/d-exclaimation/vscode-dark-modern.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-06-27 - Includes decorators for `git` status and current directory.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) ⭐ 1 | 🐛 0 | 📅 2019-10-28 - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-06-27 theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-12-07 - Based on the `ys` and [astro](https://github.com/iplaces/astro-zsh-theme) ⭐ 108 | 🐛 0 | 📅 2020-02-13 themes.
* [diy-ys](https://github.com/aprilnops/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2018-09-06 - Variant of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 without hostname or time.
* [dkniffin](https://github.com/dkniffin/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-05-07 - Includes `ruby` version and `git` status.
* [dmx](https://github.com/domix/dmx.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2017-03-19 - Optimized for dark terminal windows.
* [dp](https://github.com/davidparsson/zsh-dp-theme) ⚠️ Archived - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dragon (jeop10)](https://github.com/jeop10/dragon) ⭐ 1 | 🐛 0 | 📅 2022-01-02 - Inspired by kali linux. Includes `git` status and working directory decorations.
* [droolmaw](https://github.com/isuke/droolmaw) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-05-28 - Configurable prompt that resembles [Powerline](https://github.com/powerline/powerline) ⭐ 14,701 | 🐛 239 | 🌐 Python | 📅 2024-09-30. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Includes decorators for username, current directory, current directory path, datetime, `git` author, `git` status, `mise` language version and a configurable message based on the exit status of the last command run.
* [dustmod](https://github.com/bmihaila/dustmod) ⭐ 1 | 🐛 0 | 📅 2017-12-17 - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme in oh-my-zsh.
* [earthshaker](https://github.com/remusearthshaker/earthshaker.zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-05-02 - A minimalist, earthy ZSH theme designed for developers who prefer warmth, subtle power, and a grounded aesthetic. Includes decorators for current directory, `git` status and username\@hostname.
* [eggshausted](https://github.com/inutano/eggshausted) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2018-03-08 - A `git`-aware theme for people who are tired of getting errors.
* [elm](https://github.com/gacallea/elm-zsh-theme) ⚠️ Archived - Includes `git` status, user\@host, date, time and path decorators.
* [emojirussell](https://github.com/Bergiu/emojirussell) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-06-17 - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) ⭐ 1 | 🐛 0 | 🌐 Makefile | 📅 2020-08-07 - Takes up an enormous amount of space in the terminal.
* [escape](https://github.com/fesmjke/escape/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-11-30 - Includes decorators for `git` information, username, time, current directory and last command exit status.
* [felipec](https://github.com/felipec/zsh-prompt-felipec) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-11-15 - Minimalist theme with decorators for current directory, `git` status, exit code of last command, and root status.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) ⭐ 1 | 🐛 0 | 📅 2013-07-29 - A theme based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 oh-my-zsh-theme.
* [frlo](https://github.com/fiorillo/frlo) ⚠️ Archived - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [gallifrey-war](https://github.com/cdubos-fr/gallifrey-war) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-12-30 - Inspired by [gallifrey](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#gallifrey) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `git` information, user\@host and current directory.
* [garden](https://github.com/fecat233/garden) ⭐ 1 | 🐛 0 | 📅 2020-06-29 - Works better with a dark terminal background, includes `git` status decorations.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-03-24 - Breaks out the oh-my-zsh `gentoo` theme into a separate repository for non-omz users.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-04-08 - Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13 theme.
* [get-to-work](https://github.com/Diogo13Antunes/Get_To_Work) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-28 - Minimalistic design, includes decorators for `git` status, virtual environment and the time.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-06-23 - Simple theme that includes detailed `git` status decorations.
* [gitprompt.sh](https://github.com/danieldietrich/gitprompt.sh) ⭐ 1 | 🐛 2 | 🌐 Shell | 📅 2025-11-14 - Works with both `bash` and `git`. 256 color support. Includes decorators for `git` status and current directory.
* [glider](https://github.com/MrRedacted/zsh-glider) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-02-20 - Based on [strug](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-03-10. Includes decorators for `git` status, username, hostname and current directory.
* [glimmer](https://github.com/martnu/glimmer) ⭐ 1 | 🐛 0 | 📅 2015-06-28 - Includes `git` branch, time and user\@host decorators.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-11-14 - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 from oh-my-zsh.
* [golden-prompt](https://github.com/Goldeneye128/golden-prompt) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-01-11 - A simple prompt that incorporates fish-like functionality and decorators for `git` status, current directory.
* [greencastle](https://github.com/GustavGroenborg/greencastle-zsh-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-17 - Minimalistic theme, that supports really, **really**, long branch names, without severely truncating the prompt. The theme is inspired by the [jonathan theme](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/jonathan.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2012-12-02 and the [robby russel theme](https://github.com/thlorenz/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2012-12-02. Includes decorators for current directory, `git` information and the exit status of the last command run.
* [gugulenok](https://github.com/gugulen0k/gugulenok/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-07-09 - Has both a dark and a light mode. Includes decorators for `git` status, time and current directory.
* [handy](https://github.com/hanleylee/handy) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-21 - Colorful and lightweight theme. Shows root status, `git` status, current directory and `user@hostname` decorations.
* [hcompact](https://github.com/fusion809/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-09-05 - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [hfulldate](https://github.com/fusion809/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-09-05 - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hijack](https://github.com/thegodheehee/hijack-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-06-29 - Includes decorators for user\@hostname, current directory, and `git` information.
* [hina](https://github.com/ucpr/hina) ⚠️ Archived - Written in `golang`, includes `git` status decoration and kubernetes context.
* [ho-my-zsh](https://github.com/Mboukhal/hoMyZsh_theme) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2023-05-03 - Includes decorators for current directory and `git` information.
* [hoozeeth](https://github.com/hooay233/Hoozeeth) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-07-14 - Minimalist theme, includes decorators for user\@hostname, the date & time, and the current working directory.
* [hornix](https://github.com/fusion809/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-09-05 - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-10-26 - A clean and humble theme with left-aligned `condaenv`, `virtualenv` and `git` status. Requires [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-02-14 plugin.
* [ice](https://github.com/Lenart12/ice.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-10-15 - Very lightly modified [bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) ⭐ 1 | 🐛 1 | 📅 2019-06-06 - Fork of [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) ⭐ 117 | 🐛 1 | 📅 2021-02-23 with spacing improvements and an updated icon. Includes `git` status information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2014-09-11 - An extension of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme to use powerline fonts.
* [jc](https://github.com/jclementex/jc-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2018-10-14 - For dark terminal backgrounds, includes `git` status information.
* [jmtech](https://github.com/jmaaltech/jmtech-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-01-07 - Customizable colors and symbols. Includes decorators for `git` status, exit status of last command run, `gpg` signing information and timestamps. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 for the `git` status icons.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-12-01 - A simplified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [jpegleg](https://github.com/jpegleg/zshrc) ⭐ 1 | 🐛 0 | 📅 2021-06-06 - Similar to dark blood theme, includes timestamp and `git` decorations.
* [kawaii](https://github.com/LeonidPilyugin/kawaii-oh-my-zsh/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-11-23 - Has terminal and virtual console modes. Includes decorators for username, directory, last command exit status, timestamp and `git` status.
* [kenton](https://github.com/notnek/zsh-theme) ⭐ 1 | 🐛 0 | 📅 2021-05-17 - Optimized for dark backgrounds, includes `git` status information.
* [ko](https://github.com/JoshBenn/KoTheme-for-Oh-My-Zsh/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-03-30 - Includes decorators for `git` status and current directory.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-06-03 - Best for dark backgrounds. Includes `git` status decorations.
* [krak3n](https://github.com/krak3n/zsh-theme) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2023-05-25 - Shows golang version and the current `git` branch.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) ⭐ 1 | 🐛 0 | 📅 2018-08-23 - A dark theme for ZSH.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-09-29 - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-08-08 - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) ⭐ 1 | 🐛 0 | 📅 2016-07-21 - A minimal ZSH theme.
* [larn](https://github.com/tourcoder/larn.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-07-22 - A clean and customizable oh my zsh theme with Git integration, designed for dark terminals. It features a colorful prompt with decorators for  `git` branch and status indicators, current directory and distinct `ls` colors for files and directories.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2013-09-03 - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-12-31 - Leafy prezto theme that shows `git` status information.
* [leverage](https://github.com/gschnall/leverage) ⭐ 1 | 🐛 0 | 📅 2019-10-31 - Based on [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
* [link](https://github.com/kylegl/link-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-06-08 - Minimalist. Includes `git` status and last command exit decorations.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2021-06-13 - Includes `git` and compact `pwd` decorations.
* [luckycoding](https://github.com/ZitherPeng/oh-my-zsh-luckycoding-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-06-09 - Based on the [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme, includes `git` decorations and the last command's exit code.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) ⚠️ Archived - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes decorations for `git` status and the status of the last command run.
* [majemoji](https://github.com/metalogica/majemoji) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-05-23 - Adds a random emoji to each session's prompt. Includes `git` status decorations.
* [matter](https://github.com/mrobillard/matter-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-11-04 - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [meganerd](https://github.com/meganerd/meganerd-zsh/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-08-03 - Inspired by jonathan. Includes decorators for `git` status, user\@hostname, current directory, time and the last command's exit status.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-10-09 - Includes `rvm` and `git` status decorations.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) ⭐ 1 | 🐛 3 | 📅 2021-04-23 - POSIX-friendly cross-platform [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 mod w/ convenient timestamps and full git/ruby support.
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) ⭐ 1 | 🐛 0 | 📅 2018-02-26 - Inspired by kolo theme from oh-my-zsh.
* [mira](https://github.com/mbStavola/mira) ⭐ 1 | 🐛 0 | 🌐 Nushell | 📅 2025-12-14 - A modified [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with time info and a simplified start prompt.
* [mirage](https://github.com/robin-pfeiffer/ohmyzsh-mirage-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-08 - Includes prompt decorations for `git` status, last command exit code, whether `sudo` timestamp file is present and current active Python virtual environment.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-03-22 - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2013-10-24 - Misalabs' ZSH theme.
* [moderno](https://github.com/obrassard/moderno-zsh) ⭐ 1 | 🐛 0 | 📅 2019-06-05 - A simple and modern ZSH theme inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme from Oh-My-ZSH. Includes `git` status decorations.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) ⭐ 1 | 🐛 0 | 📅 2021-11-10 - A clean and modest ZSH theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned. Requires [condaenv](https://github.com/saravanabalagi/zsh-plugin-condaenv) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2024-02-14 plugin.
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-08-07 - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
* [moonbloom](https://github.com/moonbloom-theme/zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-09-02 - Adapts to the color scheme of your terminal emulator. Includes decorators for current directory and `git` status.
* [mzt](https://github.com/honbey/mzt) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-08-13 - Sets up `LS_COLORS`, colorizes `diff` and includes `git` status and current working directory decorations.
* [nanika](https://github.com/justforuse/nanika-zsh-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-09-05 - Optimized variant of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes `git` status decorations.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-11-07 - Includes `git` decorations and `vi`-mode indicator.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) ⚠️ Archived - Multiline theme with `git` decorations.
* [ohh IP](https://github.com/Ohh-Raven/ohh_IP) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-02-11 - A theme designed for CTFs. Includes decorators for ip address and `git` status.
* [om](https://github.com/sirshikher/zsh-om) ⭐ 1 | 🐛 0 | 📅 2020-02-29 - Minimal theme, works with dark backgrounds, includes `git` status decorations.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-08-12 - Includes `git` status and virtualenv information.
* [paramour](https://github.com/espeon/paramour) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-12-07 - Simple and clean, has decorators for `git` status, username, time, current directory and username. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 in your terminal.
* [pawsh](https://github.com/SergioBonatto/pawsh-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-03 - Pawsh is a super kawaii zsh theme for oh-my-zsh, inspired by Japanese neko culture. Your prompt becomes a cute cat face (ᓚᘏᗢ) that changes color depending on your command's mood. Includes decorators for root status, prompt color changes based on exit status of the last command run, current directory, Python virtualenv, `vi`-mode indicator, `git` status, and the current time.
* [piboy](https://github.com/sflems/piboy-zsh-theme) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2022-05-09 - A simple and elegant multi-line theme for ZSH. Includes a colourized timestamp, `git` & syntax highlighting, and elevated root theme.
* [pixelwave](https://github.com/arcnms/pixelwave) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-09 - A sleek, bright, vibrant theme that mixes old‑school pixel vibes with modern high‑color rendering. It shows a rainbow “pixel bar,” a neon‑colored identity line (via lolcat), your full path, and concise `git` status.
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-10-24 - Simple, no-frills theme.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-12-03 - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) ⭐ 1 | 🐛 0 | 📅 2018-03-14 - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) ⭐ 1 | 🐛 1 | 📅 2019-12-05 - Shows working directory, the return status of the last command, and `git` current branch.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2019-07-14 - Works well with dark terminal backgrounds, includes `git` status decorations.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) ⭐ 1 | 🐛 0 | 📅 2014-09-21 - Prezto port of oh-my-zsh's cloud prompt.
* [prompt\_blocks](https://github.com/MiloradFilipovic/promptblocks) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-21 - A minimal node js + git theme. Includes decorators for `git` status, node version and current directory.
* [promptor](https://github.com/MickaelBlet/Promptor) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-08-03 - Powerline-inspired. Includes decorators for `git` status, username, hostname, working directory and time.
* [pronto (jthat)](https://github.com/jthat/zsh-pronto) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-08 - Simple and fast theme with `git` decorations and timing information.
* [pyhack](https://github.com/williamcanin/pyhack) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-08-02 - Works well with dark terminal themes. Shows Python version, Python package version (pyproject.toml) and `git` current branch information.
* [quewui](https://github.com/kauefontes/oh-my-quewui) ⭐ 1 | 🐛 0 | 📅 2021-03-07 - Simple and clean theme optimized for dark terminal themes. Includes decorations for the current time, user, directory and `git` status.
* [r](https://github.com/rafalkaron/r-zsh-theme) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2025-11-02 - A simple yet informative ZSH theme.
* [radius](https://github.com/erikcc02/radius-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-04-12 - Includes `git` status, username, hostname, and directory decorations, plus [desk](https://github.com/jamesob/desk) ⭐ 2,568 | 🐛 20 | 🌐 Shell | 📅 2022-07-07 support.
* [redline](https://github.com/DrissTM/redline.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2019-12-05 - Minimalist theme. Includes `git` status, time, user.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) ⭐ 1 | 🐛 0 | 🌐 Haskell | 📅 2021-07-02 - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme and the [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) ⭐ 1,765 | 🐛 59 | 🌐 Haskell | 📅 2023-11-08 project.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2018-11-27 - Colorful theme, includes `git` decorations and the current directory.
* [s1ck3r](https://github.com/pseifer/s1ck3r) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-11-15 - Sleek, transient and space-efficient. Includes decorators for `vi`-mode, elevated permissions, last command exit status, if background jobs are running, working directory and `git` status,
* [sailormoon](https://github.com/Domanowska/zshSailorMoonThemes) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-05-06 - A collection of Sailor Moon themed themes.
* [samshell](https://github.com/samuelb/samshell) ⭐ 1 | 🐛 0 | 📅 2020-12-29 - A minimalist ZSH theme with `git`, kubernetes and python virtualenv decorations.
* [sashimi](https://github.com/simonmader17/sashimi-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-06-02 - Includes decorators for `git` status and the exit status of the last command run.
* [shinkansen](https://github.com/MRZ07/shinkansen.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-20 - A fast, customizable and easily extended theme. Includes decorators for python version in the active virtualenv, current ruby version if you're using `chruby`, current Node.js version, current java version, current go version, current perl version if using `chperl`, current elixir version, `git` status, time, current directory, exit code and execution time of the last command, and an optional custom message. Requires a powerline-compatible font.
* [simple (drNoob13)](https://github.com/drNoob13/SimpleZshTheme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-03-06 - Includes decorators for python virtual environment, `git` status and current directory.
* [simple (tourcoder)](https://github.com/tourcoder/simple.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2025-07-22 - Minimalist prompt, includes `git` status decorations.
* [simple-headless](https://github.com/H3xaChad/zsh-simple-headless-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-11-09 - Minimal ASCII-only prompt that just shows what you need. Includes decorators for shortened path to current directory, Python virtual env, Node version, username\@hostname and `git` information.
* [simple-zsh-catppuccin](https://github.com/ezswan/simple-zsh-catppuccin) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-03-23 - Based on the [Catppuccin Mocha](https://catppuccin.com/) color scheme, adapted from the [Dracula](https://github.com/dracula/zsh) ⭐ 290 | 🐛 9 | 🌐 Shell | 📅 2024-08-01 theme foundation. This theme features a simple and functional prompt with support for git status, time display, context, and directory information, enhanced with hex color support discovered by ezswan.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2020-05-04 - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) ⭐ 67 | 🐛 2 | 🌐 Vim Script | 📅 2026-02-03 and [odin](https://github.com/tylerreckart/odin) ⭐ 71 | 🐛 0 | 🌐 Makefile | 📅 2018-02-09.
* [spectere](https://github.com/Spectere/spectere-omz-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-02-27 - Powerline-esque. Includes decorators for current directory, root status, `user@hostname`, and `git` status.
* [taw-ys-venv](https://github.com/BrokeDudeAbula/taw-ys-venv) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-06-12 - Two-line prompt with decorators for username, current directory, `git` information and current Python `venv`. Based on [AzarAI-TOP/taw-ys-zsh-theme](https://github.com/AzarAI-TOP/taw-ys-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-12-01.
* [temeraf](https://github.com/filiptoma/temeraf-zsh) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-11-15 - Minimalist theme with decorations for `git` status, timestamps and last exit status.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2020-12-03 - Minimalist theme.
* [thayne](https://github.com/tmccombs/thayne.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-07-14 - Includes decorators for exit status of last command, time to run if > 1 second, current time, current directory and `git` status. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [themer](https://github.com/MrRedacted/zsh-themer) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-24 - Includes multiple color scheme options, with `git` status decorators. There are also multiple icons to choose from within the `.zsh-theme` file. Based on [strug](https://github.com/triplepointfive/oh-my-zsh/blob/master/themes/strug.zsh-theme) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2021-03-10.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-03-30 - Async version of [theta](https://github.com/eendroroy/theta) ⚠️ Archived. Includes vcs status information.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) ⭐ 1 | 🐛 0 | 📅 2020-02-12 - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) ⭐ 20,388 | 🐛 128 | 🌐 Shell | 📅 2025-12-24 theme.
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-06-10 - Simple theme with `git` status decorations.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) ⭐ 1 | 🐛 0 | 📅 2017-12-22 - Includes `git` information; best on dark backgrounds.
* [traffic](https://github.com/fcce/traffic-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2025-07-03 - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2012-09-05 - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) ⭐ 1 | 🐛 0 | 📅 2018-11-29 - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry) ⭐ 990 | 🐛 10 | 🌐 Shell | 📅 2025-01-13. Includes `git` decorations.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) ⭐ 1 | 🐛 0 | 📅 2021-04-10 - Minimal theme, includes `git` status decorations.
* [unicorn](https://github.com/juliuscaesar/unicorn) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-19 - Includes decorators for root status, virtualenv, nvm, rvm, current directory, the time, current directory and emoji `git` information. Inspired by [wild cherry](https://github.com/mashaal/wild-cherry) ⭐ 482 | 🐛 7 | 🌐 Less | 📅 2023-03-18.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) ⭐ 1 | 🐛 0 | 📅 2021-03-31 - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) ⭐ 667 | 🐛 4 | 🌐 TypeScript | 📅 2025-08-22 theme. Includes `git` status decorations.
* [vtex](https://github.com/charleseduardome/oh-my-zsh-vtex) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2025-11-22 - Includes decorators for `git` status, current directory, [VTEX](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-command-reference#default-commands) account and VTEX workspace.
* [winline](https://github.com/khuei/winline) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-09-24 - Async version of Greg Hurrell's [prompt](https://github.com/wincent/wincent/blob/master/aspects/dotfiles/files/.zshrc) ⭐ 1,180 | 🐛 5 | 🌐 Lua | 📅 2026-02-06. Includes decorators for `git` status, duration of last command, current directory, nested shells, root status.
* [wkentaro](https://github.com/wkentaro/wkentaro.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-15 - A simple theme for Python users. Includes virtualenv and `git` status decorators.
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-02-11 - Simple theme with `git` decorations.
* [xor](https://github.com/xor3n/xor-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-08-09 - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) ⭐ 1 | 🐛 0 | 📅 2015-12-18 - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) ⚠️ Archived - Fast, simple and streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) ⭐ 41,448 | 🐛 37 | 🌐 C | 📅 2026-02-02 and [vim-airline](https://github.com/vim-airline/vim-airline) ⭐ 17,939 | 🐛 50 | 🌐 Vim Script | 📅 2025-12-23.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) ⭐ 1 | 🐛 0 | 📅 2017-11-26 - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) ⭐ 1 | 🐛 0 | 📅 2017-09-16 - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) ⭐ 0 | 🐛 1 | 📅 2016-12-15 theme and optimized for a dark background.
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) ⭐ 1 | 🐛 1 | 📅 2018-12-18 - [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) ⭐ 1 | 🐛 0 | 📅 2018-01-02 - Simple ZSH theme with `git` status information.
* [yuyuko](https://github.com/hylwxqwq/yuyuko.zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-03-17 - Fork of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, inspired by [yuyuko.vim](https://github.com/hylwxqwq/yuyuko.vim) ⭐ 45 | 🐛 1 | 🌐 Vim Script | 📅 2023-11-15.
* [yz50](https://github.com/lacanlale/yz50-zsh) ⭐ 1 | 🐛 0 | 📅 2019-01-05 - Colorful, based off of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes. Includes `git` status decorations.
* [z4rr3t](https://github.com/inimicus/z4rr3t) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2019-11-24 - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) ⭐ 14,058 | 🐛 33 | 🌐 Shell | 📅 2025-11-15 theme.
* [zap-robbyrussell](https://github.com/devadathanmb/zap-robbyrussell) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-05-12 - The OMZ robbyrussell theme, patched to add compatibility with [zap](https://github.com/zap-zsh/zap) ⭐ 1,132 | 🐛 14 | 🌐 Shell | 📅 2025-07-12.
* [zcmder](https://github.com/bwpge/zcmder) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-04-27 - inspired by [Cmder](https://cmder.app/) with decorators for `git` information, current directory and root status.
* [zcraft](https://github.com/cpea2506/zcraft) ⚠️ Archived - Minimalist theme with decorations for `git` status, last command exit status and the time taken by the last command.
* [zenith (waki285)](https://github.com/waki285/Zenith) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2023-10-29 - Minimalist. Includes decorators for username, current directory and `git` status.
* [zido](https://github.com/SidonieBouthors/zido-zsh-theme) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2024-10-03 - Includes decorators for `git` status and current directory.
* [zish](https://github.com/RubixDev/zish/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-06-10 - Based on the `fish` shell's default look.
* [zshred](https://github.com/redxtech/zshred) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-06-22 - Shows current directory, `git` decorations, exit status of last command and time.
* [7eth](https://github.com/chokri/zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-27 - Minimalist theme with decorator for `git` status.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2017-01-27 - macOS theme, requires a Powerline-compatible font.
* [afaq](https://github.com/afaq1337/afaq.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-05-25 - Two line theme with decorators for hostname, local IP address, current working directory, current time, `git` status and Python virtualenv.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2018-04-23 - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme in oh-my-zsh.
* [agnopro](https://github.com/arhafizi/agnopro-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-23 - A high-performance, feature-rich ZSH theme with intelligent context display, inspired by and based on Agnoster but enhanced with additional developer-friendly features. Includes decorators for current directory, nodejs version, golang version, .Net version, `git` status, AWS profile, user\@host, background jobs and Python environment.
* [agnoster-multiline](https://github.com/mxkrsv/agnoster-multiline) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-07-01 - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23. Includes decorators for current directory and `git` status. Requires a font with powerline and `git` glyphs. Automatically disables non-ascii glyphs on linux ttys.
* [ai-candy](https://github.com/SihaoLiu/ai-candy) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - A responsive [oh-my-zsh](https://github.com/ohmyzsh) theme for the AI-assisted developer who works across containers, VMs, and bare metal. Includes decorators for OS, kernel info, whether it is a `ssh` session, `git` status, GitHub integration, AI tool status and smart caching.
* [ai-hayasaka](https://github.com/aeghost/ai-hayasaka-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-01 - Minimalist theme with `git` status, ruby env and python virtualenv decorators.
* [air](https://github.com/Ivan-Kuzmichev/air) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-03 - Minimalist theme with `git` status decorations.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) ⭐ 0 | 🐛 0 | 📅 2021-03-02 - Minimalist theme with `git` status decorations.
* [alesrosina](https://github.com/alesrosina/oh-my-zsh-alesrosina-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-12-09 - Includes decorators for `git` information, current directory and the last command's return status.
* [alp](https://github.com/zrut747/alp/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-04-30 - A simple theme with decorations for current directory, root status, username and host.
* [amplify](https://github.com/clintfoster/ohmyzsh-theme-amplify) ⭐ 0 | 🐛 0 | 📅 2021-12-21 - Minimalist, includes AWS Amplify envioronment and `git` status decorations.- [andy](https://github.com/andymcguinness/andys-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-12-24 - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme with better `git` support.
* [aofxta](https://github.com/aofxta/aofxta.zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-11 - Includes decorators for last command's execution time, `git` information, current directory and current time.
* [ap2](https://github.com/aungphyo-dev/ap2.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-11-12 - Minimalist them with decortators for time, OS, current directory, `git` status and the last command's exit status.
* [appa](https://github.com/givensuman/appa-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-15 - A tidy little theme based on omz's [refined](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/refined.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [apple (bjrowlett2)](https://github.com/bjrowlett2/apple-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-04-02 - Minimalist theme with `git` status decorations.
* [arael](https://github.com/aknackd/zsh-themes) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-28 - Fork of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [arity](https://github.com/hybras/Arity-Zsh-Theme) ⭐ 0 | 🐛 0 | 📅 2019-05-17 - A simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-04-22 - Minimalist theme with right-side `git` status decorations.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-03-14 - A minimal ZSH theme with `git` decorations.
* [arrow](https://github.com/milon/arrow-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-12-14 - Minimal theme, includes `git` status decorations.
* [australis](https://github.com/Kimitzuni/australis-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-01-04 - Lightweight theme with decorators for `git` information and current directory. Requires `git` plugin from [oh-my-zsh](https://github.com/ohmyzsh).
* [avil](https://github.com/avil13/avil-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-20 - Minimalist theme with `git` decorations.
* [avit-mod](https://github.com/zlsun/avit-mod) ⭐ 0 | 🐛 0 | 📅 2017-03-05 - Modified version of oh-my-zsh's [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [bash](https://github.com/starseekist/bash-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-10-01 - Looks like the default `bash` prompt.
* [bashplus](https://github.com/Elagoht/BashPlusZshTheme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-07 - Colorized replica of the default `bash` prompt with decorators for `virtualenv` and `git` status.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) ⭐ 0 | 🐛 0 | 📅 2021-08-05 - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes decorators for `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2014-06-20 - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [biraskull](https://github.com/Shahryar-Pirooz/biraSkull.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-10-18 - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes root status and `git` status decorations.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-13 - Adds mercurial support to oh-my-zsh's [blink](https://github.com/max13fr/blinks.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-13 theme.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) ⭐ 0 | 🐛 0 | 📅 2021-03-01 - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) ⭐ 231 | 🐛 4 | 🌐 Shell | 📅 2025-03-13. Includes `git` and ruby version decorations.
* [bouni](https://github.com/Bouni/bouni-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-09-05 - Includes decorators for user\@host, current directory, active python virtualenv, and `git` status.
* [boxy](https://github.com/evil-tim/boxy-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-23 - Works well with solarized terminal colors. Includes decorators for `username@hostname`, current directory, `git` status, return code for last command, and time last command was run.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) ⭐ 0 | 🐛 0 | 📅 2021-04-21 - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) ⚠️ Archived and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes.
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-10-14 - Based on [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) ⭐ 77 | 🐛 1 | 🌐 Shell | 📅 2024-04-13. Changes color when root. Includes decorators to show user\@host and current directory.
* [buddha](https://github.com/BuddhaDom/zsh-buddha) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-05-16 - Includes decorators for `git` status, current directory, exit status of last command run and username\@hostname.
* [cabovianco](https://github.com/cabovianco/cabovianco-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-26 - Includes decorators for `git` status and current directory.
* [candy-fantasy](https://github.com/fffelix-huang/candy-fantasy) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-29 - Modified version of [Candy Kingdowm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/candy-kingdom.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02theme.
* [carriage-return](https://github.com/treyssatvincent/carriage-return.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-09-23 - omz's [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with an added carriage return.
* [catpuccin-kali](https://github.com/Robinx0/catpuccin-kali-theme.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-11-07 - Inspired by oh-my-posh catpuccin theme. Includes decorators for username\@hostname, current directory and `git` status.
* [cezhanne](https://github.com/gambardellawill/cezshanne) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-12 - Minimalist ZSH theme with `git` status decorators. Requires a [Nerd Font](https://www.nerdfonts.com).
* [cf-ps1](https://github.com/mdan16/cf-ps1) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-01 - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-04-26 - Lean and simple theme.
* [cheeky](https://github.com/kampanosg/zsh-cheeky-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-21 - Includes chicken emoji, decorators for current directory, `git` information and current GCP cluster and project.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-10-20 - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 with host information added.
* [clipper](https://github.com/Robert-96/clipper) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-08-08 - Minimalist ZSH theme with `git` support. It includes decorations for pwd, last command exit status code and `git` status & branch.
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) ⚠️ Archived - Configuration file for `cmder`that is configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
* [cn](https://github.com/shinqcn/cn-zsh/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-04 - Includes `username`, `directory` and `git` status decorations.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-04-22 - Based on [agnoster](https://gist.github.com/3712874), with a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-01-14 - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [cravend](https://github.com/cravend/theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-05 - Includes `hostname` decorator (only in active `ssh` sessions) and `git` status decorations.
* [cryo-long](https://github.com/cryocaustik/cryo-long-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-31 - Variant of [cryo](https://github.com/cryocaustik/cryo-zsh-theme/) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2022-05-15 with added decorators for hostname and current directory.
* [cryptic](https://github.com/thederpykrafter/cryptic.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-05-27 - Based on [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme) ⭐ 171 | 🐛 2 | 🌐 Shell | 📅 2025-08-04. Includes decorators for current directory, `git` status, time, username, hostname and virtual environment.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Makefile | 📅 2019-09-25 - Works well on dark background, has `git` status decorations.
* [cybensis](https://github.com/cybensis/cybensis-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-14 - Based on [af-magic](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/af-magic.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `git` information, `hg` information, and python virtualenv.
* [daily](https://github.com/ghlin/zsh-theme-daily) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-27 - Includes `git` and `ssh` status decorations.
* [dalailahner](https://github.com/dalailahner/dalailahner.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-02 - Minimalist theme with decorators for `git` status, for VCS status (based on [Bart Trojanowski's zsh prompt](http://www.jukie.net/bart/blog/pimping-out-zsh-prompt)), username and current directory. Based on Steve Losh's [Prose](https://github.com/sjl/oh-my-zsh/blob/master/themes/prose.zsh-theme) ⭐ 351 | 🐛 0 | 🌐 Shell | 📅 2011-08-19 theme.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-09-16 - Minimal powerline-esque theme with `git` decorations.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) ⭐ 0 | 🐛 1 | 📅 2021-08-19 - Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) ⭐ 0 | 🐛 0 | 📅 2021-01-05 - Includes battery status and load average decorations.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2018-08-13 - Another minimal theme with embedded `git` status.
* [devj121](https://github.com/cjeonguk/devj121-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-03-09 - Includes `git` decorations with branch glyphs.
* [djkakaroto](https://github.com/djkakaroto/theme-zsh/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-06-04 - Includes `git` status decorations, works with all fonts.
* [domixgit](https://github.com/tariqdomi/ohmyzsh-domixgit) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-10-29 - Prompt with `git` status and current directory decorators.
* [dr4kk0nnys\_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) ⭐ 0 | 🐛 1 | 📅 2020-09-02 - Works well on dark backgrounds, includes `git` status decorations.
* [dyzsh](https://github.com/daotoyi/dyzsh-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-02-25 - Based on [astro](https://github.com/iplaces/astro-zsh-theme) ⭐ 108 | 🐛 0 | 📅 2020-02-13. Includes decorators for `git` branch & hash, current directory, user, host & time.
* [easytocloud](https://github.com/easytocloud/oh-my-easytocloud) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-26 - Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23. Includes decorators for AWS environment, `git` status, username and the current directory.
* [eckig](https://github.com/fouladi/eckig) ⭐ 0 | 🐛 0 | 📅 2021-04-15 - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
* [elagoht](https://github.com/Elagoht/Elagoht.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-07 - Includes decorators for user\@hostname, current directory, virtual environment, `git` status, whether it is running in an `ssh` session, and the execution time of the last command.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) ⭐ 0 | 🐛 0 | 📅 2016-12-15 - Emoji flavored [oh-my-zsh](https://ohmyz.sh/) theme.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2017-06-21 - A simple theme with `git` information.
* [even-more-emojis](https://github.com/odunlop/even-more-emojis) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-08-10 - Customized version of [emoji](https://github.com/meiokubo-zz/emoji.zsh-theme) ⭐ 20 | 🐛 0 | 📅 2021-04-25 which adds more emojis and more information. Includes decorators for `git` status, current directory and the exit status of last command.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-12-12 - Minimalist theme with `git` status decorations, inspired by [bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) ⭐ 0 | 🐛 0 | 📅 2018-01-21 - Minimal ZSH prompt that works better on dark backgrounds.
* [fbi](https://github.com/bateman/fbi-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-03-23 - Powerline-inspired fork of [Bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 with decorators for `nvm` environment, `git` status, username\@hostname and current directory.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-10-25- Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
* [fe80](https://github.com/fe80/fe80.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-13 - Includes decorators for `git` information, current directory, user\@hostname, time, and the return code of last command when it is nonzero.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2017-05-18 - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [firefoxic](https://github.com/firefoxic/firefoxic-zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-11-06 - Fork of [Bureau](https://github.com/isqua/bureau) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2022-01-12 with tweaks to the node and `git` decorators.
* [fish (sbfkcel)](https://github.com/sbfkcel/oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-03-14 - Minimalist theme with decorators for `git` status, current directory and username.
* [flux](https://github.com/jmg-duarte/flux-zsh) ⚠️ Archived - A no-nonsense minimalist theme with `git` status decorations.
* [frank](https://github.com/ronmackley/frank-theme) ⭐ 0 | 🐛 0 | 📅 2020-12-30 - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) ⭐ 0 | 🐛 0 | 📅 2016-09-12 - Fork of [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) ⭐ 0 | 🐛 0 | 📅 2014-01-20 - Red version of the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-08-02 - Works well on dark backgrounds. Includes `git` status decorations.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-05-26 - Colorful theme, works better on a dark background.
* [gabriel2m](https://github.com/gabriel2m/gabriel2m-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-30 - Minimalist theme with decorators for the current directory and `git` status.
* [gallium](https://github.com/RickConsole/gallium) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-08 - Minimal theme inspired by [gal](https://github.com/x6r/gal) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-12-30 and [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `username@host`, current directory and `git` status.
* [gerry](https://github.com/GerryLarios/gerry-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-03-14 - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#bureau) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes decorations for `git` status, current time, username, hostname and current directory.
* [gg](https://github.com/YourBrightSmile/ggZshTheme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-15 - Includes decorators for time and `git` status.
* [ghoti](https://github.com/lonr/ghoti) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-12-16 - Mimics the `fish-shell` default prompt. Includes `git` decorations.
* [gianu-alternative](https://github.com/zbentzinger/gianu-alternative-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-01-18 - An alternative to [OMZ Gianu](https://github.com/ohmyzsh/ohmyzsh/blob/61dd3682e69aa990a8a3589c5c61ea2e1edf8312/themes/gianu.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 that changes prompt based on privilege. Includes `git` status and current directory decorators.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) ⭐ 0 | 🐛 0 | 📅 2019-05-03 - Inspired by [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes `git` decorations, IP address, host and path.
* [gimme](https://github.com/nralbrecht/gimmezsh) ⭐ 0 | 🐛 0 | 📅 2019-11-06 - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome](https://github.com/mtully/gitsome) ⭐ 54 | 🐛 0 | 📅 2013-04-15 theme.
* [girazz](https://github.com/mdentremont/girazz) ⭐ 0 | 🐛 0 | 📅 2018-06-15 - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-venv-prompt](https://github.com/walkingshamrock/zsh-git-venv-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-24 - Enhances your Zsh prompt with information about the current Python virtual environment and the Git status (asynchronously). It uses zsh-async to provide async updates for Git status and displays the virtual environment in the second line of the prompt.
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-08-24 - Forked from the original [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme.
* [gk3000](https://github.com/gk3000/gk3000-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-12-07 - Includes `git` status decorations and full path to current directory.
* [gn-z11](https://github.com/xxidbr9/zsh_GN-z11-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-22 - Includes decorators for `git` status and the last command's exit status.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) ⭐ 0 | 🐛 0 | 📅 2020-08-04 - Theme for iTerm 2 and ZSH. Uncludes `git` status, user\@host, path and date decorators.
* [gorchak](https://github.com/evgenygorchakov/oh-my-zsh-gorchak-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-04-15 - Inspired by [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [af-magic](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#af-magic) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `git` information and Node.js version.
* [green-lambda](https://github.com/Ishidawg/minimal-green-lambda) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-18 - Minimalist Lambda theme. Includes `git` decorations.
* [greenclean](https://github.com/dmicha16/greenclean) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-01 - Fork of [akz92/clean](https://github.com/akz92/clean) ⭐ 9 | 🐛 0 | 📅 2017-10-26 with a bit more green and permanent clock on the right.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-12-03 - Minimalist, includes `git` status decorations.
* [grs](https://github.com/gersontpc/zsh-theme-grs) ⭐ 0 | 🐛 0 | 📅 2019-07-01 - Includes `git` status, user id and working directory decorators.
* [gus](https://github.com/gusye1234/Gus-zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-10-04 - Hackable transient theme. Includes decorators for conda, `git` information and current directory.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-02-27 - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-03-12 - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, with added `git` status decorations and `npm` status.
* [helb](https://github.com/helb/helb.zshtheme) ⭐ 0 | 🐛 0 | 📅 2021-09-21 - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-12-14 - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
* [hex](https://github.com/hectorBrown/hex-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-10-31 - Heavily based on [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, and [gruvbox](https://github.com/sbugzu/gruvbox-zsh) ⭐ 126 | 🐛 1 | 🌐 Shell | 📅 2023-11-13, which in turn is based on [agnoster](https://gist.github.com/agnoster/3712874). Includes decorators for current directory, `git` status information, active python virtualenv, exit status of the last command run. Requires a Powerline-compatible font.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2018-05-12 - Inspired by robbyrussell theme + ssh connection status prompt.
* [hip-fellow](https://github.com/haitaim/hip-fellow) ⭐ 0 | 🐛 0 | 📅 2021-09-04 - Includes `git` status decorations and works with standard fonts.
* [hoffish](https://github.com/emilHof/hoffish-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-06 - If the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 theme and [fish](https://fishshell.com/) shell had a ZSH theme for a child. Includes decorators for `git` status, trimmed path to current directory, root status, exit status of the last command run and the active python virtualenv. Requires a Powerline font and the [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) ⭐ 34,784 | 🐛 196 | 🌐 Shell | 📅 2025-06-24 and [shrink-path](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/shrink-path/shrink-path.plugin.zsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 plugins.
* [hogbal](https://github.com/hogbal/hogbal.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-12-13 - Works best with a dark background and a 256 color terminal program. Includes decorators for `virtualenv`, `git` information, `username@hostname` and current directory.
* [horse-sh](https://github.com/emileswarts/horse-sh) ⭐ 0 | 🐛 0 | 📅 2015-03-15 - A very minimal brown/red ZSH theme.
* [ichirei](https://github.com/ichirei/ichirei.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-24 - Colorful. Includes decorators for `git` status, time & current directory. Requires a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-02-22 - Minimalist theme, better on dark backgrounds.
* [inthedeepspace](https://github.com/alionapermes/inthedeepspace/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-04 - Based on [intheloop](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#user-content-intheloop) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and inspired by [vim-deep-space](https://github.com/tyrannicaltoucan/vim-deep-space) ⭐ 315 | 🐛 4 | 🌐 Vim script | 📅 2019-10-25.
* [itlbv](https://github.com/itlbv/itlbv-ohmyzsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-10 - Minimalist. Includes decorators for `git` status and the current directory.
* [ittecture](https://github.com/ittecture/ittecture-omz-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-28 - Includes decorators for current directory and `git` information.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-03-03 - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-06-22 - Shows the time, the current directory, and `git` branch information including the branch name and a red + if the branch has un-pushed changes.
* [jax](https://github.com/jhammerberg/jax-theme) ⚠️ Archived Reminiscent of Powerline. Includes decorators for current directory and current user.
* [jeff](https://github.com/jbaranski/jeff-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-25 - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.  Includes decorators for user\@host, time, current directory and `git` status.
* [jerome](https://github.com/jeromescuggs/jerome-theme) ⭐ 0 | 🐛 0 | 📅 2019-11-17 - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) ⭐ 0 | 🐛 0 | 📅 2019-11-17 theme, but with a yellow hostname. Includes `git` decorations.
* [jmsp](https://github.com/juacu7340/jmsp.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-22 - Focused on simplicity and SSH usefullness. Includes `git` status and current directory decorators.
* [jnooree](https://github.com/jnooree/jnooree-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-17 - Minimalist theme with colors adapted from the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes decorators for `git` status, whether running as non-default user and current working directory.
* [joje](https://github.com/joje6/joje.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-06-29 - Includes decorators for `git` status and current directory.
* [js-magic](https://github.com/JSextonn/js-magic) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-01-11 - A simplified take on [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2013-12-10. Includes current working directory and `git` status decorations.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) ⭐ 0 | 🐛 0 | 📅 2015-05-01 - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-09-27 - Just another theme, with hostname when you're sshed to another machine.
* [just-around-the-corner](https://github.com/DevinLeamy/just-around-the-corner) ⭐ 0 | 🐛 0 | 📅 2021-11-30 - Counts down the days until Christmas. Includes `git` status decorations.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-30 - Configuration file and installer for Powerlevel 10K.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) ⭐ 0 | 🐛 0 | 📅 2020-09-18 - Includes `git` status deorations, works well on darker backgrounds.
* [kketcham](https://github.com/prototype27/kketcham) ⭐ 0 | 🐛 0 | 📅 2014-07-12 - Theme with nifty colors on the `git` info.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-10-10 - Two line theme designed for dark terminals, has `git` decorations.
* [ksposh](https://github.com/KSposh/ksposh-zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2026-01-12 - Includes decorators for python virtual environment, `git` information, current directory and username.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2018-01-05 - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
* [lacerate](https://github.com/Petrushevsky-A/Lacerate-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-12-15 - Minimalist theme with decorations for `git`, `hg` and python `venv` status.
* [laconic](https://github.com/Saka7/laconic.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-07-21 - Simple theme with `git` status and current directory decorators.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-04-19 - Includes blazing fast, detailed `git` information. Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 and the [gitstatus](https://github.com/romkatv/gitstatus) ⭐ 1,783 | 🐛 44 | 🌐 C++ | 📅 2025-10-12 plugin.
* [lambda-p](https://github.com/paimanbandi/lambda-p) ⭐ 0 | 🐛 0 | 📅 2021-08-24 - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) ⭐ 2 | 🐛 1 | 📅 2022-02-09 themes. Includes `git` status decorations.
* [lambder](https://github.com/avillen/zsh-theme-lambder) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-08-14 - Includes `git` status decorations, works best with a dark terminal theme.
* [laniksj](https://github.com/LanikSJ/laniksj-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-06 - Works best on a dark background. Based on the great `ys` theme and [Honukai ZSH Theme](https://github.com/oskarkrawczyk/honukai-iterm-zsh) ⭐ 1,083 | 🐛 0 | 📅 2018-03-26. Shows root status and `git` status decorations.
* [lcars](https://github.com/lgulliver/lcars-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-23 - A Star Trek: The Next Generation LCARS-inspired theme for Oh My Zsh with modern powerline-style segments and authentic color palette. Includes decorators for `git` status, time, path, os and battery charge level.
* [leon](https://github.com/prince-an/Leon_zshTheme) ⭐ 0 | 🐛 0 | 📅 2021-10-13 - Works well on light background. Includes `git` status, time, username\@host, working directory and last command exit status decorations.
* [less-noise](https://github.com/ablil/less-noise) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-10-31 - Minimalist theme with decorators for `git` status, current directory and the current time.
* [lewis](https://github.com/lewisflude/oh-my-lewis) ⭐ 0 | 🐛 0 | 📅 2012-09-20 - Black, white and red theme. Shows `git` status information.
* [lgbt](https://github.com/nautilor/lgbt.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-02 - Colorful theme with decorators for current directory and `git` status.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2014-05-30 - Minimalist theme, best on a dark terminal background.
* [lilith](https://github.com/aknackd/zsh-themes) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-28 - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [hyperzsh](https://github.com/tylerreckart/hyperzsh) ⭐ 539 | 🐛 0 | 📅 2020-10-16.
* [limpide](https://github.com/shooteram/limpide) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-02-19 - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme which displays parent and current directory.
* [linuxero](https://github.com/andreshincapier/linuxero) ⭐ 0 | 🐛 0 | 📅 2022-01-18 - Minimalist. Includes decorations for root status, current directory, `git` status, current ruby rvm environment and current python virtualenv.
* [lish](https://github.com/bashelled/lish) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-06-13 - A casual theme. No roughness, just smooth. Includes `git`, user\@host, last command exit status, current directory, current time and root status decorators.
* [liver](https://github.com/RenoirTan/liver.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-05-04 - Colorful, includes `git` status, user, host, current and relative path to the current repository root decorations.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-07-31 - Texas-themed theme based on Sindre Sorhus' pure theme.
* [lorond](https://github.com/lorond/zsh-lorond/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-03-15 - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2013-12-10. Includes `git` status, works with standard fonts.
* [lperezp](https://github.com/lperezp/lperezp-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-09-08 - Includes decorators for user\@hostname, `git` status, current directory and the exit status of the last command run.
* [luceast](https://github.com/LucEast/luceast-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-16 - Optimized for `git`. Includes decorations for username, host, time & working directory.
* [ludvig](https://github.com/daviludvig/ludvig-theme-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-08-13 - Minimalist. Includes decorators for `git` status, current directory, current time and the last command's exit status.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-12-28 - Variant of [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) ⭐ 470 | 🐛 6 | 🌐 Shell | 📅 2025-04-24 theme. Has `git` decorations, requires a powerline-compatible terminal font.
* [luke](https://github.com/xueguangl23/luke_zsh_theme) ⭐ 0 | 🐛 0 | 📅 2019-03-21 - Includes `git` decorations. Based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 oh-my-zsh theme.
* [lunachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/lunachar.zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2023-05-27 - Minimalist theme.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) ⭐ 0 | 🐛 0 | 📅 2022-01-11 - Includes `git` status and last command execution time decorations.
* [madas](https://github.com/utauyo/madas-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-03-05 - Inspired by af-magic. Includes decorators for `git` status, user\@host, and whether the last command failed.
* [magento](https://github.com/cmuench/zsh-magento-cloud/blob/main/zsh-magento-cloud.plugin.zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-21 - Add Magento Cloud Command Line Interface ([magento-cloud CLI](https://experienceleague.adobe.com/docs/commerce-cloud-service/user-guide/dev-tools/cloud-cli.html?lang=en)) completions.
* [magico](https://github.com/IOsonoTAN/magico) ⭐ 0 | 🐛 0 | 📅 2016-07-22 - IOsonoTAN's magico theme.
* [magpie](https://github.com/wdjcodes/magpie) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-10-17 - Minimalist theme with custom logic to display paths relative to the root of the current `git`. Includes decorators for time, current directory, username\@hostname and `git` status.
* [mainnika](https://github.com/mainnika/zsh-theme-mainnika/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-30 - Includes decorators for last command exit status and the 1, 5 and 15 minute load averages.
* [malev](https://github.com/mvinan/malev-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-15 - Has minimalist and normal variants. Includes decorators for hostname, directory, `git` status and the last command's exit status.
* [mantis](https://github.com/dann254/mantis-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-24 - Minimal theme with `git` status and information decorators.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-01-16 - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) ⭐ 6,532 | 🐛 77 | 🌐 Shell | 📅 2025-12-24 integration.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-12-12 - Includes `git` status decorations, shows exit code of last command if nonzero.
* [michelebira](https://github.com/mortinger91/michelebira) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-06 - Variation of the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes decorators for `git` status, username, current directory and the return code of the last command run.
* [midin](https://github.com/xlshiz/midin) ⭐ 0 | 🐛 0 | 📅 2019-08-16 - Works well on dark terminal background, includes `git` status decorations.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-01-29 - Minimalist, includes `git` status decorations.
* [milight](https://github.com/frodoslaw/milight-zsh) ⭐ 0 | 🐛 0 | 📅 2017-12-18 - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-04-23 - A minimal asynchronous ZSH theme optimized for use with the [Fira Code](https://github.com/tonsky/FiraCode) ⭐ 81,125 | 🐛 426 | 🌐 Clojure | 📅 2026-01-28 font and the [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
* [mint](https://github.com/FalconLee1011/mint-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-06-14 - Includes decorators for current directory, whether running on a laptop or a desktop, and `git` status.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2018-03-21 - Optimized for dark backgrounds.
* [mocha-fusion](https://github.com/saeed0xf/mocha-fusion) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-10 - Based on [catpuccin](https://catppuccin.com/). Includes `git`, current directory and username\@host decorators.
* [modern](https://github.com/BadRat-in/zsh-modern-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-20 - Automatically adapts to light and dark terminal themes. This theme provides a clean and informative prompt with git integration, command execution time, and a beautiful rainbow directory path.
* [monsi](https://github.com/rafa-wine/monsi_oh-my-zsh_theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-23 - Includes `git` status, last command exit status and current directory decorators.
* [moon-lite](https://github.com/anotherlusitano/moon-light) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-05-28 - Minimalist. Includes decorators for `git` status, current directory and the exit status of the last command run.
* [moux](https://github.com/gagbo/moux) ⚠️ Archived - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
* [msys2](https://github.com/water-logger/MSYS2-Theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-26 - Inspired by MSYS2. Includes decorators for user\@host, `git` status and the current directory.
* [musy](https://github.com/tonyke-bot/musy-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-06-03 - Inspured by muse theme. Includes `git` status decorations.
* [my](https://github.com/fabiendelpierre/my-zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-02-27 - Variant of [kolo](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#kolo) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [myzsh](https://github.com/MaxUlysse/myzsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-21 - Maxime Garcia's myzsh theme.
* [nablaman](https://github.com/kokkonisd/nablaman-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-01 - Similar to [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 52,730 | 🐛 134 | 🌐 Shell | 📅 2026-01-28. Includes decorators for the last command's exit status, user\@hostname, `git` status and the current directory. Works best with a dark terminal theme.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-12-10 - Minimalist theme with text `git` status decorations.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-11-23 - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [neon-potato](https://github.com/algosuna/neon-potato) ⭐ 0 | 🐛 0 | 📅 2020-12-10 - Colorful and minimalist theme. Includes `git` decorations.
* [netmask](https://github.com/swomf/netmask-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 C | 📅 2025-11-03 - Termux-first theme. Includes decorators for ip address, full path to current directory, `git` status and python virtual environment.
* [newton](https://github.com/sebastienfilion/zsh.newton) ⭐ 0 | 🐛 0 | 📅 2020-12-22 - Includes `git` status and external IP address decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-08-22 - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-03-20 - A simple oh-my-zsh theme.
* [noon](https://github.com/silky/noon.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-09-15 - Has light and dark variants, shows `git` information.
* [normanius](https://github.com/normanius/normanius-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-10-21 - Derived from [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `git` status, `user@host`, python `virtualenv`, and ruby `rvm` version.
* [nova](https://github.com/body20002/nova) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-22 - Includes `git` status decroations. Overrides `LS_COLORS` and `LSCOLORS` settings.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-29 - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
* [odie](https://github.com/masterodie/zsh-theme-odie/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-09-03 - Works well on a dark background. Includes `git` status, python virtualenv and `vi`-mode status decorations.
* [ohelm](https://github.com/devopsguy/ohelm-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-04 - Includes decorators for current directory, `git` status, exitatus of last command and `kubectl` context.
* [omuse](https://github.com/ouuan/omuse-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-06-09 - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
* [owczarczak](https://github.com/ThemysciraData/owczarczak.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2022-02-03 - Inspired by bira, dieter and [fino-time](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fino-time.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes `venv` and vcs status decorations.
* [owi](https://github.com/owitech/zsh-theme/) ⭐ 0 | 🐛 1 | 📅 2021-11-25 - Minimalist theme with `git` status decorations.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) ⭐ 0 | 🐛 0 | 📅 2019-10-23 - Shows detailed `git` status information with icons in the prompt.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-11-07 - Includes `git` and `root` status decorations. Best on a dark background.
* [parrot-htb](https://github.com/Lloyd-Leo/parrot-htb-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-12-23 - Includes decorators for current directory, `git` status and username\@hostname.
* [paulmanjarres](https://github.com/paul-manjarres/paulmanjarres-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-09 - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, [agnoster](https://gist.github.com/agnoster/3712874) and [nuts](https://github.com/rafaelsq/nuts.zsh-theme) ⭐ 6 | 🐛 1 | 🌐 Makefile | 📅 2020-03-02. Includes decorators for current directory, `git` status and the time.
* [paxton](https://github.com/p1xt4n/ohmyzsh-theme-paxton) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-30 - Inspired by powerline. Includes segments for `git` branch, time, last command exit status and current directory. Requires a powerline-compatible font.
* [pbdevflow](https://github.com/pbarovsky/pbdevflow) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-01 - Designed and optimized for use with [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26. Includes decorators for current directory, `git` status and username.
* [pbsegments](https://github.com/pbarovsky/pbsegments) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-17 -A  minimal and visually appealing custom theme for [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. It features a clean, segment-based prompt, optimized for readability and usability. Includes decorators for `git` status, current directory and username.
* [pecodez](https://github.com/pecodez/pecodez-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-12-29 - Optimized for dark terminals. Has decorators for `snyk` version, `node` version, AWS profile, kubernetes context and `git` status.
* [pedantic](https://github.com/nemeshnorbert/pedantic-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-02 - Customizable colors and output. Includes decorators for detailed `git` information, root status, last command's exit status, user\@host, current directory and the time.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-03-20 - Minimal theme in the spirit of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and Pure Shell themes.
* [pickaxe](https://github.com/mikhaben/pickaxe-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-09 - Includes decorators for `user@host`, current directory, current time, conda environment, node version and `git` status.
* [pico](https://github.com/PicoGeyer/zsh-pico-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-12-18 - Simple prompt modified from [zap-prompt](https://github.com/zap-zsh/zap-prompt) ⭐ 29 | 🐛 2 | 🌐 Shell | 📅 2023-11-28 with decorators for `git` information, user\@hostname and working directory.
* [pifabs](https://github.com/pifabs/pifabs-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-06 - Minimal theme with decorators for `git` status, username, host and working directory.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) ⭐ 0 | 🐛 0 | 📅 2020-11-04 - Minimalist, but includes `git` status decorations.
* [plain](https://github.com/jimeh/plain.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2017-08-02 - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) ⚠️ Archived - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-02-13 - Programmer's theme with `git` status, ruby version and project path.
* [powermore](https://github.com/primejade/powermore-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-02-21 - Forked from [powerless](https://github.com/martinrotter/powerless) ⭐ 76 | 🐛 0 | 🌐 Shell | 📅 2020-05-14. Simple prompt that shows `git` status and current directory.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-06-26 - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) ⚠️ Archived.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) ⭐ 0 | 🐛 0 | 📅 2015-04-14 - Lambda theme (for prezto).
* [prompt\_j2](https://github.com/malinoskj2/prompt_j2) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-12-21 - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [prompt](https://github.com/nathanblair/prompt) ⚠️ Archived - A lightweight prompt consistent across `sh`, `dash`, `ash`, `zsh`, and `pwsh`. Includes `git` status decorations.
* [pronto (arzezak)](https://github.com/arzezak/pronto) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-02 - A super simple prompt with decorators for the current directory and `git` information.
* [pumpkane](https://github.com/ColinZeDev/pumpkane-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-10 - A modern, colorful, and informative theme designed for clarity, aesthetics, and productivity. It features dynamic colors, `git` status integration, time-based coloring, and optional nickname display
* [purpleblood](https://github.com/HFMorais/oh-my-zsh-purpleblood-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-25 - Based on [darkblood](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/darkblood.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for `username@host`, `git` status, and current directory.
* [purr](https://github.com/mubinben/purr-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-09-11 - Includes decorators for current directory and `git` status.
* [pustelto](https://github.com/Pustelto/shell_theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-03-02 - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) ⭐ 20,388 | 🐛 128 | 🌐 Shell | 📅 2025-12-24 theme, includes `git` decorations.
* [pwn](https://github.com/gh05t-4/pwn-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-24 - Includes decorators for user\@host, `git` & `hg` status, ruby version, python virtualenv and current working directory.
* [qi3ber2](https://github.com/nichus/qi3ber2) ⭐ 0 | 🐛 0 | 📅 2021-03-12 - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
* [r3-fresh](https://github.com/r3-fresh/r3-fresh-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-09 - Includes decorators for `git` status, current directory, exit status of last command run.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) ⭐ 0 | 🐛 0 | 📅 2022-08-16 - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23 variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
* [rabbit](https://github.com/Hera-Moon/My-rabbit-Zsh-Theme) ⭐ 0 | 🐛 2 | 🌐 Shell | 📅 2024-06-26 - Optimized for `git`. Requires a terminal program that works with unicode. Includes decorators for `git` status, current working directory and the current virtual environment.
* [ramiel](https://github.com/aknackd/zsh-themes) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-12-28 - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme) ⭐ 69 | 🐛 0 | 📅 2015-12-10.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-05-02 - Includes `git`, python, time, current host and path decorations.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-04-29 - Simple and colorful theme with `git` status decorations.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-01-12 - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [redfox](https://github.com/saeed0xf/terminal-themes) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 - Includes decorators for the current directory and a fox icon.
* [refined-flower](https://github.com/idaMakelaWork/refined-flower) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-06-17 - Requires a terminal program that can handle emoji. Includes `git` status decorator.
* [refpx](https://github.com/refpx/refpx-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-09 - Includes `git` status, last command status, user\@hostname and directory decorations.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) ⭐ 0 | 🐛 0 | 📅 2020-02-13 - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-08-08 - A simple theme with the first character 零(rei), the number 0. Includes `git` status decorations.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) ⭐ 0 | 🐛 21 | 🌐 Shell | 📅 2022-12-09 - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) ⭐ 4,194 | 🐛 83 | 🌐 Shell | 📅 2023-01-23, using emojis for tracking `git` context. Only works with [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24.
* [rho](https://github.com/andrii-rieznik/rho-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-27 - Minimalist theme. Includes decorators for `git` status, hostname and current directory.
* [ribbon](https://github.com/pyjamafish/ribbon-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-11-28 - Reminiscent of Powerline. Includes Python `virtualenv` decorator.
* [rie](https://github.com/andrii-rieznik/rie-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-27 - Minimalist theme with decorators for username, `git` status and current directory.
* [rigel](https://github.com/othiagos/rigel-zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-12-29 - Includes decorators for `git` information, user\@hostname and current directory.
* [rio](https://github.com/foxit64/zsh-theme-rio) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-28 - Minimalist theme with decorators for `git` status and current directory.
* [ritz](https://github.com/Ritzier/ritz.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-29 - Includes decorators for time, current directory, `git` status, exit status and time used for last command run.
* [rkj-logik](https://github.com/logik93/rkj-logik.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-26 - Based on omz's [rkj](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes decorators for user\@host, current directory, time & date.
* [rkj-with-conda](https://github.com/cain986/rkj-with-conda-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-03-27 - Based on omz's [rkj](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/rkj.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and adds conda environment and `git` status decorators.
* [robbyrussell-plus](https://github.com/jackjyq/robbyrussell-plus-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-03-21 - Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, adds a hostname decorator.
* [rs](https://github.com/sam-621/rs-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-17 - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) ⚠️ Archived - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-08-20 - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [ruweird](https://github.com/ruweird/ruweird.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-11-21 - Minimalist. Has decorators for `git` status and current directory. Shows an umbrella with raindrops and exit code of the last command if non-zero.
* [rwahasugui](https://github.com/rafawhs/rwahasugui.zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-12-13 - Includes decorators for `git` information, current time, current working directory and active python  virtualenv.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-10-06 - Works well with dark backgrounds. Includes `git` status decorations.
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-10-28 - Shows decorators for `git` status, `user@host` information, the exit status of last command, and whether running as root.
* [scythe](https://github.com/kostoskistefan/scythe) ⭐ 0 | 🐛 0 | 📅 2021-12-13 - Powerline-reminiscent theme. Includes `git`, last command exit status and directory decorations.
* [sdt](https://github.com/sdlea/omz-theme-sdt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-17 - Includes decorators for current directory and `git` status.
* [searocket](https://github.com/dk949/searocket/) ⭐ 0 | 🐛 1 | 🌐 D | 📅 2025-01-11 - Slimmed down version of [spaceship](https://github.com/denysdovhan/spaceship-prompt) ⭐ 20,388 | 🐛 128 | 🌐 Shell | 📅 2025-12-24. Includes decorators for working directory, last command exit code, user, background jobs, `bun`, `d`, elm, go, nodejs, python, zig and `git` status. Requires `D` build chain.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-08-22 - Inspired by the dieter theme, uses color-coding to provide information.
* [sensa](https://github.com/miccou/sensa-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-12-19 - Includes decorators for `git` status, GitHub username and current directory.
* [serenity](https://github.com/ars2062/serenity-zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-07-17 - Minimalist theme which displays essential context info in soft-colored boxes above the command line, using Unicode separators to stay clean yet expressive. Includes decorators for root status, username, hostname, host IP address, `git` status and current directory.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-08-08 - A simple theme with the first character being 七(shichi/nana), the number 7. The primary color is red with a yellow accent. Includes `git` status decorations.
* [shiftys](https://github.com/shifty0g/shiftys-zsh-theme/) ⭐ 0 | 🐛 0 | 📅 2022-09-04 - Tweaked version of the kali theme.
* [shini](https://github.com/bashelled/shini) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-12-29 - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-07-29 - Includes `git` status and `user@hostname` decorations.
* [shiro (arturDobrowolski)](https://github.com/ArturDobrowolski/shiro-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-30 - Includes decorators for current directory, `git` status, and exit status and execution time of last command run.
* [shiro (shirozuki)](https://github.com/shirozuki/shiro-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-30 - Includes decorators for current directory, `git` status and execution time and exit status of last command run.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) ⭐ 0 | 🐛 0 | 📅 2019-04-02 - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme) ⭐ 4 | 🐛 0 | 📅 2019-04-01. Has `git` decorations.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-12-05 - Based on the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme. Includes `git` and `hg` status decorations.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) ⭐ 0 | 🐛 0 | 📅 2019-10-21 - Includes `git` decorations.
* [shuttle](https://github.com/Pandademic/Shuttle/) ⭐ 0 | 🐛 2 | 🌐 Go | 📅 2022-08-04 - Written in `golang`. Has decorators for OS, user, current directory, and the exit code of the last command run.
* [siegerts](https://github.com/siegerts/zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-02-09 - Includes `git` status decorations in right prompt.
* [simpl](https://github.com/MrNeoTr1n0/simplzshell) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-10-15 - Minimalist theme focusing on elegance and simplicity. Decorators for root status, current directory and `git` status.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-10-12 - Minimal prompt, doesn't require special fonts.
* [simple-chack](https://github.com/chack93/simple-chack.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-05-16 - Works well with solarized terminal color scheme. Includes `git` status decorations.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) ⭐ 0 | 🐛 0 | 📅 2020-09-04 - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) ⭐ 5 | 🐛 0 | 📅 2020-09-30. Includes `git` decorations.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-07-05 - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simply-perfect](https://github.com/SetOfAllSets/simply-perfect-zsh-theme/) ⚠️ Archived - Reminiscent of Powerline and Bullettrain. Includes decorators for `git` status, current directory, last command exit status, current time and username.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) ⭐ 0 | 🐛 0 | 📅 2019-07-11 - k-kinzal's sinon theme. Includes `git` status decorations.
* [sit](https://github.com/svensen/sit.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-04-14 - Minimalist theme with `git`, last command exit status and path decorations.
* [sk9](https://github.com/skeiter9/sk9-zsh) ⭐ 0 | 🐛 0 | 📅 2015-04-08 - Skeiter9's ZSH theme.
* [skiff](https://github.com/xiaoshihou514/skiff) ⚠️ Archived - Lightweight ZSH theme with `git` status and current directory decorators.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) ⭐ 0 | 🐛 0 | 📅 2020-08-02 - A variant of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [smelly](https://github.com/Vicfs/smelly-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-08-18 - Minimalist prompt that includes decorators for Python `venv` and `git` status.
* [sorin-modified-dark](https://github.com/hrmeetsingh/sorin-modified-dark) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-08-13 - Based on [sorin](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#sorin) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Minimalist, adds decorators for `git` status and current directory.
* [ssfprompt](https://github.com/hugoh/zsh-ssfprompt) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-11 - Simple, slim, fast. Includes `ssh`, virtualenv and vcs decorations.
* [steef (zelongguo)](https://github.com/ZelongGuo/steeef) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-01 - Based on the [zimfw steef theme](https://github.com/zimfw/steeef) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2022-08-13. Includes decorators for username\@hostname, python venv, `git` status and current directory. Requires [git-info](https://github.com/zimfw/git-info) ⭐ 11 | 🐛 2 | 🌐 Shell | 📅 2026-02-04.
* [steeple](https://github.com/erwanjugand/steeple-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2022-01-31 - Minimalist theme with `git` status decorations.
* [stellachar](https://github.com/r-mohammadi1/armans-zsh-themes/blob/main/stellachar.zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2023-05-27 - Minimal, pastels.
* [stigmata](https://github.com/VLtim43/stigmata.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-10-14 - Includes decorators for user\@host and current directory.
* [sublime](https://github.com/pjmp/sublime) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2019-09-23 - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-02-05 - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-03-29 - The official ZSH theme of sulfuriumOS.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) ⭐ 0 | 🐛 0 | 📅 2020-05-29 - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 but includes the active Ruby version.
* [sunrise](https://github.com/tech8i/zsh_sunrise) ⭐ 0 | 🐛 0 | 📅 2024-07-21 - Includes decorators for battery status, current directory, date and time.
* [svs](https://github.com/SvS30/svs-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-06-03 - Clean and distraction free theme with `git` status and current path decorations.
* [t2er](https://github.com/t2er/t2er-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-01-12 - Minimalist theme with `git` decorations.
* [tcr](https://github.com/tulioribeiro/zsh-tcr-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-04-13 - Minimalist theme, shows decorators for current directory, `git` status information & `nvm` version.
* [teajay](https://github.com/Teajey/teajey-zsh-theme) ⭐ 0 | 🐛 1 | 🌐 Shell | 📅 2025-01-31 - Adapted from murilasso and fishy themes. Includes decorators for `git` status, and path to current directory (collapsed to show only most relevant parts) and the exit code of last command run.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) ⭐ 0 | 🐛 0 | 📅 2015-01-08 - A theme based on [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02.
* [themeraf](https://github.com/oliver-svrcek/Themeraf) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-04-28 - Has decorators for username, last two directories in working directory path, `git` status, timestamp, last exit status and also name of active virtual environment.
* [theozera](https://github.com/theogandara/zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-07-18 - Includes decorators for `git` status, a truncated current directory, and the exit status of the last command run.
* [thygod](https://github.com/Thy-GoD/thy-god-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-02-27 - Based off [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes a `git` status decorator and changes prompt to a red cross when a command fails.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-08-02 - Includes time and `git` status decorators.
* [torim](https://github.com/Aggrathon/torim) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-01-30 - Inspired by the [sorin](https://github.com/zimfw/sorin) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2026-02-04, [asciiship](https://github.com/zimfw/asciiship) ⭐ 27 | 🐛 1 | 🌐 Shell | 📅 2025-12-11 and [mh](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#mh) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes. Includes decorators for user\@hostname (when accessed by `ssh`), truncated path to working directory, whether running as root, error code of last command run if it failed, current time, duration of long running commands, current virtual environment and `git` status.
* [tron](https://github.com/iDoTron/tron-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-08-14 - Includes `git` status, working directory, time, user\@host and return status of last command decorations.
* [troopert](https://github.com/TrooperT/Troopert-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-09-05 - Includes decorators for `git` status, last return code if non-zero, full pwd and a configurable display of `$RPROMPT`.
* [turs](https://github.com/eikendev/turs) ⚠️ Archived - Fast, minimal [Purs](https://github.com/xcambar/purs) ⭐ 264 | 🐛 8 | 🌐 Rust | 📅 2020-02-15-inspired prompt.
* [type0](https://github.com/MikereDD/type0_zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-04-11 - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) ⭐ 55 | 🐛 0 | 📅 2022-06-15 by yarisgutierrez. Includes `git` decorations.
* [typedark](https://github.com/BonnyAD9/TypeDark) ⭐ 0 | 🐛 0 | 🌐 VHDL | 📅 2026-01-29 - Works with [ZSH Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) ⭐ 22,216 | 🐛 205 | 🌐 Shell | 📅 2024-11-21.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) ⭐ 0 | 🐛 0 | 📅 2020-02-12 - Mimics the default Debian/Ubuntu `bash` prompt.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) ⭐ 0 | 🐛 0 | 📅 2020-03-29 - Mimics the default Ubuntu prompt, but with `git` decorations.
* [ultimator](https://github.com/Ultimator14/ultimator-zsh-theme) ⚠️ Archived - [Agnoster](https://gist.github.com/agnoster/3712874)-like theme. Includes decorators for current directory, `user@host`, python virtualenv, background jobs, last command exit status, and `git` status information. Requires [zsh-git-prompt](https://github.com/Ultimator14/zsh-git-prompt) ⚠️ Archived plugin and Nerdfonts.
* [unit-1](https://github.com/nerdbude/Unit-1) ⭐ 0 | 🐛 0 | 📅 2020-11-23 - Minimalist theme with ITWTB colors.
* [userandnode](https://github.com/timhilton/userandnode) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-21 - A clean theme with decorators for username, node version, current directory, and `git` info.
* [valuca](https://github.com/keyaedisa/Valuca) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-03-17 - Variant of [ducula](https://github.com/janjoswig/Ducula) ⭐ 48 | 🐛 1 | 🌐 Shell | 📅 2025-11-17. Includes decorators for background job status, username, hostname, virtualenv, current directory, last command's exit code, `git` information and the current time.
* [vanan](https://github.com/avano/vanan.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-07-28 - Enhances your terminal with detailed `git` information. Also includes decorators for `vi`-mode and status of the last command run.
* [vehemence](https://github.com/H1N1-dev/vehemence-zsh) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-10-14 - Includes decorators for `pwd`, `user@host`, `tty`, time, last command exit code and `git` status.
* [velvet](https://github.com/dor133/velvet-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-11-22 - Includes decorators for `git` status, username, current directory, exit status of last command, and the time.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) ⭐ 0 | 🐛 0 | 📅 2021-08-06 - Based on ys. Includes vcs status, username and current directory decorations.
* [voidy](https://github.com/rwejdling/voidy) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-03-21 - Borrows elements from [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 themes and adds the active [aws-vault](https://github.com/99designs/aws-vault) ⭐ 8,953 | 🐛 0 | 🌐 Go | 📅 2025-12-30 profile to the right side of the prompt.
* [vszambon-ocean](https://github.com/vzambon/vszambon_ocean-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-08-16 - Includes decorators for current directory, `git` status, a day/night icon, whether or not it is running inside a `docker` container and the date and time.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2021-01-26 - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [warm-colours](https://github.com/BastionAtackDev/Warm-Colours.zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-20 - Includes decorators for user\@host, current directory and datetime.
* [whales](https://github.com/lbergelson/zsh_whales_theme) ⭐ 0 | 🐛 0 | 📅 2021-06-22 - Includes decorators for `git` status, java version, last command return status, and directory.
* [xandermute](https://github.com/SoYoureAWaffleMan/xandermute-oh-my-zsh-theme/) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-11-03 - Minimalist theme with `git` and current directory decorations.
* [xavi](https://github.com/onthedock/xavi.zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-07 - Modified version of the [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02 theme with emoji decorations for `git` status and current directory.
* [xbira](https://github.com/ITAxReal/xbira) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-08-04 - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02, includes decorators for `git` status, user\@hostname, exit status of last command run and the current directory.
* [xm](https://github.com/Shiaoming/xm) ⭐ 0 | 🐛 0 | 📅 2018-12-12 - Theme for dark terminals. Has `git` decorations.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2019-04-18 - Minimalist theme with `git` status decorations.
* [yeet](https://github.com/jeetelongname/Yeet-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2021-07-28 - Minimalist prompt with `git` status decorations.
* [yellow peach](https://github.com/tomorrowbye/yellow-peach-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-02-14 - Clean minimalist design. Includes decorators for `user@hostname`, `git` status, current directory and the current time.
* [yellow-sea-diamonds](https://github.com/jimratliff/yellow-sea-diamonds-zsh-theme) ⚠️ Archived - Includes decorations for `git` status, current directory, active python virtual environment, and the exit status of the last command run.
* [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) ⭐ 0 | 🐛 1 | 📅 2016-12-15 - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ysr](https://github.com/raykle/ysr-zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-03-22 - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) ⭐ 184,541 | 🐛 509 | 🌐 Shell | 📅 2026-02-02. Includes `git` status decorations.
* [yuni](https://github.com/skippyr/yuni) ⚠️ Archived - A modern version of the macOS default ZSH theme, adding essential developer features the original theme lacked. Includes decorators for the exit code of failed commands, your user and host names, shortened current directory path, the active branch, and privilege decorators: `%` if you're a normal user, `#` if root, and `[!]` when you don't have permissions to modify the current directory. Works on macOS 14 Sonoma or later.
* [zen (TheCrazyGM)](https://github.com/TheCrazyGM/zen) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-14 - A clean, informative, and customizable theme for Oh-My-Zsh that provides essential information without cluttering your terminal. It was designed with Python developers in mind and includes smart features like SSH detection, detailed Git status information, and command execution time tracking.
* [zenith (husniadil)](https://github.com/husniadil/zenith-oh-my-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-13 - A clean, modern Zsh theme designed for efficiency and aesthetics. Featuring a cool-toned color palette with intuitive Git status indicators, it keeps your terminal workflow smooth and distraction-free. Includes decorators for color-coded `git` status, exit status of last command and compact directory display.
* [zero (shirozuki)](https://github.com/shirozuki/zero-zsh-theme) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2024-07-30 - Minimalistic prompt with decorators for `git` status, current directory, exit status and time to execute of last command run.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) ⭐ 0 | 🐛 0 | 📅 2020-10-21 - Works better on dark brackgrounds.
* [zest](https://github.com/hash-bang/zsh-theme-zest) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-07-11 - A functional theme for ZSH. Influenced by [zsh2000](https://github.com/consolemaverick/zsh2000) ⭐ 117 | 🐛 1 | 🌐 Shell | 📅 2023-05-30, [agnoster](https://gist.github.com/agnoster/3712874) and [powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) ⚠️ Archived themes.
* [zlambda](https://github.com/wdhg/zlambda) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2020-12-04 - Minimalist, includes `git` decorations without special font requirements.
* [zodiac](https://github.com/adamalsen/zsh-zodiac) ⭐ 0 | 🐛 0 | 📅 2022-01-18 - Includes an emoji for the animal corresponding to the current year.
* [zsh313](https://github.com/amirali313/zsh313-theme) ⭐ 0 | 🐛 0 | 📅 2019-09-15 - Minimal theme with `git` status decorations.
* [zshiggy](https://github.com/malouro/zshiggy) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-11-28 - Includes decorators for `git` status, `node.js` version.
* [zwsh](https://github.com/naens/zwsh) ⭐ 0 | 🐛 18 | 🌐 Shell | 📅 2020-06-20 - A Zpm3/Wordstar mode/theme for ZSH.
* [zzshell](https://github.com/thezzisu/zzshell) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2023-06-14 - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.
* [adoz](origin/daviosoo/adoz-zsh-theme) - A minimalistic theme with a focus on purple and blue color tones. Adoz provides a clean, modern prompt that displays essential information while maintaining a sleek aesthetic. Highly customizable by setting environment variables. Includes decorators for user\@hostname, current directory, timestamp and `git` status.
* [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user\@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
* [candy-light](https://git.sr.ht/~nicolairuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [neo++](https://gitlab.com/migoa/neo) - Simpler, more intuitive, and less clustered than the one above.
* [nidoranarion](https://git.sr.ht/~nicolairuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
* [starship](https://starship.rs/) - Minimal, fast, extremely customizable.
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current `git` commit's shortened hash and message.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 61,581 | 🐛 59 | 🌐 CSS | 📅 2026-01-26 - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) ⭐ 26,221 | 🐛 182 | 🌐 Shell | 📅 2024-03-22 - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Maple](https://github.com/subframe7536/maple-font) ⭐ 23,332 | 🐛 15 | 🌐 Python | 📅 2026-01-12 - An open source monospace font with Nerd Font support focused on smoothing your coding flow.
* [Iosevka](https://github.com/be5invis/Iosevka) ⭐ 21,678 | 🐛 102 | 🌐 JavaScript | 📅 2026-02-06 - Coders' typeface, built from code. Highly customizable.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) ⭐ 7,314 | 🐛 68 | 🌐 Python | 📅 2022-12-02 - Another Powerline-compatible font.
* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) ⭐ 2,515 | 🐛 23 | 🌐 Shell | 📅 2024-01-16 - A family of fonts that includes some nice monospaced Icons.
* [SFMono Nerd Font Ligaturized](https://github.com/shaunsingh/SFMono-Nerd-Font-Ligaturized) ⭐ 1,003 | 🐛 6 | 📅 2023-07-02 - Pre-patched opentype versions of macOS's SFMono fonts with support for ligatures and Nerd Fonts.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) ⭐ 37 | 🐛 1 | 🌐 Shell | 📅 2015-02-20 - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](https://store.typenetwork.com/foundry/djr/series/input?family=input-mono) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

I recommend [zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01 if you don't already have a preferred ZSH framework. It adds minimal overhead during shell session startup because it generates a load script only when you change your plugin list, and that load script is sourced during startup instead of being recalculated every time.

### [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,301 | 🐛 97 | 🌐 Shell | 📅 2024-02-18

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh) ⭐ 230 | 🐛 2 | 🌐 Shell | 📅 2018-05-20

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,461 | 🐛 188 | 🌐 Shell | 📅 2026-01-24

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen) ⭐ 1,519 | 🐛 41 | 🌐 Shell | 📅 2021-07-21

Zgen is not being actively maintained. I recommend that you switch to the [Zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01 fork, which is.

### [Zgenom](https://github.com/jandamm/zgenom) ⭐ 414 | 🐛 5 | 🌐 Shell | 📅 2026-01-01

Most of these plugins can be installed by adding `zgenom load githubuser/reponame` to your `.zshrc` file in the same function you're doing your other `zgenom load` calls in.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug](https://github.com/zplug/zplug) ⭐ 5,990 | 🐛 150 | 🌐 Shell | 📅 2024-06-12

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm](https://github.com/zpm-zsh/zpm) ⭐ 391 | 🐛 5 | 🌐 Shell | 📅 2025-12-21

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins and Themes

I've documented some recommendations for writing new plugin and themes [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins_and_Themes.md) ⭐ 17,372 | 🐛 5 | 🌐 Shell | 📅 2026-02-03.

There is also a more detailed [Zsh Plugin Standard](https://zdharma-continuum.github.io/Zsh-100-Commits-Club/Zsh-Plugin-Standard.html).

## Other Resources

### ZSH Tools

* [argcomplete](https://github.com/kislyuk/argcomplete) ⭐ 1,546 | 🐛 70 | 🌐 Python | 📅 2025-10-20 - Generates tab completions for programs using Python's `argparse` module.
* [shellSpec](https://github.com/shellspec/shellspec) ⭐ 1,343 | 🐛 105 | 🌐 Shell | 📅 2025-11-24 - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [carapace](https://github.com/rsteube/carapace) ⭐ 1,141 | 🐛 44 | 🌐 Go | 📅 2026-02-06 - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - this does not automatically generate completions on demand, you have to explicitly run it to generate completions for a command.
* [zsh-bench](https://github.com/romkatv/zsh-bench) ⭐ 899 | 🐛 3 | 🌐 Shell | 📅 2026-01-17 - A benchmark for interactive ZSH. It measures user-visible latency of interactive `zsh`: input lag, command lag, etc.
* [shtab](https://github.com/iterative/shtab) ⭐ 439 | 🐛 38 | 🌐 Python | 📅 2026-01-05 - Automatically generate shell tab completion scripts for Python CLI apps, supports `zsh`, `bash` and `tcsh`.
* [zshdb](https://github.com/rocky/zshdb) ⭐ 322 | 🐛 6 | 🌐 Shell | 📅 2025-10-05 - A ZSH debugger.
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) ⭐ 294 | 🐛 6 | 🌐 Python | 📅 2023-01-03 - Tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [complgen](https://github.com/adaszko/complgen) ⭐ 290 | 🐛 0 | 🌐 Rust | 📅 2026-02-05 - Generates completion scripts for bash/fish/zsh from a man-page/EBNF-like grammar. The resulting standalone scripts require only the target shell to be present.
* [zunit](https://github.com/zunit-zsh/zunit) ⭐ 219 | 🐛 18 | 🌐 Shell | 📅 2023-08-14 - A powerful unit testing framework for ZSH.
* [manpage-completion-generator](https://github.com/umlx5h/zsh-manpage-completion-generator) ⭐ 59 | 🐛 0 | 🌐 Go | 📅 2024-04-24 - Generats ZSH completions from man pages. Requires [create\_manpage\_completions.py](https://github.com/fish-shell/fish-shell/blob/master/share/tools/create_manpage_completions.py) ⭐ 32,500 | 🐛 528 | 🌐 Rust | 📅 2026-02-06 which is installed by the fish shell
* [zshelldoc](https://github.com/zdharma-continuum/zshelldoc) ⭐ 22 | 🐛 0 | 🌐 Shell | 📅 2023-11-20 - Doxygen for shell scripts. Parses ZSH and Bash scripts, outputs Asciidoc document with function lists, call trees, lists of exported variables, and more.
* [shell-color-prompt-tool](https://github.com/kyletimmermans/shell-color-prompt-tool) ⭐ 16 | 🐛 4 | 🌐 Shell | 📅 2026-01-22 - Helps you create a custom prompt for `ZSH` or `bash`.
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2023-02-16 - Generates shell completions for commands lacking them.
* [crazy-complete](https://github.com/crazy-complete/crazy-complete) ⭐ 12 | 🐛 8 | 🌐 Python | 📅 2025-11-08 - Every program should have autocompletion in the shell to enhance user experience and productivity. `crazy-complete` helps solve this task by generating robust and reliable autocompletion scripts.
* [zargparse](https://github.com/ctil/zargparse) ⭐ 12 | 🐛 5 | 🌐 Python | 📅 2024-01-11 - Pass it a script that uses `argparse` and it will write a ZSH completion to your current directory.
* [zsh-ai-completions](https://github.com/iloveitaly/zsh-ai-completions) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-01-23 - AI-generated ZSH completions
* [oh-plugin](https://github.com/mbergo/oh-plugin) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2023-03-09 - Helps you install plugins for [oh-my-zsh](https://ohmyz.sh) by typing `oh-plugin install repository_address`.
* [cgen](https://github.com/acristoffers/cgen) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2025-10-22 - Generate shell completions for Fish, Bash, and ZSH and man-pages from a single YAML file. No more hand-writing separate completion files for every shell.
* [completion-generators](https://github.com/zetlen/zsh-completion-generators) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-02-05 - Has a table of tool names and the commands for outputting completion scripts for those tools. On every load, will check that table and run the completion command for every tool found in your `$PATH` and save its output to a file `toolnam`e. If the path of this repo is in `$fpath`, completions will work immediately.
* [rust-zsh-plugin-cli](https://github.com/johnstonskj/rust-zsh-plugin-cli) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-01-25 - This tool scaffolds Zsh plugins with best practices built-in, including function tracking for clean unloading, optional alias support, autoloaded functions, and CI/CD workflows for shellcheck and shellspec. Choose from minimal, simple, or complete templates to match your plugin's complexity.
* [scog](https://github.com/Agentrifat/scog) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-02-07 - Scog is the Shell COmpletion Generator. This tool helps you easily manage and generate command completions for your shell environment.

### Other Useful Lists

* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) ⭐ 32,698 | 🐛 58 | 📅 2026-02-01 - A curated list of awesome open source sysadmin resources.
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) ⭐ 12,872 | 🐛 120 | 🌐 Shell | 📅 2024-07-26 - A curated list for CLI lovers.
* [awesome-devenv](https://github.com/jondot/awesome-devenv) ⭐ 3,155 | 🐛 26 | 📅 2024-07-29 - A curated list of awesome tools, resources and workflow tips making an awesome development environment.

Find other useful awesome-\* lists at the [awesome collection](https://github.com/sindresorhus/awesome) ⭐ 435,616 | 🐛 68 | 📅 2026-01-28

### Other References

* The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.

* [Mastering ZSH](https://github.com/rothgar/mastering-zsh) ⭐ 1,588 | 🐛 2 | 📅 2021-09-11 is a great tutorial that builds on the basics to show you advanced ZSH usage, customizations, and practical examples.

## Thanks

Many thanks to all the contributors over the years. The list wouldn't be nearly as complete without all your help.

<a href="https://github.com/unixorn/awesome-zsh-plugins/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=unixorn/awesome-zsh-plugins" />
</a>

Made with [contributors-img](https://contributors-img.web.app).
