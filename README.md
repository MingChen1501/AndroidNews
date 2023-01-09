# Simple RSS Feed Reader (Android Kotlin Weekly)

This is a simple RSS feed reader app that currently reads my blog (Android Kotlin Weekly)'s feed - [rss.xml](https://vtsen.hashnode.dev/rss.xml). It is written in Kotlin and Jetpack Compose.

![](screenshots/Android_News_Overview.gif)

[![google-play-badge.png](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=vtsen.hashnode.dev.androidnews)

## Features
- Bookmark article
- Share article
- Mark article as read / unread
- Search articles

## Requirements
- Android Studio Dolphin or later

## Tech Stack
- Jetpack Compose
- MVVM Architecture
- Ktor Client
- Room Database
- Coil
- XmlPullParser
- Compose Navigation
- Scaffold (Top/Bottom Bar)
- Webview
- Coroutines & Flow & State Flow
- Accompanist (System UI & Swipe Refresh)
- Work Manager
- Notification
- BuildUtils (Own Library)

## Articles
- [Simple RSS Feed Reader - Jetpack Compose](https://vtsen.hashnode.dev/simple-rss-feed-reader-jetpack-compose)
- [Convert View Model to Use Hilt Dependency Injection](https://vtsen.hashnode.dev/convert-view-model-to-use-hilt-dependency-injection)

## Branches
- [master](https://github.com/vinchamp77/AndroidNews) - multiple view models (use recommended way to collect flow)
- [master_org](https://github.com/vinchamp77/AndroidNews/tree/master_org) - single view model (previous implementation)
- [master_org_hilt](https://github.com/vinchamp77/AndroidNews/tree/master_org_hilt) - convert view model to use hilt ([diff](https://github.com/vinchamp77/AndroidNews/compare/129e75036178fa2427e7283a605ada6e7fa27325..a23b2dfc36447be82339fb26d9a3e1a36108fb4a)) 
