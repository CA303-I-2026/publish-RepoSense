# CA303-I-2026 — RepoSense Dashboard

[![Dashboard](https://img.shields.io/badge/Ver%20Dashboard-RepoSense-blue?style=for-the-badge)](https://ca303-i-2026.github.io/publish-RepoSense/)

## 📊 Dashboard de contribuciones 

El dashboard interactivo con las contribuciones de todos los grupos está disponible en:

👉 **[https://ca303-i-2026.github.io/publish-RepoSense/](https://ca303-i-2026.github.io/publish-RepoSense/)**

El reporte se actualiza automáticamente cada día.

## Grupos registrados

La estructura de participantes refleja los equipos creados dentro de la organización `CA303-I-2026` en GitHub. Cada grupo tiene su propio equipo de organización y repositorio.

| Grupo | Repositorio | Integrantes (nombre de display — usuario GitHub) |
|-------|-------------|--------------------------------------------------|
| Grupo 1 | [Grupo-1-Los-bigotes-de-FM](https://github.com/CA303-I-2026/Grupo-1-Los-bigotes-de-FM) | AndreyGonzalez10, leouniversidad967, Randal Picado Bermudez (RandalP23), Anthonny (the-lebesgue-measure) |
| Grupo 2 | [Grupo-2](https://github.com/CA303-I-2026/Grupo-2) | Alessandro111105, Ashly Garro (ashlygarro198), Debbie Con Ortega (DebbieCon), emilysanchezm |
| Grupo 3 | [Grupo-3-p-0.05](https://github.com/CA303-I-2026/Grupo-3-p-0.05) | Alegobe23, Daniela Prado (dnielaprado), Estefania Mora (EstefaniaMora23), JoseMiguel11 |
| Grupo 4 | [Grupo-4-Martingalianos](https://github.com/CA303-I-2026/Grupo-4-Martingalianos) | Gabo0122, KevinCalderon (KevinCalderon2811), sebas-miranda, Benjamin Padua (ThePadua) |
| Grupo 5 | [Grupo-5-Alpha-Epsilon](https://github.com/CA303-I-2026/Grupo-5-Alpha-Epsilon) | César Salazar (CisarUli), Gabr64, Andrés Montero (GAndresMontero), OMECXD |
| Grupo 6 | [Grupo-6](https://github.com/CA303-I-2026/Grupo-6) | JavaLuisdi, Jeremy Garcia (JeremyGS3105), KatiaMorenoUAB |

## Equipos de la organización y RepoSense

La organización `CA303-I-2026` utiliza **equipos de GitHub** (*teams*) para gestionar el acceso de los estudiantes a los repositorios de cada grupo. Cada equipo corresponde a un grupo de trabajo.

> **¿Afectan los equipos de organización la generación del reporte de RepoSense?**
>
> **No.** RepoSense analiza el **historial de commits de git**, no la membresía de equipos de GitHub. Las siguientes condiciones determinan si un participante aparece en el reporte:
>
> 1. El participante debe estar listado en [`config/author-config.csv`](./config/author-config.csv) con su usuario de GitHub (`Author's Git Host ID`).
> 2. Los commits del participante deben coincidir con el usuario, correo o nombre de autor git configurado.
>
> **Consecuencia:** agregar o quitar miembros de los equipos de la organización **no** modifica automáticamente el reporte. Para reflejar cambios en la composición de un grupo, se debe actualizar manualmente `config/author-config.csv`.

## Configuración de RepoSense

| Archivo | Descripción |
|---------|-------------|
| [`config/repo-config.csv`](./config/repo-config.csv) | Lista los repositorios de cada grupo a analizar |
| [`config/author-config.csv`](./config/author-config.csv) | Mapea usuarios GitHub, correos y nombres de autor git para cada participante |
| [`run.sh`](./run.sh) | Descarga RepoSense y genera el reporte |
