
[![CocoaPods](https://img.shields.io/cocoapods/p/AFNetworking.svg?style=plastic)](https://github.com/JakyLow/numberToMoney)

# numberToMoney
> numberToMoney is the simple Swift function to convert any number into a currency format.

## Usage
Just add [numberToMoney.swift](https://github.com/JakyLow/numberToMoney/blob/master/numberToMoney.swift) file in your project and use `numberToMoney()` function with double numbers.



Detail example:
```swift
let number = 11_299.99
let identifier = "en_US"
let money = numberToMoney(number: number, identifier: identifier)
print("Today I donate to charity \(money).")
```


Short example:
```swift
let money = numberToMoney(number: 11_299.99, identifier: "en_US")
print("Today I donate to charity \(money).")
```

### Live example:
![](https://github.com/JakyLow/numberToMoney/blob/master/example.png?raw=true)

## Identifiers
You can get all identifiers in Xcode - use `Locale.availableIdentifiers`. The list contains a set of values. identifier itself consists of the `isoLanguageCodes` and the `isoRegionCodes`.

## Author
Maxim Mazhuga [@JakyLow](https://www.facebook.com/maxim.mazhuga). 

Feel free to get in contact if you have questions, queries, suggestions, or need help.

## License

numberToMoney is available under the MIT license. See the LICENSE file for more info.

## Disclaimer

Usage of this framework prevents the author, Maxim Mazhuga, from being held liable for any losses incurred by the user through their use of the framework.
