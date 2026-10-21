---
name: ig-perfil
description: Puntúa un perfil de Instagram sobre 100 con una rúbrica de 12 ítems y propone qué cambiar, en orden de impacto. Usala cuando Dani pida revisar el perfil, la bio, el nombre visible, los destacados, el link o la publicación fijada.
---

# ig-perfil

Adaptada para el Estudio PotenciArg de una skill MIT (Jakeschincariol/instagram-agent-skill), reescrita a mano y revisada línea por línea. Esta skill solo lee texto que le pasan y escribe recomendaciones. No ejecuta código, no usa la red, no entra a Instagram.

## Reglas de la casa que mandan sobre todo lo demás
- Español rioplatense con voseo. Revisá el texto con `stop-slop`.
- Leé antes `marca/decisiones-2026-10-20.md`. Nombre visible: "PotencIArg | IA para emprendedores". Eslogan: "La IA, sin vueltas." Sin precios, sin vender, nunca "Daniel responde".
- Solo recomendar. Nada se cambia en la cuenta sin el OK de Dani.
- No pidas contraseñas ni inicies sesión. El input lo pega o lo captura una persona.

## Input
Nombre visible, usuario, bio, a dónde apunta el link, nombres de destacados, qué hay fijado y las primeras nueve portadas (una captura alcanza). Si falta algo, decí cuál y puntuá el resto.

## Rúbrica (100 puntos): `rubric.json`
Puntuá los 12 ítems con honestidad y mostrá la tabla con el total. Un puntaje generoso no sirve.

## Reescritura, por puntos perdidos
1. Nombre visible (30 caracteres, es lo que busca Instagram). Tres opciones.
2. Primera línea de la bio: a quién le sirve y qué cambia. Resto de los 150 caracteres: una prueba real o un pedido concreto.
3. Tres publicaciones fijadas con tres trabajos distintos: mejor prueba, explicación más clara, mejor presentación.
4. Destacados: de cuatro a seis, con nombres que respondan una duda real ("Empezá acá", "HORAS", "Noticias").
5. Link: un solo destino que cumpla lo que promete la bio.
6. Portadas: legibles en miniatura, con pocas palabras.

## Salida
Tabla de puntaje, cambios copy-ready en orden de prioridad (primero lo barato y de más impacto), y un nuevo puntaje honesto. Nada de números inventados: si falta un dato, dejá `{{dato}}` y avisá.
