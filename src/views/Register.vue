<template>
  <div class="register">
    <h1>Sign up for our newsletter and alerts</h1>
    <p>Not loading? <a href="https://airtable.com/shrE8RB1sqGoJw1aH">Click here</a></p>
    <iframe class="airtable-embed airtable-dynamic-height" src="https://airtable.com/embed/shrE8RB1sqGoJw1aH?backgroundColor=teal" frameborder="0" onmousewheel="" width="100%" height="1941" style="background: transparent; border: 1px solid #ccc;"></iframe>
  </div>
</template>
<!--script src="https://static.airtable.com/js/embed/embed_snippet_v1.js"></script-->


<script>
  export default {
    name: "Register",
    data() {
      return {
        loaded: false
      }
    },
    created () {
      !function(){function d(a,b){for(var c=0;c<a.length&&!b.call(this,a[c]);c++);}function h(a){d(document.querySelectorAll("iframe.airtable-embed.airtable-dynamic-height"),a)}function e(a){var b=a.getBoundingClientRect();a.contentWindow.postMessage({key:"airtableEmbedViewportChanged",embedRectInViewport:{top:b.top,right:b.right,bottom:b.bottom,left:b.left},embedViewportSize:{height:window.innerHeight,width:window.innerWidth}},"*")}function k(){d(document.querySelectorAll("iframe.airtable-embed"),e)}function f(){clearTimeout(g);
      g=setTimeout(k,200)}if(!window._didAddAirtableGlobalEmbedListeners){window._didAddAirtableGlobalEmbedListeners=!0;var g;window.addEventListener("resize",f,!1);window.addEventListener("scroll",f,!1);window.addEventListener("message",function(a){var b=a.data;b&&"airtableEmbedContentDidResize"===b.key&&h(function(c){if(a.source===c.contentWindow)return c._airtableDidDisableScrollbar||(c._airtableDidDisableScrollbar=!0,c.contentWindow.postMessage({key:"airtableDisableScrollbar"},"*"),e(c)),c.height=b.height,
      !0})},!1)}}();
      this.loaded = true
    },
    methods: {
      loadForm() {
        !function(){function d(a,b){for(var c=0;c<a.length&&!b.call(this,a[c]);c++);}function h(a){d(document.querySelectorAll("iframe.airtable-embed.airtable-dynamic-height"),a)}function e(a){var b=a.getBoundingClientRect();a.contentWindow.postMessage({key:"airtableEmbedViewportChanged",embedRectInViewport:{top:b.top,right:b.right,bottom:b.bottom,left:b.left},embedViewportSize:{height:window.innerHeight,width:window.innerWidth}},"*")}function k(){d(document.querySelectorAll("iframe.airtable-embed"),e)}function f(){clearTimeout(g);
      g=setTimeout(k,200)}if(!window._didAddAirtableGlobalEmbedListeners){window._didAddAirtableGlobalEmbedListeners=!0;var g;window.addEventListener("resize",f,!1);window.addEventListener("scroll",f,!1);window.addEventListener("message",function(a){var b=a.data;b&&"airtableEmbedContentDidResize"===b.key&&h(function(c){if(a.source===c.contentWindow)return c._airtableDidDisableScrollbar||(c._airtableDidDisableScrollbar=!0,c.contentWindow.postMessage({key:"airtableDisableScrollbar"},"*"),e(c)),c.height=b.height,
      !0})},!1)}}();
      }
    },
    watch: {
      loaded() {
        if (!this.loaded) {
          this.loadForm()
        }
        
      }
    },
  }
</script>

<style scoped>
a {
  text-decoration: none;
  color: #42b983;
  font-weight: 500;
}
</style>