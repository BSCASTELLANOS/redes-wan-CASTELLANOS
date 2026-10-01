# redes-wan-CASTELLANOS
# Herramienta de Redes WAN — Brayan Castellanos  (trabajo individual)
Materia: Interconexión de Redes WAN
Repositorio (público): https://github.com/BSCASTELLANOS/redes-wan-CASTELLANOS

## Qué hace esta herramienta
Herramienta web que permite calcular subnetting IPv4, cargar la topología
de una red WAN (dispositivos, roles y enlaces), generar configuraciones
para Cisco IOS y Huawei VRP a partir de la topología, y aplicar
ciberdefensa contra IA (validación de entradas, sin secretos en el repo,
advertencia de configuraciones inseguras).

## Funciones
- Subnetting / IP Planning (IPv4, público/privado)
- Carga de la topología (dispositivos, enlaces, ISP)
- Generación de configuraciones: Cisco, Huawei, Fortinet, MikroTik
- Ciberdefensa contra IA (aplica docs/politicas-ia.md)

## Cómo ejecutarla
1. Clona el repositorio: `git clone https://github.com/BSCASTELLANOS/redes-wan-CASTELLANOS.git`
2. Abre `index.html` en Chrome.
3. Usa la sección "Subnetting" o carga `data/topologia.json` en la sección "Topología".

## Pruebas y % de confianza  (Corte 3)
- Pruebas superadas: __ de __  =  __%  (ver docs/pruebas.md)

## Documentos
- docs/informe-corte2.pdf
- docs/politicas-ia.md

## Capturas (evidencias)
docs/capturas/01-subnetting.png
docs/capturas/02-topologia.png
docs/capturas/03-config-cisco.png
docs/capturas/04-config-huawei.png
docs/capturas/05-github-commits.png

## Autoevaluación (marca Sí/No)
| Criterio                          | ¿Cumplido? | Evidencia            |
|-----------------------------------|------------|----------------------|
| Subnetting funciona               | Sí         | 01-subnetting.png    |
| Carga de topología                | Sí         | 02-topologia.png     |
| Config Cisco y Huawei             | Sí         | 03 / 04              |
| Ciberdefensa (politicas-ia.md)    | Sí         | docs/politicas-ia.md |
| Pruebas con % de confianza (C3)   | No         | docs/pruebas.md      |
