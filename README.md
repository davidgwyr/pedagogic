# pedagogic

Strict and opinionated Dart analysis options following the approach to start with all lint rules and then apply select exclusions.

## Use

Add as a **dev dependency** in your project `pubspec.yaml`

```yaml
dev_dependencies:
  pedagogic: ^0.1.1
```

Use as the **include** in your `analysis_options.yaml` in the root of your project
```yaml
include: package:pedagogic/analysis_options.yaml
```

If you don't have an `analysis_options.yaml` yet, just create one and check out [Dart Analysis Options: Customizing static analysis](https://dart.dev/guides/language/analysis-options).

## Reading

[Dart Lint Rules](https://dart-lang.github.io/linter/lints/)

[Effective Dart style guide](https://dart.dev/guides/language/effective-dart/style)

[Flutter analysis_options.yaml](https://github.com/flutter/flutter/blob/master/analysis_options.yaml)
