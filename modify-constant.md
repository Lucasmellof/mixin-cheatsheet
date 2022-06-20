# `@ModifyConstant`

[<- Return](README.md)

Changes a literal

Parameters: the original target value

Return type: the target type

Example mixin:
```java
@ModifyConstant(
    method = "target()V",
    constant = @Constant(intValue = 10,ordinal = 0)
)
private int mixin(int in) {
    return in+10;
}
```

Method modification:

```patch
  public void target() {
-   return 10;
+   return this.mixin(10);
  }
```
 
