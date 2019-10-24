---
title: Third Party Tools
---

Screeps 具有丰富的第三方开发社区，该社区已构建了许多工具，库和 Web 应用程序。
如果您的工具未在此处列出，请随时编辑本文。

{% note warn Use Caution %}

-   切勿将密码泄露给第三方。
-   许多第三方程序是使用非官方 API 构建的，并且可能随时停止运行。
-   所有第三方程序的运行风险均由您自己承担-游戏开发者不会审查它们，并且可能会导致无法预料的问题。
{% endnote %}

## Languages Support

您可以设置一个外部编译器，用另一种语言编写 Screeps AI。

### TypeScript

-   [screeps-typescript-starter](https://github.com/screepers/screeps-typescript-starter) 是想要使用 TypeScript 进行编程的玩家的起点。
-   [typed-screeps](https://github.com/screepers/typed-screeps) 是一组涵盖 Screeps API 的 TypeScript 声明。

### Python

-   [screeps-starter-python](https://github.com/daboross/screeps-starter-python/) 是一个可用 Python 中玩 Screeps 的平台。

### Rust

-   [screeps-starter-rust](https://github.com/daboross/screeps-starter-rust) 是一个开发中的平台，可用 Rust 玩 Screeps。

### Kotlin

-   [screeps-kotlin](https://github.com/exaV/screeps-kotlin) 是一个 Kotlin 的简单示例.
-   [screeps-kotlin-starter](https://github.com/exaV/screeps-kotlin-starter) 是想要在 Kotlin 编程的玩家的起点。
-   [screeps-kotlin-types](https://github.com/exaV/screeps-kotlin-types) 是一组涵盖 Screeps API 的 Kotlin 声明。

## API Clients

Screeps API 不是官方的，可能随时更改。 这些客户端由社区维护，并用于生成此页面上的许多服务和程序。

-   [python](https://github.com/screepers/python-screeps)
-   [node](https://github.com/screepers/node-screeps-api)

## Apps

-   [Screeps Monitor](https://play.google.com/store/apps/details?id=com.danielscholte.screepsmonitor) 是一款 Android 应用程序，可为玩家提供帐户和游戏统计信息，以及完整的消息客户端和市场历史记录。 （不再可用）。

## Backups

-   [screeps-backup](https://github.com/screepers/screeps-backup) 是用于内存和段的简单备份和还原实用程序。

## Consoles

-   [screeps_console](https://github.com/screepers/screeps_console) 是使用 python 构建的交互式独立控制台。 它支持常见的控制台键盘快捷键，具有许多内置命令，并且具有明暗主题。 也包括一个非交互式版本。

## Profilers

-   [gdborton's profiler](https://github.com/gdborton/screeps-profiler) 是基于函数包装的探查器，在发现性能问题时非常有用。

## Programming Tools

-   [closure-compiler-externs](https://github.com/screepers/screeps-closure-compiler-externs) 定义了 Screeps API，以便闭包不用重写这些调用。
-   [ScreepsAutocomplete](https://github.com/Garethp/ScreepsAutocomplete) provides autocomplete data for the Screeps API.
-   [screeps-server-mockup](https://github.com/Hiryus/screeps-server-mockup) 用于单元测试的专用服务器包。

## Notifications

-   [Screeps Notify](https://github.com/screepers/screeps_notify) 提供游戏内界面，使玩家可以将消息发送到游戏外服务。 它具有内置的 SMS 系统，还可以支持将消息发送到任意 http 接口。

## Statistics

Screeps runs constantly, and as a player it's not possible to watch everything that occurs. There are also issues which may show up when watching long term trends but not during the times which players are watching. For these reasons it's not surprising that the most popular applications are those used to track statistics.

-   [ScreepsPlus Grafana](https://screepspl.us/services/grafana) is a services provided by [ags131]() that works with Grafana. In order to avoid password sharing it uses an agent to run and collect statistics.
-   [screeps-stats](https://github.com/screepers/screeps-stats) stores console data and statistics in elasticsearch, making it accessible in kibana. This system utilizes segments to reduce the in game demand that storing lots of data can cause. This is a self hosted service.
-   [screeps-grafana](https://github.com/screepers/screeps-grafana) is the original stats program. It uses Grafana as it's front it. Like screeps-stats this is a self hosted option.
-   [screeps-ConsoleStats](https://github.com/screepers/screeps-ConsoleStats) provides stats without requiring an external service.

## Uploaders

使用这些通用程序插件可以将代码推送到服务器。

-   [grunt-screeps](https://github.com/screeps/grunt-screeps) is written and maintained by the Screeps team. It used to upload code to the screeps server using [Grunt](https://gruntjs.com/).
-   [gulp-screeps](https://github.com/screepers/gulp-screeps) is used to upload code to the screeps server using [Gulp](http://gulpjs.com/).

## Web Client Extensions

javascript 插件扩展，例如[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=zh-CN)和[Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)。

-   [Alliance Overlay](https://raw.githubusercontent.com/LeagueOfAutomatedNations/loan-browser-ext/master/dist/alliance-overlay.user.js) adds information from the [League of Automated Nations](http://www.leagueofautomatednations.com/map) to the game map.
-   [Room Claim Assistant](https://github.com/Esryok/screeps-browser-ext/raw/master/room-claim-assistant.user.js) colors extends the "Owner Control Level" to make room selection easier. It adds the mineral to the view, turns two source rooms green, claimed or reserved rooms red, and "signed" rooms by other players orange.
-   [Visible Room Tracker](https://github.com/Esryok/screeps-browser-ext/blob/master/visible-room-tracker.user.js) automatically sets a memory location with your current visible room, allow you to do things such as turn on visualizations only when needed.
-   [ScreepsSC](https://github.com/stybbe/Screeps-SC) is a Chrome extension which adds new features and makes more information available on the Screeps website. Some features include making market history more readable, adding a battle radar, letting users view other player's creep names, and enhancing the leaderboard.
