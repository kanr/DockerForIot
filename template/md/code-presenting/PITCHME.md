---?image=template/img/graph.jpg
@title[Code Presenting Templates]

## @color[white](Project Structure)

@fa[arrow-down text-white]

<!-- 

@snap[south docslink span-50]
[The Template Docs](https://gitpitch.com/docs/the-template)
@snapend

-->


+++?code=template/examples/docker-compose.yml&lang=yaml
@title[Repo Source File]


@[1,2-9](Volumes and Database)
@[10-18](Grafana Dashboard)
@[19-24](Sensor Container)


@snap[north-east template-note text-gray]
Balena Multi-Container Build with `docker-compose.yml`
@snapend

<!--
+++?color=lavender
@title[Fenced Code Block]

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```
-->

<!--
@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Your code is displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)
-->

@snap[north-east template-note text-gray]
Code presenting fenced code block template.
@snapend


+++?gist=kanr/d1c9e5fb06417ae8f8b3d8c37a6b4a50&=ruby&color=black
@title[GitHub GIST]

@[1-6](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](Code-presenting works seamlessly both online and offline.)

@snap[north-east template-note text-white]
Code presenting GitHub GIST template.
@snapend


+++?color=#36454F
@title[Project Tree]

```text
.
├── CHANGELOG.md
├── LICENSE
├── README.md
├── VERSION
├── docker-compose.yml
├── grafana
│   ├── Dockerfile.template
│   ├── grafana.db
│   ├── grafana.ini
│   └── start.sh
├── influxdb
│   └── Dockerfile.template
├── repo.yml
└── sensor
    ├── Dockerfile.template
    └── scripts
        ├── bme680_air_quality.py
        ├── happy.png
        ├── hmm.png
        ├── sad.png
        ├── sense_hat_air_quality.py
        └── take_measurement.py

```

@[4-5, 10,12](root directory)
@[8,13,16](Dockerfile.template)
@[18,22,23](Scripts)

@snap[north-east template-note text-white]
Code presenting fenced text block template.
@snapend
