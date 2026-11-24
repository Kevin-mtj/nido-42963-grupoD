# Pruebas

| ID | Requisito | Orden o secuencia | Resultado esperado | Resultado obtenido | OK |
|---|---|---|---|---|---|
| P01 | R1 | `registrar @kiwi` (dos veces) | La segunda vez: `E: No se pudo registrar @kiwi` |Registrado: @kiwi (id 10);E: No se pudo registrar @kiwi  | si |
| P02 | R1 | `registrar kiwi` (sin @) | `E: No se pudo registrar kiwi` |E: No se pudo registrar kiwi  | si |
| P03 | R2 |  |  |  |  |
| P04 | R3 | `seguir @a @a` | `E: Una cuenta no puede seguirse a si misma` |E: Una cuenta no puede seguirse a si misma  | si |
| P05 | R4 |  |  |  |  |
| P06 | R5 |  |  |  |  |
| P07 | R6 | `guardar`, `salir`, abrir, `cargar`, `arbol` | El mismo preorden, la misma altura y los mismos seguimientos;Preorden: @radio @puma @dron @emoji @quena @trueno @selfie @zorro @vapor @wifi, Nodos: 10 ; altura: 4 ; hojas: 4, 16 seguimientos  | si |
| P08 | R7 | `hola`, `seguir`, `perfil @nadie` | Mensajes de error; el programa sigue | hola: orden no encontrada (escribe ayuda), Uso: seguir @a @b, E: No existe @nadie | si |

Agreguen todas las que necesiten. Incluyan casos con datos invalidos.
