# Diseño de la red

## 1. Objetivo

Diseñar la red local de la Clínica Dental Sonrisa para conectar los equipos, el servidor y proporcionar acceso a Internet.

## 2. Equipos de red

La red estará formada por:

- 1 router
- 1 switch
- 1 servidor
- 3 ordenadores cliente
- 1 punto de acceso Wi-Fi
- 1 impresora de red

## 3. Esquema básico

Internet → Router → Switch → Servidor y ordenadores

## 4. Direccionamiento IP

La red utilizada será:

`192.168.10.0/24`

Direcciones principales:

- Router: `192.168.10.1`
- Servidor: `192.168.10.10`
- Impresora: `192.168.10.20`

Los clientes recibirán su dirección IP mediante DHCP.

Rango DHCP:

`192.168.10.100 - 192.168.10.200`

## 5. Servicios de red

- DHCP
- DNS
- Carpetas compartidas
- Servicio web

## 6. Pruebas

Se comprobará:

- Que los clientes reciben una IP
- Que existe comunicación con el servidor
- Que funciona DNS
- Que hay acceso a Internet
- Que se puede acceder a las carpetas compartidas

## Estado

- [x] Diseño inicial
- [ ] Montaje de la red
- [ ] Configuración del servidor
- [ ] Configuración de clientes
- [ ] Pruebas finales
