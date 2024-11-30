# 🐳 Reto: Microservicios con Ingress en Kubernetes

## Descripción

Este reto consiste en implementar dos servicios REST simples y exponerlos utilizando **Ingress** en Kubernetes. 

| Lenguaje / Tecnología       | Ruta Ingress       | Respuesta Esperada         |
|-----------------------------|--------------------|----------------------------|
| **Java**                    | `/java`           | `Hello from Java`          |
| **Node.js o Python**        | `/node` o `/python` | `Hello from Node.js` o `Hello from Python` |

Tu misión será crear ambos servicios, desplegarlos en un clúster local de **Minikube** y configurarlos con **Ingress** para enrutar las solicitudes a las rutas correspondientes.

---

## Requisitos

| Recurso                | Detalles                          |
|------------------------|-----------------------------------|
| **Servicio en Java**    | Un microservicio REST que responda `"Hello from Java"`. |
| **Servicio en Node.js o Python** | Un microservicio REST que responda `"Hello from Node.js"` o `"Hello from Python"`. |
| **Kubernetes**         | Clúster local configurado con Minikube. |
| **Ingress**            | Configuración para enrutar `/java` a Java y `/node` o `/python` al segundo servicio. |

---

## Instrucciones

| Paso                      | Acción                                                              |
|---------------------------|---------------------------------------------------------------------|
| **1. Crear los servicios** | Implementa dos servicios REST en los lenguajes especificados.      |
| **2. Construir imágenes Docker** | Empaqueta ambos servicios en imágenes Docker listas para despliegue. |
| **3. Crear despliegues y servicios** | Despliega cada aplicación en Kubernetes y expónlas como servicios. |
| **4. Configurar Ingress** | Configura un recurso Ingress para enrutar `/java` y `/node` o `/python`. |
| **5. Probar la solución** | Accede a las rutas configuradas y verifica las respuestas.          |

---

## Resultados Esperados

| Ruta Visitada             | Respuesta                      |
|---------------------------|--------------------------------|
| `http://<minikube-ip>/java` | `Hello from Java`             |
| `http://<minikube-ip>/node` | `Hello from Node.js`          |
| `http://<minikube-ip>/python` | `Hello from Python` (si eliges Python) |

---

¡Buena suerte! 🚀 No olvides documentar tu proceso y compartir tu solución con la comunidad. 😊
