# 🌀 Laberinto Ontológico — Octavio Paz

> *"El mexicano no quiere o no puede ser su vecino, y cada vez que intenta serlo, vuelve sobre sí mismo, aún más solo."*
> — Octavio Paz, *El laberinto de la soledad* (1950)

Mapa mental ontológico e interactivo de **El laberinto de la soledad** de Octavio Paz, construido como un grafo con pesos sobre un canvas infinito. Creado por **Bogdan Rivera** como proyecto académico universitario.

🔗 **[Ver mapa en vivo →](https://bogdanrivera.github.io/laberinto-ontologico/)**

---

## Vista previa

![Mapa ontológico del Laberinto de la Soledad](https://github.com/user-attachments/assets/093957f4-de40-4c40-9238-b48fd639299b)
---

## ¿Qué es esto?

Una visualización filosófica y literaria que traduce las ideas centrales del ensayo de Paz en una red de conceptos interconectados. Cada **nodo** representa un concepto ontológico de la obra; cada **arista** representa una relación entre conceptos con un **peso del 1 al 10** que indica la intensidad de esa relación.

El canvas es infinito: el grafo se expande hacia las cuatro esquinas con ideas que irradian desde el eje central — *El Mexicano* — hacia regiones temáticas alejadas.

---

## Estructura del grafo

| Categoría | Color | Nodos representativos |
|-----------|-------|-----------------------|
| 🟡 Núcleo | `#c9922a` | El Mexicano |
| 🔴 Identidad | `#9b2335` | La Soledad, La Máscara, El Pachuco, El Otro |
| 🩵 Psique | `#2a9d8f` | La Chingada, El Hermetismo, La Zozobra |
| 🟣 Historia | `#7b52ab` | La Conquista, La Malinche, La Revolución, La Colonia |
| 🟠 Cultura | `#c47c2b` | La Fiesta, La Muerte, El Laberinto |
| 🟢 Modernidad | `#3d7a5e` | La Modernidad, El Estado, La Utopía |
| 🔵 Filosofía | `#4a7fb5` | La Comunión, La Apertura, El Tiempo, La Poesía |
| 🟤 Mito | `#8b5e3c` | Mundo Prehispánico, Coatlicue, Guadalupe, El Sacrificio |

**42 nodos · ~120 aristas con pesos**

---

## Interacción

| Acción | Resultado |
|--------|-----------|
| 🖱️ Arrastrar el canvas | Navegar por el espacio infinito |
| 🖱️ Scroll | Zoom in / out |
| 👆 Click en un nodo | Abre panel lateral con descripción, capítulo y conexiones |
| 👆 Click en una conexión del panel | Vuela suavemente al nodo conectado |
| ✋ Arrastrar un nodo | Reposicionar nodo individualmente |
| 🔘 Botones `+` / `−` / `↺` | Zoom y restablecer vista |

---

## Tecnologías

- **HTML5 Canvas** — renderizado del grafo y las animaciones
- **CSS3** — interfaz, panel lateral, tipografía, efectos visuales
- **JavaScript vanilla** — simulación de fuerzas, interacción, cámara
- **Google Fonts** — *Cinzel* (títulos) · *Cormorant Garamond* (texto)
- Sin dependencias externas · Sin frameworks · Un solo archivo

---

## Cómo usar localmente

```bash
# Clonar el repositorio
git clone https://github.com/bogdanrivera/laberinto-ontologico.git

# Abrir directamente en el navegador
open index.html
```

No requiere servidor ni instalación. Funciona directamente desde el sistema de archivos.

---


---

## Fuente académica

> Paz, Octavio. *El laberinto de la soledad*. México: Cuadernos Americanos, 1950.
> Edición ampliada con *Postdata* (1969) y *Vuelta a El laberinto de la soledad* (1975).

Los conceptos, descripciones y relaciones del grafo están basados en lectura directa de la obra. Los capítulos referenciados en cada nodo corresponden a la estructura del ensayo original.

---

## Autor

**Bogdan Rivera**
Proyecto académico universitario · Algoritmos y complejidad
