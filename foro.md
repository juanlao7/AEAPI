---
no_title: true
---

<style>
    #backgroundImage {
        background-image: url('assets/img/background_1.jpg');
    }
</style>

# Foro

<iframe id="forum_embed"
  src="javascript:void(0)"
  scrolling="no"
  frameborder="0"
  width="100%"
  height="700">
</iframe>
<script type="text/javascript">
  document.getElementById('forum_embed').src =
     'https://groups.google.com/a/aeapi.es/forum/embed/?place=forum/foro'
     + '&showsearch=true&showpopout=true&showtabs=false'
     + '&parenturl=' + encodeURIComponent(window.location.href);

    console.log(document.getElementById('forum_embed').src);
</script>
