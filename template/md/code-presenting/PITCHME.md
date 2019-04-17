---?image=template/img/balena_artboard.png&size=auto 99%
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

@[7,12,15](root directory)
@[7-8,12-13,15-16](Dockerfile.template)
@[18,22,23](Scripts)

@snap[north-east template-note text-white]
Project Tree
@snapend
