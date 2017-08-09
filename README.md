# Taller Persistencia Básico

Al finalizar, el estudiante podrá:

* Construir una entidad persistente con sus respectivos métodos (CRUD) Create,
Retrieve, Update, Delete
* Probar con las pruebas unitarias dadas para tal fin.

## Ambiente de Desarrollo y Ejecución

Netbeans >= 8.2

Glassfish 4.1

Java >8


|Pasos| |
|----|---|
|1. Clonar el proyecto| a. En github ir a |
| |https://github.com/Uniandes-isis2603/company-TallerPersistencia|
| |Copiar la url del proyecto.|
| |b. En Netbeans ir a Team/clone y pegar la url copiada|
| |c. Seleccionar una carpeta local donde quedarán los archivos fuentes del proyecto|
| |d. Abrir el módulo company-logic|
| |e. Ir a la barra de menú de Netbeans Tools/Options/Java/Maven y allí seleccionar la opción
| |   SkipTest
| |f. Seleccionar el proyecto company-TallerPersistencia, click derecho e ir a checkout/checkout revision
| |g. click en select y el tags seleccionar **paso.1**
|2. Ejecutar las pruebas| |
||a. Seleccionar el archivo EmployeePersistenceTest.java|
||b.Click derecho **Test File**  |
||c. Debe aparecer el mensaje de que todas las pruebas se ejecutaron correctamente|
|3. Crear una entidad nueva| a. Company (id, name, descripción)|
| |b. Crear la clase de persistencia utilizando la misma unidad de persistencia|
| |c. Para obtener el archivo de pruebas, 
| |d. Seleccionar el proyecto company-TallerPersistencia, click derecho e ir a checkout/checkout revision
| |e. click en select y el tags seleccionar **paso.2**
| |f. ir a CompanyPersistenceTest.java|
| |g. Click derecho Test File |
