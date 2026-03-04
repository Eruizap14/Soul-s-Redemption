# Soul’s Redemption

![Unity](https://img.shields.io/badge/Engine-Unity-blue?logo=unity)
![Academic](https://img.shields.io/badge/Project-Educational-green)
![Year](https://img.shields.io/badge/Year-2026-orange)

## 🇪🇸 Español

### 🎮 Descripción General
**Soul’s Redemption** es un proyecto educativo desarrollado en **Unity** para la asignatura de *Programación Multimedia y Dispositivos Móviles* del 2º curso del grado de Desarrollo de Aplicaciones Multiplataforma (DAM).

El juego consiste en sobrevivir a oleadas de enemigos durante un máximo de **10 minutos**, mejorando al personaje a medida que obtiene experiencia y objetos.

---

### 🖥️ Flujo del Juego

#### 1️⃣ Title Screen
Pantalla inicial con tres opciones:
* **Comenzar:** Accede al menú de selección de arma.
* **Instrucciones:** Muestra las características y controles del juego.
* **Salir:** Cierra la aplicación.

#### 2️⃣ Menú de Selección de Arma
Permite elegir el arma inicial para comenzar la aventura:
* 🔥 **Piro**
* 🌌 **Gravedad**

#### 🕹️ Escena de Juego (Game Scene)
La interfaz principal incluye:
* ⏱️ **Temporizador:** La partida finaliza al alcanzar los 10 minutos.
* 🎒 **Inventario:** Ubicado en la esquina superior izquierda.
* 📊 **Barra de Experiencia:** Indicador de nivel en la parte superior.
* ❤️ **Barra de Vida:** Situada bajo el jugador para monitoreo rápido.

---

### 🔥 Mecánicas y Sistemas

* **Combate:** Los enemigos dañados parpadean en rojo y muestran el daño recibido.
* **Peligros:** Aparecen charcos de lava que infligen daño continuo por segundo.
* **Pausa (ESC):** Menú con estadísticas, opción de reanudar o volver al menú principal.

#### 💎 Sistema de Experiencia
Los enemigos sueltan gemas al ser derrotados:
| Gema | Valor de EXP |
| :--- | :--- |
| 🔵 Gema Azul | 100 EXP |
| 🟢 Esmeralda | 200 EXP |
| 🔴 Rubí | 350 EXP |
| 💎 Diamante | 500 EXP |

> **Subida de nivel:** El juego se pausa y permite elegir una mejora. Las mejoras son progresivas; una vez alcanzado el nivel máximo de una habilidad, esta dejará de aparecer en la lista.

#### 🧪 Objetos Especiales
* 🪨 **Roca Dorada:** Probabilidad de soltar pociones al destruirse.
* 🧴 **Pociones de Vida:** Curan **+20 HP** o **+50 HP**.

#### 👾 Variaciones de Enemigos
* 🟢 **Verde:** Suelta Esmeralda (100%).
* 🔵 **Azul:** Suelta Rubí (100%).
* 🟣 **Morado:** Suelta Diamante (100%).

---

### 🏁 Final del Juego
Tras sobrevivir a las oleadas, aparecerá el **Jefe Final**. Al derrotarlo, se muestra una pantalla de estadísticas con:
* Arma inicial utilizada.
* Objetos en el inventario.
* Nivel alcanzado y tiempo total.

---

## 🇬🇧 English

### 🎮 Overview
**Soul’s Redemption** is an educational Unity project developed for the *Multimedia Programming and Mobile Devices* course in the 2nd year of the Multiplatform Application Development (DAM) degree.

The goal is to survive waves of enemies for **10 minutes** while leveling up and upgrading your character.

---

### 🖥️ Game Flow

#### 1️⃣ Title Screen
* **Start:** Opens weapon selection.
* **Instructions:** Displays game features.
* **Exit:** Closes the game.

#### 2️⃣ Weapon Selection
Choose your starting power:
* 🔥 **Piro**
* 🌌 **Gravity**

---

### 💎 Progression & Mechanics
* **Leveling:** When the EXP bar fills, the game pauses for you to pick an upgrade. Maxed-out upgrades are removed from the pool.
* **Enemies:** Special colored variants (Green, Blue, Purple) have 100% drop rates for high-tier gems.
* **Endgame:** Defeat the final boss to see your summary (Weapon, Inventory, Level, and Time).

---
**🎓 Educational project – 2º DAM – 2026**
