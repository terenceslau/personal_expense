# Personal Expenses

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## More information
Networking in Flutter:

```dart
// 1
Future<dynamic> getRecipes(String query, int from, int to) async {
  // 2
  final recipeData = await getData(
      '$apiUrl?app_id=$apiId&app_key=$apiKey&q=$query&from=$from&to=$to');
  // 3
  return recipeData;
}`
```