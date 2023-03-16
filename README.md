
## NodeJs Basic Run

kali ini kita membuat web simpel pakai NodeJs


## STEP by STEP

 - membuat file .js

 ![App Screenshot](https://raw.githubusercontent.com/haydar-hilmy/NodeJs-Basic-Run/main/JS%20file.png)


#### code example

    var http = require('http');

    http.createServer(function (req, res) {
        res.writeHead(200, {'Content-Type': 'text/html'});
        res.end('EveryBody Fellas!');
    }).listen(8080);
- buka cmd dan ubah file directory ke file .js mu tadi, and then write this line

```bash
node <filename>.js
```

- Cek browsermu dengan link ini

[Localhost](http://localhost:8080/)

![App Screenshot](https://raw.githubusercontent.com/haydar-hilmy/NodeJs-Basic-Run/main/Node%20js%20web.png)
