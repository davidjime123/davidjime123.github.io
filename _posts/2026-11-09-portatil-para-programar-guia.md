---
layout: post
title: "Qué portátil comprar para estudiar programación (DAM, DAW, ASIR o ingeniería)"
date: 2026-11-09 09:00:00 +0100
description: "RAM, procesador, SSD, pantalla y sistema operativo: qué necesitas de verdad en un portátil para programar y en qué no merece la pena gastar."
categories: [guias, portatiles]
---

Si vas a estudiar programación, el portátil va a ser tu herramienta de trabajo durante años.
La buena noticia: **no necesitas un portátil gaming de 2.000 €**. La mala: hay un par de
cosas en las que no conviene ahorrar. Vamos por partes.

## Lo más importante: la memoria RAM

Programar en sí no es exigente, pero las herramientas que lo rodean sí: un IDE como IntelliJ
o Android Studio, el navegador con 20 pestañas, una base de datos local, Docker o una máquina
virtual… Todo a la vez.

- **8 GB**: se queda corto. Funciona para empezar, pero con el emulador de Android o una
  máquina virtual vas a notar tirones.
- **16 GB**: el mínimo recomendable hoy. Es también lo que Microsoft exige a los portátiles
  "Copilot+ PC".
- **32 GB**: interesante si vas a usar a menudo máquinas virtuales, Docker o varios
  proyectos grandes abiertos.

**Ojo:** muchos portátiles finos llevan la RAM soldada y no se puede ampliar. Si el modelo que
te gusta viene con 8 GB soldados, descártalo.

## Almacenamiento: SSD sí o sí

Un SSD es imprescindible: el sistema y el IDE arrancan en segundos. En capacidad:

- **512 GB** es el punto dulce para la mayoría.
- **256 GB** se llena rápido con SDKs, máquinas virtuales e imágenes de Docker.
- Si el portátil tiene un segundo hueco M.2, podrás ampliar más adelante por poco dinero.

## Procesador: no hace falta lo más caro

Cualquier procesador actual de gama media va sobrado para programar: un Intel Core Ultra 5 /
Core i5 reciente o un AMD Ryzen 5 reciente. Compilar proyectos grandes va mejor con más
núcleos, pero en clase no vas a notar gran diferencia entre gama media y gama alta.

Donde sí hay que fijarse es en la **arquitectura**:

### Cuidado con los portátiles ARM si usas máquinas virtuales

En muchos ciclos de informática se trabaja con **VirtualBox** y máquinas virtuales de Windows
o Linux para PC (x86). Eso tiene una consecuencia importante:

- **Portátiles Windows con Snapdragon (ARM)**: la mayoría de programas funcionan, pero las
  máquinas virtuales x86 de VirtualBox no. Si tus profesores te pasan máquinas virtuales,
  evita este tipo de portátil o pregunta antes.
- **MacBook con chip Apple (M1, M2, M3…)**: son excelentes para programar y tienen una
  autonomía enorme, pero tampoco ejecutan máquinas virtuales x86 de forma normal. Si tu curso
  usa VirtualBox o herramientas solo de Windows, puede darte problemas.
- **Intel o AMD**: la opción más segura si no sabes qué vas a necesitar.

## Pantalla y teclado: lo que usarás 6 horas al día

- **Resolución**: Full HD (1920×1080) como mínimo. Por debajo, el código se ve borroso.
- **Tamaño**: 14" si lo vas a llevar a clase a diario; 15-16" si se va a quedar casi siempre
  en casa.
- **Panel IPS u OLED**, no TN: los TN se ven mal en cuanto mueves la pantalla.
- **Teclado cómodo** con buena distribución en español. Si puedes, pruébalo en tienda.

## Batería y peso

Si vas a clase con él, busca algo que pese menos de 1,6 kg y que aguante una mañana entera sin
enchufe. Los datos de autonomía de los fabricantes suelen ser optimistas: mira análisis
independientes.

## Tarjeta gráfica: solo si la vas a usar

Para programar aplicaciones, webs o bases de datos **no necesitas gráfica dedicada**. Solo
merece la pena si quieres jugar, desarrollar videojuegos en 3D o entrenar modelos de IA en
local. Si no, ese dinero rinde más en RAM o SSD.

## Resumen rápido

| Componente | Mínimo razonable | Recomendado |
|---|---|---|
| RAM | 16 GB | 32 GB si usas VMs/Docker |
| Almacenamiento | 512 GB SSD | 1 TB o segundo hueco M.2 |
| Procesador | Gama media reciente (x86) | Más núcleos si compilas mucho |
| Pantalla | Full HD IPS | 14" para llevar, 16" para casa |

{% include amazon.html busqueda="portatil 16gb ram 512gb ssd" texto="Ver portátiles con 16 GB de RAM y 512 GB SSD en Amazon" %}

## Conclusión

Prioriza en este orden: **16 GB de RAM, SSD de 512 GB, procesador x86 de gama media y una
buena pantalla**. Con eso tienes portátil para todo el ciclo o la carrera. Y antes de comprar,
pregunta en tu centro si vais a usar máquinas virtuales: te puede ahorrar un disgusto.
