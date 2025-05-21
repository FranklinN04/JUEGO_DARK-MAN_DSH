## 📥 Visualización de archivos

Este proyecto contiene archivos grandes (como imágenes, datos o modelos) que han sido almacenados utilizando **Git LFS (Large File Storage)**.

### 🔍 ¿Por qué no puedo ver algunos archivos desde GitHub?

GitHub **no permite la previsualización directa** de archivos almacenados con Git LFS si superan cierto tamaño.  
En su lugar, verás un mensaje como:

> “This file is stored with Git LFS. You need to download it to view it.”

### ✅ ¿Qué hacer si quieres visualizar un archivo?

1. **Descarga manualmente** el archivo que deseas ver desde el repositorio.
2. **O bien**, clona el repositorio con Git LFS para que los archivos se descarguen correctamente:

   ```bash
   git lfs install
   git clone https://github.com/usuario/repositorio.git
