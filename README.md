# Salesforce Bookmarklets

![demo gif](assets/overview.gif?raw=true)

### Switch to Classic
```js
javascript:(function(){window.open("/ltng/switcher?destination=classic","_blank");})()
```

### Switch to Lightning
```js
javascript:(function(){window.open("/ltng/switcher?destination=lex-campaign","_blank");})()
```

### Setup Home
```js
javascript:(function(){window.open("/lightning/setup/SetupOneHome/home","_blank");})()
```
### Object Manager
```js
javascript:(function(){window.open("/lightning/setup/ObjectManager/home","_blank");})()
```

### Flow Home
```js
javascript:(function(){window.open("/lightning/setup/Flows/home","_blank");})()
```

### Developer Console
```js
javascript:(function(){window.open("/_ui/common/apex/debug/ApexCSIPage","_blank");})()
```

### Anonymous Window
```js
javascript:(function(){window.open("/_ui/common/apex/debug/ApexExecAnon","_blank");})()
```
### Load a Record from ID
```js
javascript:(function(){var RecordId = prompt('Record Id:');window.open(`/${RecordId}`,"_blank");})()
```


Add Shortcuts (Firefox)