# rox-vpn

La configuración de la VPN propia de Rox Solutions: **WireGuard** con
[wg-easy](https://github.com/wg-easy/wg-easy), para no pagar una VPN comercial.

Este repo es **público a propósito y no tiene ningún secreto dentro**: la contraseña
del panel y la dirección del servidor se inyectan como variables de entorno desde
EasyPanel. Está separado del resto porque EasyPanel necesita poder leerlo para
desplegar, y los demás repos son privados.

El original se mantiene en `Jarvis/vps/vpn/docker-compose.yml`.
