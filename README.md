# 🚀 AWS Developer Associate - Study Roadmap (Abril - Julio)

Este repositorio contiene el **plan de estudio detallado** para obtener la certificación **AWS Certified Developer Associate (DVA-C02)** y dominar la arquitectura Cloud.

---

# 📅 Estructura de la Semana

**Lunes a Viernes**

* 1 hora de teoría dirigida
* Laboratorios rápidos (Consola AWS)

**Sábados**

* 1 hora de Sesión de Mentoría
* Repaso de conceptos
* Debate de arquitecturas
* Preguntas tipo examen

**Domingos**

* 3 horas de Hands-on / Proyecto Real
* Implementación con Serverless Framework o Consola

---

# 🏗️ Módulo 1: Seguridad y Cómputo Serverless (Abril)

## Semana 1: IAM y el Core de Seguridad

### Tópicos

* Usuarios vs. Roles
* Políticas IAM (JSON: Effect, Action, Resource, Condition)
* Managed vs. Customer Policies
* Identity-based vs Resource-based
* Principio de Menor Privilegio

### Logro

Ser capaz de configurar el acceso de una aplicación sin usar Access Keys de administrador.

---

## Semana 2: Lambda - El Motor del Backend

### Tópicos

* Ciclo de Vida (Handler, Event Object, Context)
* Configuración (Memoria, Timeout, Variables de Entorno)
* Invocaciones:

  * Síncronas (API Gateway)
  * Asíncronas (S3, SNS)
  * Event Source Mapping (SQS, DynamoDB)
* Optimización:

  * Cold Starts
  * Lambda Layers
  * Concurrencia reservada vs provisionada

### Logro

Implementar una Lambda que procese archivos de S3 y manejar reintentos automáticos.

---

## Semana 3: API Gateway & AppSync

### Tópicos

* Tipos de API: REST vs HTTP
* Integraciones: Proxy vs No-Proxy
* Seguridad:

  * Lambda Authorizers
  * API Keys
  * Cognito Authorizers
* Stages (dev, prod)

### Logro

Exponer un microservicio seguro con Authorizer personalizado.

---

## Semana 4: Amazon Cognito

### Tópicos

* User Pools
* Identity Pools
* Custom Attributes

### Logro

Implementar login y permitir subir archivos a S3 solo a usuarios autenticados.

---

# 📦 Módulo 2: Data & Mensajería (Mayo)

## Semana 5: DynamoDB Experto

### Tópicos

* Partition Key vs Sort Key
* GSI vs LSI
* Consistencia eventual vs fuerte
* DynamoDB Streams

### Logro

Modelar base NoSQL para carrito de compras.

---

## Semana 6: S3 & CloudFront

### Tópicos

* Versionamiento
* Lifecycle Rules
* Encriptación (KMS)
* CloudFront
* OAI/OAC

### Logro

Configurar sitio estático con caché global.

---

## Semana 7: RDS, Aurora & RDS Proxy

### Tópicos

* RDS Proxy
* Aurora Serverless
* Multi-AZ vs Read Replicas

### Logro

Conectar Lambda a base SQL eficientemente.

---

## Semana 8: Mensajería (SQS, SNS & EventBridge)

### Tópicos

* SQS:

  * Standard vs FIFO
  * Visibility Timeout
  * DLQ
* SNS (Fan-out pattern)
* EventBridge

### Logro

Crear arquitectura desacoplada basada en eventos.

---

# 🏗️ Módulo 3: Infraestructura y DevOps (Junio)

## Semana 9: VPC para Developers

### Tópicos

* Subredes
* Internet Gateway
* NAT Gateway
* Security Groups vs NACL
* VPC Endpoints

### Logro

Configurar base de datos privada accesible desde Lambda.

---

## Semana 10: CI/CD

### Tópicos

* CodeCommit
* CodeBuild
* CodeDeploy
* CodePipeline
* Blue/Green
* Canary Deployments

### Logro

Automatizar despliegue de Lambda.

---

## Semana 11: Infraestructura como Código

### Tópicos

* CloudFormation
* AWS SAM
* AWS CDK

### Logro

Desplegar infraestructura con código.

---

## Semana 12: Observabilidad

### Tópicos

* CloudWatch
* Métricas
* Logs
* Alarmas
* AWS X-Ray

### Logro

Identificar cuellos de botella en arquitectura serverless.

---

# 🏁 Módulo 4: Refactorización y Examen (Julio)

## Semana 13: Refactorización y Migración

### Tópicos

* Re-hosting
* Re-platforming
* Refactoring
* AWS DMS

### Logro

Planificar migración a arquitectura escalable.

---

## Semana 14: Whitepapers y Mejores Prácticas

### Tópicos

* AWS Well-Architected Framework
* Caché
* CloudFront
* ElastiCache

### Logro

Evaluar arquitectura bajo estándares AWS.

---

## Semana 15-16: Simulacros Finales

### Actividades

* Exámenes de 65 preguntas
* Análisis de errores
* Repaso preguntas trampa

### Logro

Obtener más del 80% en simulacros.

---

# 🎯 Objetivo Final

Convertirme en **AWS Cloud Developer** con dominio en:

* Serverless
* Arquitecturas escalables
* DevOps
* Seguridad
* Event-driven systems
