# ReSharper configurations

## ArrangeActAssert.DotSettings

Snippet I use in unittests. Shortcut is `aaa` Available in cs files named `*Test.cs|*Test*.cs`.

```csharp
// arrange
$END$

// act

// assert
```

## FakeItEasy.DotSettings

FakeItEasy is a mocking library. This file contains a few templates. All of these are only available in test files (see filname filter above).

Creating a fake/stub. Use the shortcut `fake`.

```csharp
var $name$ = FakeItEasy.A.Fake<$interface$>();$END$
```

Setup a call to a method. Use the shortcut `smr` (setup method result).

```csharp
FakeItEasy.A.CallTo(() => $fake$.$method$).Returns($result$);$END$
```

Verify if a call happened (or not happened). Use the shortcuts `mhh` (must have happened), `mhh1` (must have happened once), and `mnhh` (must not have happend).

```csharp
// mhh
FakeItEasy.A.CallTo(() => $methodCall$).MustHaveHappened();$END$

// mhh1
FakeItEasy.A.CallTo(() => $methodCall$).MustHaveHappenedOnceExactly();$END$

// mnhh
FakeItEasy.A.CallTo(() => $methodCall$).MustNotHaveHappened();$END$
```

## Guid.DotSettings

Generate a GUID value as string. Use the shortcut `nguid`.

```csharp
$GUID$
```

Create a guid varibale and generate the GUID value. Use the shortcut `varguid`.

```csharp
var $guid$ = new System.Guid("$GUID$");$END$
```


## NUnit.DotSettings

Although I prefer xUnit, I also like to have two NUnit snippits (only available in test files) to create tests (`test` and `atest` where the a stands for `async`).

```csharp
// test
[NUnit.Framework.Test]
public void $Method$()
{
    // arrange
    $END$

    // act

    // assert
}

// atest
[NUnit.Framework.Test]
public async Task $Method$()
{
    // arrange
    $END$

    // act

    // assert
}
```

## xUnit.DotSettings

For xUnit the same two snippits are created (`fact` and `afact` where the a stands for `async`). I didn't create ones for theories because I always end up with theories after refactoring facts.

```csharp
// fact
[Xunit.Fact]
public void $Method$()
{
    // arrange
    $END$

    // act

    // assert
}

// afact
[Xunit.Fact]
public async Task $Method$()
{
    // arrange
    $END$

    // act

    // assert
}
```
