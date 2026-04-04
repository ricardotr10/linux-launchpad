# 🚀 Launchpad con Rofi

Configura un estilo tipo *Launchpad* usando **Rofi** en Linux.

---

## 📦 Pre-Requisitos

Instala Rofi si aún no lo tienes:

```bash
sudo apt update
```

```bash
sudo apt install rofi
```

## ⚙️ Instalación paso a paso

### 🚀 Launchpad con Rofi

1 Crear el archivo .desktop

```ini
nano ~/.local/share/applications/launchpad.desktop
```

2 Crear carpeta de configuración de Rofi (si no existe)

```ini
mkdir -p ~/.config/rofi
```

3 Crear el tema .rasi

```ini
nano ~/.config/rofi/launchpad.rasi
```

4 (Opcional) Añadir icono

Coloca Launchpad.png en una ruta accesible y asegúrate de que esté bien referenciado en el .desktop.

## ▶️ Ejecutar Launchpad

Puedes abrirlo de dos formas:

🔍 Desde tu buscador de aplicaciones

Busca: Launchpad

💻 Desde terminal

```ini
rofi -show drun -theme ~/.config/rofi/launchpad.rasi
```
