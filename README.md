Vue is called a progressive framework because it can be used in just a small part of a website alongside other frameworks.

This is the simplest example of how this concept can be implemented.

```html
<div id="app">{{ message }}</div>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>  
  const app = new Vue({
    el: "#app",
    data: {
      message: 'Hello Jeune Entrepreneur'
    }
  })
</script>

```

Source: [Why Vue.js?](https://player.vimeo.com/video/247494684?dnt=1)