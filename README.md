# Crear README.md
readme_content = """
# Pruebas Unitarias para la Calculadora

## Descripción
Este proyecto contiene pruebas unitarias para dos casos de uso:
- **Caso de Uso 1:** Validación de la función `suma()`.
- **Caso de Uso 2:** Validación de la función `division()`.

 Pruebas Implementadas
### 1️⃣ Caso de Uso 1: Pruebas de `suma()`
- `test_suma_positivos`: Verifica la suma de números positivos.  
- `test_suma_negativos`: Verifica la suma de números negativos.  
- `test_suma_mixtos`: Verifica la suma de positivos y negativos.  

### 2️⃣ Caso de Uso 2: Pruebas de `division()`
- `test_division_valida`: Verifica una división válida.  
- `test_division_negativos`: Verifica la división de negativos.  
- `test_division_por_cero`: Verifica que la división por cero lance un `ValueError`.  

---

**Requisitos Previos**
- Python 3.10 o superior  
- `pip` (administrador de paquetes de Python)  
- `pytest` (framework para pruebas)  

## 💻 **Instrucciones para Ejecutar las Pruebas**

1. **Instalar dependencias:**  
   ```bash
   pip install pytest
