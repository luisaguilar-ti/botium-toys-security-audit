# botium-toys-security-audit
Internal security audit project based on the NIST Cybersecurity Framework.
# Botium Toys: Alcance, objetivos e informe de evaluación de riesgos

## Alcance y objetivos de la auditoría

### Alcance

El alcance de esta auditoría se define como todo el programa de seguridad de Botium Toys. Esto incluye sus activos, como los equipos y dispositivos de los empleados, su red interna y sus sistemas. Será necesario revisar los activos que posee Botium Toys, así como los controles y prácticas de cumplimiento que tienen implementados.

### Objetivos

Evaluar los activos existentes y completar la lista de controles y cumplimiento para determinar qué controles y mejores prácticas de cumplimiento deben implementarse para mejorar la postura de seguridad de Botium Toys.

---

# Activos actuales

Los activos administrados por el Departamento de TI incluyen:

* Equipos locales utilizados para las necesidades operativas de oficina.
* Equipos de empleados: dispositivos de usuario final (computadoras de escritorio/laptops, teléfonos inteligentes), estaciones de trabajo remotas, audífonos, cables, teclados, ratones, estaciones de acoplamiento, cámaras de vigilancia, etc.
* Productos disponibles para venta física y en línea, almacenados en el almacén adjunto de la empresa.
* Administración de sistemas, software y servicios: contabilidad, telecomunicaciones, bases de datos, seguridad, comercio electrónico y gestión de inventario.
* Acceso a internet.
* Red interna.
* Retención y almacenamiento de datos.
* Mantenimiento de sistemas heredados o fuera de ciclo de vida útil que requieren supervisión humana.

---

# Evaluación de riesgos

## Descripción del riesgo

Actualmente existe una administración inadecuada de activos. Además, Botium Toys no cuenta con todos los controles adecuados implementados y podría no cumplir completamente con las regulaciones y estándares nacionales e internacionales.

---

## Mejores prácticas de control

La primera de las cinco funciones del NIST CSF es “Identificar”. Botium Toys necesitará dedicar recursos para identificar correctamente sus activos y poder administrarlos adecuadamente. Además, será necesario clasificar los activos existentes y determinar el impacto que tendría la pérdida de dichos activos, incluyendo los sistemas, sobre la continuidad del negocio.

---

## Puntuación de riesgo

En una escala del 1 al 10, la puntuación de riesgo es de 8, lo cual se considera bastante alto. Esto se debe a la falta de controles y al incumplimiento de las mejores prácticas de cumplimiento.

---

# Comentarios adicionales

El impacto potencial derivado de la pérdida de un activo se considera medio, debido a que el departamento de TI no sabe exactamente qué activos podrían estar en riesgo.

El riesgo relacionado con la pérdida de activos o posibles multas regulatorias es alto, debido a que Botium Toys no cuenta con todos los controles necesarios y no cumple completamente con las mejores prácticas relacionadas con regulaciones de cumplimiento orientadas a mantener los datos críticos privados y seguros.

Revise los siguientes puntos para obtener detalles específicos:

* Actualmente, todos los empleados de Botium Toys tienen acceso a los datos almacenados internamente y podrían acceder a información de tarjetas de pago y datos personales/sensibles de clientes (PII/SPII).
* Actualmente no se utiliza cifrado para garantizar la confidencialidad de la información de tarjetas de crédito aceptada, procesada, transmitida y almacenada localmente en la base de datos interna de la empresa.
* No se han implementado controles de acceso relacionados con el principio de mínimo privilegio ni separación de funciones.
* El departamento de TI ha garantizado disponibilidad e implementado controles para asegurar la integridad de los datos.
* El departamento de TI cuenta con un firewall que bloquea tráfico según reglas de seguridad adecuadamente definidas.
* El software antivirus está instalado y es monitoreado regularmente por el departamento de TI.
* El departamento de TI no ha instalado un sistema de detección de intrusiones (IDS).
* Actualmente no existen planes de recuperación ante desastres y la empresa no cuenta con respaldos de datos críticos.
* El departamento de TI ha establecido un plan para notificar a clientes de la Unión Europea dentro de las primeras 72 horas en caso de una brecha de seguridad. Además, se han desarrollado e implementado políticas, procedimientos y procesos de privacidad para documentar y mantener adecuadamente los datos.
* Aunque existe una política de contraseñas, sus requisitos son mínimos y no cumplen con estándares modernos de complejidad (por ejemplo: mínimo ocho caracteres, combinación de letras, números y caracteres especiales).
* No existe un sistema centralizado de administración de contraseñas que haga cumplir los requisitos mínimos de la política de contraseñas, lo que en ocasiones afecta la productividad cuando empleados o proveedores necesitan recuperar o restablecer una contraseña mediante tickets al departamento de TI.
* Aunque los sistemas heredados son monitoreados y mantenidos, no existe un calendario regular para estas tareas y los métodos de intervención no están claramente definidos.
* La ubicación física de la tienda, que incluye oficinas principales, tienda y almacén, cuenta con cerraduras adecuadas, cámaras CCTV actualizadas y sistemas funcionales de detección y prevención de incendios.

