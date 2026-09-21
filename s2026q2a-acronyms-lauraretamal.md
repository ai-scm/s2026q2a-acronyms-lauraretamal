# Assignment - Acronyms
## Sesión 3

### 1.
- **KISS** (Keep It Simple, Stupid): Principio de diseño que busca mantener las soluciones lo más simples posible, evitando complejidad innecesaria.
- **CQRS** (Command Query Responsibility Segregation): Separa las operaciones que modifican datos (Commands) de las que solo consultan datos (Queries).
- **SOLID**: Conjunto de 5 principios para diseñar código orientado a objetos que sea mantenible, flexible y fácil de modificar:
  - **(S) Single Responsibility Principle**: Una clase debe tener una sola responsabilidad.
  - **(O) Open/Closed Principle**: El código debe estar abierto a extensión, pero cerrado a modificación.
  - **(L) Liskov Substitution Principle**: Una clase hija debe poder sustituir a su clase padre sin romper el funcionamiento del programa.
  - **(I) Interface Segregation Principle**: Una clase no debería depender de métodos que no necesita; es mejor tener interfaces pequeñas y específicas.
  - **(D) Dependency Inversion Principle**: Las partes de alto nivel no deben depender directamente de las de bajo nivel; ambas deben depender de abstracciones.
- **JWT** (JSON Web Token): Formato de token firmado utilizado para transmitir información y, comúnmente, autenticar usuarios en APIs.
- **XSS** (Cross-Site Scripting): Vulnerabilidad en la que un atacante consigue ejecutar código JavaScript malicioso dentro del navegador de otro usuario.

### 2.
- **LLM** (Large Language Model): Modelo de IA entrenado con grandes cantidades de texto para comprender y generar lenguaje natural.
- **GRASP** (General Responsibility Assignment Software Patterns): Conjunto de principios/patrones para decidir qué responsabilidades debe tener cada clase u objeto.
- **SoC** (Separation of Concerns): Separar distintas responsabilidades o preocupaciones del sistema para evitar que todo quede mezclado.
- **SRP** (Single Responsibility Principle): Una clase o módulo debe tener una única responsabilidad principal y, por tanto, una única razón para cambiar.
- **DRY** (Don't Repeat Yourself): Evitar duplicar lógica o conocimiento en diferentes partes del código.
- **YAGNI** (You Aren't Gonna Need It): No implementar funcionalidades que actualmente no son necesarias.

Combinados, **SoC + SRP + DRY + YAGNI** buscan un código organizado, con responsabilidades separadas, sin duplicación y sin complejidad o funcionalidades innecesarias.

### 3.
- **RAG** (Retrieval-Augmented Generation): Técnica que permite a un LLM buscar información externa relevante y utilizarla para generar su respuesta.
- **CAP** (CAP Theorem): Establece que un sistema distribuido no puede garantizar simultáneamente Consistency, Availability y Partition Tolerance al máximo; ante una partición de red, debe priorizar consistencia o disponibilidad.
- **EDA** (Event-Driven Architecture): Arquitectura donde los componentes se comunican mediante eventos, por ejemplo: `OrderCreated`.
- **DDD** (Domain-Driven Design): Enfoque para diseñar software alrededor del dominio y sus reglas de negocio.
- **BFF** (Backend for Frontend): Backend específico para una interfaz concreta, como un BFF para una aplicación web y otro para una aplicación móvil.

### 4.
- **IaC** (Infrastructure as Code): Administrar y crear infraestructura mediante código, por ejemplo servidores, redes y bases de datos.
- **TDD** (Test-Driven Development): Escribir primero las pruebas, después el código necesario para hacerlas pasar y finalmente refactorizar.
- **BDD** (Behavior-Driven Development): Desarrollo basado en el comportamiento esperado del sistema, normalmente expresado en escenarios comprensibles para negocio y desarrollo.
- **ATDD** (Acceptance Test-Driven Development): Definir primero pruebas de aceptación que establecen cuándo una funcionalidad cumple los requisitos.
- **SLA** (Service Level Agreement): Acuerdo que define niveles de servicio comprometidos, como disponibilidad, tiempos de respuesta y soporte.

### 5.
- **MLOps** (Machine Learning Operations): Prácticas para desarrollar, desplegar, monitorear y mantener modelos de machine learning en producción.
- **CI/CD** (Continuous Integration / Continuous Delivery o Deployment): Automatización para integrar, probar y entregar/desplegar cambios de software de forma frecuente.
- **CORS** (Cross-Origin Resource Sharing): Mecanismo del navegador que controla cuándo una página puede realizar solicitudes a un dominio/origen diferente.
