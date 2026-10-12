# Dashboard SGSI — FarmaSalud El Oro S.A.

Página web interactiva de **seguridad de la información y gestión de riesgos** desarrollada como trabajo práctico de la asignatura *Sistema de Gestión de la Seguridad de la Información* de la Universidad Estatal de Milagro.

🔗 **Sitio publicado:** https://cristhiancango.github.io/sgsi-farmasalud/

---

## Caso de estudio

**FarmaSalud El Oro S.A.** es una cadena farmacéutica de tamaño mediano, con matriz en Machala y cinco sucursales en Pasaje, Santa Rosa, Huaquillas, El Guabo y Arenillas. Cuenta con unos 70 empleados y vende medicamentos con y sin receta, productos de higiene y cuidado personal, con entrega a domicilio.

La empresa trabaja con recetas y datos de salud de sus clientes, que la Ley Orgánica de Protección de Datos Personales (LOPDP) clasifica como datos sensibles, y depende de un único servidor para operar sus seis puntos de venta. Esa combinación define los riesgos analizados.

## Contenido de la página

| Sección | Qué contiene |
|---|---|
| 01 · Información de la empresa | Actividad, procesos de negocio, infraestructura tecnológica e inventario de 9 activos de información con propietario y criticidad |
| 02 · Seguridad de la información | Confidencialidad, integridad y disponibilidad aplicadas al caso; controles de seguridad física y lógica |
| 03 · Clasificación de la información | Cuatro niveles (pública, interna, confidencial y restringida) con ejemplos, acceso autorizado y medidas de protección |
| 04 · Aplicación de la ISO/IEC 27001:2022 | 16 controles del Anexo A con su aplicación concreta y su estado de implantación |
| 05 · Gestión de riesgos | 15 riesgos valorados por probabilidad e impacto, mapa de calor 5 × 5, distribución por nivel y por categoría |
| 06 · Plan de acción | Una acción por riesgo, con control propuesto, responsable, plazo y prioridad |

## Metodología de valoración del riesgo

El nivel de cada riesgo se obtiene multiplicando la probabilidad por el impacto, ambos en escala de 1 a 5, siguiendo el enfoque de la ISO/IEC 27005:

```
Nivel de riesgo = Probabilidad (1–5) × Impacto (1–5)
```

| Rango | Nivel |
|---|---|
| 1 – 4 | Bajo |
| 5 – 9 | Medio |
| 10 – 14 | Alto |
| 15 – 25 | Crítico |

La cobertura de controles se calcula asignando 1 punto a cada control implantado y 0,5 a cada control en curso, sobre el total de controles seleccionados.

## Funciones interactivas

- Indicadores calculados a partir de los datos, no escritos de forma fija.
- Pestañas para los tres principios de seguridad y filtro entre seguridad física y lógica.
- Filtros de controles por tema del Anexo A y por estado de implantación.
- Mapa de riesgos 5 × 5 en el que cada casilla filtra la tabla de riesgos.
- Buscador, ordenamiento y filas desplegables con amenaza, vulnerabilidad, consecuencia y control asociado.
- Lista de verificación del plan de acción, cuyo avance se guarda en el navegador del usuario.
- Tema claro y oscuro automático y diseño adaptable a teléfono, tableta y escritorio.

## Aspectos técnicos

- HTML5, CSS3 y JavaScript sin dependencias externas ni frameworks.
- Todo el contenido vive en un único archivo `index.html`, de modo que el sitio funciona en cualquier servidor estático e incluso abriéndolo de forma local.
- Ilustraciones e iconos dibujados en SVG dentro del propio documento.
- Paleta definida con variables CSS, lo que permite el cambio de tema sin recargar.
- Tipografías Bricolage Grotesque e IBM Plex, cargadas desde Google Fonts.
- Alojamiento en GitHub Pages.

## Estructura del repositorio

```
sgsi-farmasalud/
├── index.html    Página completa: estructura, estilos, lógica e ilustraciones
└── README.md     Este documento
```

## Grupo N.° 7

| N.° | Integrante |
|---|---|
| 01 | Walter Julio Astudillo Banchón |
| 02 | Cristhian Rafael Cango Estrada |
| 03 | María Verónica Cedillo Carpio |
| 04 | Yaritza Jecenia Lastra Klinger |
| 05 | Carmen Gabriela Guzmán Boconsaca |
| 06 | Nicole Yamileth Narváez Abad |

**Asignatura:** Sistema de Gestión de la Seguridad de la Información
**Docente:** Mgs. Jessica Janina Cabezas Quinto
**Carrera:** Ingeniería en Tecnologías de la Información — Universidad Estatal de Milagro
**Período:** Octubre de 2026

## Referencias

- International Organization for Standardization. (2022). *ISO/IEC 27001:2022. Information security, cybersecurity and privacy protection — Information security management systems — Requirements.*
- International Organization for Standardization. (2022). *ISO/IEC 27002:2022. Information security controls.*
- International Organization for Standardization. (2022). *ISO/IEC 27005:2022. Guidance on managing information security risks.*
- International Organization for Standardization. (2019). *ISO 22301:2019. Business continuity management systems — Requirements.*
- Asamblea Nacional del Ecuador. (2021). *Ley Orgánica de Protección de Datos Personales.* Registro Oficial Suplemento 459.

---

*FarmaSalud El Oro S.A. es una empresa ficticia construida sobre una situación real del sector farmacéutico de la provincia de El Oro. Los datos presentados son de carácter académico.*
