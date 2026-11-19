# Trabajo Integrador — Arquitectura y Sistemas Operativos

**Alumna:** Michela Juárez  
**Correo:** michelajuarez@hotmail.com

## Título
Virtualización de sistemas operativos: implementación y recuperación mediante snapshots.

## Enlaces de la entrega

**Repositorio GitHub:** https://github.com/michelaj95/TPI-Arquitectura-Sistemas-Operativos

**Video explicativo (Google Drive):** https://drive.google.com/file/d/1JIYCfX2LRpAuaYjHS0X-ERK52Z6Phl-c/view?usp=sharing

Para visualizar el video, abrir el enlace. Verificar que el permiso de Google Drive permita el acceso a cualquier persona con el enlace en modo Lector.

## Proyecto

Se creó una máquina virtual Ubuntu Server 24.04.5 LTS en Oracle VirtualBox (hipervisor de tipo 2), con 2 vCPU, 2 GB de RAM y 20 GB de disco. Se instaló Apache y se comprobó el acceso HTTP desde Windows mediante una regla NAT que redirige el puerto local 8080 al puerto 80 del invitado.

Se tomó la instantánea **Estado funcional - Apache**, se simuló una falla controlada deteniendo el servicio y se recuperó el estado anterior restaurando la instantánea. Las evidencias están en la carpeta `Evidencias/` y en el informe principal.

## Contenido de la carpeta

- `Trabajo Final Integrador.pdf`: informe final para evaluación.
- `Evidencias/`: capturas del entorno, la instantánea, la falla y la recuperación.
- `comandos_practica.txt`: comandos del caso práctico.
- `Presentacion video.pptx`: presentación de apoyo.

## Bibliografía

Se emplea principalmente la bibliografía de la cátedra, en particular los módulos sobre virtualización de la Unidad 7 y servicios HTTP del Módulo 6. Las referencias se detallan en el informe.
