# Un dashboard sencillo en Tailwind CSS

<!-- hide -->

Por [@marcogonzalo](https://github.com/marcogonzalo) y [otros contribuidores](https://github.com/4GeeksAcademy/first-dashboard-tailwind-css/graphs/contributors) en [4Geeks Academy](https://4geeksacademy.com/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![4Geeks Academy](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=x)](https://x.com/4geeksacademy)

🌐 _These guidelines are also [available in English](./README.md)_.

**Antes de empezar**:

> ¡Te necesitamos! Estos ejercicios se construyen y mantienen en colaboración con personas como tú. Si encuentras algún error 🐞 o falta de ortografía, por favor contribuye y/o repórtalos.

<!-- endhide -->

---

## 🎯 Tu reto

Tu vecino, el artista del barrio, vuelve con buenas noticias: ha lanzado una tienda online para vender entradas de sus presentaciones. El problema es que, aunque el sitio está teniendo muchas visitas y compras, nadie sabe responder preguntas básicas como:

- ¿Cuánto dinero estamos ingresando?
- ¿Cuántas entradas se han vendido y cuántas quedan?
- ¿Qué tan bien convierte la web (compras / visitas)?
- ¿Qué promociones funcionan y cuáles están canibalizando el precio?
- ¿Quiénes han comprado más entradas?

El artista te contacta porque necesita un reporte claro (un dashboard) que le permita supervisar el negocio sin perderse en datos. Y tú, aunque estás empezando, quieres entregar una propuesta sólida y profesional, así que tu misión es diseñar un dashboard que le muestre lo más importante para tomar decisiones rápidas.

---

### ¿Qué hace que un dashboard sea “bueno”?

Organiza el dashboard en grandes bloques:

**1️⃣ Bloque superior:** Indicadores principales del resultado (KPI):

- **Volumen:** ventas/inscripciones/usuarios activos
- **Ingresos:** revenue, MRR, ticket medio
- **Retención:** churn, permanencia, completion
- **Satisfacción:** NPS/CSAT
- **Eficiencia:** coste por resultado, margen, tiempos

**2️⃣ Bloque intermedio:** “Drivers” (factores que explican el resultado):

- **Conversión** por etapas (funnel)
- **Calidad** (ratio de leads cualificados, attendance rate, pass rate)
- **Actividad** (touches, sesiones, entregas, asistencia)
- **Capacidad** (ocupación, plazas disponibles, ratio mentor/estudiante)

**3️⃣ Bloque inferior:** Detalles operacionales (tablas/listados, alertas):

- Backlog, tiempos de respuesta, SLA
- Alertas: caídas fuertes, picos, anomalías
- Listados y tablas con filtros: “top problemas”, “top oportunidades”

> Ejemplo visual de dashboard administrativo:

![Ejemplo de dashboard](images/image1.png "Dashboard ejemplo")

---

## 💻 Qué debes hacer

Crea un dashboard que permita identificar al menos **tres KPIs**, **tres drivers** y detalles operacionales (tablas/listados), como los mencionados previamente. El dashboard debe verse correctamente en cualquier dispositivo (móviles, tabletas y computadoras).

- [ ]Primero, identifica los elementos visuales (componentes) necesarios. Por ejemplo:
  - ¿Requiere navbar/cabecera o sidebar?
  - ¿En cuántas secciones se divide el contenido principal?
  - ¿Qué tipos de gráficos se pueden usar para cada indicador?
- [ ] Empieza por el diseño móvil, que es el formato más restringido, pero pensando siempre en cómo se trasladarán esos elementos a pantalla de escritorio.
- [ ] Para gráficos puedes utilizar [Chart CSS](https://chartscss.org/), una biblioteca solo de CSS (los datos pueden ser inventados; lo importante es la jerarquía visual y la organización).

⚠️ **IMPORTANTE:** En este proyecto solo usaremos **HTML y Tailwind CSS**. Asegúrate de que tu IA Copiloto **no incluya tecnologías más avanzadas** (por ejemplo, React). Indícalo desde el inicio del trabajo.

---

## ✅ Qué vamos a evaluar

- [ ] **Uso correcto de de HTML semántico**
- [ ] **Uso adecuado de Tailwind CSS**
- [ ] **Correcta diagramación y agrupación de componentes visuales**
- [ ] **Aplicación de diseño responsivo**

---

## 📦 Cómo entregar este proyecto

Debes entregar un repositorio que incluya el documento HTML con toda la estructura y el CSS con los estilos y las media queries necesarias para adaptar el dashboard a los distintos _breakpoints_.

---

## 🌱 Cómo iniciar el proyecto

Esto se puede trabajar de forma guiada, permitiendo que distintas personas enseñen su resultado compartiendo pantalla.

---

Este y muchos otros proyectos son construidos por estudiantes como parte de los [Coding Bootcamps](https://4geeksacademy.com/) de 4Geeks Academy. Encuentra más acerca de los [cursos](https://4geeksacademy.com/es/comparar-programas) de [Full-Stack Software Developer](https://4geeksacademy.com/es/coding-bootcamps/programador-full-stack), [Data Science & Machine Learning](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning), [Ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad) e [Ingeniería de IA](https://4geeksacademy.com/es/coding-bootcamps/ingenieria-ia).
