

````md
# 🎮 Example-Tetris

Juego clásico de **Tetris** desarrollado por **ZaBaDeVgit**.  
Una versión de ejemplo para aprender la lógica de juego, la gestión de gráficos y la estructura básica de un Tetris.

---

## 📸 Captura de pantalla

![Captura del juego](assets/screenshot.png)  
*(Reemplaza `assets/screenshot.png` por la ruta de tu propia captura dentro del repo)*

---

## ✨ Características

- Generación aleatoria de tetrominós  
- Rotación de piezas, desplazamiento lateral y caída  
- Comprobación de colisiones  
- Eliminación de líneas completas  
- Control de niveles / velocidad progresiva  
- Reinicio de partida cuando se llena la zona superior  
- Pantalla de “Game Over”  

---

## 🧰 Tecnologías / Requisitos

- Lenguaje: **C#**  
- Plataforma: **.NET (ej: .NET 6)**  
- Sistema operativo: Windows / Linux / macOS  
- IDE recomendado: Visual Studio o VS Code  
- Dependencias: ninguna adicional (solo .NET)

---

## 🏃 Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/ZaBaDeVgit/Example-Tetris.git
````

2. Abrir el proyecto en tu IDE.
3. Restaurar paquetes si es necesario.
4. Compilar y ejecutar.

Con línea de comandos:

```bash
dotnet build
dotnet run --project Tetris/Tetris.csproj
```

---

## ⌨️ Controles

* ⬅️ Flecha izquierda → mover a la izquierda
* ➡️ Flecha derecha → mover a la derecha
* ⬇️ Flecha abajo → caída suave
* ⬆️ Flecha arriba → rotar pieza
* ␣ Barra espaciadora → caída rápida (*hard drop*)
* P → pausar
* R → reiniciar partida

---

## 📈 Lógica del juego

1. **Tablero**: matriz 2D que representa el área de juego
2. **Tetrominós**: definición de formas y rotaciones
3. **Generador**: cola de piezas aleatorias
4. **Movimiento / colisión**: evita salir de límites o solapar piezas
5. **Bloqueo**: fija la pieza al no poder descender
6. **Eliminación de líneas**: borra y desciende filas superiores
7. **Dificultad**: aumenta progresivamente la velocidad
8. **Estados**: ejecución, pausa, *Game Over*

---

## ✅ Estado del proyecto

| Funcionalidad         | Estado       |
| --------------------- | ------------ |
| Movimiento lateral    | ✅            |
| Rotación de piezas    | ✅            |
| Caída progresiva      | ✅            |
| Eliminación de líneas | ✅            |
| Próxima pieza / hold  | ⚠️ Pendiente |
| Sonido / música       | ⚠️ Pendiente |
| Ranking de puntuación | ⚠️ Pendiente |

---

## 🧩 Contribuciones

1. Haz un **fork** del repositorio
2. Crea una rama: `feature/nueva-funcionalidad`
3. Haz tus commits
4. Envía un *pull request*

---

## 📄 Licencia

Distribuido bajo licencia **MIT**.
Consulta el archivo `LICENSE` para más detalles.

---

## 🧾 Créditos

* Inspirado en el clásico Tetris
* Implementación educativa y de ejemplo por **ZaBaDeVgit**

---

## 🚀 Ideas futuras

* Añadir efectos de sonido / música retro
* Guardado de récords en archivo o base de datos
* Interfaz gráfica con animaciones
* Modo multijugador local o en línea
* Fondos personalizados por nivel



