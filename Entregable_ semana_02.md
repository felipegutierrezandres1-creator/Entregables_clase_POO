## 1. Diferencias entre Programación Estructurada y Programación Orientada a Objetos

| Característica | Programación Estructurada | Programación Orientada a Objetos (POO) |
|----------------|----------------------------|----------------------------------------|
| **Enfoque principal** | Se basa en funciones y procedimientos. | Se basa en clases y objetos. |
| **Organización del código** | El código se organiza en bloques de funciones o módulos. | El código se organiza en clases que agrupan datos (atributos) y comportamientos (métodos). |
| **Manejo de datos** | Los datos se manejan mediante variables globales o locales. | Los datos se encapsulan dentro de los objetos, mejorando la seguridad y reutilización. |
| **Reutilización de código** | Limitada; se logra reutilizar funciones. | Alta; se puede reutilizar mediante herencia y composición. |
| **Abstracción** | Menor nivel de abstracción; se trabaja directamente con funciones y datos. | Mayor nivel de abstracción; se modelan entidades del mundo real. |
| **Ejemplo típico** | C, Pascal. | Java, Python, C++, C#. |

---
En este ejemplo utilizare el agendamiento de citas para una odontologia

## EJEMPLO CONCEPTUAL DE PROGRAMACION ESTRUCTURADA 

- Se definen las variables del programa ejemplo:  
  Paciente = Andres Gutierrez  
  Fecha = 27/10/2025  
  Hora = 7:30 AM  
  Motivo = Blanqueamiento dental  

- Se crea una función para mostrar los datos de la cita (se utiliza la función print).  
  CITA ODONTOLÓGICA  
  Paciente: Andres Gutierrez  
  Fecha: 27/10/2025  
  Hora: 7:30 AM  
  Motivo: Blanqueamiento dental  

- Se genera otra función para cambiar la hora de la cita.  
- Se crea otra función para reagendar la cita y mostrar el mensaje con la nueva información.  

---

## EJEMPLO CONCEPTUAL DE POO

- Se comienza por crear la clase y definir sus atributos:  
  Clase: cita_odontologica  
  Atributos: Nombre, fecha, hora, motivo.  

- A los atributos se le definen los métodos (acciones del objeto):  
  - Mostrar cita  
  - Cambiar hora  
  - Agendar Cita  

- Crear un objeto de tipo cita_odontologica:  
  Cita1 = cita_odontologica  

- Se llaman los métodos del objeto:  
  cita1.mostrarcita  
  cita1.cambiarhora  
  cita1.agendarcita  

