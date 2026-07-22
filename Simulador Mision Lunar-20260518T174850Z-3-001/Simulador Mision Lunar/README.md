<div align="center">

# 🚀 PROGRAMADORES LUNARES 🌕

<img width="1920" height="600" alt="SIMULADOR DE PROGRAMADORES LUNARES" src="https://github.com/user-attachments/assets/504c98ec-29a6-4ec1-bd84-ed2be2370764" />

## Artemis II Mission Simulator

Simulador académico desarrollado en Java utilizando Orekit y JavaFX para recrear las principales fases de una misión lunar tipo Artemis II.

</div>

---

# 📖 Descripción del Proyecto

El **Artemis II Mission Simulator** es un proyecto académico cuyo objetivo es simular el recorrido de una misión lunar desde una órbita baja terrestre (LEO), la maniobra **Trans-Lunar Injection (TLI)**, el sobrevuelo de la Luna y el retorno libre hacia la Tierra.

La aplicación utiliza **Orekit** para el cálculo de la dinámica orbital y **JavaFX** para la visualización gráfica de la misión.

---

# 👨‍🚀 Integrantes

| Integrante | Rol |
|------------|------|
| Enmanuel Suriel | CDR |
| Jesús Polanco | FDO |
| Franklin Isaac Serrano | ARCH |
| John Mario Ventura Contreras | CAPCOM |
| Osvaldo Díaz | REQ |

---

# 🚀 Funcionalidades

- Simulación de órbita terrestre baja (LEO).
- Maniobra Trans-Lunar Injection (TLI).
- Propagación orbital utilizando Orekit.
- Sobrevuelo lunar.
- Retorno libre hacia la Tierra.
- Interfaz gráfica desarrollada en JavaFX.
- Visualización de la Tierra, Luna y nave espacial.
- Representación gráfica de la trayectoria.
- Panel de telemetría en tiempo real.
- Parámetros configurables por el usuario.
- Control de velocidad de simulación.

---

# 🖥️ Tecnologías Utilizadas

- Java 17
- JavaFX
- Maven
- Orekit
- Hipparchus
- Git
- GitHub

---

# 📂 Estructura del Proyecto

```
programadores-lunares/
│
├── Docs/
│   ├── ArquitecturaSimulacion.md
│   ├── ArquitecturaSistemas.md
│   ├── RequisitosTecnicos.md
│   ├── Riesgos.md
│   ├── SpikeTLI.md
│   ├── VistaLogica.md
│   ├── VistaProcesos.md
│   └── decisiones.md
│
├── Evidencias/
│   └── Entregable-4/
│
├── src/
│   └── main/java/com/nasa/simulador/
│
├── pom.xml
├── README.md
└── .gitignore
```

---

# ▶️ Requisitos

- Java JDK 17 o superior.
- Maven 3.9 o superior.
- JavaFX SDK.
- Conexión para descargar dependencias Maven.

---

# ⚙️ Compilación

Desde la raíz del proyecto ejecutar:

```bash
mvn clean package
```

---

# ▶️ Ejecución

Ejecutar:

```bash
mvn javafx:run
```

o ejecutar la clase principal desde el IDE.

---

# 🖥️ Interfaz Gráfica

La aplicación utiliza **JavaFX** para representar la misión espacial.

La interfaz permite visualizar:

- 🌍 Tierra
- 🌙 Luna
- 🚀 Nave espacial
- 🛰️ Trayectoria orbital

También incluye un panel de telemetría con información en tiempo real.

---

# 🎮 Controles del Simulador

## Ejecutar

Inicia la simulación completa de la misión.

## Reiniciar

Limpia la simulación y devuelve el sistema al estado inicial.

## Reproducir

Continúa la animación desde el punto actual.

## Pausar

Detiene temporalmente la simulación.

---

# ⚙️ Parámetros Configurables

El usuario puede modificar:

- Magnitud del impulso TLI.
- Tiempo del encendido.
- Altitud de la órbita inicial.
- Velocidad de simulación.

---

# 🚀 Velocidad de Simulación

La interfaz permite acelerar la simulación desde:

```
1× hasta 1000×
```

---

# 📊 Telemetría

Durante la simulación se muestran:

- Tiempo de misión.
- Altitud.
- Velocidad.
- Distancia a la Luna.
- Distancia a la Tierra.
- Estado de la misión.

---

# 📸 Evidencias

La carpeta **Evidencias** contiene:

- Capturas de la interfaz.
- Ejecución de la simulación.
- Evidencias de compilación.
- Resultados obtenidos.
- Material utilizado para la demostración.

---

# 📄 Documentación

Toda la documentación técnica se encuentra en la carpeta:

```
Docs/
```

Incluye:

- Arquitectura.
- Riesgos.
- Requisitos.
- Vista lógica.
- Vista de procesos.
- Decisiones de arquitectura.
- Spike TLI.

---

# 📦 Compilación Exitosa

El proyecto debe compilar correctamente mediante:

```bash
mvn clean package
```

sin errores ni advertencias críticas.

---

# 📌 Estado del Proyecto

🟢 En desarrollo

Entrega correspondiente al **Entregable #4** del Proyecto Simulador de Misión Lunar Artemis II.

---

# 📜 Licencia

Proyecto desarrollado con fines exclusivamente académicos para la asignatura Ingeniería de Software.
