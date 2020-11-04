# SASS DEMO

### Presentation
Find the slides [here](https://docs.google.com/presentation/d/1YH76pvAPE53sTtiwZR8ZEW9sOkSkUnlAsQKd7FRhfoY/edit?usp=sharing)

### Concepts
* Variables
* Modules
* Nesting
* Inheritance
* Mixins

### File structure
```
.
├── login.html
├── signup.html
├── sass
│   ├── style.sass
│   ├── _variables.sass
│   └── _mixins.sass
└── css
    └── style.css
```

### Settings.json

In VS Code, open the file settings.json with `Ctrl (or Cmd) + shift + P`    
and select "Preferences: Open Settings (JSON)"

Add the following lines:

```json
  "liveSassCompile.settings.autoprefix": [],
   "liveSassCompile.settings.formats": [
       {
           "format": "expanded",
           "extensionName": ".css",
           "savePath": "/css"
       }
   ],
   "liveSassCompile.settings.generateMap": false,
   "liveServer.settings.donotVerifyTags": true
```