# simple_url_preview

Flutter package to show url preview

## Getting Started

This shows url preview of a URL.
Currently only supports [Open Graph Protocol](https://www.ogp.me/)

## How to use ?

Add simple_url_preview to pubspec.yaml, and hit command 'flutter pub get'
```yaml
dependencies:
  ...
  simple_url_preview: ^1.0.0
```

#### 1) **Simple use:**
```dart
SimpleUrlPreview(
  url: 'https://pub.dev/',
),
```

#### 2) **Override preview height.(Default and minimum possible height is 150):**
```dart
SimpleUrlPreview(
  url: 'https://pub.dev/',
  previewHeight: 200,
),
```

#### 3) **Override text color and background color:**
```dart
SimpleUrlPreview(
  url: 'https://pub.dev/',
  textColor: Colors.white,
  bgColor: Colors.red,
),
```

#### 4) **If you want closable preview (Click on x to close the preview.):**
```dart
SimpleUrlPreview(
  url: 'https://pub.dev/',
  isClosable: true,
),
```

### Contribution:

Would :heart: to see any contributions.

### Appreciate:
If you liked my work, show some :heart: by :star: repo.
Also you can appreciate by

<p>
 <table style="border-spacing: 5px 10px;">

 <tr>
  <td>
<a href="https://www.buymeacoffee.com/amitbhave10"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="max-width:90%;" width="200" height="60"></a>
</td>

  <td style="margin: 10px">
<a href="https://paypal.me/amitbhave10"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-200px.png" alt="PayPal Logo"
style="max-width:90%;" width="200" height="60">
 </td>
 </tr>
 </table>
</p> 