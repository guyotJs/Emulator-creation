# Emulator creation

How to make a emulator in <a href="https://neptunjs.xyz/">NeptunJS</a>

> In the body include 

``` html
<div id='emu'></div>
```

> Under that, You **Must** include this in a <script></script> tag


``` js
      var NepPlayer = "#emu";     
      // ID of html element where emulator will be inserted

      var NepEmu = "gba";         
      // Platform select ex. nes, snes, gba

      var NepLang = "en";
      // Option "en,rus,ptBR,ja"
      // The language options

      var gameUrl = "./yoshis_island.smc"; 
      // The game file link

```

> Under this include 

``` html
<script src="https://mem.neptunjs.com/njs/njsLoader.js" type="text/javascript"></script>
```

> And BAM there is your emulator!

```html
<!DOCTYPE html>
<html>
    <head>
        <title>MyFirstEmulator</title>
    </head>
    <body>
      <div class="#emu"></div>
      <script>
          var NepPlayer = "#emu";     
          // ID of html element where emulator will be inserted

          var NepEmu = "gba";         
          // Platform select ex. nes, snes, gba

          var NepLang = "en";
          // Option "en,rus,ptBR,ja"
          // The language options

          var gameUrl = "./yoshis_island.smc"; 
          // The game file link
      </script>
      <script src="https://mem.neptunjs.com/njs/njsLoader.js" type="text/javascript"></script>
    </body>
</html>
```

> Optional, Submit a PR (Pull request) with the new emulator to <a href="https://github.com/ClassicMC-Studios/ClassicMC-Studios.github.io/tree/main/guyot/games">The old server<a><br/>
> Make sure to include the <b>game file (smc,gba,etc)</b>
