# Start New Page

Open the blank.vue file in `/src/components` folder.

It has the following structure:

```markup
<template>
    <div>
    </div>
</template>
<script>
import Vue from "vue";

export default {
    // ===Component name
    name: "blank",
    // ===Components used by this component
    components: {},
    // ===Code to be executed when Component is mounted
    mounted() {},
    // ===Computed properties for the component
    computed: {},
    // ===Component data
    data() {
        return {

        }
    },
    // ===Component methods
    methods: {

    }
}
</script>
<!-- styles -->
<!-- adding scoped attribute will only apply the css to this component only -->
<style scoped></style>
```

Place your html content inside the div in template.

_Note: Each template must only have one root element._

Then give the name of your component in the name value and your javascript in the appropriate lifecycle hook.

Then give the appropriate route in main.js routes section. If needed add the component path to left-side menu.

