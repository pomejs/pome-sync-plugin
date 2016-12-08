pome-sync-plugin
==================

sync plugin for pome(>=0.6)


Use [pome-sync](https://github.com/NetEase/pome-sync) to compose this plugin, you can check the detail information in [here](https://github.com/NetEase/pome-sync/blob/master/README.md).


#Installation

```
npm install pome-sync-plugin
```

#Usage

```
var sync = require('pome-sync-plugin');

//app.js

app.use(sync, {sync: {
  key1: value1,
  key2: value2
}});

//get
app.get('globalChannelService');
```
