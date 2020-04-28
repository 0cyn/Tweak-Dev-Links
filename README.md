## LLDB Cheatsheet

https://www.nesono.com/sites/default/files/lldb%20cheat%20sheet.pdf

## Entitlements List

http://newosxbook.com/ent.jl

## UI Modifications on the main thread

https://medium.com/@duwei199714/ios-why-the-ui-need-to-be-updated-on-main-thread-fd0fef070e7f

dispatch_async(dispatch_get_main_queue(), ^{
   // Async UI Code goes here
});
dispatch_sync(dispatch_get_main_queue(), ^{
   // Sync UI Code goes here
});

---
