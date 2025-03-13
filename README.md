# Simulación de Difusión de Bulos en NetLogo

## 📌 **Descripción del Proyecto**
Este proyecto es una simulación desarrollada en **NetLogo** para modelar la propagación de un **bulo (noticia falsa)** dentro de una población con diferentes características sociodemográficas. El objetivo es estudiar cómo ciertos factores influyen en la propagación del bulo y cómo intervienen los verificadores para contrarrestarlo.

## 🎯 **Objetivo del Proyecto**
El modelo busca representar cómo las características individuales de las personas influyen en la probabilidad de que crean y difundan un bulo. Además, permite experimentar con distintos parámetros para observar cómo la difusión cambia en diferentes escenarios.

## ⚙️ **Características del Modelo**
- Los agentes (personas) tienen atributos como **ideología política, nivel educativo, confianza en la información y religión**.
- Se pueden configurar los porcentajes iniciales de creyentes del bulo, escépticos, inmunes, verificadores y neutrales mediante **sliders**.
- Se simula la propagación del bulo a través de **interacciones sociales**.
- Se pueden introducir verificadores que intentan **desmentir el bulo**.
- Los agentes se **mueven aleatoriamente** por el entorno.
- Se registra la evolución del bulo mediante **gráficos y monitores**.

## 🛠 **Cómo Ejecutar el Modelo en NetLogo**
### **1️⃣ Requisitos Previos**
- **Descargar e instalar NetLogo**: [Descargar NetLogo](https://ccl.northwestern.edu/netlogo/)
- **Abrir NetLogo y cargar el código del modelo**.

### **2️⃣ Configuración Inicial**
1. **Abrir NetLogo y cargar el código del modelo**.
2. **Configurar los sliders** en la pestaña **Interface**:
   - `% Creyentes` (`init-percent-believers`)
   - `% Escépticos` (`init-percent-skeptics`)
   - `% Inmunes` (`init-percent-immune`)
   - `% Verificadores` (`init-percent-verifiers`)
   - `% Neutrales` (`init-percent-neutral`)
3. **Añadir monitores** para visualizar los estados de la población.

### **3️⃣ Ejecución de la Simulación**
1. **Presionar `Setup`** para inicializar la simulación.
2. **Si se quiere iniciar manualmente el bulo, presionar `Start Bulo`**.
3. **Presionar `Go`** para comenzar la simulación y observar la difusión del bulo.

## 📊 **Visualización de Resultados**
- **Mapa de agentes**: Representa a las personas con diferentes colores según su estado:
  - 🔴 **Rojo**: Creyentes del bulo.
  - 🔵 **Azul**: Escépticos.
  - 🟢 **Verde**: Inmunes.
  - 🟡 **Amarillo**: Verificadores.
  - ⚫ **Gris**: Neutrales.
- **Gráficos**: Muestran la evolución del número de creyentes, escépticos y verificadores a lo largo del tiempo.
- **Monitores**: Muestran los porcentajes actuales de cada grupo.

## 🔄 **Parámetros Configurables**
Los siguientes parámetros pueden ajustarse mediante **sliders** en la interfaz:
- **Factores de probabilidad para creer en el bulo:**
  - Influencia de la **ideología política**.
  - Influencia del **nivel educativo**.
  - Influencia de la **confianza en la información**.
  - Influencia de la **religión**.
- **Distribución inicial de la población:**
  - Porcentaje de **creyentes del bulo**.
  - Porcentaje de **escépticos**.
  - Porcentaje de **inmunes**.
  - Porcentaje de **verificadores**.
  - Porcentaje de **neutrales**.

## 🚀 **Extensiones y Mejoras Futuras**
- Implementar **influencers o medios de comunicación** para acelerar o detener la difusión del bulo.
- Agregar **diferentes estructuras sociales** para ver cómo afectan la propagación (redes tipo "pequeño mundo", "aleatorias", etc.).
- Introducir **factores externos** como campañas de verificación.

## 📝 **Conclusión**
Este modelo permite explorar cómo se difunden los bulos y cómo intervienen los verificadores para frenarlos. Es una herramienta útil para **educación, investigación y experimentación** en el estudio de la desinformación.

---

📌 **Autor**: [Tu Nombre]  
📅 **Fecha**: [Fecha del Proyecto]  
🛠 **Tecnología utilizada**: NetLogo

