# ReSharper configurations

## ArrangeActAssert.DotSettings

Snippet I use in unittests. Shortcut is `aaa` Available in cs files named `*Test*.cs`.

```csharp
// arrange
$END$

// act

// assert
```

## FakeItEasy.DotSettings

FakeItEasy is a mocking library. This file contains a few templates. All of these are only available in test files (ie. filename like `*Test*.cs`).

Creating a fake/stub. Use the shortcut `fake`.

```csharp
var $var$ = FakeItEasy.A.Fake<$interface$>();$END$
```

Setup a call to a method. Use the shortcut `sm` (setup method).

```csharp
FakeItEasy.A.CallTo(() => $methodCall$).Returns($result$);$END$
```

Verify if a call happened (or not happened). Use the shortcuts `mhh1` (must have happened once), and `mnhh` (must not have happend).

```csharp
// mhh1
FakeItEasy.A.CallTo(() => $methodCall$).MustHaveHappenedOnceExactly();$END$

// mnhh
FakeItEasy.A.CallTo(() => $methodCall$).MustNotHaveHappened();$END$
```



