# Docker-Compose-nginx-Django-prometheus-grafana-nginx-exporter

The goal of this Docker-compose file is monitoring Nginx with Grafana, Prometheus and Nginx-prometheus-exporter. 
The Nginx is ```proxy-pass``` ing a Django App which you can see its dockerfile in https://github.com/hedeesa/Dockerizing-Django


for more help, this is the map of directory that I was working:
```
└── app
    ├── Pipfile
    ├── Pipfile.lock
    ├── config
    ├── grafana
    ├── prometheus
    ├── django_hedeesa
    ├── docker-compose.yml
    └── Dockerfile
```
and you should making the ```docker-compose.yml``` under ```app/```

