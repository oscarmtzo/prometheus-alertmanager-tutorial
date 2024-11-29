# Monitoreo con Prometheus y Grafana


## Metricas
Tipos de Mtericas:
- Histograma
- Counter 
- Gauge

**Prometheus** - software que obtiene metricas para monitoreo
- Toma las metricas 
- se requiere un configuracion para tomar tales metricas
- Monitoreo de contenedores:
    - Prometheus
    - Alert Manager 
    - Graphana

- Al clonear o realizar fork del ejemplo o tutorial provisto por Prometheus, ya sea en Codespaces o en en tu local (computadora)
    - https://github.com/grafana/prometheus-alertmanager-tutorial
    - es una web app, con servicios separados 
    - **Cada herramienta (Prometheus, Alert Manager, Graphana)** contiene:
        - arhcivo YAML de configuracion para programar o ajustar parametros de las web apps
        - se inicializa con el comando ```docker compose up```