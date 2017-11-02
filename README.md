# CardsLayout

[![Platform](https://img.shields.io/badge/platform-iOS-green.svg)]()
[![Twitter](https://img.shields.io/badge/twitter-@__filletofish__-blue.svg?style=flat)](https://twitter.com/_filletofish_)
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)

![Preview](https://github.com/filletofish/Cards/blob/master/Animation.gif)

CardsLayout is a lightweight Collection Layout.

## Installation

1. Add `CardsCollectionViewLayout` file to your project
2. Configure `collectionView`:

```swift
    collectionView.collectionViewLayout = CardsCollectionViewLayout()
    collectionView.dataSource = self
    collectionView.delegate = self
    collectionView.isPagingEnabled = true
    collectionView.showsHorizontalScrollIndicator
```
