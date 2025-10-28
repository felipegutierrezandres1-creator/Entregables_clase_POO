# 💻 Actividad 2: Comparación de Paradigmas (Ejercicio 02)

## Instrucciones
- Investiga las diferencias entre **programación estructurada** y **programación orientada a objetos (POO)**.  
- Escribe un ejemplo conceptual de cómo se manejaría la información de una cita odontológica en:  
  1. Programación estructurada (usando variables sueltas y funciones).  
  2. Programación orientada a objetos (usando una clase).  

---

## 🧩 1. Diferencias entre Programación Estructurada y Programación Orientada a Objetos

| Característica | Programación Estructurada | Programación Orientada a Objetos (POO) |
|----------------|----------------------------|----------------------------------------|
| **Enfoque principal** | Se basa en funciones y procedimientos. | Se basa en clases y objetos. |
| **Organización del código** | El código se organiza en bloques de funciones o módulos. | El código se organiza en clases que agrupan datos (atributos) y comportamientos (métodos). |
| **Manejo de datos** | Los datos se manejan mediante variables globales o locales. | Los datos se encapsulan dentro de los objetos, mejorando la seguridad y reutilización. |
| **Reutilización de código** | Limitada; se logra reutilizar funciones. | Alta; se puede reutilizar mediante herencia y composición. |
| **Abstracción** | Menor nivel de abstracción; se trabaja directamente con funciones y datos. | Mayor nivel de abstracción; se modelan entidades del mundo real. |
| **Ejemplo típico** | C, Pascal. | Java, Python, C++, C#. |

---

## 🧠 2. Ejemplo Conceptual: Cita Odontológica

### 🧱 A. Programación Estructurada

En este paradigma, se utilizan variables sueltas y funciones que operan sobre ellas.  

```python
# Ejemplo de programación estructurada

# Variables sueltas
paciente_nombre = "Carlos Gómez"
fecha_cita = "2025-11-02"
hora_cita = "10:30 AM"
motivo = "Limpieza dental"

# Funciones separadas
def mostrar_cita(nombre, fecha, hora, motivo):
    print("=== CITA ODONTOLÓGICA ===")
    print("Paciente:", nombre)
    print("Fecha:", fecha)
    print("Hora:", hora)
    print("Motivo:", motivo)

def cambiar_hora(hora_nueva):
    global hora_cita
    hora_cita = hora_nueva
    print("La hora de la cita fue actualizada a:", hora_cita)

# Uso del código
mostrar_cita(paciente_nombre, fecha_cita, hora_cita, motivo)
cambiar_hora("11:00 AM")
mostrar_cita(paciente_nombre, fecha_cita, hora_cita, motivo)

