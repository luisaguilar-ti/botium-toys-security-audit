# Evaluación de Riesgos — Botium Toys

## Resumen

Botium toys la empresa tiene multiples riesgo debido a controles que no son suficientes, tenemos malas practicas de acceso y asustencia de mecanismo de proteccion y recuperacion.

La auditoria encontre difencias relacionadas con los controles de acceso,cifrado , recuperacion amtes desastre y administracion de contrase;as, lo que aumenta el riesgo de exposcion de datos sensibles y posibles incumplimiewntos regulatorios.

---

# Riesgos identificados

## Falta de controles de acceso

Uno de los puntos que debemos recalcar de esta auditoria es que todos los usuarios tienen acceso a datos internos que son potencialmente sensibles de los clientes, tarjetas de credio eso quiere decir que no se esta cumpliendo los controles de minimo privilegio ni separaciones de funciones por empleado o puesto.

 # Impacto:
* Acceso no autorizado a informacion sensible.
* mayor riesgo de amenazas internas.
* Posible incumplimientos regulatorios.
  
---

# Ausencia de cifrado

La empresa no utiliza ningun tipo de cifrado para proteger la informacion de las tarjeta almacenadas, procesadas y transmitida.

# Impacto:
* Exposicion de informacion financiera.
* Riesgo de robo de datos.
* Incumplimiento de PCI DSS.
  
---

# Falta de sistema IDS

No existe un sistema de deteccion de instruiones (IDS) para el chequeo de trafico malioso o comportamiento de anamolias.

# Impacto : 
* Deteccion de ataques tardio.
* Mayor exposicion a amenazas externas.

---

# Ausencia de respaldos y recuperacion antes desastres.

La organizacion no cuenta con respaldos criticos ni planes de contigencia antes desastres.

# Impacto:
* Perdida de la iformacion critica.
* interrupcion de operaciones diarias.
* Riesgo a no continuar operando el negocio continuamente.

  ---

# Controles implementados

Actualmente la empresa si cuenta con algunos controles de seguridad:

* Firewall configurado
* software antivirus
* CCTV
* cerraduras fisicas
* Sistema de dettencion y prevencion de incendios
* Politicas de privavidad para GDPR

  ---

  # Nivel de riesgo
  
  En esta Evaluacion se determina que el nivel de riesgo es :
  
  # 8/10 — Riesgo Alto

  El Principal problema de identificacion es la falta de controles criticos relacionados con acceso, cifrado y recuperacion de informacion.

---
# Recomendaciones

* Implementar principio de minimo privilegio.
* Aplicar separacion de funciones.
* Implementar cifrado para infomracion sensible.
* Instalar IDS.
* Crear politicas modernas de contrase;a.
* Implementar respaldos periodicos.
* desarrollo de un plan de recuperacion antes algun desastre.
* Centralizar la administracion de contrase;as.
  
  
