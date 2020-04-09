# Using .vue files

To use a .vue file from clear follow these steps:

* Copy the required .vue file from clear to "resources/assets/js/components" directory.
* Also copy the necessary css and js files to their respective folders.
* Then register the component in the "resources/assets/js/app.js" file.

eg:

```javascript
var app = new Vue({
    mixins: [require('spark')],
    components: {
        'invoice': require('./components/clear.vue')
    }
});
```

* Then use the component in any of the blade files by using the component tag

```php
<invoice></invoice>
```

**Note**:

* The links to the vendors css files and images should be adjusted to the new directory structure.

