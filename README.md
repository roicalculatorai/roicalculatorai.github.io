# 🌉 Calculadora de ROI (Retorno de la Inversión) - SAP Value Bridge

Este repositorio aloja la herramienta **SAP Value Bridge - Edición Joule**, una calculadora web para el Retorno de la Inversión (ROI). Esta herramienta está diseñada para demostrar los beneficios financieros y las ganancias de productividad que se obtienen al implementar **SAP Joule**, cuantificando el ahorro potencial y el retorno del proyecto.

La calculadora está activa y se puede acceder a ella en: [https://roicalculatorai.github.io/](https://roicalculatorai.github.io/)

---

## ✨ Características Principales

* **Controles Interactivos:** Utiliza **controles deslizantes** para ajustar métricas empresariales clave (usuarios SAP, coste de empleados, tiempo diario en SAP).
* **Inversión Personalizada:** Permite introducir los costes específicos de inversión para consultoría y servicios (**Inversión Servicios**).
* **Cálculo Instantáneo del ROI:** Calcula y muestra automáticamente tres métricas clave:
    * **Ahorro Anual:** El total estimado de ahorro financiero por año debido al aumento de la productividad.
    * **ROI del Proyecto:** El porcentaje de retorno de tu inversión inicial.
    * **Período de Recuperación (Payback Period):** El tiempo necesario para que el ahorro cubra el coste inicial del proyecto.
* **Proyección Financiera:** Un **gráfico de línea dinámico** visualiza el balance financiero acumulado durante un período de 12 meses.
* **Basado en Datos:** Los cálculos se basan en métricas oficiales de eficiencia del SAP Discovery Center, incluyendo mejoras como "**Búsqueda un 95% más rápida**" y "**Navegación un 90% más rápida**".
* **Generación de Leads:** Los resultados se muestran inicialmente difuminados y se revelan después de que el usuario proporciona una **dirección de correo electrónico**.

---

## 📝 Cómo Usar

1.  Navega a [https://roicalculatorai.github.io/](https://roicalculatorai.github.io/).
2.  Ajusta los controles deslizantes bajo **Datos del Cliente** para reflejar las especificaciones de tu empresa:
    * **Usuarios SAP:** Número de empleados que utilizan SAP.
    * **Coste Empleado / Año:** Salario anual promedio de un empleado.
    * **Tiempo diario en SAP:** El porcentaje de un día laboral que un usuario promedio dedica al ERP de SAP.
3.  Introduce el coste único estimado para consultoría y servicios en el campo **Inversión Servicios**.
4.  En el panel de la derecha, **ingresa tu dirección de correo electrónico** para desbloquear y ver los resultados calculados.
5.  Analiza el **Ahorro Anual**, el **ROI del Proyecto**, el **Tiempo de Recuperación** y el gráfico de **Proyección Financiera**.

---

## 💻 Pila Tecnológica

* **Frontend:** HTML5
* **Estilismo:** Tailwind CSS
* **Lógica:** Vanilla JavaScript
* **Gráficos:** Chart.js