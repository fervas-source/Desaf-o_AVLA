
### Desafío Técnico - Proceso Data Scientist - AVLA

## Objetivo
Determinar la probabilidad de que un cliente caiga en mora - Score de riesgo.

## Base de datos
900 observaciones
22 variables: 
    •Estado de cuenta corriente existente.
    •Duración en meses.
    •Historia crediticia.
    •Propósito del crédito.
    •Monto del crédito.
    •Ahorros en la cuenta.
    •Tiempo en el empleo actual .
    •Tasa a plazo en porcentaje de la renta disponible.
    •Estatus y sexo.
    •Otros deudores y garantes.
    •Tiempo desde el cual tiene residencia .
    •Posesiones a su nombre.
    •Edad en años.
    • Otros pagos pendientes en cuotas.
    •Forma en la que vive.
    •Número de créditos existentes en este banco actualmente.
    •Tipo de trabajo.
    •Número de personas por las cuales es responsable de dar mantenimiento (legalmente).
    •Si tiene teléfono.
    •Si es un trabajador extranjero.
    •Clasificación actual.
    
## Variable que determina probabilidad

•Calificación del cliente:
        1 -> Malo
        0 -> Bueno
        
## Modelamiento

Modelo Logístico 
 —> Probit
 —> Logit
 
 En función de criterio AIC se selecciona modelo Probit.