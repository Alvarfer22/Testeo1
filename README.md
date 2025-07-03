
---

## 📓 Notebook (Google Colab)

Puedes abrir el proyecto directamente en Google Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_COLAB)

---

## 🧪 Detectores incluidos

# Comparativa de detectores de características en imágenes

| Detector      | Tipo             | Sensibilidad | Dirección | Escalable | Comentarios (¿Para qué sirve?)                                       |
|---------------|------------------|--------------|-----------|-----------|------------------------------------------------------------------------|
| Canny         | Bordes           | Alta         | Sí        | No        | Detecta bordes bien definidos; ideal para contornos de objetos.       |
| Sobel         | Bordes           | Media        | Sí        | Sí        | Detecta cambios suaves de intensidad; útil para resaltar formas.      |
| Scharr        | Bordes           | Alta         | Sí        | Sí        | Más preciso que Sobel en detalles finos; bueno para estructuras finas.|
| Laplaciano    | Bordes           | Alta         | No        | No        | Detecta zonas donde cambia bruscamente el color; útil para resaltes.  |
| Harris        | Esquinas         | Media        | No        | No        | Detecta esquinas o puntos donde se cruzan líneas; útil en geometría.  |
| Shi-Tomasi    | Esquinas         | Alta         | No        | Sí        | Mejora de Harris; usado para rastrear puntos interesantes entre frames.|
| FAST          | Esquinas         | Alta         | No        | Sí        | Muy rápido; ideal para cámaras en tiempo real (drones, móviles).      |
| ORB           | Puntos clave     | Alta         | Sí        | Sí        | Detecta y compara puntos clave; útil para emparejar imágenes.         |
| SIFT          | Puntos clave     | Muy Alta     | Sí        | Sí        | Encuentra detalles únicos sin importar tamaño o rotación; robusto.    |
| LBP           | Textura          | Media        | N/A       | Sí        | Detecta patrones en la textura local; útil para clasificar materiales.|


---

## 🖼️ Ejemplo de imagen procesada


![Madrid_Canny](https://github.com/user-attachments/assets/f0cc37cc-3bde-40d8-a1b7-0157ab405710)

---

## ⚙️ Tecnologías usadas

- 🐍 Python 3.10
- 📷 OpenCV
- 📊 NumPy
- 📓 Google Colab
- 🧾 Markdown

---

## 📬 Contacto

👨‍💻 Álvaro Fernández  
📧 [alvaro.f.rodriguez@protonmail.com](mailto:alvaro.f.rodriguez@protonmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/alvarofernandezoficial)

---

## 🌟 ¡Dale una estrella si te ha gustado el proyecto!

---


