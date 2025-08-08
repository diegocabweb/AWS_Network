# AWS_Network

17 Services:

A. Network Fundations
1. VPC - Virtual Private Cloud: proporciona una ubicación privada para lanzar recursos de AWS en una red virtual aislada.
2. Transit Gateway: es un servicio que administra y simplifica las conexiones y el peering de sus VPC de Amazon.
3. Private Link: Ayuda a establecer una conectividad segura y privada entre las VPC de Amazon y los servicios de AWS dentro de tu Región o dentro de otro VPC de Amazon, y su red local.

B. Hybrid connectivity
1. Direct Connect: Si necesita conectar su centro de datos a AWS, puede usarlo para establecer una conexión privada y dedicada.
2. Site to Site VPN: Si necesita conectar oficinas remotas a AWS, puede usarlas para crear conexiones seguras y cifradas rápidamente.
3. Client VPN: Conectar un equipo remoto a AWS y sus recursos locales.
4. Cloud WAN: Conectar cloud routing y Software-defined Wide Area Networks (SD-WANs) Provee un panel centrañ para hacer conexiones entre sus oficinas, centros de datos y VPCs de Amazon.

C. Edge Networking
1. Cloud Front: entrega datos, vídeos, aplicaciones y APIs con menor latencia y mayores velocidades de transferencia.
2. Route 53: el sistema de nombres de dominio (DNS) de AWS.
3. Global Accelerator: optimiza el tráfico de sus usuarios, desde el usuario hasta su aplicación.

D. Application Networking
1. App Mesh: conecta contenedores y microservicios con redes a nivel de aplicación.
2. API Gateway: crea, mantiene y protege API a cualquier escala.
3. Cloud Map: descubre el acceso a los recursos y servicios más recientes.

E. Networking Security
1. Shield: agrega una protección a sus aplicaciones contra ataques DDoS.
2. WAF: protege su aplicación web de exploits web comunes.
3. Network Firewall: protege su aplicación web de exploits web comunes.
4. Firewall Manager: ayuda a configurar y administrar de forma centralizada las reglas de su firewall.

# VPC
Recuerda:
- Las VPC de Amazon viven completamente dentro de la nube de AWS.
- Un VPC de Amazon vive en una región.
- Una subred solo puede vivir en una zona de disponibilidad.
- Algunos recursos de AWS deben iniciarse en una VPC de Amazon.
- Las puertas de enlace de Internet permiten que sus recursos VPC lleguen a Internet.
- Las tablas de rutas controlan el enrutamiento del tráfico que entra, sale y se mueve dentro de su Amazon VPC.
