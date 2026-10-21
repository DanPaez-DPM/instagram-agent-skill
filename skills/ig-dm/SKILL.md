---
name: ig-dm
description: Escribe mensajes directos de Instagram: la entrega de la palabra clave (HORAS), el primer mensaje a quien ya interactuó y los dos seguimientos. Usala cuando haya que responder por DM a alguien que comentó, preguntó o pidió el recurso.
---

# ig-dm

Adaptada para el Estudio PotenciArg de una skill MIT (Jakeschincariol/instagram-agent-skill), reescrita a mano. Solo redacta mensajes. No envía nada ni usa la red.

## Reglas de la casa
- Español rioplatense con voseo, sin relleno de IA (`stop-slop`).
- Nada se envía sin el OK de Dani. Él manda cada mensaje a mano, o por la respuesta automática de palabra clave de Instagram, que solo responde a quien comentó primero.
- Si preguntan el precio: sin número ni rango. Respuesta fija: "Contame qué querés resolver y vemos si tiene sentido." Si cuentan el caso, proponer una reunión corta para medir el alcance.
- Nunca mensajes masivos a quien no interactuó. Nunca "Daniel responde".

## Los tres tipos de DM que valen
1. **Respuesta a una mano levantada** (comentó HORAS, respondió una encuesta): casi todos.
2. **Acercamiento a alguien con quien ya hubo conversación** previa en comentarios.
3. **Propuesta de colaboración** a una cuenta concreta, con un motivo.
Sin disparador no hay mensaje. Contestá "no hay motivo para escribirle hoy".

## Entrega de HORAS
Se manda el PDF primero, sin condiciones, dentro de los 7 días del comentario (límite de Meta: una respuesta privada por comentario).
```
{nombre}, acá está: {link o PDF}.
{una línea de cómo usarlo}
{una pregunta que se conteste en pocas palabras}
```
La pregunta final es opcional para la persona. Al final del PDF va una línea para pedir más info, sin vender.

## Primer mensaje a alguien que interactuó
De dos a cuatro oraciones. Citar lo que dijo. Dar antes de pedir. Un pedido chico. Sin link ni calendario en el primer mensaje.

## Seguimientos: dos y listo
- A los 4 días, solo si hay algo nuevo para aportar. Nunca "te reescribo".
- A los 10 días, cierre: avisar que no se insiste. Después no se escribe más.

## Nunca
Inventar que se vio algo o que hay conocidos en común; abrir con "una consulta" sin hacerla; mezclar elogio y pedido en el mismo mensaje.

## Salida
El mensaje, su cantidad de caracteres y los dos seguimientos con el día de cada uno.
