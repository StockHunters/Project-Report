<!--* caratula -->

<div align="center">

# ✨ Informe Trabajo Final ✨

<img src="./resources/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas 🎓

🧑‍💻 Ingeniería de software - 2025-01

**Sección:** 4364

**Docente:** Alex Humberto Sánchez Ponce

**StartUp:** StockHunters 📦

**Producto:** Lubrimax

<div align='left'>	

~~~C#
string[] Integrantes() {
    return new string[] {
        "🧑‍💻 Yum Gonzales, Jorge Suin - U202210838",
        "👩‍💻 Miranda Ayasta, Rogger Faryd - U202319239",
        "👩‍💻 Apellidos, Nombres - Codigo",
        "👩‍💻 Apellidos, Nombres - Codigo",
        "👩‍💻 Apellidos, Nombres - Codigo"
    };
}
~~~

</div>

Abril del 2025 🗓️

</div>

<!--* informacion sobre el proyecto -->

## Registro de versiones del Informe

## Project Report Collaboration Insights

<div>

## Contenido

- [✨ Informe Trabajo Final ✨](#-informe-trabajo-final-)
	- [Universidad Peruana de Ciencias Aplicadas 🎓](#universidad-peruana-de-ciencias-aplicadas-)
	- [Registro de versiones del Informe](#registro-de-versiones-del-informe)
	- [Project Report Collaboration Insights](#project-report-collaboration-insights)
	- [Contenido](#contenido)
	- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
	- [1.1. Startup Profile](#11-startup-profile)
		- [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
		- [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
	- [1.2. Solution Profile](#12-solution-profile)
		- [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
			- [⁉️5“W”s + 2"H"'s](#️5ws--2hs)
				- [🟡 WHAT (QUÉ)](#-what-qué)
				- [🟡 WHEN (CUANDO)](#-when-cuando)
				- [🟡 WHERE (DONDE)](#-where-donde)
				- [🟡 WHO (QUIEN)](#-who-quien)
				- [🟡 WHY (POR QUE)](#-why-por-que)
				- [🟡 HOW (COMO)](#-how-como)
				- [🟡 HOW MUCH (CUANTO)](#-how-much-cuanto)
		- [1.2.2 Lean Ux Process](#122-lean-ux-process)
			- [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
			- [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
				- [Business Outcomes:](#business-outcomes)
				- [User Outcomes](#user-outcomes)
			- [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
			- [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [Capítulo II: Requeriments Elicitation \& Analysis](#capítulo-ii-requeriments-elicitation--analysis)
- [Capítulo III: Requeriments Specification](#capítulo-iii-requeriments-specification)
- [Capítulo IV: Product Desing](#capítulo-iv-product-desing)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)

## Student Outcome

</div>


<!--* contenido -->

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Falta descripción

### 1.1.2 Perfiles de integrantes del equipo

   <!--TODO: integrante 1 -->

**> 🧑‍💻 Jorge Suin Yum Gonzales**
   <div align='center'>

   <img src="https://files.catbox.moe/g2gms8.jpg" alt="Jorge Suin Yum Gonzales" width="100" align='right'>

   ~~~txt
   🎓 Soy estudiante de la Universidad Peruana de Ciencias Aplicadas (UPC), 
   actualmente curso la carrera de Ingeniería de Software.
   
   💻 Tengo experiencia en lenguajes como C++ y Python, así como en el uso 
   de Git y la estructura de trabajo basada en Gitflow 🔁.
   
   🤝 Poseo habilidades que me permiten trabajar en equipo de forma puntual, 
   responsable y con iniciativa para participar activamente en el desarrollo 
   de aplicaciones y sus requerimientos 📱⚙️.
   ~~~

   </div>

   <!--TODO: integrante 2 -->

**> 🧑‍💻 Rogger Faryd Miranda Ayasta**
   <div align='center'>

   <img src="" alt="Rogger Faryd Miranda Ayasta" width="100" align='right'>

   ~~~txt
   🎓 Soy estudiante de Ingeniería de Software, 
   actualmente curso el 5.º ciclo de la carrera.

   💻 A lo largo de mi formación he aprendido diversos lenguajes de programación, como:
   ➡️ C++
   ➡️ Python
   ➡️ JavaScript
   ➡️ HTML & CSS

   🤝 Me destaco por mi responsabilidad, mis habilidades 
   para el trabajo en equipo y mi motivación constante por 
   seguir aprendiendo 📚.
   ~~~

   </div>


   <!--TODO: integrante 3 -->

**> 🧑‍💻 Integrante 3**
   <div align='center'>

   <img src="link-img" alt="name" width="100" align='right'>

   ~~~txt
   Descripción
   ~~~

   </div>


   <!--TODO: integrante 4 -->

**> 🧑‍💻 Integrante 4**
   <div align='center'>

   <img src="link-img" alt="name" width="100" align='right'>

   ~~~txt
   Descripción
   ~~~

   </div>


   <!--TODO: integrante 5 -->

**> 🧑‍💻 Integrante 5**
   <div align='center'>

   <img src="link-img" alt="name" width="100" align='right'>

   ~~~txt
   Descripción
   ~~~

   </div>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

En el presente la gran mayoría de companias que ofrecen productos, requieren de un sistema de inventario y venta para
gestionar y visualizar las estadísticas necesarias para futuras decisiones. Sin embargo, esto puede econtrarse
desafiante e impractico debido a las formas limitadas de acceso, gestion y registro que son causados metodos
ineficientes de registro y almacenamiento de esta información. Esto causa retrasos, incomodidades y perdidas de tiempo
del dueño y el cliente interesesada en esta información.

#### ⁉️5“W”s + 2"H"'s

##### 🟡 WHAT (QUÉ)

- **¿Cual es el problema?**

  El problema se refiere al método ineficiente de registrar inventario y ventas lo que causan formas impracticas de
  acceder la información, como ir al mismo almacén solo para saber cuanto de un producto hay o la cantidad de ventas en
  un Mes. Este registro manual e inflexible también impide un facil análisis de las ventas y las estadísticas que
  potencialmente podrian mejorar las deicisiones futuras. Finalmente este tipo de registro causa que la base de datos o
  el medio en que se esté guardando la información tenga que ser copiado o movido para trabajar en ello lo cual puede
  causar errores de asincronización o falta de datos causados por error humano.
  <br>

##### 🟡 WHEN (CUANDO)

- **¿Cuando sucede el problema?**

  El problema ocurre cada vez que el dueño quiere acceder al inventario y a la información de venta desde el exterior al
  inventario. Esto problema puede presentarse de las siguentes maneras: al querer visualizar el inventario desde
  cualquier dispositivo o lugar, al querer analizar rapidamente las estadisticas y al querer saber informacion de
  clientes y fechas de manera rápida.
  <br>

- **¿Cuando utiliza el cliente el producto?**

  El cliente (usuario del sistema) lo utiliza diariamente para registrar nuevas ventas, actualizar el inventario,
  acceder a reportes estadísticos y consultar información desde cualquier lugar y en cualquier momento, lo cual mejora
  la productividad y la capacidad de respuesta del negocio.
  <br>

##### 🟡 WHERE (DONDE)

- **¿Dónde se presenta el problema?**
  En negocios que no cuentan con un sistema centralizado accesible desde múltiples plataformas, y que dependen de
  registros físicos, hojas de cálculo o software local para controlar el inventario y las ventas.
  <br>

- **¿Dónde se usa el producto?**
  La aplicación web se utiliza desde cualquier dispositivo con acceso a internet (PC, laptop, tablet o celular),
  permitiendo a los usuarios ingresar y consultar información desde su oficina, casa, viaje o punto de venta.
  <br>

##### 🟡 WHO (QUIEN)

- **¿Quién tiene este problema?**
  Pequeñas y medianas empresas (pymes), emprendedores y administradores de tiendas físicas o virtuales que buscan una
  solución más práctica, automatizada y accesible para manejar su inventario y sus ventas.
  <br>

- **¿Quién se beneficia del producto?**
  Los propietarios del negocio, sus empleados, y los clientes, quienes se benefician de un servicio más rápido,
  confiable y bien gestionado.
  <br>

##### 🟡 WHY (POR QUE)

- **¿Por qué ocurre el problema?**

  Porque muchas empresas no cuentan con herramientas tecnológicas adecuadas o actualizadas, y dependen de sistemas
  obsoletos o limitados que no se adaptan a las necesidades actuales de movilidad, análisis rápido y disponibilidad de
  la información en tiempo real. Al mismo tiempo los clientes (especialmente los de mayor edad) no pueden encontrar un
  servicio que encaje con sus requisitos ellos recurren a lo que a pesar de ser ineficiente, funciona.
  <br>

##### 🟡 HOW (COMO)

- **¿Cómo soluciona el producto el problema?**

  La aplicación web centraliza y automatiza el registro de inventario y ventas, y permite acceder a esa información
  desde cualquier dispositivo. Además, integra herramientas de análisis con filtros dinámicos para facilitar la
  interpretación de datos y la toma de decisiones.
  <br>

##### 🟡 HOW MUCH (CUANTO)

- **¿Cuánto mejora el producto la situación actual?**

  El uso de la aplicación reduce drásticamente el tiempo invertido en el control manual, disminuye los errores por
  registro duplicado o desactualizado, y permite una mejor planificación comercial basada en datos precisos y siempre
  disponibles.
  <br>

### 1.2.2 Lean Ux Process

#### 1.2.2.1. Lean UX Problem Statements

En la empresa LubriMax, existe una necesidad de implementar un sistema integral de gestión de inventario y ventas que
sea eficiente, automatizado y accesible desde cualquier dispositivo con conexión a internet. Este sistema debe permitir
la visualización del inventario en tiempo real, facilitar el registro de entradas y salidas de productos, así como el
seguimiento de ventas y clientes, incluyendo la recopilación organizada de datos relevantes como nombre, contacto,
historial de compras, entre otros. Todo ello con el objetivo de optimizar la operación comercial, mejorar la toma de
decisiones estratégicas y fortalecer la interacción con el cliente.

Actualmente, la compañía gestiona su inventario de forma manual utilizando hojas de cálculo en Excel tanto en formato
digital como físico, desde un único dispositivo. Por otro lado, se mantiene un registro de los clientes de manera
informal. Estos métodos provocan una serie de dificultades: Errores frecuentes en el registro por duplicación o falta de
actualización, perdida de tiempo al buscar información específica, falta de acceso remoto al sistema de inventario y
dificultades para generar reportes útiles para la planificación o auditorías.
Estas limitaciones impactan directamente en la eficiencia operativa, la toma de decisiones estratégicas, la atención al
cliente y el control de stock, generando retrasos, frustración y potenciales pérdidas económicas.

¿Cómo podríamos digitalizar y automatizar el control de inventario y ventas de LubriMax para mejorar la eficiencia
diaria del negocio? ¿Cómo podríamos permitir el acceso remoto al sistema desde múltiples dispositivos de manera segura y
sincronizada? ¿Cómo podríamos generar reportes claros, visuales y actualizados que respalden las decisiones estratégicas
y el análisis de desempeño?

#### 1.2.2.2. Lean UX Assumptions

##### Business Outcomes:

1. Creemos que nuestros usuarios necesitan:
   Una aplicación que permita la gestión y análisis de ventas e inventario desde cualquier plataforma o navegador con
   acceso a internet, para acceder a datos actualizados en tiempo real y tomar decisiones informadas.
   <br>

2. Estas necesidades se pueden satisfacer con:
   Una aplicación web interactiva, con una base de datos estructurada que permita registrar entradas y salidas de
   inventario, gestionar ventas, generar reportes dinámicos, y acceder a toda la información desde múltiples
   dispositivos.
   <br>

3. Nuestros clientes iniciales son:
   LubriMax y empresas similares que requieran gestionar un inventario de productos físicos, como almacenes, tiendas de
   repuestos, o centros de distribución.
   <br>

4. El valor más importante que un cliente quiere de nuestros servicios es:
   Acceso en tiempo real desde cualquier dispositivo, facilidad de uso, y mayor control operativo sobre el inventario y
   las ventas.
   <br>

5. El cliente también va a obtener estos beneficios adicionales:
   Mejores reportes y visualización de estadísticas, reducción de errores humanos, registro eficiente de clientes,
   optimización del tiempo operativo, mejora en la toma de decisiones estratégicas.
   <br>

6. Vamos a adquirir la mayoría de nuestros clientes a través de:
   Estrategias de marketing digital, incluyendo publicaciones promocionales, demostraciones del software en redes
   sociales, campañas segmentadas y alianzas con distribuidores.
   <br>

7. Haremos dinero a través de:
   Subscripciones mensuales, anuales o de por vida por el uso del software. De otro lado podemos ofrecer servicios
   adicionales como mantenimiento técnico, soporte personalizado, y posibles integraciones especiales.
   <br>

8. Nuestra competencia principal en el mercado será
   Software genérico de inventario como Excel avanzado, sistemas POS comerciales, o plataformas tipo ERP que ofrecen
   funciones similares pero menos personalizadas.
   <br>

9. Vamos a tener ventaja frente a nuestra competencia debido a
   Un enfoque adaptado a las necesidades específicas de cada cliente, interfaz simple y amigable, acceso multiplataforma
   sin instalaciones complejas, costos más accesibles que los sistemas ERP tradicionales y soporte personalizado para
   pequeñas y medianas empresas.
   <br>

10. El mayor riesgo del servicio es que
    Nuestro segmento objetivo (empresas pequeñas y tradicionales) no adopte fácilmente nuevas tecnologías, o prefiera
    seguir con sistemas conocidos como Excel por resistencia al cambio.
    <br>

11. Eliminaremos los riesgos
    Ofrecer capacitación inicial gratuita y soporte técnico continuo y presentar casos de éxito y comparativas claras
    que evidencien los beneficios reales frente a los métodos actuales.

<br>

##### User Outcomes

* **¿Quien es nuestro usuario?**
  El administrador o personal de ventas y logística de LubriMax (y empresas similares), responsable del inventario y la
  atención al cliente.
  <br>

* **¿Que problema tiene nuestro producto y como se pueden resolver?**
  El problema es la ineficiencia operativa y falta de visibilidad en tiempo real. Esto se resuelve con un sistema
  centralizado accesible desde cualquier lugar y con datos actualizados.
  <br>

* **¿Donde encaja nuestro producto en su vida?**
  Encaja en sus rutinas diarias de trabajo, ya que forma parte del proceso de venta, control de stock y toma de
  decisiones administrativas.
  <br>

* **¿Como y cuando es usado nuestro producto?**
  Se usa varias veces al día, durante horarios laborales, para registrar ventas, revisar niveles de stock, consultar
  reportes, y revisar información de clientes.
  <br>

* **¿Que problemas tiene nuestro producto?**
  Podría enfrentar barreras de adopción tecnológica, falta de conectividad constante o dificultad de integración con
  otros sistemas ya existentes.
  <br>

* **¿Que características son importantes?**
  Interfaz intuitiva, reportes visuales y fáciles de entender, acceso remoto, registro rápido de productos, ventas y
  clientes y seguridad de datos y respaldos automáticos.
  <br>

#### 1.2.2.3. Lean UX Hypothesis Statements

`💡[Creemos que]` permitir el acceso al sistema desde múltiples dispositivos (PC, tablet, celular) facilitará el uso
continuo de la aplicación en cualquier momento,

`💭[sabremos que esto es cierto cuando]` los usuarios accedan desde más de un dispositivo durante la primera semana de
uso.

   ---

`💡[Creemos que]` digitalizar la gestión de inventario permitirá mayor control sobre el stock y reducirá el tiempo
dedicado a esta tarea,

`💭[sabremos que esto es cierto cuando]` los usuarios puedan registrar entradas/salidas en menos de 1 minuto y generen
reportes sin necesidad de hojas de cálculo externas.

   ---

`💡[Creemos que]` incluir un sistema de registro de ventas vinculado a clientes mejorará el seguimiento comercial y la
personalización del servicio,

`💭[sabremos que esto es cierto cuando]`al menos el 90% de las ventas registradas estén asociadas a un cliente con
información básica completa (nombre, contacto, fecha).

   ---

`💡[Creemos que]` ofrecer reportes visuales y estadísticas facilitará la toma de decisiones basadas en datos reales,

`💭[sabremos que esto es cierto cuando]` los usuarios consulten los reportes al menos 3 veces por semana y utilicen la
información para ajustar su inventario o estrategia de ventas.

   ---

`💡[Creemos que]` ofrecer una interfaz intuitiva y soporte técnico desde el primer uso ayudará a que usuarios con baja
familiaridad tecnológica adopten la herramienta,

`💭[sabremos que esto es cierto cuando]` el 80% de los usuarios completen las tareas básicas sin requerir asistencia
directa durante la primera semana.
<br><br>

#### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas](resources/LeanUX_canvas_v5.jpg)

## Segmentos Objetivos

<table>
  <tr>
    <th>Segmento objetivo</th>
    <th>Dueños o administradores de negocios con inventario físico</th>
  </tr>
  <tr>
    <td>Descripción</td>
    <td>Personas que manejan un negocio físico (por ejemplo, salones de belleza, barberías, distribuidores) y que actualmente gestionan su inventario de manera manual, ya sea en cuadernos, hojas de Excel o simplemente de forma visual. Tienen la necesidad de organizar mejor su inventario y operaciones, reducir errores y acceder a información en tiempo real.</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>	Más de 24 años</td>
  </tr>
<tr>
    <td>Sexo</td>
    <td>Masculino o Femenino</td>
  </tr>
<tr>
    <td>Ubicación</td>
    <td>	Lima Metropolitana y principales ciudades urbanas del Perú (Arequipa, Trujillo, Chiclayo, Piura)</td>
  </tr>
    <tr>
        <td>Sexo</td>
        <td>Masculino o Femenino</td>
    </tr>
    <tr>
      <th>Formación educativa</th>
      <td>Educación técnica o superior completa/incompleta</td>
    </tr>
    <tr>
      <th>Poder adquisitivo</th>
      <td>Medio a medio-alto</td>
    </tr>
    <tr>
      <th>Clase social</th>
      <td>Media y media emergente y alta</td>
    </tr>
    <tr>
      <th>Datos de sustento</th>
      <td>
        Según el INEI (Demografía Empresarial 2024), el 99.5% de las empresas peruanas son MYPES, y más del 75% no lleva registros contables. Estas empresas emplean al 48.3% de la PEA.<br>
        Fuente: <a href="https://m.inei.gob.pe/biblioteca-virtual/boletines/demografia-empresarial-8237/1/" target="_blank">INEI – Demografía Empresarial</a>
      </td>
    </tr>
</table>

<table>
  <tr>
    <th>Segmento objetivo</th>
    <th>Compradores o clientes registrados</th>
  </tr>
  <tr>
      <th>Descripción</th>
      <td>Clientes finales que compran productos o servicios de los negocios registrados. Sus datos son almacenados para seguimiento, historial, promociones o fidelización.</td>
    </tr>
    <tr>
      <th>Edad</th>
      <td>Más de 18 años</td>
    </tr>
    <tr>
      <th>Ubicación</th>
      <td>Áreas urbanas y semiurbanas con acceso a internet (Lima, Callao, Arequipa, La Libertad, Lambayeque)</td>
    </tr>
    <tr>
      <th>Sexo</th>
      <td>Principalmente femenino, también masculino</td>
    </tr>
    <tr>
      <th>Formación educativa</th>
      <td>Secundaria completa, técnico o universitario en curso</td>
    </tr>
    <tr>
      <th>Poder adquisitivo</th>
      <td>Bajo a medio</td>
    </tr>
    <tr>
      <th>Clase social</th>
      <td>Media y media-baja</td>
    </tr>
    <tr>
      <th>Datos de sustento</th>
      <td>
        El INEI señala que más del 70% de jóvenes entre 18 y 29 años usan internet activamente, y Osiptel indica que el 68% de peruanos accede a internet por celular.<br>
        Fuente: <a href="https://www.inei.gob.pe/media/MenuRecursivo/boletines/01-informe-tecnico-n01_estadisticas-genero_oct-nov-dic2017.pdf" target="_blank">INEI – Estadísticas de Género</a>
      </td>
    </tr>
</table>

# Capítulo II: Requeriments Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
<table>
  <tr>
    <th colspan="6" valign="top">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4" valign="top">El objetivo de este análisis es identificar las características de los competidores y encontrar maneras de diferenciarnos.</td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2" valign="top">Startup y Competidores</td>
    <td valign="top">Mi Startup</td>
    <td valign="top">Bsale</td>
    <td valign="top">Defontana</td>
    <td valign="top">Microsoft Excel</td>
  </tr>
  <tr>
    <td valign="top"><img src="img/mistartup.png" alt="Logo Mi Startup" height="100px"></td>
    <td valign="top"><img src="https://yt3.googleusercontent.com/kH5MizoIzldC54QkNt1zNehJxroIU4D71l9gQRroMPr04WToKg1BfQbigz-_Ki5ZUDgdpmckzmk=s160-c-k-c0x00ffffff-no-rj" alt="Logo Bsale" height="100px"></td>
    <td valign="top"><img src="https://yt3.googleusercontent.com/bly9PPL4rYGzO7BdSc32EBQOScwskQ-pXmIw7y64dvTp5hog-AJ3n7b-GgcRVAaovXPH_8NARA=s900-c-k-c0x00ffffff-no-rj" alt="Logo Defontana" height="100px"></td>
    <td valign="top"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg/1200px-Microsoft_Office_Excel_%282019%E2%80%93present%29.svg.png" alt="Logo Excel" height="100px"></td>
   </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil</td>
    <td valign="top">Overview</td>
    <td valign="top">Aplicación web moderna para gestionar inventario, ventas y clientes en tiempo real desde cualquier dispositivo.</td>
    <td valign="top">Software de ventas con control de stock, emisión de comprobantes y reportes en línea.</td>
    <td valign="top">ERP 100% online que integra ventas, inventario, contabilidad y compras.</td>
    <td valign="top">Herramienta de hojas de cálculo ampliamente utilizada para gestionar inventarios manualmente.</td>
  </tr>
  <tr>
    <td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td valign="top">Acceso remoto, visualización y gestión de datos, reportes sencillos.</td>
    <td valign="top">Interfaz amigable, sin comisiones por ventas, soporte local.</td>
    <td valign="top">Escalabilidad total, integración completa entre procesos.</td>
    <td valign="top">Alta familiaridad, bajo costo, sin curva de aprendizaje inicial.</td>
  </tr>
  <tr>
    <td rowspan="2" valign="top">Perfil de Marketing</td>
    <td valign="top">Mercado objetivo</td>
    <td valign="top">Dueños o administradores de negocios que requieran de un metodo efectivo y rápido de gestionar su inventario</td>
    <td valign="top">Pequeños comercios que requieren control básico de ventas e inventario.</td>
    <td valign="top">Empresas medianas o grandes que buscan centralizar procesos.</td>
    <td valign="top">Negocios tradicionales que ya lo usan como solución manual de bajo costo.</td>
  </tr>
  <tr>
    <td valign="top">Estrategias de marketing</td>
    <td valign="top">Publicidad en campañas desde redes sociales</td>
    <td valign="top">Publicidad en Google, marketing en redes, venta consultiva.</td>
    <td valign="top">Alianzas con consultoras y campañas dirigidas a empresas.</td>
    <td valign="top">No es promocionado como solución directa, pero su uso es masivo por familiaridad.</td>
  </tr>
  <tr>
    <td rowspan="3" valign="top">Perfil de Producto</td>
    <td valign="top">Productos & Servicios</td>
    <td valign="top">Gestión de stock, ventas, clientes, reportes visuales, soporte técnico, acceso multiplataforma.</td>
    <td valign="top">Facturación electrónica, control de inventario, reportería automatizada.</td>
    <td valign="top">ERP completo con módulos de ventas, compras, contabilidad, etc.</td>
    <td valign="top">Plantillas de control manual con fórmulas básicas, personalizables por el usuario.</td>
  </tr>
  <tr>
    <td valign="top">Precios & Costos</td>
    <td valign="top">Suscripción mensual o anual con soporte incluido.</td>
    <td valign="top">Desde S/89 mensuales.</td>
    <td valign="top">Desde $50 mensuales según plan.</td>
    <td valign="top">Gratuito (Google Sheets / LibreOffice) o incluido con Microsoft Office.</td>
  </tr>
  <tr>
    <td valign="top">Canales de distribución (Web y/o Móvil)</td>
    <td valign="top">Web responsive para PC, tablet y celular.</td>
    <td valign="top">Web y móvil, acceso en la nube.</td>
    <td valign="top">Web app con integraciones externas.</td>
    <td valign="top">Local (instalado) o en la nube (OneDrive, Office 365).</td>
  </tr>
  <tr>
    <td rowspan="4" valign="top">Análisis SWOT</td>
    <td valign="top">Fortalezas</td>
    <td valign="top">Fácil de usar, accesible desde cualquier lugar, soporte cercano.</td>
    <td valign="top">Ampliamente usado, soporte técnico, adaptado a comercio.</td>
    <td valign="top">Altamente escalable, funcionalidad robusta.</td>
    <td valign="top">Conocido, flexible, económico, sin curva de aprendizaje.</td>
  </tr>
  <tr>
    <td valign="top">Debilidades</td>
    <td valign="top">Dependencia de internet, poca visibilidad de marca aún.</td>
    <td valign="top">Limitado para empresas que buscan integración total.</td>
    <td valign="top">Curva de aprendizaje alta, costos elevados.</td>
    <td valign="top">Propenso a errores humanos, no automatizado, sin trazabilidad.</td>
  </tr>
  <tr>
    <td valign="top">Oportunidades</td>
    <td valign="top">Captar clientes que usan Excel con migración asistida y automatización.</td>
    <td valign="top">Expandirse a otros sectores como food service o retail grande.</td>
    <td valign="top">Desarrollar versiones simplificadas para pequeñas empresas.</td>
    <td valign="top">Integrarse con plataformas digitales o APIs.</td>
  </tr>
  <tr>
    <td valign="top">Amenazas</td>
    <td valign="top">Resistencia al cambio de quienes ya usan Excel o sistemas manuales.</td>
    <td valign="top">Competencia con herramientas más económicas y simples.</td>
    <td valign="top">Competidores más accesibles para pymes.</td>
    <td valign="top">Sistemas web especializados que reemplazan su funcionalidad manual.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores
**Estrategias**

* Diferenciarnos por simplicidad y rapidez de adopción: desarrollaremos caracteristicas unicas que permitan al usuario adaptarse rapidamente al sistema y migrar datos o configuraciones de otro programa.
* Responder a la falta de capacidad movil de Defontana y Ecel.
* Diferenciarnos con precios accesibles.

**Tácticas**

* Implementar una guía de onboarding visual y autoguiada desde el primer acceso y ofrecer soporte técnico personalizado.
* Implementación de un sistema de migración de datos desde Excel a la nueva plataforma, con asistencia técnica para asegurar una transición fluida y sin errores.
* Optimizar toda la experiencia para celulares y tablets desde la interfaz principal.
* Crear una calculadora de ahorro: cuánto cuesta usar nuestro sistema vs. pagar módulos por separado.


# Capítulo III: Requeriments Specification

# Capítulo IV: Product Desing

# Capítulo V: Product Implementation, Validation & Deployment