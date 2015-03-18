# PMPlaceholderTextView

![Demo](http://pm-dev.github.io/PMPlaceholderTextView.gif)

## Requirements & Notes

- PMPlaceholderTextView was built for iOS and requires a minimum iOS target of iOS 7.

#### Podfile

```ruby
pod "PMUtils/PMPlaceholderTextView"
```

## Usage

```objective-c
- (void)viewDidLoad {
    [super viewDidLoad];    
    self.placeholderTextView.attributedPlaceholder = [[NSAttributedString alloc] initWithString:@"Enter Description" attributes:@{NSForegroundColorAttributeName: [UIColor redColor], NSFontAttributeName: [UIFont systemFontOfSize:16.0f]}];
}
```

## Communication

- If you **need help**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/PMUtils). (Tag 'PMUtils')
- If you'd like to **ask a general question**, use [Stack Overflow](http://stackoverflow.com/questions/tagged/PMUtils).
- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.


## Author

- [Peter Meyers](mailto:petermeyers1@gmail.com)

## License

All PMUtils specs are available under the MIT license. See the LICENSE file for more info.

