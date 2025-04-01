## Obtención de información pública con Whois, DomainTools y DNSrecon

- **Whois**: Es un protocolo que permite consultar bases de datos para obtener información sobre la titularidad de un dominio, incluyendo datos del registrante, fechas de registro y expiración, y servidores DNS asociados. Herramientas como [Who.is](https://who.is/) ofrecen interfaces web para realizar estas consultas.

- **DomainTools**: Ofrece servicios avanzados de búsqueda Whois, proporcionando información detallada sobre la propiedad de dominios, historial de direcciones IP, ranking, tráfico y más. Su herramienta de búsqueda Whois está disponible en [DomainTools Whois](https://whois.domaintools.com/).

- **DNSrecon**: Es una herramienta utilizada para recopilar información sobre registros DNS de un dominio, identificar subdominios y realizar transferencias de zona, lo que ayuda en la enumeración de la infraestructura de red de un objetivo.

## Uso de Nmap y Nikto para buscar equipos, puertos abiertos, servicios y vulnerabilidades

- **Nmap**: Es una herramienta de código abierto diseñada para la exploración de redes y auditorías de seguridad. Permite identificar dispositivos en una red, los puertos abiertos en esos dispositivos, los servicios que se están ejecutando y las versiones de esos servicios. Además, Nmap puede detectar sistemas operativos y realizar detección de vulnerabilidades mediante scripts específicos. Una guía completa sobre cómo usar Nmap está disponible en [NinjaOne](https://www.ninjaone.com/es/blog/utilizar-nmap-guia-completa/).

- **Nikto**: Es un escáner de vulnerabilidades enfocado en servidores web. Analiza el servidor en busca de archivos y programas potencialmente peligrosos, configuraciones incorrectas y versiones desactualizadas de software. Nikto es efectivo para identificar problemas de seguridad en aplicaciones web y servidores. Más información sobre Nikto se puede encontrar en [Ciberseguridad.com](https://ciberseguridad.com/herramientas/software/nikto/).

## Uso de Wfuzz y Dirb para localizar recursos web en servidores

- **Wfuzz**: Es una herramienta diseñada para realizar ataques de fuerza bruta en aplicaciones web, útil para descubrir recursos ocultos como directorios y archivos no enlazados. Permite personalizar las solicitudes y utilizar diccionarios específicos para mejorar la eficacia del escaneo. Una descripción detallada de Wfuzz está disponible en [Kali Linux Tools](https://www.kali.org/tools/wfuzz/).

- **Dirb**: Es una herramienta que realiza escaneos de fuerza bruta en servidores web para descubrir directorios y archivos ocultos. Utiliza listas predefinidas de nombres comunes para identificar recursos que no están directamente accesibles o indexados en el sitio web. Más información sobre Dirb y otras herramientas similares se puede encontrar en [Hackplayers](https://www.hackplayers.com/2018/01/diccionarios-para-el-descubrimiento-de-rutas.html).

## Scripts de Nmap para la búsqueda de vulnerabilidades

Nmap cuenta con el **Nmap Scripting Engine (NSE)**, que permite la ejecución de scripts para diversas tareas, incluyendo la detección de vulnerabilidades. Algunos scripts útiles son:

- **vuln**: Ejecuta una serie de scripts orientados a la detección de vulnerabilidades conocidas en el sistema objetivo.
- **auth**: Busca problemas de autenticación, como credenciales por defecto o contraseñas vacías.
- **safe**: Ejecuta scripts considerados seguros y no intrusivos.

Una lista más completa y detallada de scripts NSE disponibles se puede consultar en [The Hacker Way](https://thehackerway.es/2024/02/12/15-scripts-nse-disponibles-en-nmap/).

## Búsqueda de información de explotación de vulnerabilidades con SearchSploit

- **SearchSploit**: Es una herramienta de línea de comandos que permite buscar exploits en la base de datos de Exploit-DB de manera local. Es especialmente útil para identificar exploits disponibles para vulnerabilidades específicas sin necesidad de una conexión a Internet. SearchSploit está incluido en distribuciones como Kali Linux y su manual oficial se encuentra en [Exploit Database](https://www.exploit-db.com/searchsploit).

Para una comprensión más profunda de estas herramientas, se recomienda consultar la documentación oficial y realizar prácticas en entornos controlados.
