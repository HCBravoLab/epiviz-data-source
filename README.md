to access datamanger

```
var elem = document.querySelector('epiviz-data-source');

elem.dataManager 

Use any available functions following the epiviz API
// get Measurements from dataManager
callback = function(data) {console.log(data);};

elem.dataManager.getMeasurements(callback);
```

