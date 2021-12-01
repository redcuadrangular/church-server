# Redcuadrangular Server
Servidor para la Red Cuadrangular
## Cómo usar
Para hacer uso del Servidor de la red usted deberá preparar un servidor con Fedora 35
Es importante que este servidor posea una instalación limpia, es decir que no tenga nada instalado salvo la distribución oficial.
Entendiendo que este servidor se utilizará para hacer un servidor para la red cuadrangular dedicada a un país de latinoamérica.

Ejecutar esto como usuario sudo o desde la cuenta root.
`curl -1sLf \
  'https://dl.cloudsmith.io/public/redcuadrangular/server/setup.rpm.sh' \
  | sudo -E bash`
  
  Luego realizar la instalación de 
  `dnf install redcuadrangular-server -y`
  
  Si la distribución no es Fedora 35 sino 34 en su lugar no se preocupe, el paquete de instalación se hará cargo de la actualización.
  
 En Servidor requiere una dirección IP el cuál al terminar la instalación mostrará un asistente de Configuración Inicial.
 ## Qué incluye el servidor de Red Cuadrangular
 El servidor está preparado para asistir las herramientas básicas para una red de iglesias por país con la capacidad de ofrecer 
 un panel administrativo para administrar todas las iglesias en Red de ese país.
 Entre estas herramientas se incluye:
 
 * Portal Web de Red
 * Portal Web de Federación u Organización Nacional
 * Portal Web de Desarrollo.
 * Portal web de La Iglesia Nacional
 * Infraestructura por Iglesia que incluye
   * Portal de Iglesia
     * Instalación y configuración de Sitio Web
     * Administración de Portal de Iglesia
     * Correo electrónico para los miembros de la Iglesia
     * Plataforma de Streaming para transmitir Audio y Vídeo en Vivo para Radio o Televisión en Línea
   * Portal Red Cuadrangular
     * Instalación y configuración de Sitio Web
     * Administración de Portal de Red
     * Correo electrónico para los miembros de la red
     * Plataforma de Streaming para transmitir Audio y Vídeo en Vivo para Radio o Televisión en Línea

