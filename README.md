## O que é?
Um player em HTML5 bem leve e "Clean", a idéia é que funcione em qualquer plataforma.
Nesta versão ainda existe alguns bugs na Versão Mobile, que está sendo corrigido.

## Marcação HTML
```html
<video class="meuvideo"  style="width:100% !important; margin-bottom:-10px"   width="100%" height="auto" poster="https://cdn.plyr.io/static/poster.jpg">
   <source src="https://cdn.selz.com/plyr/1.0/movie.mp4" type='video/mp4' />
   <source src="https://cdn.selz.com/plyr/1.0/movie.webm" type='video/webm' />
   <source src="http://video-js.zencoder.com/oceans-clip.ogv" type='video/ogg' />
   <track kind="captions" src="demo.captions.vtt" srclang="en" label="English"></track>
   <track kind="subtitles" src="demo.captions.vtt" srclang="en" label="English"></track>
</video>

```

## Executando o Plugin
```html
  <script type='text/javascript'>
  $(document).ready(function() {
  	$('video').videoPlayer({
  		'playerWidth' : 1,
  		'videoClass' : 'video'
  	});
  });
  </script>
```
#Demonstração
http://zuly.com.br/
