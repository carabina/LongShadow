# ProgressNode
UILabel extension to generate dynamic long shadow effects in swift.

## How shoud you use
Just add the file to your project, and apply the effect as you want.

```swift
@IBOutlet weak var textLabel: UILabel!
@IBOutlet weak var detailTextLabel: UILabel!
@IBOutlet weak var button: UIButton!

override func viewDidLayoutSubviews() {
    super.viewDidLayoutSubviews()

    self.textLabel.longShadow(4)
    self.detailTextLabel.longShadow(4)
    self.button.titleLabel?.longShadow(4)
}
```

## How it looks like
![alt tag](https://github.com/tib/LongShadow/blob/master/preview.png)

## License
WTFPL

