---
title: Flutter News 📰
publishDate: 2023-02-08
img: /assets/flutter-news.webp
img_alt: A screenshot of the Flutter News app
description: |
  A Flutter app that allows users to view the latest news from various countries.
tags:
  - Flutter
  - Dart
  - API
  - Web View
---
### Flutter News: A Flutter App for Keeping Up with the Latest News

In today's fast-paced world, staying informed about the latest news is crucial. Whether it's politics, sports, entertainment, or technology, it's important to know what's happening around the world. With the Flutter News app, you can do just that! This app is designed to help you keep up with the latest news from various countries using the [NewsAPI](https://newsapi.org/).

The Flutter News is a Flutter app that allows users to view the latest news from various countries. It's simple to use and has a clean and attractive design. The app has two main features:

### Features 📋

1. Retrieve news from a variety of countries using the NewsAPI
2. Display articles in a scrollable list

When you open the app, you'll be taken to the home screen, where you can see a list of the latest news articles from around the world. You can scroll through the articles to find the one you're interested in. The articles are displayed with the headline, description, and source of the article.

When you tap on an article, you'll be taken to a screen where you can read the full article.

**Note:** Unfortunately, viewing the full story in a web view will not work on Android due to restrictions with CORS policies.

### Getting Started 🚀

Getting started with the Flutter News is easy. Simply clone or download the repository to your local machine. You will need to have [Flutter](https://flutter.dev/docs/get-started/install) installed. In order to use the NewsAPI, you will need to sign up for an API key [here](https://newsapi.org/register). Once you have your API key, add it to the `article_repository.dart` file in the following line:

```dart
// TODO: Update this with your own API key
static const String _apiKey = 'YOUR_API_KEY_HERE';
```
## Screenshots 📸
![App Screenshot](https://i.imgur.com/kP9vRok.mp4)
|                                                    |                                                    |
| -------------------------------------------------- | -------------------------------------------------- |
| ![App Screenshot](https://i.imgur.com/YqjmFJp.png) | ![App Screenshot](https://i.imgur.com/emhLN96.png) |
| ![App Screenshot](https://i.imgur.com/LemDPma.png) | ![App Screenshot](https://i.imgur.com/WMyvXGf.png) |
