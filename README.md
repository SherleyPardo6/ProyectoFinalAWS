# Proyecto Final: AWS - Red Team

## Miembros del Equipo

<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/AnaGonzalezBueno.jpg" alt="Ana Gonzalez" width="150" height="150">
    <p>Ana González</p>
  </div>
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/AnaisReyes.jpg" alt="Anais Reyes" width="150" height="150">
    <p>Anaís Reyes</p>
  </div>
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/MariaDelCarmenFernadez.jpg" alt="Maria Del Carmen" width="150" height="150">
    <p>Mª del Carmen Fernández</p>
  </div>
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/MarPrietp.png" alt="Mar Prieto" width="150" height="150">
    <p>Mar Prieto</p>
  </div>
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/PaulaSanz.jpg" alt="Paula Sanz" width="150" height="150">
    <p>Paula Sanz</p>
  </div>
  <div style="text-align: center;">
    <img src="IntegrantesProyecto/SherleyJohanaPardo.jpg" alt="Sherley Johana Pardo" width="150" height="150">
    <p>Sherley Johana Pardo</p>
  </div>
</div>

## Objetivo del Proyecto
El cliente desea desplegar una web estática en AWS que cumpla con los siguientes requisitos:
- Alta disponibilidad: Garantizar que la caída de una zona de disponibilidad no afecte el servicio.
- Escalabilidad: Manejar incrementos en el tráfico sin interrupciones del servicio.

## Procedimiento
El proyecto se llevó a cabo siguiendo los pasos:

1. **Desarrollo de la web**: Implementación de una página estática sencilla.
2. **Creación de plantilla de lanzamiento**: Configuración inicial para el despliegue.
3. **Creación de grupo de Auto Scaling**: Ajuste automático del número de instancias según la demanda.
4. **Configuración del ELB (Elastic Load Balancer)**: Distribución del tráfico entre las instancias.
5. **Configuración de grupos de seguridad**: Políticas de acceso para EC2 y ELB.

## Diagrama de Arquitectura
![Diagrama de Arquitectura](architecture-diagram.png)

## Mejoras Propuestas para el Cliente
Se identificaron herramientas adicionales para optimizar la solución:
- **Amazon CloudFront**: CDN para una entrega más rápida de contenido.
- **Amazon RDS**: Base de datos administrada.
- **Amazon S3**: Almacenamiento para contenido estático.
- **AWS WAF**: Firewall para aplicaciones web.
- **Políticas avanzadas de Auto Scaling**: Escalado más eficiente y granular.
- **Route 53**: Gestión avanzada de DNS.

## Demo
Puedes ver una demostración del proyecto en AWS [aquí](https://youtu.be/vYToZIg20BM).

## Presupuesto
El proyecto fue diseñado para ser rentable, aprovechando los servicios escalables y de pago por uso de AWS.

![Presupuesto Arquitectura](PresupuestoAquitectura.png)

## Preguntas
Si tienes alguna consulta, no dudes en preguntar. ¡Gracias por tu atención!
