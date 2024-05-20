Introducción
Este proyecto tiene como objetivo diseñar e implementar una libreta de direcciones utilizando técnicas de programación orientada a objetos (POO) en Python. La aplicación contará con un menú interactivo para realizar las siguientes operaciones sobre los contactos:

Búsqueda por nombre, apellido o número de teléfono
Consulta de información de un contacto
Creación de nuevos contactos
Eliminación de contactos
Modificación de datos de contactos
Requisitos de la Aplicación
Las clases necesarias para la libreta de direcciones son:

Contacto: Representa un registro individual en la libreta de direcciones, almacenando información como nombre, apellido, teléfono, dirección y empleo.
Libreta: Gestiona la colección de contactos, permitiendo operaciones como búsqueda, creación, eliminación y modificación.
El enfoque OO se considera adecuado por las siguientes razones:

Modularidad: Permite dividir la lógica en clases independientes y reutilizables.
Encapsulación: Oculta la implementación interna de cada clase, protegiendo los datos y facilitando el mantenimiento.
Reutilización: Promueve la creación de componentes reutilizables en futuros proyectos.
Plan de Desarrollo
Se propone utilizar un modelo de desarrollo ágil, como Scrum o Kanban, debido a la naturaleza evolutiva de la aplicación. Este enfoque permite una rápida adaptación a cambios y la entrega incremental de funcionalidades.

Gestión de Bugs: Se utilizará un sistema de seguimiento de bugs, como Jira o Trello, para registrar, priorizar y resolver los errores encontrados durante el desarrollo.

Crecimiento del Programa: La aplicación se segmentará en módulos funcionales, permitiendo un desarrollo iterativo y la incorporación de nuevas funcionalidades de forma gradual.

Pruebas Unitarias: Se implementarán pruebas unitarias para verificar el correcto funcionamiento de cada módulo y clase de la aplicación.

Diseño Funcional
Pseudocódigo:

Python
def main():
    libreta = Libreta()

    while True:
        mostrarMenu()
        opcion = input("Seleccione una opción: ")

        if opcion == "1":
            buscarContacto(libreta)
        elif opcion == "2":
            consultarContacto(libreta)
        elif opcion == "3":
            crearContacto(libreta)
        elif opcion == "4":
            eliminarContacto(libreta)
        elif opcion == "5":
            modificarContacto(libreta)
        elif opcion == "0":
            salir()
        else:
            print("Opción no válida.")

def buscarContacto(libreta):
    # Implementar búsqueda por nombre, apellido o teléfono
    pass

def consultarContacto(libreta):
    # Implementar consulta de información de un contacto
    pass

def crearContacto(libreta):
    # Implementar creación de un nuevo contacto
    pass

def eliminarContacto(libreta):
    # Implementar eliminación de un contacto
    pass

def modificarContacto(libreta):
    # Implementar modificación de datos de un contacto
    pass

def mostrarMenu():
    # Mostrar opciones del menú
    pass

def salir():
    # Terminar la ejecución del programa
    pass
Usa el código con precaución.
content_copy
Flujos de Datos:

El usuario interactúa con la aplicación a través del menú de texto.
Las operaciones sobre los contactos se realizan utilizando las funciones correspondientes.
La información de los contactos se almacena en la libreta.
Requisitos:

La aplicación debe ser fácil de usar y tener un menú intuitivo.
Las operaciones sobre los contactos deben ser eficientes y confiables.
La información de los contactos debe almacenarse de manera segura y persistente.
Modelos de Desarrollo:

Se propone utilizar un modelo de desarrollo ágil, como Scrum o Kanban.
Se utilizará un sistema de control de versiones, como Git, para gestionar el código fuente.
Implementación
La aplicación se implementará en Python, utilizando las siguientes librerías:

collections: Para la gestión de colecciones de datos.
os: Para funciones básicas del sistema operativo.
La aplicación se distribuirá en módulos que contengan las clases por tipo, utilizando la instrucción import para incluir las dependencias necesarias en cada módulo.

Se implementarán pruebas unitarias utilizando el módulo unittest de Python para verificar el correcto funcionamiento de la lógica de la aplicación.
