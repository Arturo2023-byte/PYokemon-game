# pokemon-game
este es un juego basico y perfecto para practica en el github.

# 🕹️ Pyokemon CLI

**Pyokemon CLI** es un juego de Pokémon por consola hecho en Python. Está diseñado como una práctica educativa para aprender estructuras de datos, modularidad y trabajo con archivos. Inspirado en el universo Pokémon, cuenta con combates, exploración, efectos sonoros y almacenamiento en la nube.

---

## 📦 Requisitos

- Python 3.10 o superior
- Linux, macOS o WSL (recomendado)
- Git (opcional, para clonar el repositorio)
- Conexión a internet (solo si se usa Dropbox)

---

## 📥 Instalación

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/Arturo2023-byte/pokemon-game.git
   cd pokemon-game
   
## Crea y activa un entorno virtual:
python3 -m venv venv
 source venv/bin/activate

Instala las dependencias:
pip install -r requirements.txt

  Si no tienes mpg123 (necesario para el sonido), instálalo con:
        sudo apt install mpg123

Ejecuta el juego con:
              python3 main.py

              
🎮 Características del juego: 

✅ Menú interactivo por consola

✅ Batallas contra pokémon salvajes

✅ Recolección y almacenamiento de pokémon

✅ Módulo de música de fondo y efectos de sonido

✅ Opcional: sincronización con Dropbox

✅ Colores y animaciones en texto gracias a fabulous y colored

Estructura del proyecto:

pokemon-game/
├── main.py              # Punto de entrada del juego
├── menu.py              # Menú principal
├── pokemon.py           # Clases y funciones de Pokémon
├── route1.py            # Primera ruta del juego
├── interfaz.py          # Funciones visuales de consola
├── musica.py            # Control de música y efectos de sonido
├── modulo_dropbox.py    # Opcional: guardado en Dropbox
├── sonidos/             # Carpeta de sonidos .wav o .mp3
├── music/               # Música de fondo
└── README.md            # Este archivo

🔊 Soporte de sonido
Por defecto, el juego usa:

+ afplay en macOS

+ mpg123 en Linux/WSL (recomendado)

       Puedes modificar el archivo musica.py para usar otros reproductores como aplay o ffplay.

       Nota: Si tienes problemas con el sonido, puedes desactivarlo comentando la línea musica.initMusica() en main.py.

☁️ Sincronización con Dropbox (Opcional):
El juego permite guardar progreso o datos en Dropbox. Para activarlo:

Asegúrate de tener una clave de acceso API de Dropbox.

Configura la clave en modulo_dropbox.py.

Llama a modulo_dropbox.initDropbox() desde main.py.

Desactivar características opcionales:

Si deseas desactivar música o Dropbox, comenta estas líneas en main.py:
# musica.initMusica()
# modulo_dropbox.initDropbox()

📄 Licencia
Proyecto académico sin fines comerciales. Basado en el universo Pokémon, propiedad de Nintendo/GameFreak.

✨ Autor
Desarrollado por Arturo2023-byte
Colaboración y asistencia: ChatGPT


