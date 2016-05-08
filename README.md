# SwiftyOAuth

```swift
let github: Provider = .GitHub(
    clientID: "xxxxxxxxxx",
    clientSecret: "xxxxxx",
    redirectURL: "myapp://callback"
)

github.authorize { result in
    if let credentials = result.credentials {
        print(credentials.token)
    }
}
```

## Usage

### Providers

- GitHub
- Twitter
- Facebook
- Weibo
- Instagram
- Dribbble

## Demo

## Installation

#### Carthage

#### CocoaPods

## License
