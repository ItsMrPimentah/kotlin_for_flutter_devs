# Kotlin for Flutter Devs
Some tips to help Flutter developers to understand relation of Kotlin vs Dart and fell confortable at Native World.


## Elvis Operator - Kotlin
Concept behind the operator it's assign a default value to variable in case of null, after the null check.

Kotlin
```kotlin
variable ?: ""
```

Dart
```Dart
variable ?? "";
```

## No Ternary for Kotlin

Dart 
```Dart
variable = booleanCondition ? resultIfTrue : resultIfFalse;
```

Kotlin
```kotlin
variable = if (condition) resultIfTrue else resultIfFalse
```
