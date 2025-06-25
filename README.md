# Observabilidad y monitoreo I

## Tabla de contenido

- [Introducción a monitoreo y observabilidad](#introduccion-a-monitoreo-y-observabilidad)
  - [Definición y diferencias](#definicion-y-diferencias)
  - [¿Por qué ambos son necesarios?](#por-que-son-necesarios)
    - [Beneficios al implementarlos](#beneficios-de-monitoreo-y-observabilidad)
  - [Pilares de la observabilidad](#pilares-de-observabilidad)
    - [Métricas](#metricas)
    - [Logs](#logs)
    - [Trazas](#trazas)
- [Spring Boot Actuator](#spring-boot-actuator)
  - [Endpoints Integrados](#endpoints-integrados)
    - [Endpoint /health](#endpoint-health)
    - [Endpoint /info](#endpoint-info)
    - [Endpoint /metrics](#endpoint-metrics)
    - [Endpoints beans, env, loggers y otros más](#otros-endpoints)
  - [Configuración y seguridad](#configuracion-y-seguridad-para-actuator)
    - [Habilitando y asegurando endpoints específicos](#asegurando-endpoints-de-actuator)
    - [Personalización de endpoints](#personalizacion-de-endpoints)
  - [Métricas con Micrometer](#metricas-con-micrometer)
    - [Tipos de métricas](#tipos-de-metricas)
    	- [Contadores](#contadores)
    	- [Medidores](#medidores)
    	- [Temporizadores](#temporizadores)
    	- [Histogramas](#histogramas)
    	- [¿Cuándo usar cada uno?](#cuando-usar-cada-uno)
  - [Métricas por defecto con Spring Boot Actuator](#metricas-por-defecto-de-spring-actuator)
  - [Métricas personalizadas](#metricas-personalizadas)
  - [Exportando métricas a Grafana](#exportando-metricas-a-grafana)
  - [Exportando métricas a Prometheus](#exportando-metricas-a-prometheus)
- [Gestión de Logs en Spring Boot](#gestion-de-logs)
  - [Conceptos Básicos de Logging](#conceptos-basicos-de-logging)
    - [Logback/SLF4J](#sl4j)
    - [Niveles de logs](#niveles-de-logs)
        - [INFO, DEBUG, WARN, ERROR](#info-debug-warn-error)
        - [¿Cuándo utilizar cada nivel?](#cuando-utilizar-cada-nivel)
  - [Configuración del Logging](#configuracion-de-logging)
    - [Configuración dentro del application.properties](#configuracion-en-properties)
    - [Appenders](#appenders)
    - [Formatos de logs](#formatos-de-logs)
    - [Buenas prácticas en Logging](#buenas-practicas-en-logging)
    	- [¿Qué loguear y qué no?](#no-todo-se-loguea)
    	- [Contextualización básica](#contextualizacion-basica)
  - [Centralización de Logs](#centralizacion-de-logs)
    - [Uso de la herramienta Grafana Loki](#grafana-loki)
- [Visualización de métricas y logs con un proyecto real de Spring Boot](#logs-y-metricas-en-un-proyecto-de-spring)


<a id="introduccion-a-monitoreo-y-observabilidad"></a>
## Introducción a monitoreo y observabilidad

<a id="definicion-y-diferencias"></a>
### Definición y diferencias

<a id="por-que-son-necesarios"></a>
### ¿Por qué ambos son necesarios?

<a id="beneficios-de-monitoreo-y-observabilidad"></a>
#### Beneficios al implementarlos
      
<a id="pilares-de-observabilidad"></a>
### Pilares de la observabilidad

<a id="metricas"></a>
#### Métricas

<a id="logs"></a>
#### Logs

<a id="trazas"></a>
#### Trazas

<a id="spring-boot-actuator"></a>
## Spring Boot Actuator

<a id="endpoints-integrados"></a>
### Endpoints Integrados

<a id="endpoint-health"></a>
#### Endpoint /health

<a id="endpoint-info"></a>
#### Endpoint /info

<a id="endpoint-metrics"></a>
#### Endpoint /metrics

<a id="otros-endpoints"></a>
#### Endpoints beans, env, loggers y otros más

<a id="configuracion-y-seguridad-para-actuator"></a>
### Configuración y seguridad

<a id="asegurando-endpoints-de-actuator"></a>
#### Habilitando y asegurando endpoints específicos

<a id="personalizacion-de-endpoints"></a>
#### Personalización de endpoints

<a id="metricas-con-micrometer"></a>
### Métricas con Micrometer

<a id="tipos-de-metricas"></a>
#### Tipos de métricas

<a id="contadores"></a>
##### Contadores

<a id="medidores"></a>
##### Medidores

<a id="temporizadores"></a>
##### Temporizadores

<a id="histogramas"></a>
##### Histogramas

<a id="cuando-usar-cada-uno"></a>
##### ¿Cuándo usar cada uno?

<a id="metricas-por-defecto-de-spring-actuator"></a>
### Métricas por defecto con Spring Boot Actuator

<a id="metricas-personalizadas"></a>
### Métricas personalizadas

<a id="exportando-metricas-a-grafana"></a>
### Exportando métricas a Grafana

<a id="exportando-metricas-a-prometheus"></a>
### Exportando métricas a Prometheus

<a id="gestion-de-logs"></a>
## Gestión de Logs en Spring Boot

<a id="conceptos-basicos-de-logging"></a>
### Conceptos Básicos de Logging

<a id="sl4j"></a>
#### Logback/SLF4J

<a id="niveles-de-logs"></a>
#### Niveles de logs

<a id="info-debug-warn-error"></a>
##### INFO, DEBUG, WARN, ERROR

<a id="cuando-utilizar-cada-nivel"></a>
##### ¿Cuándo utilizar cada nivel?

<a id="configuracion-de-logging"></a>
### Configuración del Logging

<a id="configuracion-en-properties"></a>
#### Configuración dentro del application.properties

<a id="appenders"></a>
#### Appenders

<a id="formatos-de-logs"></a>
#### Formatos de logs

<a id="buenas-practicas-en-logging"></a>
#### Buenas prácticas en Logging

<a id="no-todo-se-loguea"></a>
##### ¿Qué loguear y qué no?

<a id="contextualizacion-basica"></a>
##### Contextualización básica

<a id="centralizacion-de-logs"></a>
### Centralización de Logs

<a id="grafana-loki"></a>
#### Uso de la herramienta Grafana Loki

<a id="logs-y-metricas-en-un-proyecto-de-spring"></a>
## Visualización de métricas y logs con un proyecto real de Spring Boot
