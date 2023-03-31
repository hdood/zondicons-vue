# ZondIcons Vue.js
Zondicons components for Vue.js.

   ## Icons preview
   [See icons preview](https://www.zondicons.com/icons.html)
   
## Instalation 
       Run the following commande to install the package : 
	foo@bar:~$ npm i zondicons-vue

## How to use

    // main.js
    
    import { createApp } from  "vue";
    import App from  "./App.vue";
    import zondicons from  "zondicons-vue";
    
    const app = createApp(App)
    
    // tell Vue.js to use the plugin
    app.use(zondicons)
    
    app.mount("#app"); 
   In template write the icon name in pascal case, eg: arrow-left becomes ArrowLeft
   

	// App.vue
	    
	<template>
		<ArrowLeft />  
	</template>

   

    

