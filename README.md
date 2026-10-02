# nm_police · Notas de versión

Registro público de versiones de **nm_police**, una tablet policial para servidores de FiveM con
Qbox: ciudadanos, vehículos, incidentes, dispatch, radio, celdas, registro horario, galería y el
resto de herramientas del día a día de un departamento de policía de rol.

> Este repositorio **no contiene código**. El recurso se desarrolla en un repositorio privado;
> aquí solo se publican los números de versión y sus notas de cambios.

## Qué hay aquí

- **[Releases](https://github.com/MrSandor/nm_police-releases/releases)**: una entrada por versión,
  con sus novedades, correcciones y mejoras. La más reciente es siempre la
  [última release](https://github.com/MrSandor/nm_police-releases/releases/latest).
- El archivo "Source code" que GitHub añade automáticamente a cada release es el de este
  repositorio, es decir, solo este README. No es el recurso.

## Para qué sirve

Los servidores que usan nm_police consultan este repositorio al arrancar. Si hay una versión más
nueva que la instalada, la consola del servidor lo avisa y muestra los cambios de cada versión
publicada desde entonces, por ejemplo:

```
[nm_police] Hay una version nueva: v3.1.0 (tienes la 3.0.0)
  v3.1.0 (2026-10-01)
  Novedades:
  + Fecha de alta de los agentes
  Correcciones:
  * Hablar hacia otros canales de radio vuelve a funcionar
Descarga: https://github.com/MrSandor/nm_police-releases/releases/tag/v3.1.0
```

La consulta es una simple lectura de la API pública de GitHub: no envía ningún dato del servidor
ni necesita credenciales.

## Cómo leer las notas

Cada release agrupa los cambios en secciones:

| Sección | Qué significa |
|---|---|
| **Importante** | Cambios que requieren atención al actualizar (dependencias, migraciones, compatibilidad). Léela siempre antes de actualizar. |
| **Novedades** | Funciones nuevas. |
| **Correcciones** | Fallos arreglados. |
| **Mejoras** | Rendimiento, accesibilidad y pulido general. |

Las versiones siguen el formato `MAYOR.MENOR.PARCHE`: un cambio de versión mayor puede requerir
pasos manuales, que se detallan en la sección **Importante**.
