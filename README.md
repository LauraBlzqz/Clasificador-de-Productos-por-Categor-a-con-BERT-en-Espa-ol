🛍️ Clasificador de Productos por Categoría con BERT (Español)
Este proyecto es un prototipo de clasificador de productos utilizando BERT en español (modelo BETO de dccuchile). El objetivo es predecir la categoría de un producto a partir de su nombre o descripción breve.

🧠 ¿Qué incluye?
- Dataset de ejemplo con productos y sus categorías.

- Tokenización y entrenamiento usando transformers de Hugging Face.

- Entrenador con Trainer de transformers y separación train/test.

- Exportación del modelo entrenado y tokenizador.

- Interfaz web con Gradio para realizar predicciones en tiempo real.

P- reparado para ejecutarse en Google Colab.

📦 Requisitos
pip install transformers gradio pandas scikit-learn datasets

Nota: Se ha desactivado la integración con Weights & Biases para evitar errores al ejecutar en Colab sin configuración adicional.

🚀 ¿Cómo usarlo?
1.Carga tu archivo .py en Google Colab.

2.Ejecuta todas las celdas. Se entrenará el modelo y se abrirá una interfaz web para probarlo.

3. Introduce el nombre de un producto para obtener su categoría predicha.

🎯 Categorías de ejemplo
- Electrodomésticos
- Moda
- Hogar
- Tecnología
- Bienestar
- Accesorios
- Muebles

El dataset es de ejemplo. Para un rendimiento óptimo, es necesario entrenar con un conjunto de datos más amplio y realista.

🧪 Ejemplo de uso:
print(predecir_categoria("Auriculares Bluetooth con micrófono"))
# → Tecnología (esperado)

🗂️ Estructura del proyecto

├── model/                  # Modelo entrenado y tokenizador
├── model.zip              # Versión comprimida para descarga
├── clasificador.py        # Código principal
├── README.md              # Este archivo

🧩 Pendiente
- Mejora del dataset con más ejemplos reales.
- Evaluación con métricas más completas.
- Posible integración con una API o backend.


