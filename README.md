# SwiftCompilerBug


This demo project shows how subclassing a class with a private field gives a compile error when deploying on a real device.

Steps to reproduce.

1. Run TestPrivate schema targeting a physical iOS device (doesnt happen on simulator).
2. Observe compile errors.
