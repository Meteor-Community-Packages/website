---
title: Publish composite
description: Push notifications for Cordova and browser
---

`publishComposite(...)` provides a flexible way to publish a set of related documents from various collections using a reactive join. This makes it easy to publish a whole tree of documents at once. The published collections are reactive and will update when additions/changes/deletions are made.

This project differs from many other parent/child relationship mappers in its flexibility. The relationship between a parent and its children can be based on almost anything. For example, let's say you have a site that displays news articles. On each article page, you would like to display a list at the end containing a couple of related articles. You could use `publishComposite` to publish the primary article, scan the body for keywords which are then used to search for other articles, and publish these related articles as children. Of course, the keyword extraction and searching are up to you to implement.

## Managers
* [Sean Dwyer](https://github.com/reywood)
* [Jan Dvorak](https://github.com/sponsors/StorytellerCZ)
* [Kelly Copley](https://github.com/sponsors/copleykj)

## Package
* [GitHub repository](https://github.com/Meteor-Community-Packages/meteor-publish-composite)
* [Packosphere](https://packosphere.com/reywood/publish-composite)

