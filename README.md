# ZondIcons Vue.js
zondicons components for Vue.js.

   ## Icons preview
   [See icons preview](https://www.zondicons.com/icons.html)

## How to use

    // main.js
    
    import { createApp } from  "vue";
    import App from  "./App.vue";
    import zondicons from  "zondicons-vue";
    
    const app = createApp(App)
    
    // tell Vue.js to use the plugin
    app.use(zondicons)
    
    app.mount("#app"); 
   in template 
   

	// App.vue
	    
	<template>
		<ArrowLeft />  
	</template>

   

    

