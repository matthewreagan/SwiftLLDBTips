# Swift LLDB Tips

### Switching to Obj-C for easier messaging / commands

`settings set target.language objc`

### Changing language back to Swift

`settings set target.language swift`

### Type casting

`po unsafeBitCast(0x600003973c20, to: MyModule.MyClass.self)`

### Importing 

```
settings set target.language swift
expr import MyModule
```
