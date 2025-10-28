## 1. Paciente

**¿Qué es?**  
Es la persona que asiste a la clínica para recibir servicios odontológicos. Representa uno de los objetos principales del sistema.

**Atributos (características):**
Nombre, documento identidad, teléfono, correo electrónico, fecha de nacimiento.  

**Métodos (comportamientos):**
Recibir atencion medica, modificar información personal, agenda una nueva cita odontológica, cancelar cita odontologica, solicitar reagendamiento en citas.  

---

## 2. Odontólogo

**¿Qué es?**  
Es el profesional encargado de atender al paciente y realizar los procedimientos odontológicos.

**Atributos:**
Nombre, especialidad, horario de disponibilidad, teléfono, correo electronico.  

**Métodos:**
Realiza el procedimiento asignado, guarda la observación del paciente, cambia sus horas disponibles.

---

## 3. Cita Odontológica

**¿Qué es?**  
Es el registro que une al paciente con el odontólogo en una fecha y hora específicas para una atención determinada.

**Atributos:**
Numero de cita, fecha, hora, motivo, estado (pendiente, atendida, cancelada)  

**Métodos:**
Crea una nueva cita, elimina o marca como cancelada, actualiza la fecha u hora de la cita.  

---

## 4. Tratamiento

**¿Qué es?**  
Es el procedimiento odontológico que se aplica al paciente, como limpieza, ortodoncia, extracción, etc.

**Atributos:**
- id_tratamiento  
- tipo  
- descripción  
- costo  
- duración_estimada  

**Métodos:**
- `registrar_tratamiento()` → almacena un nuevo tratamiento  
- `calcular_costo_total()` → determina el valor según la duración o materiales  
- `generar_informe()` → muestra los detalles del tratamiento aplicado  

---

## 5. Factura

**¿Qué es?**  
Es el documento que refleja los costos de los servicios odontológicos prestados al paciente.

**Atributos:**
- id_factura  
- fecha_emisión  
- paciente  
- lista_servicios  
- total_pagar  

**Métodos:**
- `generar_factura()` → crea una nueva factura con los servicios del paciente  
- `aplicar_descuento()` → reduce el costo total  
- `imprimir_factura()` → muestra o exporta el documento para entrega  

---

## 💡 Conclusión

En la **Programación Orientada a Objetos (POO)**, cada elemento del mundo real puede representarse como un **objeto** con **atributos (datos)** y **métodos (acciones)**.  

En una clínica odontológica, estos objetos interactúan entre sí:  
un **paciente** solicita una **cita**, que es atendida por un **odontólogo**, que realiza un **tratamiento**, y finalmente se emite una **factura**.  

Este enfoque facilita la organización, reutilización y comprensión del sistema.

