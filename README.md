<!--
SPDX-FileCopyrightText: 2024 Pablo Portas López

SPDX-License-Identifier: MIT
-->

# Panamax 📦🚢

<div align="center">

[![Docker](https://img.shields.io/badge/Docker-2496ED.svg?logo=docker&logoColor=white)](https://www.docker.com/)
[![Composes](https://img.shields.io/badge/Composes-8-2496ED.svg?logo=docker&logoColor=white)](./composes)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./CODE_OF_CONDUCT.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Stars](https://img.shields.io/github/stars/TeenBiscuits/Panamax.svg)](https://github.com/TeenBiscuits/Panamax)

**Panamax** 📦🚢 es una recopilación de [Docker Composes](https://docs.docker.com/compose/) que me han sido útiles a lo largo
de mi breve experiencia como [Self-Hoster](https://es.wikipedia.org/wiki/Self-hosting). 💻🏠

</div>


# Composes 📚

- 💶 **Actual Budget** ( [Website](https://actualbudget.org/) - [GitHub](https://github.com/actualbudget/actual-server) ): Uso Actual Budget todos los días, es la herramienta más sencilla, moderna y conveniente que hay (en mi opinión) para manejar tus finanzas del día a día.
- 📸 **Immich** ( [Website](https://immich.app/) - [GitHub](https://github.com/immich-app/immich) ): Es de esos proyectos que una vez los descubres solo puedes pensar donde han estado toda tu vida. Immich es el perfecto sustituto a iCloud Fotos y Google Fotos. Consume muchos recursos pero merece la pena.
- 📊 **Netdata** ( [Website](https://www.netdata.cloud/) - [Github](https://github.com/netdata/netdata) ): Monitorizar tus servicios y tu servidor en general no puede ser más fácil que con Netdata, es super fácil de integrar, y aunque poco tiene que hacer contra dashboards como Grafana, ya viene preconfigurado lo cual es un plus para algunos. 
- 🔐 **Nginx Proxy Manager** ( [Website](https://nginxproxymanager.com/) - [GitHub](https://github.com/NginxProxyManager/nginx-proxy-manager) ): Es un reverse-proxy muy cómodo y que requiere poco conocimiento técnico para exponer tus servicios, fué de los primeros reverse-proxys que aprendí a usar y sigue siendo mi elección principal.
- 💾 **Nextcloud** ( [Website](https://nextcloud.com/es/) - [GitHub](https://github.com/nextcloud/server) ): Es el sustituto perfecto para Dropbox, Google Drive, iCloud, etc. Antiguamente era _relativamente_ complicado de levantar, pero ahora tienen una imagen llamada ```nextcloud/all-in-one:latest``` que levanta una instancia ya configurada completa y muy personalizable, no la adjunto al repo ya que hay que configurarla a mano, pero puedes seguir los pasos [aquí](https://github.com/nextcloud/all-in-one).
- 🎞️ **Plex Media Server** ( [Website](https://www.plex.tv/es/) - [GitHub](https://github.com/plexinc/pms-docker) ): Plex prácticamente no necesita presentación, si tienes una colección de DVD, BlueRays o incluso CDs (con [Plexamp](https://www.plex.tv/es/plexamp/)), reclama tu derecho a disfrutar de tu propiedad como consumidor y disfruta de tu contenido legalmente obtenido donde quiera que vayas (y sin publicidad). Yo lo uso a diario para disfrutar de mi colección de CDs y Vinilos digitalizados y de vez en cuando de alguna Película o Serie que todavía guardo en DVD.
- 🗃️ **Syncthing** ( [Website](https://syncthing.net/) - [GitHub](https://github.com/syncthing/syncthing) ): Syncthing es una herramienta muy versátil para la sincronización de archivos entre máquinas, y una solución alternativa y más ligera para quien solo necesite sincronizar archivos y no quiera levantar una instancia de Nextcloud entera.
- ⏲️ **Watchtower** ( [Website](https://containrrr.dev/watchtower/) - [GitHub](https://github.com/containrrr/watchtower/) ): Uno no puede estar atento a su servidor 24/7 es por eso que tener a un container vigilando por las actualizaciones automáticas es muy cómodo, tampoco es buena idea abusar del el. Solo dejarlo actualizar aquellos containers que sabes que tienen actualizaciones estables y regulares.

# Otros recursos interesantes 🧐

- 😎 **Awesome Selfhosted** ( [Website](https://awesome-selfhosted.net/#software) - [GitHub](https://github.com/awesome-selfhosted/awesome-selfhosted) ): Lista en la que me inspiré para hacer este repositorio, es realmente util y me ha ayudado a descubrir varias de estas herramientas.
- 🐧 **LinuxServer.io** ( [Website](https://www.linuxserver.io/) - [GitHub](https://github.com/linuxserver) ): Muchas de las imágenes que uso son mantenidas por linuxserver.io, son imágenes en algunos casos mejor mantenidas que las oficiales y facilita en gran medida el levantar muchos de estos servicios.

## Youtube 📹

Algunos canales interesantes de la comunidad **SelfHoster** y **Open Source** en general.

<div align="center">

| 📺 [DB Tech](https://www.youtube.com/@DBTechYT) | 📺 [Christian Lempa](https://www.youtube.com/@christianlempa) | 📺 [Hardware Haven](https://www.youtube.com/@HardwareHaven) |
|---|---|---|
| 📺 [Techno Tim](https://www.youtube.com/@TechnoTim) | 📺 [Wolfgang's Channel](https://www.youtube.com/@WolfgangsChannel) | 📺 [Jeff Geerling](https://www.youtube.com/@JeffGeerling) |
| 📺 [NetworkChuck](https://www.youtube.com/@NetworkChuck) | 📺 [SpaceRex](https://www.youtube.com/@SpaceRexWill) | 📺 [Learn Linux TV](https://www.youtube.com/@LearnLinuxTV) |
| 📺 [TechHut](https://www.youtube.com/@TechHut) | 📺 [The Linux Experiment](https://www.youtube.com/@TheLinuxEXP) | 📺 [Linus Tech Tips](https://www.youtube.com/@LinusTechTips) |

</div>

# ¿Porqué Panamax? 🚢

![Un_Panamax](UnPanamax.png)

El nombre del repositorio es en honor a los barcos de [la clase Panamax](https://es.wikipedia.org/wiki/Panamax). Ya que
van llenos de containers, pues este repositorio también está lleno. 🚢
