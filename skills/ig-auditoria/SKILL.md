---
name: ig-auditoria
description: Lee las métricas de lo ya publicado en Instagram y dice qué funcionó, qué no y qué hacer más o menos. Usala cuando Dani pegue estadísticas de piezas o pida entender por qué una pieza anduvo bien o mal.
---

# ig-auditoria

Adaptada para el Estudio PotenciArg de una skill MIT (Jakeschincariol/instagram-agent-skill), reescrita a mano. Solo analiza los números que le pasan. No ejecuta código ni entra a Instagram.

## Reglas de la casa
- Español rioplatense. Leé antes `marca/` y las reglas de creatividad.
- No mezclar vistas con alcance. Un benchmark solo vale con el mismo denominador.
- No concluir con menos de 10 piezas por formato y 7 días publicadas. Hasta el día 14 es línea de base y no hay metas numéricas.
- El registro de qué gancho y qué zona usó cada pieza está en su ficha (`clientes/potenciarg/entregas/marketing/2026-10-20-ficha-tipo-pieza.md`).

## Input
Estadísticas por pieza: vistas, alcance, interacciones, tiempo de reproducción, guardados, compartidos, seguidores ganados y porcentaje de alcance de no seguidores. Una captura del gráfico de retención de la mejor y la peor vale más que el resto.

## Qué calcular, mostrando la cuenta
| Métrica | Cómo | Qué dice |
|---|---|---|
| Múltiplo sobre la mediana propia | vistas / mediana de la cuenta | Si fue un hit real o un día normal |
| Alcance a no seguidores | % del alcance | Si viajó más allá de quienes ya nos siguen |
| Retención a los 3 s | los que siguen a los 3 s / los que empezaron | La nota del gancho |
| Guardados / alcance | | Utilidad |
| Compartidos / alcance | | La señal más fuerte |
| Seguidores / alcance | | Si el perfil convierte |

Ordená por múltiplo y por compartidos/alcance, no por vistas.

## Buscar el patrón
Comparar las cinco mejores con las cinco peores: retención a los 3 s, tipo de gancho, formato, duración, tema y si se respondieron los comentarios en la primera hora. El día y el horario se miran último. Con pocas piezas, decí que todavía no se puede concluir.

Distinción clave: muchas vistas y pocos seguidores es problema del perfil (usar `ig-perfil`); pocas vistas es problema del gancho.

## Salida
Top 5 y últimas 5, lo que dicen los datos con su nivel de confianza, y "dejar de hacer" / "hacer más". No inventes cifras: si falta un dato, pedilo.
