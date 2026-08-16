# Registro de Incidencias

## Incidencia 001

**Título:** Error en la validación del registro inicial del niño

**Fecha:** 05/08/2026

**Descripción:** Al realizar pruebas del formulario de registro inicial, se detectó que el sistema permitía continuar aunque algunos campos obligatorios estuvieran vacíos.

**Prioridad:** Alta

**Estado:** Resuelta

**Impacto:** Podía provocar registros incompletos y afectar el almacenamiento correcto de la información del usuario.

**Solución aplicada:** Se agregaron validaciones a los campos obligatorios y mensajes de advertencia para indicar al usuario qué información debía completar.

**Fecha de resolución:** 06/08/2026

---

## Incidencia 002

**Título:** Problema al actualizar la información del perfil

**Fecha:** 08/08/2026

**Descripción:** Durante las pruebas se detectó que algunos cambios realizados en el perfil del usuario no se reflejaban correctamente después de actualizar la información.

**Prioridad:** Media

**Estado:** Resuelta

**Impacto:** Los usuarios podían visualizar información desactualizada, generando inconsistencias en los datos registrados.

**Solución aplicada:** Se revisó el proceso de actualización y consulta de datos, corrigiendo la lógica responsable de guardar y recuperar la información actualizada.

**Fecha de resolución:** 09/08/2026
