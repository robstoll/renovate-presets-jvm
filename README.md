This repo contains a default.json with presets for renovate to group dependencies of certain monorepos.

You can use it as follows in your `renovate.json`:
```
{ 
  "extends": [..., "github>robstoll/renovate-presets-jvm"],
  ...
}
```

e.g. 
```json
{
  "extends": ["config:base", "github>robstoll/renovate-presets-jvm"],
}
```


# License
All files in this repository are licensed under [Apache 2.0](http://opensource.org/licenses/Apache2.0).
