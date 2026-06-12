# Prácticas Diseño Interfaces de Usuario (Parte II: Caso de Estudio ECO MERCADO UGR)

Curso: 2025/26 

Nombre del Proyecto: **ECOMERCADO UGR App**

Descripción: "Del campus a tu mesa en un clic" — Una plataforma mobile-first que conecta a la comunidad universitaria con productores agroecológicos locales, permitiendo conocer las fechas del mercado, explorar a los productores, reservar productos de temporada y gamificar el consumo sostenible.

Logotipo: 🌿 (Icono de hoja verde minimalista utilizado en la propuesta)

Miembros y nombre del equipo:
 * :bust_in_silhouette:  Florín Emanuel Todor Gliga

----- 

### 1.a User Research Plan
-----
**El ECOMERCADO UGR** es una iniciativa de la UGR y la Red Agroecológica de Granada que se celebra mensualmente en los Paseíllos Universitarios. 
Nuestro plan de investigación se enfoca en entender cómo la **comunidad universitaria** (estudiantes, PDI y PAS) se informa y participa en iniciativas de consumo local y sostenible, con el objetivo de detectar barreras actuales y diseñar una solución digital que aumente la asistencia y el volumen de ventas.

### 1.b Competitive Analysis
-----
Hemos analizado dos iniciativas reales de mercados y cestas ecológicas para identificar buenas prácticas y áreas de mejora:
1. **Nuestras Huertas:** Ofrece transparencia sobre el origen y ubicaciones claras, pero separa la tienda del sitio web principal y carece de funcionalidades interactivas (filtros, mapas).
2. **Mercat Pagès:** Tiene un fuerte componente comunitario (talleres, grupos de Telegram), pero fragmenta la comunicación en demasiados canales (Web, WhatsApp, Formularios) generando fricción.

**Decisión:** Nuestra propuesta debe unificar estos enfoques, ofreciendo transparencia en los productores (como Nuestras Huertas) y valor comunitario (como Mercat Pagès), pero centralizado en una única plataforma mobile-first interactiva.

### 1.c Personas
-----
Hemos definido dos perfiles principales basados en la demografía del campus:
- **Ana (21 años, estudiante eco-curiosa):** Necesita saber qué hay barato y bueno, recibir notificaciones del próximo mercado y compartir en redes. Busca inmediatez.
- **Carlos (48 años, PDI investigador):** Compra ecológico habitualmente, le interesa conocer las certificaciones y hacer pedidos recurrentes sin perder tiempo.

### 1.d User Journey Map
----
El flujo de experiencia diseñado abarca antes, durante y después del mercado:
1. **Días antes:** El usuario recibe una notificación, entra a la app, ve el "Countdown", explora los productores que asistirán y hace una **reserva anticipada** de productos.
2. **El día del mercado:** Llega al Campus de Fuentenueva, usa el **mapa interactivo** de la app para localizar rápidamente el puesto del productor y recoge/paga su pedido.
3. **Después del mercado:** Valora su experiencia, acumula "Puntos Verdes" y sube de nivel (Gamificación).

### 1.e Usability Review
----
- Enlace al documento: *(Evaluación detallada en el documento PDF de la Parte II)*
- Comentario sobre la revisión: Ninguno de los referentes analizados ofrece una experiencia *mobile-first* real. Sus diseños visuales son básicos/anticuados y carecen de elementos que fomenten la retención, como notificaciones o sistemas de fidelización. 

<br>

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map
----
De la investigación previa, extrajimos los siguientes **Insights clave**:
1. La confianza se construye con transparencia visual (ver caras y certificaciones).
2. La fragmentación de canales destruye la experiencia de usuario.
3. El calendario (la fecha del próximo evento) debe ser el eje central de la interfaz.
4. El diseño debe ser nativo móvil (el 85% del público universitario usará el móvil).
5. Falta gamificación para fidelizar al público joven.

### 2.b ScopeCanvas
----
**Propuesta de valor:** "ECOMERCADO UGR App es la plataforma que conecta a la comunidad universitaria con productores agroecológicos locales. Antes de cada mercado, descubre quién viene, qué trae y reserva tu cesta. El día del mercado, localiza cada puesto en el mapa interactivo. Después, valora tu experiencia y acumula puntos verdes."

### 2.c IA: Sitemap + Labelling
----
La arquitectura de la información se estructura en una **Bottom Navigation Bar** con 5 secciones:
- **Inicio:** Countdown, accesos rápidos, productores destacados y agenda.
- **Productores:** Directorio con fichas, certificaciones e historias.
- **Productos:** Catálogo de temporada filtrable con opción de reserva.
- **Mapa:** Plano interactivo de los Paseíllos Universitarios con puestos numerados.
- **Perfil:** Perfil UGR, reservas activas e insignias de gamificación.

### 2.d Wireframes
-----
Se ha elaborado un wireframe de baja fidelidad para visualizar la disposición del layout mobile-first.
![Wireframes de la App](img/ecomercado_wireframe.png)

<br>

### 3.a Moodboard
-----
El *Design System* propuesto se basa en tokens coherentes con la identidad ecológica:
- **Paleta de colores:** Verde bosque `#2D5016` (primario), Verde claro `#7CB342` (acentos), Tierra cálido `#8D6E63` (secundario), Blanco roto `#FAFAF5` (fondo).
- **Tipografía:** *Inter* o *Outfit*, modernas, legibles y limpias.
- **Componentes:** Tarjetas (cards) con bordes redondeados suaves y sombras sutiles. Botones redondeados tipo "pill" para categorías.

### 3.b Mockup e Implementación (Figma Make)
----
Aplicando las metodologías de la fase de prototipado, hemos utilizado la IA de **Figma Make** para transformar los wireframes en un prototipo Hi-Fi funcional e interactivo.

🔗 **Enlace al prototipo desplegado:** [ECOMERCADO UGR - Figma Make](https://brief-valley-80733194.figma.site)

El prototipo incluye **5 pantallas navegables** con datos reales de los productores del ECOMERCADO (Valle y Vega, Horno María Diezma, etc.), un sistema de reserva con confirmación modal y la integración visual de la gamificación (Puntos Verdes).

<br>

### 4. Autoevaluación Final (Conexión con Prácticas)
----
Al abordar este caso real, se han aplicado con éxito las metodologías de **P1 (Research)** para analizar competidores y definir usuarios; **P2 (Ideation)** para los insights, propuesta de valor y wireframing; y **P3/P4 (Prototyping)** para la generación del producto Hi-Fi.

**Cosas que hubiera sido interesante aplicar pero no he podido:**
1. **Testing con usuarios reales de la UGR:** Aunque se generó el prototipo interactivo, habría sido ideal evaluarlo (usando el Cuestionario SUS o A/B Testing) con estudiantes o profesores reales del campus.
2. **Contextual Inquiry real:** Observar *in situ* el comportamiento de los asistentes durante un mercado real.
3. **Accessibility Audit:** Una auditoría completa WCAG 2.1 AA para garantizar accesibilidad total.

**Valoración final como jurado experto:**
La oportunidad de crear una plataforma dedicada al ECOMERCADO UGR desde cero permite solucionar los problemas típicos del sector (fragmentación, falta de diseño mobile-first y baja interactividad). La aplicación de metodologías DCU (Diseño Centrado en el Usuario) asegura que el resultado final responda a las necesidades reales del entorno universitario, potenciando el consumo sostenible de manera moderna e intuitiva.
