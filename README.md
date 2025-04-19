# 🎨 Aplicación Gráfica en .NET (WinForms)

Este proyecto es una aplicación de escritorio desarrollada en **C#** con **Windows Forms (WinForms)** que permite al usuario generar y visualizar figuras geométricas básicas como triángulos, cuadrados o círculos a partir de un número determinado de puntos aleatorios.

## 🧠 Descripción del Proyecto

La aplicación tiene como objetivo principal **dibujar figuras geométricas básicas** mediante la generación de puntos aleatorios en un área gráfica. Incluye funcionalidades para validar la entrada del usuario, seleccionar el tipo de figura a dibujar y aplicar una matriz (por defecto, la identidad) para futuras transformaciones.

---

## 🚀 Características Principales

- Ingreso del número de puntos a usar para crear la figura.
- Selección del tipo de figura: **Triángulo**, **Cuadrado**, o **Círculo**.
- Generación de puntos aleatorios para formar la figura.
- Dibujo gráfico dinámico de la figura elegida.
- Aplicación de una **matriz de transformación 3x3** (actualmente identidad).
- Validaciones automáticas de entradas del usuario.
- Interfaz intuitiva con controles simples: `TextBox`, `ComboBox` y `Button`.

---

## 🖥️ Tecnologías Utilizadas

- Lenguaje: **C#**
- Framework: **.NET Framework**
- Interfaz: **Windows Forms (WinForms)**

---

## 📂 Estructura de la Aplicación

| Archivo/Clase       | Descripción |
|---------------------|-------------|
| `Program.cs`        | Punto de entrada principal. Lanza `Form1`. |
| `Form1.cs`          | Lógica del formulario principal. Contiene eventos, generación de puntos, dibujo y validaciones. |
| `Form1.Designer.cs` | Archivo autogenerado que define los componentes visuales. |

---

## 🧩 Funcionalidades de la Interfaz

| Componente     | Funcionalidad |
|----------------|---------------|
| `TextBox`      | Ingresar el número de puntos para la figura. Solo acepta dígitos. |
| `ComboBox`     | Seleccionar el tipo de figura (Triángulo, Cuadrado, Círculo). |
| `Button`       | Dibuja la figura con los puntos generados aleatoriamente. |
| `OnPaint`      | Redibuja la figura elegida y marca los puntos con pequeños círculos. |
---

## ✅ Requisitos

- Visual Studio (2019 o superior recomendado)
- .NET Framework 4.x
- Windows OS

---

## ▶️ Cómo Ejecutar

1. Clona el repositorio:
2. Abre el proyecto en Visual Studio.
3. Ejecuta el proyecto con F5 o desde el botón Start.
