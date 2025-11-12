# ✈️ Sistema de Gestión de Aerolínea

Aplicación desarrollada en **C# y .NET 8** que simula el funcionamiento de un sistema de gestión y venta de pasajes de una aerolínea.  
Forma parte del **Obligatorio de Programación 2** (Facultad de Ingeniería ORT Uruguay, Marzo 2025).

---

## 🧠 Descripción general
El sistema permite administrar los principales componentes de una aerolínea: **aviones, rutas, aeropuertos, vuelos, clientes y pasajes**.  
Incluye funcionalidades para **emitir pasajes**, **calcular precios**, **listar vuelos**, y **gestionar clientes** (ocasionales y premium).

---

## 🧩 Arquitectura del proyecto

El sistema se estructura en tres proyectos dentro de la solución:

| Proyecto | Descripción |
|-----------|--------------|
| 🧱 **Dominio** | Contiene las clases principales del modelo de negocio (Clientes, Administradores, Aviones, Aeropuertos, Rutas, Vuelos, Pasajes, etc.), las validaciones y la lógica de cálculo. |
| 💻 **Consola** | Interfaz de usuario por línea de comandos. Permite interactuar con el sistema: listar clientes, dar de alta nuevos, consultar vuelos y pasajes entre fechas. |
| 🌐 **WebApplication1 (MVC)** | Versión web del sistema (ASP.NET MVC). Permite visualizar y gestionar la información de forma más interactiva. |

---

## ⚙️ Funcionalidades principales

- Precarga automática de datos: administradores, clientes, aviones, aeropuertos, rutas, vuelos y pasajes.  
- Alta y listado de **clientes Premium y ocasionales** (con elegibilidad aleatoria).  
- Cálculo de **costo por asiento** y **precio final del pasaje** según tipo de cliente y equipaje.  
- Validaciones de negocio (frecuencia del vuelo, alcance del avión, etc.).  
- Listados de vuelos por aeropuerto y pasajes entre fechas.  
- Uso de **métodos polimórficos**.

---

## 🧰 Tecnologías utilizadas

- Lenguaje: **C# (.NET 8)**
- IDE: **Visual Studio 2022**
- Paradigmas: POO, herencia, polimorfismo, encapsulación
- Patrón de arquitectura: separación en capas (Dominio / Consola / Web)

---

## 🚀 Ejecución

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/SistemaAerolínea.git
