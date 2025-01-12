# Mixin Cheatsheet

What mixins should you use, for what purpose, and how exactly do they affect the code?

_Note: the method modifications listed in these documents are what the code_ effectively _does, not what the modified bytecode will actually look like. Mixin generates additional methods in the target classes that are inlined here._

## Table of Contents

### Injectors
 - [`@Inject`](inject.md)
 - [`@Inject`, cancellable](inject-cancellable.md)
 - [`@Inject`, locals](inject-locals.md)
 - [`@Redirect`](redirect.md)
 - [`@Overwrite`](overwrite.md)
 - [`@ModifyArg`](modify-arg.md)
 - [`@ModifyArgs`](modify-args.md)
 - [`@ModifyConstant`](modify-constant.md)
 - [`@ModifyVariable`](modify-variable.md)

 ### Non-Injectors
  - [`@Invoker`](invoker.md)
  - [`@Accessor`](accessor.md)
  - [`@Shadow`](shadow.md)
  - [`@Shadow`, final](shadow-final.md)
  - [`@Shadow`, anonymous class](shadow-anonymous.md)
  - [`@At`](at.md)
  - [`@Unique`](unique.md)

### Other helpful docs
  - [Changing your mixin's priority](mixin-priority.md)
  - [Mixing into classes that may not exist at runtime](pseudo-mixin.md)
