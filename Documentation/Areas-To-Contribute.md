# Areas to Contribute

Below is a list of areas where LLILC needs work.
Their order follows the path to creating a functioning JIT, that can compile
most C# programs; and doing so with contributions from the Community - so good
documentation comes early.
Each item is given a "star" rating: 1 star denotes easy; many stars denote challenging.

We always keep a [list of open issues](https://github.com/dotnet/llilc/issues)
in the repo, to track open work items.  This is a good place to start.  But
beware that it changes day-by-day.  So if you spot an item you'd like to work
on, assign it to yourself, so everyone can see it's being worked on.

As you work on an issue, it will likely spawn more work.  So enter these as issues.

## Major Areas

+ (*) Areas where documentation needs improving.
  Eg: [#122](https://github.com/dotnet/llilc/issues/122) thru
      [#176](https://github.com/dotnet/llilc/issues/176)

+ (**) Extend the Reader
  Eg: [#278](https://github.com/dotnet/llilc/issues/278) thru
      [#286](https://github.com/dotnet/llilc/issues/286) thru

+ (**) Add support for more MSIL opcodes.
  Eg: [#187](https://github.com/dotnet/llilc/issues/187) thru
      [#192](https://github.com/dotnet/llilc/issues/192)

+ (**) Implement missing TODO features.  Eg:
  + Synchronized methods [#271](https://github.com/dotnet/llilc/issues/271)
  + Just my code [#272](https://github.com/dotnet/llilc/issues/272)
  + Explicit class initialization [#274](https://github.com/dotnet/llilc/issues/274)
  + Union types [#275](https://github.com/dotnet/llilc/issues/275)
  + Virtual stub dispatch [#267](https://github.com/dotnet/llilc/issues/267)
  + Intrinsic calls

+ (***) Finish support for CoreCLR Generics.

+ (****) Exception Handling.
  Eg: [#63](https://github.com/dotnet/llilc/issues/63) thru
      [#77](https://github.com/dotnet/llilc/issues/77)

+ (**) Memory allocation [#233](https://github.com/dotnet/llilc/issues/233)

+ (***) Function inlining [#239](https://github.com/dotnet/llilc/issues/239)

+ (*) Enable vectorization (System.Numerics.Vector)

+ (**) Add aliasing information for loads that are known to be
  invariants (eg array length, vtables, etc).
  [#291](https://github.com/dotnet/llilc/issues/291)

+ (**) GC Lifetime Checker.
  [#34](https://github.com/dotnet/llilc/issues/34)

+ (***) Ports to other platforms.
  +  Linux and MAC OSX are basically working, but need refining
  +  Other platforms (eg: ARM-64)

+ (**) Enable deferred lowering of certain runtime
  contructs [#292](https://github.com/dotnet/llilc/issues/292)
  + Helper calls (eg: double->int conversions)
  + Write barriers
  + Struct copying


+ (***)Design & Architecture.
  Eg: [#22](https://github.com/dotnet/llilc/issues/22); Object-Model Operators;

+ (**) Optimizations specific to C#:
  + null check
  + bounds check
  + type check
  + overflow check
  + etc

+ (*) Add benchmarks for optimization

+ (\*\*) Add web-crawler to *harvest* MSIL tests and execute

+ (***) Generator for random (but legal) MSIL code [#503](https://github.com/dotnet/llilc/issues/503)

+ (**) Bugs
  +  If you want to fix an existing bug, assign to yourself and go
  +  If you find a new bug, please check it's not a
  duplicate, then enter as an issue, with as simple a repro as you can devise

+ (**) NGEN support [#287](https://github.com/dotnet/llilc/issues/287)
