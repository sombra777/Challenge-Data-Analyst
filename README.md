# Análisis de Tiendas para Venta

## 📌 Objetivo
Identificar qué tienda tiene el peor desempeño para recomendar su venta.

## 📊 Datos Analizados
- Ingresos totales
- Productos menos vendidos
- Satisfacción de clientes
- Costos de envío

## 🛠️ Cómo Usar
1. Descargar los archivos CSV de las 4 tiendas
2. Ejecutar el script Python:
```python
python analizar_tiendas.py
📉 Resultado Principal
Tienda recomendada para vender: Tienda 3
Razones:

Menores ingresos ($9,000)

Producto menos vendido (Control Remoto, solo 3 unidades)

Categoría con peor desempeño (Accesorios)

📋 Requisitos
Python 3

Pandas y Matplotlib

bash
pip install pandas matplotlib
📜 Licencia
MIT


### Versión ultra-minimalista:
```markdown
# Análisis Tiendas

Identifica la tienda con peor desempeño para vender.

**Uso:**
1. Poner archivos CSV en /data
2. Ejecutar `python analizar.py`

**Resultado:**  
Vender Tienda 3 (ingresos bajos, productos poco vendidos)
