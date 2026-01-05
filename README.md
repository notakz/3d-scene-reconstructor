# 3d-scene-reconstructor
3d reconstr
# 🌟 3D Scene Reconstructor

Aplikacja do rekonstrukcji przestrzennej sceny 3D z pojedynczego zdjęcia z interaktywnym viewerem.

## ✨ Możliwości

- 🖼️ Wczytanie pojedynczego zdjęcia
- 🎯 Automatyczna estymacja głębi (depth estimation)
- 🌐 Generowanie pełnej sceny 3D (Gaussian Splatting)
- 🎮 Interaktywny viewer z kontrolą kamery:
  - Pełna rotacja 360°
  - Widoki z góry, z boku, z przodu
  - Tryb FPS - wejście w scenę
  - Regulacja głębi i FOV

## 🚀 Technologie

- **VistaDream** - single-view to 3D scene reconstruction
- **Gaussian Splatting** - real-time rendering
- **Depth-Pro** - monocular depth estimation
- **Three.js** - interaktywny 3D viewer

## 📦 Instalacja

```bash
pip install -r requirements.txt
from scene_reconstructor import SceneReconstructor3D

reconstructor = SceneReconstructor3D(device='cuda')
reconstructor.reconstruct_from_single_image('input.jpg', 'output')

### 2. Dodaj plik requirements.txt
Kliknij **"Add file"** → **"Create new file"** → nazwij `requirements.txt`:


### 3. Udostępnij swoją aplikację!
Twoje repozytorium jest publiczne pod adresem:
**https://github.com/notakz/3d-scene-reconstructor**

