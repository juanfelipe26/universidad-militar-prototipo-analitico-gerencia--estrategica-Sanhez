## Supuesto Central

| Supuesto central |
|---|
| Si se implementan mecanismos alternativos de acceso junto al sistema biométrico, entonces los habitantes del conjunto podrán movilizarse de manera más segura y continua incluso cuando ocurran fallas en la huella. |

---

## Paso 1: Objetivo del Indicador

| ¿QUÉ HAGO? (Acción) | ¿CÓMO LO HAGO? (Método) | ¿PARA QUÉ LO HAGO? (Propósito) |
|---|---|---|
| Implemento y habilito mecanismos alternativos de acceso para garantizar la continuidad de movilidad cuando el sistema biométrico falle. | Habilitando accesos alternativos y protocolos de contingencia que permitan a los habitantes ingresar o salir de la torre durante fallas del sistema biométrico. | Para garantizar la continuidad segura de movilidad y acceso de los habitantes del conjunto residencial. |

| Aspecto específico a Medir | Público objetivo (Para quién): | Dimensión (Marca una) |
|---|---|---|
| El nivel de continuidad y seguridad en la movilidad de los habitantes del conjunto residencial durante fallas del sistema biométrico, en relación con la disponibilidad de mecanismos alternativos de acceso. | Adultos mayores residentes del conjunto residencial. | Eficacia (¿Logra el resultado?) |

---

## Paso 2: Fórmula

| Nombre del indicador | Numerador (Variable Y) | Denominador (Población) | Fórmula (Matemática) | Prueba de estrés | Tipo (Marca una) |
|---|---|---|---|---|---|
| **Tasa de Movilidad Segura en Contingencia (TMSC)** | `tasa_exito_acceso × nivel_seguridad_percibida` | `total_intentos_contingencia` | [Ver bloque de código 1] | Riesgo de registros nulos en percepción de seguridad.<br>La percepción puede variar entre tipos de residentes.<br>Pueden existir falsos positivos si el período analizado tiene pocas fallas biométricas. | Índice |

```text
tasa_exito_acceso × nivel_seguridad_percibida/cantidad_fallas_biometricas + evento_bloqueo_acceso
```

| Frecuencia de medición | Fuente de datos (Verificación) |
|---|---|
| Mensual: Una vez al mes. | Encuesta corta a residentes. |

---

## Paso 3: Seguimiento

| Línea base (Patrón actual) | Patrón esperado (Meta) | Condición de refutación (Fallo). Es el número que te dice que tu idea no funcionó. |
|---|---|---|
| 0 | Mayor o igual a (≥) 60% | **Menor o igual a (≤) 59.9%** |
