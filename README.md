# Nest.js exe

### add the following to package.json
```
  "bin": "dist/main.js",
  "pkg": {
    "scripts": "dist/**/*.js",
    "assets": "logs/**/*"
  },
```

```
pkg . -t node16-win-x64 -o app --debug
```


