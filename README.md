<img width="947" height="84" alt="Captura de pantalla_2026-04-04_07-35-23" src="https://github.com/user-attachments/assets/8b118c57-04cd-4ebc-b60e-3225bce7aebd" />

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

1. Crear el archivo .desktop

```ini
nano ~/.local/share/applications/launchpad.desktop
```
  y pegas el codigo .desktop

2. Crear carpeta de configuración de Rofi (si no existe)

```ini
mkdir -p ~/.config/rofi
```

3. Crear el tema .rasi

```ini
nano ~/.config/rofi/launchpad.rasi
```
  y pegas el codigo .rasi

## ▶️ Ejecutar Launchpad

Puedes abrirlo de dos formas:

🔍 Desde tu buscador de aplicaciones

Busca: Launchpad

💻 Desde terminal

```ini
rofi -show drun -theme ~/.config/rofi/launchpad.rasi
```



4. (Opcional) Añadir icono

Coloca Launchpad.png en una ruta accesible y asegúrate de que esté bien referenciado en el .desktop.

primero busca el launchpad

<img width="600" height="551" alt="Captura de pantalla_2026-04-04_07-28-05" src="https://github.com/user-attachments/assets/8d281120-ad0f-49b3-821b-dfe3ccf6c8ac" />

click derecho y pon editar aplicacion

<img width="375" height="402" alt="Captura de pantalla_2026-04-04_07-29-17" src="https://github.com/user-attachments/assets/76698ae9-0a09-4502-95df-f0f63e4481db" />

asignas el icono que guardaste el [Launchpad.png](https://github.com/ricardotr10/linux-launchpad/blob/main/Launchpad.png) , lo guardas y lo arrastras al plank:

<img width="558" height="295" alt="Captura de pantalla_2026-04-04_07-33-36" src="https://github.com/user-attachments/assets/bba0536e-edd2-44d2-901c-1057676cfbb0" />

<img width="1920" height="1080" alt="imagen" src="https://github.com/user-attachments/assets/19893250-9bfa-474f-8fb6-22e17de12121" />

