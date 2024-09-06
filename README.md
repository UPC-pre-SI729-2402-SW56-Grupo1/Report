<h2>Universidad Peruana de Ciencias Aplicadas</h2>

<img src="https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png" alt="UPC Logo" width="15%" height="15%">

<h2>Informe del Trabajo Final</h2>

<h3>Curso: Desarrollo de Aplicaciones Open Source</h3>
<h3>Carrera: Ingeniería de Software </h3>
<h3>Sección: SW56</h3>
<h3>Profesor: Efraín Ricardo Bautista Ubillús</h3>

<strong>Startup:</strong> FeatherBook

<strong>Producto:</strong> FeatherBook

<h3>Integrantes:</h3>

<ul>
  <li>Iparraguirre Rueda, Cristian Luis (u202113111)</li>
  <li>Fernández Remón Roy (U20221B778)</li>
  <li>Rioja Nuñez, Franco Diego (u202221597)</li>
  <li>Burga Loarte, Anaely (u202118264)</li>
  <li>La Torre Valle, Franz Jair (u202012378)</li>
</ul>

**<h3>Septiembre, 2024</h3>**

# Registro de Versiones del Informe

| Versión | Fecha | Autor                                                                                                     | Descripción de modificación |
|--------------|--------------|-----------------------------------------------------------------------------------------------------------|--------------|
| TB1           | 04/09/2024      | - Iparraguirre Rueda, Cristian Luis<br>- Rioja Nuñez, Franco Diego<br>- Fenández Remón Roy<br>- Anaely Burga Loarte<br>- La Torre Valle, Franz Jair | Implementación del capítulo 1 al 5      |

# Project Report Collaboration Insights

# Contenido
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
    - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
      - [5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)
      - [5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
      - [5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome
| Criterio Específico | Acciones realizadas | Conclusiones |
|---------|---------|---------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **TB1** <br> Iparraguirre Rueda, Cristian Luis <br> - En el contexto de FeatherBook, es fundamental que los resultados del desarrollo tecnológico sean comunicados de manera clara y objetiva a autores y lectores. Esto asegura que todos los usuarios de la plataforma comprendan las funciones clave, como las recomendaciones personalizadas y los eventos exclusivos, independientemente de su nivel técnico.<br><br> Fernández Remón Roy <br> - Dado que FeatherBook conecta a autores, lectores y colaboradores de diferentes especialidades, es importante ajustar la forma en que se presentan los resultados del proyecto. Esto garantiza que los detalles técnicos sean entendidos por ingenieros y especialistas, mientras que otros aspectos sean claros para los autores y lectores.<br><br> Rioja Nuñez, Franco Diego <br> - La habilidad de comunicar los avances del proyecto de manera objetiva y comprensible permite implementar mejoras en la plataforma, asegurando que tanto lectores como autores puedan disfrutar de una experiencia más atractiva e interactiva, según los resultados de las actualizaciones y nuevas funcionalidades.<br><br> Burga Loarte, Anaely <br> - Comunicar los avances del proyecto a diferentes equipos (técnico, marketing, editorial) ayuda a integrar las perspectivas de cada área, fomentando una colaboración efectiva que impulse el crecimiento de FeatherBook como la plataforma líder en lectura digital.<br><br> La Torre Valle, Franz Jair <br> - Comunicar los resultados y avances del proyecto a los niveles jerárquicos de la empresa, desde los desarrolladores hasta los directores, asegura que las decisiones estratégicas se tomen con base en datos objetivos, lo que beneficia tanto la implementación de nuevas funciones como la experiencia general del usuario.<br><br> | En el desarrollo de FeatherBook, la comunicación efectiva y objetiva de los avances y resultados es clave para garantizar que tanto los autores, lectores, equipos técnicos y niveles jerárquicos comprendan el progreso del proyecto. Adaptar la información según el público permite que todas las partes involucradas, independientemente de su nivel de especialización, colaboren de manera eficiente. Esto no solo mejora la experiencia del usuario final, sino que también asegura que las decisiones estratégicas dentro de la startup se basen en información clara, fomentando la innovación y el liderazgo en la lectura digital. |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | **TB1** <br> Iparraguirre Rueda, Cristian Luis <br> - Es esencial que en FeatherBook se comuniquen por escrito los avances del proyecto de manera clara y objetiva, tanto para el equipo técnico como para el público no especializado, como autores y lectores. Esto facilita la comprensión de nuevas funciones y asegura que todos los involucrados estén alineados con los objetivos del proyecto.<br><br> Fernández Remón Roy <br> - La forma de comunicar resultados varía según el público al que se dirijan los reportes y documentos escritos. Mientras que los ingenieros y desarrolladores necesitan detalles técnicos precisos, los autores y ejecutivos requieren un enfoque más accesible que resuma los beneficios y funcionalidades de la plataforma.<br><br> Rioja Nuñez, Franco Diego <br> - En FeatherBook, comunicar los resultados de manera estructurada y objetiva en documentos escritos permite a los niveles jerárquicos más altos tomar decisiones estratégicas informadas. Esto asegura que el proyecto avance de acuerdo con la visión de la empresa y que los recursos se asignen de manera efectiva.<br><br> Burga Loarte, Anaely <br> - Al redactar documentos que describan el progreso del proyecto, es importante ser transparente y objetivo, destacando tanto los éxitos como los desafíos. Esto permite a todas las partes, desde desarrolladores hasta directores, estar al tanto de la realidad del proyecto y trabajar de manera colaborativa en soluciones.<br><br> La Torre Valle, Franz Jair <br> - La comunicación escrita clara y objetiva de los resultados permite que diferentes equipos de FeatherBook (tecnología, marketing, editorial) trabajen de manera más coordinada. Al tener un entendimiento común de los avances y necesidades del proyecto, se mejora la colaboración interdisciplinaria, logrando un producto final más robusto y atractivo.<br><br> | En el desarrollo de FeatherBook, la comunicación escrita clara y objetiva es fundamental para asegurar que los avances y resultados del proyecto sean comprendidos por todas las partes involucradas, independientemente de su especialización o nivel jerárquico. Adaptar el lenguaje según la audiencia facilita la toma de decisiones estratégicas y fomenta la colaboración interdisciplinaria, garantizando que tanto el equipo técnico como los autores, lectores y ejecutivos tengan una visión alineada del progreso y los objetivos de la plataforma. |

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
<div align="justify">
Feather Book es una startup innovadora que busca transformar la forma en que las personas disfrutan la lectura mediante el uso de tecnología avanzada. Nos especializamos en crear un entorno dinámico que 	conecta a autores y lectores, ofreciendo una experiencia de lectura más inmersiva y accesible. A través de herramientas como recomendaciones personalizadas, foros de libros y eventos exclusivos con 		autores. Nuestra plataforma ofrece una extensa variedad de libros electrónicos, audiolibros y contenido exclusivo disponible tanto en nuestra tienda como a través de nuestra suscripción premium. Con el lanzamiento de Feather Book, nuestra propuesta estrella, prometemos llevar la lectura digital a otro nivel, todo mientras garantizamos la máxima seguridad y privacidad para nuestros usuarios. Con Feather 	Book, leer nunca ha sido tan atractivo ni tan interactivo.<br>

<ul>
        <li>
            <b>Misión:</b>
        </li>
        En Feather Book, nuestra misión es inspirar y enriquecer la vida de las personas mediante la lectura. Nos esforzamos por ofrecer un acceso fácil y conveniente a una extensa variedad de contenidos 		literarios, al tiempo que apoyamos a autores emergentes y fomentamos su visibilidad. Nuestro objetivo es conectar a los lectores con experiencias significativas que fortalezcan y profundicen su amor por 	los libros, creando un espacio donde la pasión por la lectura pueda florecer y expandirse.
        <li>
            <b>Visión:</b>
        </li>
        Aspiramos a ser la plataforma líder en lectura digital, ofreciendo acceso a contenido literario de alta calidad. Queremos ser el destino preferido de los lectores para descubrir, compartir y disfrutar 	historias que los transporten a nuevos mundos.
</ul>
</div>

### 1.1.2. Perfiles de integrantes del equipo
<TABLE BORDER>
	<TR>
		<TH><h2>Intregantes</h2></TH> 
		<TH><h2>Descripción</h2></TH>
	</TR>
  <TR>
		<td style="text-align: center" align="center"><p align="center"> Cristian Luis Iparraguirre Rueda - U202113111  <img src="images/fotoCristian.jpeg" alt="Foto Cristian" width="40%"> </p></td> 
		<td style="text-align: center" align="center">Soy una persona con habilidades de aprendizaje rápido, lo que me permite optimizar tanto mi trabajo individual como en equipo para alcanzar los objetivos establecidos. Tengo experiencia trabajando en equipo, contribuyendo con ideas creativas y soluciones prácticas. Me apasiona aprender sobre nuevas tecnologías y mantengo una actitud perseverante en el desarrollo de cualquier proyecto. Tengo conocimientos sólidos en C++, Java, Python, SQL y NoSQL, así como en el desarrollo web con HTML, CSS y JavaScript. Mi enfoque está en la resolución de problemas a través de la programación y en el manejo de bases de datos. Disfruto aprendiendo y explorando nuevas tecnologías, lo que me permite optimizar mis proyectos para que se completen de manera innovadora y efectiva.</td>
	</TR>
	<TR>
		<td style="text-align: center" align="center"><p align="center"> Franco Diego Rioja Nuñez - U202221597 <img src="XXXXXXX" alt="XXXXXXX" width="40%"> </p></td>
		<td style="text-align: center" align="center">XXXXXXX</td>
	</TR>
  	<TR>
		<td style="text-align: center" align="center"><p align="center"> Roy Fernández Remón - U20221B778 <img src="XXXXXXX" alt="XXXXXXX" width="40%"> </p></td> 
		<td style="text-align: center" align="center">XXXXXXX</td>
	</TR>
    <TR>
		<td style="text-align: center" align="center"><p align="center"> Anaely Burga Loarte - U202118264 <img src="https://github.com/user-attachments/assets/2fd5fee2-d55e-4f08-9a49-be37c9c5ab77" alt="XXXXXXX" width="40%"> </p></td> 
		<td style="text-align: center" align="center">Soy estudiante del quinto ciclo de la carrera Ingeniería de Software. Mis pasatiempos son escuchar música, ver películas y leer. Me considero responsable y perseverante. En términos de habilidades, tengo experiencia en programación, especialmente en los lenguajes C++, html y css. Cont coribuiré con mis habilidades y conocimientos a este proyecto, y estoy seguro de que, con trabajo en equipo, alcanzaremos buenos resultados.
</td>
	</TR>
    <TR>
		<td style="text-align: center" align="center"><p align="center"> Franz Jair La Torre Valle - U202012378 <img src="images/FJ.jpg" alt="Foto Franz" width="40%"> </p></td> 
		<td style="text-align: center" align="center">Soy estudiante de la carrera de Ingeniería de Software en la UPC, tengo conocimientos básicos sobre programación en el lenguaje de C++ y Python, conocimiento sobre configuración de redes y aplicación de la complejidad algorítmica. Siempre dispuesto a trabajar en equipo, me considero una persona paciente y respetuosa que tiene como objetivo llevar a cabo este proyecto de forma satisfactoria.</td>
	</TR>
</TABLE>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
<div align="justify">
    Según el INEI, el 91.3 % de las personas mayores de 6 años acceden a internet a través de un celular, el medio más utilizado para la lectura (82.7 %), seguido por periódicos (63.4 %), libros (47.3 %) y revistas (22.5 %) (Ministerio de Cultura, 2022). La Encuesta Nacional de Lectura (ENL) de 2022 revela que el 47.3 % de los ciudadanos leyó al menos un libro en el último año, mayormente en su casa (90 %), en el trabajo (30.3 %) o en transporte público (12.8 %). En promedio, los adultos leen 1.9 libros al año, de los cuales el 31.1 % son textos académicos y el 68.5 % son de interés personal.

Morales y Ramírez (2023) señalan que la falta de interés en la lectura se debe principalmente a la falta de tiempo y desinterés. En cuanto a los medios físicos, el 80 % de la población menciona desinterés, y solo el 7.4 % lo atribuye a razones económicas. En medios digitales, el 60 % indica falta de interés y el 30 % nunca ha utilizado plataformas virtuales, mientras que el 68.3 % menciona que no lee por falta de tiempo.
    <ul>
        <li>
            Who (Quién): La problemática involucra a las personas que día a día presentan inconvenientes, excusas o un total desinterés por la lectura voluntaria.
        </li>
        <li>
            What (Qué): El desafío es crear una plataforma digital que conecte de manera directa y efectiva a los usuarios con bibliotecas en línea, para poder leer lo que les sea conveniente.
        </li>
        <li>
            Where (Dónde): La problemática es relevante a nivel mundial, pero el proceso inicial de prueba e implementación se realizará en la ciudad de Lima, Perú. 
        </li>
        <li>
            When (Cuándo): La necesidad de una solución más eficaz para el acceso a medios de lectura se ha visto incrementado con la llegada de la pandemia y ante el alto nivel de analfabetismo en nuestro país.
        </li>
        <li>
            Why (Por qué): Se aborda esta problemática para facilitar el acceso a la información, mejorar la educación en el país y fomentar la lectura en todo el país
        </li>
        <li>
            How (Cómo): La solución implica el desarrollo de una plataforma de lectura, en que los usuarios vean fomentados sus hábitos de lectura mediante el uso de tecnologías que facilitan el acceso, la distribución 
            y la creación de contenidos. Para garantizar su sostenibilidad a largo plazo, se han establecido estrategias clave, como una suscripción premium que brindará a los usuarios acceso a contenido exclusivo, 
            funciones avanzadas y una experiencia sin publicidad. 
        </li>
        <li>
            How Much (Cuánto): La solución afecta tanto de manera individual como de manera colectiva. Además, se establecerán acuerdos con editores y autores para ofrecer una amplia variedad de títulos a precios competitivos.
            Los ingresos generados por las ventas en la tienda contribuirán significativamente a la sostenibilidad financiera de la aplicación.
        </li>
    </ul>
</div>

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
<div align="justify">
	<ul>
		<li>
			A pesar del notable aumento en la popularidad de la lectura digital y la disponibilidad sin precedentes de una amplia diversidad de contenido, aún persisten numerosos obstáculos que dificultan que los lectores se comprometan con hábitos de lectura regulares y gratificantes. ¿Cómo podemos superar los desafíos que enfrentan los lectores en la era digital para fomentar hábitos de lectura consistentes y satisfactorios, aprovechando las ventajas de la tecnología y ofreciendo experiencias de lectura más atractivas y personalizadas?
		</li>
		<li>
			A pesar de la abundancia de opciones disponibles en el ámbito de la lectura digital, es común que muchos lectores experimenten una profunda frustración debido a la ausencia de interacción y comunidad que enriquezca su experiencia de lectura. ¿Cómo podemos mejorar la interacción y construir comunidad en la experiencia de lectura digital para satisfacer las necesidades de los lectores?
		</li>
		<li>
			A pesar del deseo de muchos lectores de interactuar directamente con sus autores favoritos, actualmente existe una brecha en la comunicación entre autores y lectores en el mundo digital. ¿Cómo podemos facilitar una conexión más significativa y directa entre autores y lectores a través de nuestra plataforma, ofreciendo funciones como sesiones de preguntas y respuestas en línea, eventos exclusivos y la posibilidad de enviar comentarios y preguntas directamente a los autores?
		</li>
		<li>
			Notamos que existen numerosas opciones de lectura digital disponibles, muchos lectores encuentran frustrante la falta de interacción y comunidad en torno a su experiencia de lectura. ¿Cómo podemos mejorar la participación y el compromiso de los lectores mediante la creación de una plataforma que facilite la formación de clubes de lectura virtuales, eventos con autores y discusiones en línea, todo mientras garantizamos la seguridad y privacidad de los usuarios?
		</li>
	</ul>
</div>

#### 1.2.2.2. Lean UX Assumptions
<b>Business Assumptions:</b>
<div align="justify">
    <ul>
        <li>
            Existe una necesidad en el mercado para una plataforma que fomente y motive los hábitos de lectura entre la población, lo que respalda la demanda de una plataforma como Feather Book.
        </li>
        <li>
            Los autores y lectores están dispuestos y son capaces de participar activamente en la plataforma, contribuyendo con contenido, colaboración y retroalimentación para enriquecer la experiencia de lectura.
        </li>
        <li>
            Nuestros usuarios estarán dispuestos a pagar por una suscripción premium que les brinde acceso a contenido exclusivo y funciones avanzadas, lo que generará ingresos recurrentes y fomentará la lealtad de los usuarios.
        </li>
        <li>
            La plataforma será capaz de operar con éxito a través de una combinación de recursos humanos y tecnológicos.
        </li>
        <li>
            Los usuarios estarán dispuestos a comprar libros electrónicos, audiolibros y otros productos relacionados con la lectura a través de la tienda integrada de Feather Book, lo que contribuirá significativamente a la sostenibilidad financiera de la aplicación.
        </li>
        <li>
            Los usuarios valoran altamente la seguridad y privacidad de sus datos personales, es por lo que la implementación de medidas robustas de seguridad en la aplicación garantizará la confianza y satisfacción de los usuarios.
        </li>
        <li>
            Feather Book respetará la originalidad y legalidad de los trabajos ofrecidos. Esto implica garantizar que todos los contenidos sean legales y no infrinjan derechos de autor, así como también fomentar la creación de contenido original y respetar los derechos de propiedad intelectual de autores y editores.
        </li>
        <li>
            El modelo de negocio incluye ingresos provenientes de suscripciones premium y ventas en la tienda integrada, es viable y sostenible a largo plazo, a su vez permitirá el crecimiento y mantenimiento de la plataforma.
        </li>
        <li>
            Nuestra competencia principal en el mercado son otras plataformas y aplicativos existentes que brindan servicios similares al nuestro como “Goodreads”, “Scribd” y “Audible”.
        </li>
        <li>
            Nuestro mayor riesgo es el control de la calidad del contenido y la falta de apoyo continuo por parte de autores y lectores.
        </li>
        <li>
            Resolveremos esto estableciendo verificaciones adecuadas de calidad de contenido. Además, se realizarán campañas de marketing, se promoverán algún tipo de reconocimientos y se obtendrán alianzas estratégicas con la industria editorial.
        </li>
    </ul>
</div>
<br>
<b>User Assumptions:</b>
<div align="justify">
    <ul>
        <li><b>¿Quién es nuestro usuario?</b></li>
        Nuestro usuario principal es un amante de la lectura, que puede variar en edad, género y preferencias de lectura.
        <li><b>¿Dónde encaja mi producto en su trabajo o vida?</b></li>
        Feather Book encaja en la vida de nuestro usuario al proporcionarles una plataforma conveniente y accesible para descubrir, acceder y disfrutar de una amplia gama de contenido de lectura. Puede ser utilizado en su tiempo libre en casa, durante viajes, en pausas en el trabajo, o en cualquier momento en que deseen sumergirse en una buena lectura.
        <li><b>¿Qué problemas tiene nuestro cliente y cómo se puede resolver?</b></li>
        Algunos usuarios pueden experimentar interrupciones en su experiencia de lectura debido a problemas como la falta de sincronización entre dispositivos o la dificultad para encontrar nuevos libros que les interesen. Esto se puede solucionar con la sincronización del progreso de lectura entre dispositivos, recomendaciones personalizadas basadas en intereses de lectura y la capacidad de interactuar con autores y otros lectores, lo que mejora la experiencia de lectura y ayuda a mantener a los usuarios comprometidos y satisfechos.
        <li><b>¿Cuándo y cómo es nuestro producto usado?</b></li>
        Se podrá acceder a nuestra plataforma por medio de la web a cualquier hora del día ofreciendo flexibilidad. Cada uno de los usuarios lo usará en momentos específicos, ya sea mientras viajan en transporte público, durante su tiempo libre en casa, o antes de ir a dormir.
        <li><b>¿Qué características son importantes?</b></li>
        En primer lugar, se debe priorizar la facilidad de uso de la plataforma. Luego, debemos garantizar su correcto funcionamiento para satisfacer a cada uno de los usuarios. Además, se debe enfocar la seguridad en cuanto a la información de usuarios, también se debe considerar su compatibilidad con diferentes sistemas y dispositivos. Finalmente, la plataforma debe ser escalable para manejar una amplia selección de títulos y a manera que crezca se expanda correctamente.
        <li><b>¿Cómo debe verse nuestro producto y cómo debe comportarse?</b></li>
        Nuestro producto debe tener una interfaz limpia y moderna, con un diseño atractivo y fácil de navegar. Además, debe comportarse de manera rápida y fluida evitando largos tiempos de espera. Igualmente, debe contar con medidas de seguridad y privacidad, guardando información de cada usuario.
    </ul>
</div>
<br>
<b>Business Outcomes:</b>
<div align="justify">
    <ul>
        <li>
            Generar un impacto positivo en hábitos de lectura y creatividad.
        </li>
        <li>
            Colaboraciones exitosas con autores y lectores.
        </li>
        <li>
            Aumento del impacto social y usuarios suscritos.
        </li>
        <li>
            Fortalecimiento de alianzas con la industria editorial.
        </li>
        <li>
            Generar ingresos mediante publicidad y nuestros usuarios premium.
        </li>
        <li>
            Divulgar la plataforma para ser usada como la principal en este rubro.
        </li>
    </ul>
</div>
<br>
<b>User Outcomes & Benefits:</b>
<div align="justify">
    <ul>
        <li>
            Acceso conveniente a una amplia variedad de contenido de lectura.
        </li>
        <li>
            Ahorro de tiempo y esfuerzo al evitar la necesidad de visitar librerías físicas para comprar libros.
        </li>
        <li>
            Descubrimiento de nuevos títulos y autores.
        </li>
        <li>
            Interacción con la comunidad de lectores y autores.
        </li>
        <li>
            Flexibilidad y portabilidad de momentos y lugares en donde se puede acceder a la plataforma.
        </li>
    </ul>
</div>

#### 1.2.2.3. Lean UX Hypothesis Statements
<div align="justify">
	
**Hipótesis 1:**

Creemos que los lectores necesitan una forma conveniente y atractiva de acceder a una amplia variedad de libros. Sabremos que hemos tenido éxito cuando nuestra aplicación se convierta en parte de su rutina diaria para descubrir y leer libros.

**Hipótesis 2:**

Creemos que los autores necesitan una plataforma que les permita alcanzar a una audiencia más amplia y aumentar las ventas de sus libros. Sabremos que hemos tenido éxito cuando los autores experimenten un aumento en las ventas y visibilidad de sus obras después de utilizar nuestra plataforma.

**Hipótesis 3:**

Creemos que los lectores necesitan una forma conveniente de comprar libros electrónicos y audiolibros. Sabremos que hemos tenido éxito cuando nuestra tienda integrada sea la principal opción para adquirir contenido de lectura digital.

**Hipótesis 4:**

Creemos que la privacidad y seguridad de los datos son fundamentales para los usuarios de Feather Book. Sabremos que hemos tenido éxito cuando implementamos medidas robustas de protección de datos y recibimos comentarios positivos sobre la seguridad de la plataforma.

**Hipótesis 5:**

Creemos que la suscripción premium será atractiva para los usuarios que buscan contenido exclusivo y una experiencia sin publicidad. Sabremos que hemos tenido éxito cuando una proporción significativa de usuarios opten por la suscripción premium.
</div>

#### 1.2.2.4. Lean UX Canvas
<table>
  <tr>
    <th>Lean UX Canvas</th>
    <th >Feather Book</th>
    <th>Fecha: 30/03/2004</th>
  </tr>
  <tr>
    <td>1. Problema de Negocio:
La comprensión lectora en el país ha ido en decadencia en los últimos años, afectando a chicos y grandes por igual, ya que los más chicos ven la lectura más como una obligación que una afición. Según el Banco Mundial (2021), en América Latina y el Caribe más del 60% de “niños de 10 años son incapaces de leer y comprender un relato simple”.
</td>
    <td rowspan=2>5. Ideas de Soluciones:
Implementación de un algoritmo que ayude a los usuarios a encontrar lecturas de su interés.
·         Añadir una opción de crear clubes de lectura virtuales para que nuestros usuarios puedan compartir sus gustos con los demás.
·         Diseñar una interfaz de usuario intuitiva y fácil de usar para la aplicación.
·         Establecer un modelo de negocio que incluya asociaciones con bibliotecas y escuelas.</td>
    <td>2. Resultados Comerciales:
Generar ingresos a través de asociaciones con bibliotecas, escuelas, editoriales y autores.
Gracias a las suscripciones se generarán recursos recurrentes, así como la implementación de una tienda virtual donde se podrán comprar libros electrónicos, audiolibros y otros productos relacionados con la lectura.

 </td>
  </tr>
  <tr>
    <td>3. Usuarios y Clientes:
Usuarios: Personas con ganas de fomentar un hábito de lectura o mejorar esos hábitos de lectura. Así como, estudiantes que necesitan lecturas para sus estudios.
Autores que quieran dar una visualización de sus trabajos o quieran llegar a una audiencia más amplia.
Clientes:
Instituciones que desean fomentar hábitos de lectura en sus estudiantes.
</td>
    <td>4. Beneficios del usuario:
·         Recomendación eficaz de lecturas ayudadas por los algoritmos.
·         Confianza en las recomendaciones de lecturas respaldadas por la aplicación.
·         Comodidad y flexibilidad.
·         Descubrimientos de nuevas lecturas y autores desconocidos.
·         Acceso a una amplia variedad de lecturas expandiendo su vocabulario.</td>
  </tr>
  <tr>
    <td>6. Hipótesis:
Creemos que, si nuestro aplicativo establece conexiones con bibliotecas importantes, proporcionaremos libros suficientes para empezar y así atraer a nuestros posibles usuarios de una gran variedad de edades.
</td>
    <td>7. ¿Qué es lo más importante que necesitamos aprender primero?
Lo más importante es establecer asociaciones con bibliotecas y escuelas para tener una cantidad decente de libros reconocidos y entretenidos de leer para todas las edades y así no infringir alguna ley de copyright.

</td>
    <td>8. ¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer lo siguiente más importante?
La menor cantidad de trabajo necesaria es definir nuestro problema principal y a qué apuntamos resolver y evaluar si es rentable nuestro modelo de negocio.
</td>
  </tr>
</table>

## 1.3. Segmentos objetivo
<p align="justify">
	Los segmentos objetivos consisten en un conjunto particular de individuos que comparten rasgos y requerimientos afines, estableciéndolos como un público objetivo atractivo para una compañía o marca.

**Segmento objetivo #1:** Lectores


Aspectos demográficos:
* Sexo: Masculino y femenino
* Edades: Personas entre 18 - 50 años.
* Nivel socioeconómico: Clases A,B y C (Alta, Media Alta y Media)

Aspectos psicográficos:

* Buscan una aplicación eficiente de lectura
* Buscan tener comunicación con otros lectores
* Buscan tener comunicación con autores

**Segmento objetivo #2:** Autores

Aspectos demográficos:


* Sexo: Masculino y femenino
* Edades: Personas entre 25 - 50 años.
* Nivel socioeconómico: Clases A,B y C (Alta, Media Alta y Media)

Aspectos psicográficos:

* Buscan una aplicación para publicar sus libros
* Buscan tener comunicación con otros autores
* Buscan tener comunicación con sus lectores

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
Algunos de los competidores a los que FeatherBook podría enfrentarse son:
<ul>
    <li>
        <b>Goodreads: </b>Plataforma líder en la recomendación de libros, donde los usuarios pueden descubrir nuevos títulos, llevar un registro de los libros que han leído y conectarse con otros lectores. Ofrece funciones como 
        reseñas de libros, listas de lectura y grupos de discusión.
    </li>
    <li>
        <b>Scribd: </b>Plataforma de suscripción que ofrece acceso a una amplia variedad de libros electrónicos, audiolibros, revistas y documentos. Los usuarios pagan una tarifa mensual para acceder a contenido ilimitado, lo que
        les permite explorar de una amplia gama de material de lectura.
    </li>
    <li>
        <b>Audible: </b>Plataforma de audiolibros propiedad de Amazon, que ofrece una amplia selección de audiolibros narrados por profesionales. Los usuarios pueden comprar audiolibros individualmente o suscribirse a un plan 
        mensual. También ofrece contenido exclusivo y original.
    </li>
</ul>

### 2.1.1. Análisis competitivo
<table><tr><th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th></tr>
<tr><td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?  </td><td colspan="7" valign="top">Este análisis se lleva a cabo para poder investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado.</td></tr>
<tr><td colspan="6" valign="top"><p><b>Nombre</b></p><p></p></td><td colspan="3" valign="top"><b>FeatherBook</b></td><td colspan="3" valign="top"><b>Goodreads</b></td><td colspan="3" valign="top"><b>Scribd</b></td><td valign="top"><b>Audible</b></td></tr>
<tr><td colspan="6" valign="top"><b>Logo</b> </td><td colspan="3" valign="top"><img src="./images/Logo.jpeg"></td><td colspan="3" valign="top"><img src="./images/Goodreads.jpg"></td><td colspan="3" valign="top"><img src="./images/Scribd.png"><td valign="top"><img src="./images/Audible.png"></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td><td colspan="3" rowspan="2" valign="top"><b>Overview</b></td><td colspan="3" rowspan="2" valign="top">Plataforma diseñada para</b> promover hábitos de lectura mediante tecnologías innovadoras que facilitan el acceso, distribución y creación de contenido. Su objetivo principal es fomentar la sostenibilidad a largo plazo. Además, cuenta con una tienda integrada donde los usuarios pueden comprar libros electrónicos, audiolibros y otros productos relacionados con la lectura. </td><td colspan="3" rowspan="2" valign="top">Plataforma diseñada para ayudar a los lectores a descubrir, seguir y compartir sus libros favoritos. Su objetivo principal es conectar a los lectores, permitiéndoles descubrir nuevos títulos, llevar un registro de lo que han leído y lo que desean leer, además de proporcionarles reseñas y recomendaciones de otros usuarios.</td><td colspan="3" rowspan="2" valign="top">Plataforma de suscripción que ofrece acceso ilimitado a una amplia variedad de libros electrónicos, audiolibros, revistas y documentos. Su objetivo principal es proporcionar a los usuarios una experiencia de lectura completa y personalizada, permitiéndoles explorar y disfrutar de una amplia gama de contenido bajo un modelo de suscripción mensual.</td><td rowspan="2" valign="top">Plataforma líder en audiolibros que ofrece a los usuarios acceso a una extensa biblioteca de títulos narrados por profesionales. Su objetivo principal es brindar una experiencia de lectura inmersiva y conveniente, permitiendo a los usuarios disfrutar de libros mientras realizan otras actividades, como conducir, hacer ejercicio o relajarse. </td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td><td colspan="3" rowspan="2" valign="top">Acceso conveniente a una amplia variedad de contenido de lectura, una experiencia premium sin publicidad y un entorno seguro para disfrutar de la lectura.</td><td colspan="3" rowspan="2" valign="top">Facilidad en el descubrimiento de libros, la interacción social entre los lectores y la personalización de recomendaciones.</td><td colspan="3" rowspan="2" valign="top">Amplia selección de contenido, conveniencia de acceso, recomendaciones personalizadas y un modelo de suscripción rentable.</td><td rowspan="2" valign="top">Amplia selección de audiolibros de alta calidad, narraciones profesionales, flexibilidad de acceso y funciones adicionales exclusivas.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td><td colspan="3" valign="top"><b>Mercado objetivo</b></td><td colspan="3" valign="top">Lectores apasionados, usuarios digitales, suscriptores de servicios de lectura y personas interesadas en participar en una comunidad de lectura en línea.</td><td colspan="3" valign="top">Lectores apasionados, profesionales del mundo editorial, grupos de lectura y clubes literarios, así como a personas interesadas en la crítica y el análisis literario.</td><td colspan="3" valign="top">lectores ávidos, personas ocupadas que valoran la conveniencia, una audiencia diversa con diferentes intereses de lectura, y aquellos que buscan material educativo y de aprendizaje.</td><td valign="top">Amantes de los audiolibros, personas que buscan multitarea, aquellos con discapacidades visuales o dificultades de lectura.</td></tr>
<tr><td colspan="3" valign="top"><b>Estrategias de Marketing</b></td><td colspan="3" valign="top"><p>Presencia en redes sociales. Landing page atractiva. Participación en consorcios de lectura.</p><p>Ofertas por nuevo lanzamiento.</p><p>Colaboraciones con influencers.</p></td><td colspan="3" valign="top"><p>Construir una comunidad activa de lectores, ofreciendo características como grupos de lectura y reseñas.</p><p>Promocionar nuevos lanzamientos.</p></td><td colspan="3" valign="top">Ofrece períodos de prueba gratuitos y promociones para destacar su amplia selección de contenido. Colaboraciones con influencers para aumentar su alcance entre el público objetivo.</td><td valign="top"><p>Patrocinios y asociaciones con eventos y celebridades.</p><p>Programas de recomendación para aumentar su base de usuarios y generar lealtad entre los clientes existentes.</p><p></p></td></tr>
<tr><td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td><td colspan="3" valign="top"><b>Productos y Servicios</b></td><td colspan="3" valign="top">Una plataforma de lectura digital, dos planes de suscripción, una tienda integrada, funciones de comunidad y colaboraciones con autores y editores.</td><td colspan="3" valign="top">Ofrece una plataforma en línea integral que facilita el descubrimiento de libros, el seguimiento de la lectura y la interacción con una comunidad de lectores.</td><td colspan="3" valign="top">Ofrece una suscripción de contenido ilimitado que permite a los usuarios acceder a una amplia variedad de material de lectura en diferentes formatos.</td><td valign="top">ofrece una amplia gama de audiolibros y contenido adicional, con una suscripción mensual que permite a los usuarios acceder al contenido en múltiples plataformas</td></tr>
<tr><td colspan="3" valign="top"><b>Precios y Costos</b></td><td colspan="3" valign="top">Ofrece una suscripción mensual que brinda a los usuarios acceso a contenido exclusivo, recomendaciones personalizadas, comentar y calificar libros a $8.95 USD al mes. Además, otra suscripción mensual con capacidad de comunicación con autores, descuentos y preventa exclusiva a $18.95 USD.</td><td colspan="3" valign="top">Ofrece opciones publicitarias pagadas para autores y editores que deseen promocionar sus libros de manera destacada por $19.95 USD.</td><td colspan="3" valign="top">Ofrece una suscripción mensual que proporciona acceso ilimitado a su biblioteca de libros electrónicos, audiolibros, revistas y documentos. Los precios de estas suscripciones pueden oscilar entre aproximadamente $8.99 a $9.99 USD por mes.</td><td valign="top"><p>La suscripción mensual a Audible generalmente cuesta alrededor de $14.95 por mes. Esta tarifa mensual incluye un crédito que puede canjearse por un audiolibro.</p><p>El costo de los audiolibros individuales varía según el título y la duración del libro. Los precios pueden oscilar entre $10 y $40 por audiolibro.</p></td></tr>
<tr><td colspan="3" valign="top"><b>Canales de distribución</b></td><td colspan="3" valign="top"><p>- Página web</p><p>- Aplicaciones móviles en dispositivos iOS y Android.</p><p></p></td><td colspan="3" valign="top"><p>- Página web</p><p>- Aplicaciones móviles en dispositivos iOS y Android.</p></td><td colspan="3" valign="top"><p>- Página web</p><p>- Aplicaciones móviles en dispositivos iOS y Android.</p></td><td valign="top"><p>- Página web</p><p>- Aplicaciones móviles en dispositivos iOS y Android.</p></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td><td colspan="3" valign="top"><b>Fortalezas</b></td><td colspan="3" valign="top"><p>- Plataforma integral</p><p>- Suscripción premium</p><p>- Tienda integrada</p><p>- Enfoque a la comunidad</p><p>- Interfaz de usuario llamativo</p></td><td colspan="3" valign="top"><p>- Gran comunidad de lectores</p><p>- Funciones de descubrimiento</p><p>- Integración con otras plataformas</p><p>- Plataforma diversificada</p></td><td colspan="3" valign="top"><p>- Amplia variedad de contenido</p><p>- Modelo de suscripción ilimitada</p><p>- Flexibilidad de acceso</p><p>- Funciones de personalización</p></td><td valign="top"><p>- Gran selección de audiolibros</p><p>- Calidad de producción</p><p>- Flexibilidad de acceso</p><p>- Programas y contenido adicional</p></td></tr>
<tr><td colspan="3" valign="top"><b>Debilidades</b></td><td colspan="3" valign="top"><p>- Competencia feroz</p><p>- Dependencia de la tecnología</p></td><td colspan="3" valign="top"><p>- Interfaz de usuario</p><p>- Funcionalidades limitadas</p><p>- Calidad de las reseñas</p><p>- Competencia</p></td><td colspan="3" valign="top"><p>- Limitaciones de disponibilidad</p><p>- Rotación de contenido</p><p>- Experiencia del usuario</p><p>- Competencia</p></td><td valign="top"><p>- Modelo de suscripción</p><p>- Precios individuales</p><p>- Limitaciones regionales</p><p>- Competencia</p></td></tr>
<tr><td colspan="3" valign="top"><b>Oportunidades</b></td><td colspan="3" valign="top"><p>- Expansión internacional</p><p>- Colaboraciones estratégicas</p><p>- Innovación tecnológica</p></td><td colspan="3" valign="top"><p>- Expansión internacional</p><p>- Innovación en la experiencia del usuario</p><p>- Colaboraciones estratégicas</p></td><td colspan="3" valign="top"><p>- Expansión internacional</p><p>- Colaboraciones con editores y autores</p><p>- Innovación tecnológica</p></td><td valign="top"><p>- Expansión internacional</p><p>- Colaboraciones con autores y celebridades</p><p>- Innovación en la experiencia del usuario</p></td></tr>
<tr><td colspan="3" valign="top"><b>Amenazas</b></td><td colspan="3" valign="top"><p>- Competencia de otras plataformas de suscripción</p><p>- Problemas legales de derechos de autor</p><p>- Limitaciones de catálogo</p><p>- Cambios en las preferencias de los usuarios</p></td><td colspan="3" valign="top"><p>- Competencia de otras plataformas</p><p>- Cambios en los hábitos de lectura</p><p>- Problemas de privacidad y seguridad</p><p>- Cambios en las políticas de la empresa matriz</p></td><td colspan="3" valign="top"><p>- Competencia de otras plataformas de suscripción</p><p>- Problemas legales de derechos de autor</p><p>- Limitaciones de catálogo</p><p>- Cambios en las preferencias de los usuarios</p></td><td valign="top"><p>- Competencia de otras plataformas de audiolibros</p><p>- Cambios en el mercado editorial</p><p>- Precios de audiolibros</p><p>- Cambio en los hábitos de consumo</p></td></tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
<div align="justify">
  
**Estrategia de distinción:**

Para diferenciarnos, hemos creado un club de lectura virtual en el que los usuarios podrán debatir libros seleccionados directamente con los autores. Estos eventos incluirán sesiones de preguntas y respuestas en vivo, paneles de discusión y oportunidades para interactuar de manera cercana con los escritores. También ofreceremos talleres en línea impartidos por autores y profesionales de la industria editorial. Además, implementaremos una inteligencia artificial que proporcionará recomendaciones de lectura altamente personalizadas, basadas en las preferencias, historial de lectura y actividades de cada usuario dentro de la plataforma, asegurando una experiencia única y adaptada a sus intereses.

**Estrategia de liderazgo en costos:**

Nos centraremos en minimizar los costos operativos y ofrecer precios competitivos para nuestras suscripciones premium y productos en la tienda integrada. Para lograrlo, optimizaremos procesos internos, negociaremos acuerdos favorables con proveedores y aprovecharemos tecnologías eficientes que reduzcan los gastos. Al mantener bajos los costos, FeatherBook podrá ofrecer tarifas más atractivas para sus usuarios, aumentando su competitividad en el mercado y capturando una mayor cuota de clientes, todo mientras mantenemos la calidad del servicio.

**Estrategia de mercadotecnia:**

Implementamos diversas estrategias de mercadotecnia, como campañas publicitarias en línea dirigidas a audiencias específicas interesadas en la lectura y los libros electrónicos. Utilizamos redes sociales como Instagram, Twitter, Facebook y LinkedIn para promover contenido, interactuar con la comunidad lectora, responder preguntas y compartir novedades de la plataforma. Además, colaboramos con influencers del ámbito literario para promocionar FeatherBook. Para atraer a nuevos usuarios, también lanzamos ofertas promocionales, como períodos de prueba gratuitos para la suscripción premium y descuentos en la tienda integrada, incentivando a más personas a probar la plataforma.

**Tácticas:**

Nuestras tácticas incluyen llevar a cabo investigaciones exhaustivas del mercado digital para comprender mejor las necesidades insatisfechas de los usuarios en el ámbito de la lectura. Esta información nos permite adaptar nuestro sistema de manera precisa para satisfacer esas demandas específicas, asegurando que nuestras soluciones estén alineadas con las expectativas del mercado. Con este enfoque, logramos ofrecer una experiencia de lectura más satisfactoria y relevante para nuestros usuarios, diferenciándonos al responder de manera efectiva a sus necesidades.
</div>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
Lectores
<ol>
    <li>¿Qué géneros literarios prefieres leer?
</li>
    <li>¿Cuál es tu mayor desafío al encontrar tiempo para leer?
</li>
    <li>¿Qué te motiva a seguir leyendo un libro hasta el final?
</li>
    <li>¿Qué tipo de funciones o características te resultan más atractivas en una aplicación de lectura?
</li>
    <li>¿Qué otros tipos de contenido relacionado con la lectura te interesaría encontrar en la aplicación?
</li>
    <li>¿Cómo te gustaría interactuar con otros lectores en la aplicación?
</li>
    <li>¿Qué medidas de seguridad y privacidad consideras más importantes al usar una aplicación de lectura?
</li>
    <li>¿Qué estrategias te ayudarían a mantener un hábito de lectura constante?
</li>
    <li>¿Qué aspectos te resultan más atractivos al comprar libros electrónicos o audiolibros en línea?
</li>
    <li>¿Qué te hace abandonar la lectura de un libro antes de terminarlo?
</li>
    <li>¿Qué tipo de recompensas o beneficios te gustaría obtener por ser un usuario leal de la aplicación?
</li>
    <li>¿Cómo te gustaría que la aplicación te ayudara a descubrir nuevos títulos y autores de interés?</li>
</ol>

Autores

<ol>
    <li>¿En qué géneros te especializas como escritor? ¿Qué te atrae de esos géneros?
    </li>
    <li>¿Podrías describir tu proceso creativo? ¿Cómo se te ocurren las ideas para tus historias?
    </li>
    <li>¿Qué herramientas o recursos utilizas para escribir? ¿Hay algún software o aplicación que te sea indispensable?
    </li>
    <li>¿Cómo te mantienes motivado y disciplinado para escribir con regularidad?
    </li>
    <li>¿Qué papel juega la lectura en tu vida como autor? ¿Cómo influyen tus lecturas en tu propia escritura?
    </li>
    <li>¿Has tenido la oportunidad de publicar tu trabajo? ¿En qué plataformas o formatos has publicado?
    </li>
    <li>¿Cómo te ha impactado la tecnología en tu experiencia como escritor? ¿Utilizas alguna herramienta digital para la escritura o la promoción de tu trabajo?
    </li>
    <li>¿Has participado en talleres de escritura o comunidades de autores? ¿Qué beneficios has obtenido de estas experiencias?
    </li>
    <li>¿Cuáles son tus principales desafíos como autor? ¿Qué obstáculos has enfrentado en tu carrera?
    </li>
    <li>¿Qué consejos le darías a un aspirante a escritor que está empezando su camino?
    </li>
    <li>¿Qué te parece la idea de una aplicación dedicada a fomentar la lectura? ¿Qué funcionalidades te gustaría que tuviera una aplicación así para ser útil a los autores?
    </li>
    <li>¿Cómo te gustaría que la aplicación te ayudara a mejorar tu experiencia como autor? ¿Qué beneficios esperas obtener de su uso?</li>
</ol>

### 2.2.2. Registro de entrevistas
### Lectores:

Entrevistada #1: Maryori Atanacio Cruces

<ul>
    <li>
        Sexo: Femenino
    </li>
    <li>
        Edad: 23 años
    </li>
    <li>
        Distrito en el que vive: San Juan de Lurigancho
    </li>
</ul>
Entrevista:
<ul>
    <li>
        Link: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b778_upc_edu_pe/ERZMOTxg4GJPhNCGMfCLIHoB86oF3X99fvjMUQsO19HaEQ?e=OcfmTb&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Click para ver la entrevista</a>
    </li>
    <li>
        Duración: 06:23
    </li>
      <li>
        Entrevistador: Fernández Remón, Roy
    </li>
</ul>
<img src="images/Entrevista Lector 1.png" alt="Entrevista Lector 1">

Resumen:
<p align="justify">
    Entrevistamos a Maryori Atanacio Cruces, de 23 años, estudiante y vive en San Juan de Lurigancho. Maryori menciona que disfruta leer de géneros como el drama y la ciencia ficción, aunque encuentra dificultades para dedicar tiempo a la lectura debido al ruido, especialmente en su entorno universitario. A pesar de estos desafíos, lo que lo motiva a seguir leyendo un libro es el suspenso y la curiosidad por lo que ocurrirá en la trama.
Maryori también menciona que, en una aplicación de lectura, apreciaría características como el bloqueo de pantalla para evitar movimientos involuntarios y una mejor navegación. Además de libros, le interesaría encontrar artículos científicos y podcasts. Le gustaría interactuar con otros lectores a través de recomendaciones basadas en intereses compartidos y considera importante que una aplicación de lectura ofrezca medidas de seguridad en los métodos de pago, sugiriendo el uso de tokens para confirmar compras.
Para mantener un hábito de lectura constante, Maryori planearía leer unos minutos al día, aunque no siempre pueda dedicar una hora completa. En cuanto a la compra de libros electrónicos o audiolibros, valora mucho las reseñas bien detalladas y estructuradas. Considera que un mal uso del lenguaje o un cambio abrupto en el estilo podrían hacerle abandonar un libro. Finalmente, menciona que si fuera un usuario leal de una aplicación de lectura, le gustaría recibir recompensas como monedas virtuales, que podrían canjearse por libros. También sugiere que la aplicación ofrezca recomendaciones de títulos similares y permita que los usuarios compartan sus reseñas para ayudar a otros a descubrir nuevas lecturas.
</p>

Entrevistada #2: Jefrey Prado

<ul>
    <li>
        Sexo: Masculino
    </li>
    <li>
        Edad: 23 años
    </li>
    <li>
        Distrito en el que vive: San Juan de Lurigancho
    </li>
</ul>
Entrevista:
<ul>
    <li>
        Link: <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b778_upc_edu_pe/ETbYbE3zCZBOrfesMA79IQ4BpN9y517rv3_FN_K0gM7gzg?e=P0C3fb&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Click para ver la entrevista</a>
    </li>
    <li>
        Duración: 05:27
    </li>
      <li>
        Entrevistador: Fernández Remón, Roy
    </li>
</ul>
<img src="images/Entrevista Lector 2.png" alt="Entrevista Lector 2">

Resumen:
<p align="justify">
    Entrevistamos a Jefrey Prado, de 23 años, estudiante y vive en San Juan de Lurigancho. Le gustan los géneros de ficción y drama, aunque su mayor desafío para encontrar tiempo para leer es la acumulación de trabajos universitarios. Lo que lo motiva a terminar un libro es la calidad de la trama y lo interesante que le parezca.
En cuanto a las funciones deseadas en una aplicación de lectura, destaca que le gustaría encontrar una mayor variedad de géneros y obras, ya que a veces se limita a un solo género. También le interesarían cuentos cortos y contenidos relacionados con la juventud. Para interactuar con otros lectores, sugiere utilizar comentarios y reseñas. En términos de privacidad, prefiere no usar nombres completos y optar por apodos.
Para mantener un hábito de lectura constante, Jeffrey menciona que necesita una mejor organización del tiempo. Al comprar libros electrónicos o audiolibros, valora la accesibilidad del precio y la calidad del contenido. También le interesarían artículos científicos y de investigación. Abandonaría un libro si la ortografía es mala o la trama se vuelve predecible. Como recompensa por ser un usuario leal de la aplicación, le gustaría tener acceso a libros premium o recibir descuentos. Por último, le gustaría que la aplicación sugiera nuevos títulos basados en sus preferencias literarias.
</p>


### Autores:
Entrevistada #1: Aleshka Fernandez

<ul>
    <li>
        Sexo: Femenino
    </li>
    <li>
        Edad: 24 años
    </li>
    <li>
        Distrito en el que vive: San Borja
    </li>
</ul>
Entrevista:
<ul>
    <li>
        Link: <a href="https://www.youtube.com/watch?v=V8NYPikl5B8">Click para ver entrevista</a>
    </li>
    <li>
        Duración: 10:45
    </li>
      <li>
        Entrevistador: La Torre Valle, Franz Jair 
    </li>
</ul>
<img src="images/EntrevistaAleshka.png" alt="Entrevista Autor 1">

Resumen:
<p align="justify">
    Entrevistamos a Aleshka Fernández, de 24 años, quien se siente atraída principalmente por los géneros de fantasía y terror. Aleshka menciona que suele utilizar Google Docs para escribir y prefiere no tener distracciones digitales ni acceder a redes sociales durante ese tiempo. Destaca la importancia de la lectura para ampliar su vocabulario y encontrar referencias para sus personajes. Comenzó su trayectoria en Wattpad y luego llevó algunos de sus cuentos cortos a Webtoon. Para promocionar sus historias, utiliza Twitter e Instagram. Además, ha participado en talleres de autores, los cuales le resultaron muy útiles para conocer la experiencia de otros escritores y superar bloqueos creativos. Una de sus mayores dificultades es mantenerse relevante en el medio, ya que requiere mucha creatividad. Sus consejos para los aspirantes son leer mucho, buscar referentes y nutrirse de información sobre los temas que desean abordar. Considera que una aplicación útil debería tener una buena recepción de archivos, un espacio para publicar borradores, un foro de interacción y actividades recurrentes como charlas para discutir trabajos destacados. Espera que la aplicación le ayude a divulgar su trabajo, impulse a escritores nuevos, ofrezca sugerencias de búsqueda y brinde recomendaciones constantes.
</p>

### 2.2.3. Análisis de entrevistas
### Segmento Objetivo #1: Lectores

<p align="justify">
    Los lectores expresaron un fuerte deseo de formar parte de una comunidad literaria donde puedan interactuar con otros lectores, discutir libros, compartir experiencias de lectura y descubrir nuevas obras. Además, mostraron interés en participar en eventos virtuales con autores, como sesiones de preguntas y respuestas, charlas o lanzamientos de libros. La personalización de perfiles y recomendaciones basadas en gustos individuales, así como la posibilidad de compartir reseñas y recomendaciones con la comunidad, fueron aspectos destacados. En conclusión, los usuarios buscan una plataforma que fomente la interacción entre lectores, proporcione acceso a eventos con autores y ofrezca herramientas de personalización para mejorar su experiencia de lectura.
</p>

### Segmento Objetivo #2:  Autores

<p align="justify">
    Los autores buscan una plataforma que les permita interactuar con los lectores, promocionar sus libros y participar en eventos virtuales. Valorizan el feedback directo de los lectores y desean visibilidad, especialmente para autores emergentes, así como herramientas para el descubrimiento de sus obras. La posibilidad de participar en clubes de lectura virtuales y la seguridad de su información, junto con análisis de datos sobre el rendimiento de sus libros, también son aspectos importantes para ellos.
</p>

## 2.3. Needfinding
### 2.3.1. User Personas
### Lectores:
<img src="images/UserPersonaLector.png">

### Autores:
<img src="images/UserPersonaAutor.png">

### 2.3.2. User Task Matrix
### Lectores:
<img src="images/TaskMatrixLector.png">

### Autores:
<img src="images/TaskMatrixAutor.png">

### 2.3.3. User Journey Mapping
### Lectores:
<img src="images/UserJourneyLector.png">

### Autores:
<img src="images/UserJourneyAutor.png">

### 2.3.4. Empathy Mapping
### Lectores:
<img src="images/EmpathyMapLector.png">

### Autores:
<img src="images/EmpathyMapAutor.png">

### 2.3.5. As-is Scenario Mapping
### Lectores:
<img src="images/As-IsLector.png">

### Autores:
<img src="images/As-IsAutor.png">

## 2.4. Ubiquitous Language
Estos son los términos y conceptos comunes utilizados en nuestro proyecto:
<div align="justify">
    <ul>
        <li>
            <b>Lector:</b> Persona que utiliza la aplicación para leer libros electrónicos o escuchar audiolibros.
        </li>
        <li>
            <b>Autor:</b> Persona que escribe y publica libros electrónicos en la plataforma.
        </li>
        <li>
            <b>Perfil de usuario:</b> Página o sección que contiene información personal de un usuario, como nombre, preferencias de lectura y actividad en la plataforma.
        </li>
        <li>
            <b>Libros electrónicos:</b> Versiones digitales de libros que pueden leerse en dispositivos electrónicos.
        </li>
        <li>
            <b>Audiolibros:</b> Versiones de audio de libros que permiten a los usuarios escuchar narraciones en lugar de leer el texto.
        </li>
        <li>
            <b>Interacción en plataforma:</b> Actividades y comunicación realizadas por los usuarios dentro de la aplicación, como buscar, comprar o dejar reseñas.
        </li>
        <li>
            <b>Comunidad:</b> Conjunto de usuarios de FeatherBook que comparten intereses comunes en la lectura y la cultura literaria.
        </li>
        <li>
            <b>Tienda integrada:</b> Sección de la aplicación donde los usuarios pueden comprar libros electrónicos, audiolibros y otros productos relacionados con la lectura.
        </li>
        <li>
            <b>Transacción:</b> Acción de compra o intercambio de libros electrónicos, audiolibros u otros productos en la plataforma.
        </li>
    </ul>
</div>

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog
# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
Para esta sección se seleccionarán los colores y fuentes que se usaremos para elaborar la aplicación web. Elegimos una paleta de colores atractiva, funcional y agradable de leer:

* Colores primarios: Beige, marfil y blanco roto
* Color del texto: Gris oscuro 
* Decoración y botones: Cobre


  ![Guía de Estilo de Colores](images/Colores_Style_Guidelines.PNG)

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.X. Sprint n
#### 5.2.X.1. Sprint Planning n
#### 5.2.X.2. Sprint Backlog n
#### 5.2.X.3. Development Evidence for Sprint Review
#### 5.2.X.4. Testing Suite Evidence for Sprint Review
#### 5.2.X.5. Execution Evidence for Sprint Review
#### 5.2.X.6. Services Documentation Evidence for Sprint Review
#### 5.2.X.7. Software Deployment Evidence for Sprint Review
#### 5.2.X.8. Team Collaboration Insights during Sprint
## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas
## 5.4. Video About-the-Product
# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team
# Bibliografía
# Anexos
