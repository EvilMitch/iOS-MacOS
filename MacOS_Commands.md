Markdown File of usefull MacOS commands
---

### Clear Quarantine on File aka. "Unable to open file due to unauthorised developer". 
```
xattr -r -d *quarantine name* *file path*
```
- com.apple.quarantine
- Xattr is Extended Attributes, it is used to modify attributes of a file.
- This is useful in this situation, where -r will select all quarantine attributes, and -d will delete the selected (typed) attribute. 
---

