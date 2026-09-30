# XR Interaction Challenge

## Datos del estudiante

- **Apellidos y nombres:** Choquehuanca Capia Angel Fabian
- **Código del estudiante:** 2231891328
- **Curso:** Laboratorio de Realidad Extendida (XR) para Videojuegos
- **Docente:** Victor Alejandro Arroyo Castro
- **Universidad:** Universidad Autónoma del Perú – Ingeniería de Software

---

## Descripción del proyecto

Experiencia interactiva desarrollada en Unity que representa una pequeña sala de entrenamiento XR. El usuario puede moverse por el escenario e interactuar con tres objetos 3D utilizando el **XR Interaction Toolkit**. Al no contar con un visor físico, las pruebas se realizan con el **XR Interaction Simulator**, que emula la cabeza y los controladores con teclado y ratón.

El proyecto se centra en la correcta configuración del entorno XR y en el funcionamiento de las interacciones, no en la complejidad gráfica.

---

## Funcionalidades implementadas

- Escena propia **EC_XR_ApellidoNombre** con piso, iluminación, límites visuales y cinco objetos 3D.
- Interacción con **3 objetos** mediante XR Interaction Toolkit:
  - **Objeto 1:** [ej. Cubo] – manipulable con *XR Grab Interactable* y *Rigidbody*.
  - **Objeto 2:** [ej. Esfera] – manipulable con *XR Grab Interactable* y *Rigidbody*.
  - **Objeto 3:** [ej. Cilindro / interruptor] – [describir la interacción: agarrar, rayo, cambio de color, etc.].
- Interacción a distancia mediante rayo (*XR Ray Interactor*): [describir: encender/apagar luz, cambiar color, abrir puerta, etc.].
- Reto libre: [describir: teletransporte, lanzamiento de objetos, UI espacial, contador, etc.].

> Ajusta esta sección a lo que realmente implementaste en tu escena.

---

## Controles / instrucciones de uso

La experiencia se ejecuta con el **XR Interaction Simulator** (teclado y ratón). Presiona **Play** en Unity y usa:

| Acción | Control |
|---|---|
| Mover al jugador | `W` `A` `S` `D` |
| Girar la vista | Mover el ratón |
| Controlar el mando izquierdo | Mantener `Shift izquierdo` |
| Controlar el mando derecho | Mantener `Espacio` |
| Alternar entre cabeza y mandos | `Tab` |
| Agarrar objeto (Select) | Clic izquierdo del ratón |
| Interacción con el rayo | Apuntar al objeto y clic izquierdo |

> Los controles exactos aparecen en el panel del propio simulador durante la ejecución. Verifica que coincidan con tu versión.

**Pasos para probar:**
1. Abrir el proyecto en Unity.
2. Abrir la escena `Assets/Scenes/EC_XR_ApellidoNombre.unity`.
3. Presionar **Play**.
4. Acercarse a los objetos, agarrarlos y soltarlos, y usar el rayo para la interacción a distancia.

---

## Capturas de pantalla

**1. Vista general del escenario**

![Vista general](Capturas/01_escenario.png)

**2. Configuración XR y componentes en el Inspector**

![Inspector](Capturas/02_inspector.png)

**3. Interacción funcionando**

![Interacción](Capturas/03_interaccion.png)

> Crea una carpeta `Capturas` en la raíz del repositorio, guarda ahí las imágenes y verifica que los nombres coincidan con los de arriba.

---

## Video demostrativo (máx. 1 minuto)

[Ver video](PEGA-AQUI-EL-ENLACE-DEL-VIDEO)

---

## Tecnologías y paquetes utilizados

- **Unity** [versión, ej. 6000.0.x / 2022.3.x LTS]
- **Universal Render Pipeline (URP)**
- **XR Interaction Toolkit** [versión]
- **XR Plugin Management**
- **XR Interaction Simulator** (sample del XR Interaction Toolkit)
- **Input System**

---

## Estructura del repositorio

```
├── Assets/
├── Packages/
├── ProjectSettings/
├── Capturas/
└── README.md
```
