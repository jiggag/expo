---
'@expo/metro-config': patch
---

Use granular chunking for web exports that have async imports inside web workers. The worker bundle now includes those modules.
