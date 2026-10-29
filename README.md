# Anexos del trabajo de grado

Anexos del trabajo de grado *Desarrollo y validación de un módulo automatizado de análisis de imágenes DICOM para el control de calidad de tomografía computarizada y mamografía en un entorno clínico*, de Karol Andrea Peña Arango (Pregrado en Ingeniería Física, Escuela de Ciencias Aplicadas e Ingeniería, Universidad EAFIT, Medellín, 2026).

## Contenido

| Carpeta | Archivo | Qué es |
|---|---|---|
| `Guias_Mediciones_Manuales` | `Guia_Mediciones_Manuales_TC.pdf` | Guía paso a paso para medir a mano las pruebas de calidad de imagen del tomógrafo con el fantoma Pro-CT AAPM. |
| `Guias_Mediciones_Manuales` | `Guia_Mediciones_Manuales_MG.pdf` | Guía paso a paso para hacer a mano las pruebas del mamógrafo: calidad de imagen con el fantoma Mammo 156, y repetibilidad y compensación del control automático de la exposición con placas de PMMA. |
| `Hojas_de_Registro` | `Control_Calidad_TC_ProCT_AAPM.xlsx` | Hoja de cálculo que acompaña a la guía de tomografía. Se escriben los valores medidos y la hoja calcula los resultados y los compara con los criterios de aceptación. |
| `Hojas_de_Registro` | `Control_Calidad_MG_Mammo156_CAE.xlsx` | Hoja de cálculo que acompaña a la guía de mamografía, con una pestaña por prueba y un resumen. |
| `Manual_de_Usuario` | `Manual_Usuario_Modulo.pdf` | Manual de usuario del módulo de análisis de imágenes DICOM en la plataforma de gestión de control de calidad. |

## Uso de las hojas de cálculo

Las celdas de entrada se llenan con los valores medidos siguiendo la guía correspondiente. Los estados (CUMPLE, NO CUMPLE, SIN REFERENCIA) y el resumen se calculan solos. Los criterios que comparan con la línea base del equipo quedan como SIN REFERENCIA hasta que se escribe esa línea base, es decir, los primeros valores medidos en el equipo con la misma técnica.

Los criterios marcados como «de este trabajo» no vienen de un protocolo. Son provisionales y se revisan cuando la institución tenga su línea base.
