# UIStackView Photo Collage

A multiple-column photo collage implemented using `UIStackView`, `UICollectionView`, and a custom `UICollectionViewLayout` subclass.

### Uses

Implement your own dynamic `UICollectionView` backed photo collage with caption support. 

## Getting started

1. Clone this project
2. Drag the **ColumnViewLayout** folder into your project in XCode
3. Initialize a `UICollectionView` with the `MultipleColumnLayout` layout
4. Customize your layout as follows

```Swift
let multiColumnLayout = MultipleColumnLayout()

multiColumnLayout.cellPadding = 5
multiColumnLayout.delegate = self
multiColumnLayout.numberOfColumns = 2

let myCollectionView = UICollectionView(frame: CGRectZero, collectionViewLayout: multiColumnLayout)
```

Screenshots
---------
!["Variable height layout"](docs/assets/1.png)
!["Variable height layout"](docs/assets/2.png)
!["Variable height layout"](docs/assets/3.png)
!["Variable height layout"](docs/assets/4.png)
