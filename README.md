`<router>...</router>` inside `pages/products/chairs/_.vue` causes error on generate.  
  
  works fine on non-dynamic routes, ie, `pages/index.vue`

    
Goal here is to generate `pages/products/chairs/*` to `dist/products/*
  

Files of interest are:
- nuxt.config.js  
- pages/index.vue
- pages/products/chairs/_.vue
