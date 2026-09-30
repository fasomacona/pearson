# 2.1.1 Coeficiente de Correlación de Pearson

**Asignatura:** Análisis y visualización de datos (GAD-2401)  
**Carrera:** Ingeniería Informática  
**Institución:** Tecnológico de Estudios Superiores de Chalco  

---

## Descripción

Sitio web educativo (HTML) + práctica en Jupyter Notebook sobre el **Coeficiente de Correlación de Pearson**.

Ideal para publicar en **GitHub Pages**.

## Estructura

```
tema-2.1.1-pearson-html/
├── index.html                      ← Página principal
├── 01-introduccion.html
├── 02-formula-y-calculo.html
├── 03-interpretacion.html
├── 04-propiedades.html
├── 05-ejemplos.html
├── css/estilos.css
├── ejercicios/
│   └── ejercicios-manuales.html    ← Ejercicios para cuaderno
├── practica/
│   └── practica_pearson.ipynb      ← Práctica Jupyter
├── requirements.txt
└── README.md
```

## Cómo ver las páginas HTML

### Opción 1: Localmente
Abre `index.html` con cualquier navegador (doble clic).

### Opción 2: GitHub Pages
1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En "Source" elige la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos tendrás la URL:  
   `https://tu-usuario.github.io/nombre-del-repo/`

## Práctica en Jupyter

1. Descarga `practica/practica_pearson.ipynb`.
2. Ábrelo en:
   - **Google Colab** (recomendado): [colab.research.google.com](https://colab.research.google.com) → Subir notebook
   - VS Code (con extensión Jupyter)
   - Jupyter Notebook local

```bash
pip install -r requirements.txt
jupyter notebook practica/practica_pearson.ipynb
```

## Flujo de trabajo recomendado para el estudiante

1. Lee las páginas HTML de teoría en orden (1 → 5).
2. Resuelve los **ejercicios manuales** en tu cuaderno (sin calculadora ni código).
3. Abre el notebook y verifica tus resultados.
4. Completa los ejercicios adicionales del notebook.

## Requisitos previos

- Conceptos básicos de media, desviación estándar y covarianza.
- Manejo elemental de Python (`pandas`, `numpy`, `scipy`, `seaborn`).

---

**Material generado para GAD-2401 · Uso educativo · 2026**
