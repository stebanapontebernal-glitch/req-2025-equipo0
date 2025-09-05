# Requisitos del sistema
**Equipo:** <Nombre del equipo>  
**Fecha:** <AAAA-MM-DD>  
**Versión:** 1.0

> Guía de redacción (29148/INCOSE): requisito **singular, no ambiguo, verificable, factible, necesario y trazable**.  
> **Patrón sugerido**:  
> **[Condición]**, el **[Sistema]** **debe** **[acción] [objeto]** **en/≤ [métrica/unidad]** **para [criterio/propósito]**.

## 1. Convenciones
- **ID**: `REQ-<Stakeholder>-<NN>` (p. ej., `REQ-PROF-01`).
- **Tipo**: F (funcional) / RNF (no funcional, mapea a ISO 25010).
- **Prioridad**: MoSCoW (Must/Should/Could/Won’t).
- **Estado**: Propuesto / En revisión / Aprobado.

## 2. Lista de requisitos
> Incluye 5–8 por stakeholder. Añade filas según sea necesario.

| ID | Tipo | Stakeholder | Enunciado del requisito | Criterio de verificación / Prueba | Fuente (traza) | Prioridad | Estado | Issue | PR |
|---|---|---|---|---|---|---|---|---|---|
| REQ-PROF-01 | F | Profesor/a | [En clase], el **Sistema** **debe** **generar** un **resumen de la explicación** **≤ 2 min** después de cerrar la explicación **para** que el profesor no reexplique. | Demostración en sesión con cronómetro; artefacto Markdown generado. | Entrevista P1 (2025-09-05) | Must | Propuesto | # | # |
| REQ-EST-01 | RNF (Rendimiento) | Estudiante | [En red 4G], el **Sistema** **debe** **iniciar** la **visualización del resumen** **en ≤ 2 s en móvil**. | Prueba de rendimiento (medición LCP o tiempo de arranque). | Entrevista E2 | Must | Propuesto | # | # |
| REQ-TI-01 | RNF (Fiabilidad) | TI | El **Sistema** **debe** mantener **≥ 99,5 %** de **disponibilidad mensual** del endpoint de resúmenes. | Registro de uptime mensual; cálculo de indisponibilidad. | Política TI 2025 | Must | Propuesto | # | # |

> **Ejemplos anteriores** son de referencia: **elimínalos o adáptalos**.

## 3. Definiciones operativas de métricas
- **Tiempo de arranque móvil**: desde tap en “Ver resumen” hasta contenido visible útil.  
- **Disponibilidad mensual**: 1 – (minutos de indisponibilidad / minutos del mes); incluir ventanas de mantenimiento si aplican.

## 4. Reglas de calidad por requisito (checklist)
Para cada requisito, verificar:
- [ ] Necesario (aporta valor al stakeholder)
- [ ] No ambiguo (evita “rápido”, “fácil” sin métrica)
- [ ] Verificable (hay prueba/medición)
- [ ] Singular (una sola idea)
- [ ] Consistente (no contradice otros)
- [ ] Factible (viable con recursos)
- [ ] Trazable (a fuente y a prueba)

## 5. Riesgos y su impacto en requisitos
- Riesgo: <Descripción> → Requisitos afectados: <IDs> → Mitigación: <Acción>.

## 6. Control de cambios
| Versión | Fecha | Cambio | Autor |
|---|---|---|---|
| 1.0 | <AAAA-MM-DD> | Versión inicial | <Nombre> |
