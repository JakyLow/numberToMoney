
[![CocoaPods](https://img.shields.io/cocoapods/p/AFNetworking.svg?style=plastic)](https://github.com/JakyLow/numberToMoney)

# numberToMoney
> numberToMoney is the simple Swift function to convert any number into a currency format.

## Usage
Detail version:
```swift
let number = 11_299.99
let identifier = "en_US"
let money = NumberToMoney(number: number, identifier: identifier)
print("Today I donate to charity \(money).")
```

Short version
```swift
let money = NumberToMoney(number: 11_299.99, identifier: "en_US")
print("Today I donate to charity \(money).")
```

### For example:
![](https://github.com/JakyLow/numberToMoney/blob/master/example.png?raw=true)


## Author
Maxim Mazhuga [@JakyLow](https://www.facebook.com/maxim.mazhuga). 

Feel free to get in contact if you have questions, queries, suggestions, or need help.

## License

numberToMoney is available under the MIT license. See the LICENSE file for more info.

## Disclaimer

Usage of this framework prevents the author, Maxim Mazhuga, from being held liable for any losses incurred by the user through their use of the framework.
