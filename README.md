
<!--* caratula -->

<div align="center">

# ✨ Informe Trabajo Final ✨

<img src="./resources/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas 🎓

🧑‍💻 Ingeniería de software  - 2025-01

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

1. [📄 Capitulo I: Introducción](#capítulo-i-introducción)
   
   1.1.  [Startup Profile](#11-startup-profile)

      1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)

      1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)

[📄 Capitulo II: Requeriments Elicitation & Analysis](#capítulo-ii-requeriments-elicitation--analysis)

[📄 Capitulo III: Requeriments Specification](#capítulo-iii-requeriments-specification)

[📄 Capitulo IV: Product Desing](#capítulo-iv-product-desing)

[📄 Capitulo V: Product Implementation, Validation & Deployment](#capítulo-iv-product-desing)


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
   
   <img src="https://files.catbox.moe/g2gms8.jpg" alt="Rogger Faryd Miranda Ayasta" width="100" align='right'>

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
   En el presente la gran mayoría de companias que ofrecen productos, requieren de un sistema de inventario y venta para gestionar y visualizar las estadísticas necesarias para futuras decisiones. Sin embargo, esto puede econtrarse desafiante e impractico debido a las formas limitadas de acceso, gestion y registro que son causados metodos ineficientes de registro y almacenamiento de esta información. Esto causa retrasos, incomodidades y perdidas de tiempo del dueño y el cliente interesesada en esta información.

   #### ⁉️5“W”s + 2"H"'s

   ##### 🟡 WHAT (QUÉ)
   - **¿Cual es el problema?**
      
      El problema se refiere al método ineficiente de registrar inventario y ventas lo que causan formas impracticas de acceder la información, como ir al mismo almacén solo para saber cuanto de un producto hay o la cantidad de ventas en un Mes. Este registro manual e inflexible también impide un facil análisis de las ventas y las estadísticas que potencialmente podrian mejorar las deicisiones futuras. Finalmente este tipo de registro causa que la base de datos o el medio en que se esté guardando la información tenga que ser copiado o movido para trabajar en ello lo cual puede causar errores de asincronización o falta de datos causados por error humano. 
      <br>

   ##### 🟡 WHEN (CUANDO)
   - **¿Cuando sucede el problema?**

      El problema ocurre cada vez que el dueño quiere acceder al inventario y a la información de venta desde el exterior al inventario. Esto problema puede presentarse de las siguentes maneras: al querer visualizar el inventario desde cualquier dispositivo o lugar, al querer analizar rapidamente las estadisticas y al querer saber informacion de clientes y fechas de manera rápida. 
      <br>

   - **¿Cuando utiliza el cliente el producto?**

      El cliente (usuario del sistema) lo utiliza diariamente para registrar nuevas ventas, actualizar el inventario, acceder a reportes estadísticos y consultar información desde cualquier lugar y en cualquier momento, lo cual mejora la productividad y la capacidad de respuesta del negocio.
      <br>

   ##### 🟡 WHERE (DONDE)
   - **¿Dónde se presenta el problema?**
      En negocios que no cuentan con un sistema centralizado accesible desde múltiples plataformas, y que dependen de registros físicos, hojas de cálculo o software local para controlar el inventario y las ventas.
      <br>

   - **¿Dónde se usa el producto?**
      La aplicación web se utiliza desde cualquier dispositivo con acceso a internet (PC, laptop, tablet o celular), permitiendo a los usuarios ingresar y consultar información desde su oficina, casa, viaje o punto de venta.
      <br>

   ##### 🟡 WHO (QUIEN)
   - **¿Quién tiene este problema?**
      Pequeñas y medianas empresas (pymes), emprendedores y administradores de tiendas físicas o virtuales que buscan una solución más práctica, automatizada y accesible para manejar su inventario y sus ventas.
      <br>

   - **¿Quién se beneficia del producto?**
      Los propietarios del negocio, sus empleados, y los clientes, quienes se benefician de un servicio más rápido, confiable y bien gestionado.
      <br>

   ##### 🟡 WHY (POR QUE)
   - **¿Por qué ocurre el problema?**

      Porque muchas empresas no cuentan con herramientas tecnológicas adecuadas o actualizadas, y dependen de sistemas obsoletos o limitados que no se adaptan a las necesidades actuales de movilidad, análisis rápido y disponibilidad de la información en tiempo real. Al mismo tiempo los clientes (especialmente los de mayor edad) no pueden encontrar un servicio que encaje con sus requisitos ellos recurren a lo que a pesar de ser ineficiente, funciona. 
      <br>

   ##### 🟡 HOW (COMO)
   - **¿Cómo soluciona el producto el problema?**

      La aplicación web centraliza y automatiza el registro de inventario y ventas, y permite acceder a esa información desde cualquier dispositivo. Además, integra herramientas de análisis con filtros dinámicos para facilitar la interpretación de datos y la toma de decisiones.
      <br>

   ##### 🟡 HOW MUCH (CUANTO)
   - **¿Cuánto mejora el producto la situación actual?**

      El uso de la aplicación reduce drásticamente el tiempo invertido en el control manual, disminuye los errores por registro duplicado o desactualizado, y permite una mejor planificación comercial basada en datos precisos y siempre disponibles.
      <br>

   ### 1.2.2 Lean Ux Process
   #### 1.2.2.1. Lean UX Problem Statements
   En la empresa LubriMax, existe una necesidad de implementar un sistema integral de gestión de inventario y ventas que sea eficiente, automatizado y accesible desde cualquier dispositivo con conexión a internet. Este sistema debe permitir la visualización del inventario en tiempo real, facilitar el registro de entradas y salidas de productos, así como el seguimiento de ventas y clientes, incluyendo la recopilación organizada de datos relevantes como nombre, contacto, historial de compras, entre otros. Todo ello con el objetivo de optimizar la operación comercial, mejorar la toma de decisiones estratégicas y fortalecer la interacción con el cliente.
   Actualmente, la compañía gestiona su inventario de forma manual utilizando hojas de cálculo en Excel tanto en formato digital como físico, desde un único dispositivo. Por otro lado, se mantiene un registro de los clientes de manera informal. Estos métodos provocan una serie de dificultades: Errores frecuentes en el registro por duplicación o falta de actualización, perdida de tiempo al buscar información específica, falta de acceso remoto al sistema de inventario y dificultades para generar reportes útiles para la planificación o auditorías.
   Estas limitaciones impactan directamente en la eficiencia operativa, la toma de decisiones estratégicas, la atención al cliente y el control de stock, generando retrasos, frustración y potenciales pérdidas económicas.
   ¿Cómo podríamos digitalizar y automatizar el control de inventario y ventas de LubriMax para mejorar la eficiencia diaria del negocio? ¿Cómo podríamos permitir el acceso remoto al sistema desde múltiples dispositivos de manera segura y sincronizada? ¿Cómo podríamos generar reportes claros, visuales y actualizados que respalden las decisiones estratégicas y el análisis de desempeño?
   
   #### 1.2.2.2. Lean UX Assumptions
   ##### Business Outcomes:
   1. Creemos que nuestros usuarios necesitan:

      Una aplicación que permita la gestión y análisis de ventas e inventario desde cualquier plataforma o navegador con acceso a internet, para acceder a datos actualizados en tiempo real y tomar decisiones informadas.

   2. Estas necesidades se pueden satisfacer con:

      Una aplicación web interactiva, con una base de datos estructurada que permita registrar entradas y salidas de inventario, gestionar ventas, generar reportes dinámicos, y acceder a toda la información desde múltiples dispositivos.

   3. Nuestros clientes iniciales son:

      LubriMax y empresas similares que requieran gestionar un inventario de productos físicos, como almacenes, tiendas de repuestos, o centros de distribución.

   4. El valor más importante que un cliente quiere de nuestros servicios es:

      Acceso en tiempo real desde cualquier dispositivo, facilidad de uso, y mayor control operativo sobre el inventario y las ventas.

   5. El cliente también va a obtener estos beneficios adicionales:

      Mejores reportes y visualización de estadísticas, reducción de errores humanos, registro eficiente de clientes, optimización del tiempo operativo, mejora en la toma de decisiones estratégicas.
   6. Vamos a adquirir la mayoría de nuestros clientes a través de:

      Estrategias de marketing digital, incluyendo publicaciones promocionales, demostraciones del software en redes sociales, campañas segmentadas y alianzas con distribuidores.
   7. Haremos dinero a través de:

      Subscripciones mensuales, anuales o de por vida por el uso del software. De otro lado podemos ofrecer servicios adicionales como mantenimiento técnico, soporte personalizado, y posibles integraciones especiales.

   8. Nuestra competencia principal en el mercado será

      Software genérico de inventario como Excel avanzado, sistemas POS comerciales, o plataformas tipo ERP que ofrecen funciones similares pero menos personalizadas.
   9. Vamos a tener ventaja frente a nuestra competencia debido a

      Un enfoque adaptado a las necesidades específicas de cada cliente, interfaz simple y amigable, acceso multiplataforma sin instalaciones complejas, costos más accesibles que los sistemas ERP tradicionales y soporte personalizado para pequeñas y medianas empresas.
   10. El mayor riesgo del servicio es que
   Nuestro segmento objetivo (empresas pequeñas y tradicionales) no adopte fácilmente nuevas tecnologías, o prefiera seguir con sistemas conocidos como Excel por resistencia al cambio.
   
   11. Eliminaremos los riesgos
   Ofrecer capacitación inicial gratuita y soporte técnico continuo y presentar casos de éxito y comparativas claras que evidencien los beneficios reales frente a los métodos actuales.
  
   ##### User Outcomes
   * ¿Quien es nuestro usuario?

   El administrador o personal de ventas y logística de LubriMax (y empresas similares), responsable del inventario y la atención al cliente.
   * ¿Que problema tiene nuestro producto y como se pueden resolver?

   El problema es la ineficiencia operativa y falta de visibilidad en tiempo real. Esto se resuelve con un sistema centralizado accesible desde cualquier lugar y con datos actualizados.
   * ¿Donde encaja nuestro producto en su vida?

   Encaja en sus rutinas diarias de trabajo, ya que forma parte del proceso de venta, control de stock y toma de decisiones administrativas.
   * ¿Como y cuando es usado nuestro producto?

   Se usa varias veces al día, durante horarios laborales, para registrar ventas, revisar niveles de stock, consultar reportes, y revisar información de clientes.
   * ¿Que problemas tiene nuestro producto?

   Podría enfrentar barreras de adopción tecnológica, falta de conectividad constante o dificultad de integración con otros sistemas ya existentes.
   * ¿Que características son importantes?

   Interfaz intuitiva, reportes visuales y fáciles de entender, acceso remoto, registro rápido de productos, ventas y clientes y seguridad de datos y respaldos automáticos.
   
   #### 1.2.2.3. Lean UX Hypothesis Statements
   **Creemos que** permitir el acceso al sistema desde múltiples dispositivos (PC, tablet, celular) facilitará el uso continuo de la aplicación en cualquier momento,  
   **y sabremos que esto es cierto cuando** los usuarios accedan desde más de un dispositivo durante la primera semana de uso.

   **Creemos que** digitalizar la gestión de inventario permitirá mayor control sobre el stock y reducirá el tiempo dedicado a esta tarea,  
   **y sabremos que esto es cierto cuando** los usuarios puedan registrar entradas/salidas en menos de 1 minuto y generen reportes sin necesidad de hojas de cálculo externas.

   **Creemos que** incluir un sistema de registro de ventas vinculado a clientes mejorará el seguimiento comercial y la personalización del servicio,  
   **y sabremos que esto es cierto cuando** al menos el 90% de las ventas registradas estén asociadas a un cliente con información básica completa (nombre, contacto, fecha).

   **Creemos que** ofrecer reportes visuales y estadísticas facilitará la toma de decisiones basadas en datos reales,  
   **y sabremos que esto es cierto cuando** los usuarios consulten los reportes al menos 3 veces por semana y utilicen la información para ajustar su inventario o estrategia de ventas.

   **Creemos que** ofrecer una interfaz intuitiva y soporte técnico desde el primer uso ayudará a que usuarios con baja familiaridad tecnológica adopten la herramienta,  
   **y sabremos que esto es cierto cuando** el 80% de los usuarios completen las tareas básicas sin requerir asistencia directa durante la primera semana.
   
   #### 1.2.2.4. Lean UX Canvas


# Capítulo II: Requeriments Elicitation & Analysis

# Capítulo III: Requeriments Specification

# Capítulo IV: Product Desing

# Capítulo V: Product Implementation, Validation & Deployment