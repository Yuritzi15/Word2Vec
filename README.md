# 🎯 Representación de Requerimientos Funcionales y No Funcionales mendiante Word2Vec 🎯

El objetivo de este repositorio es compartir una implementación de la técnica de representación Word2Vec en sus versiones **CBOW** y **Skipgram** con el fin de obtener embeddings que permitan clasificar **requerimientos funcionales** y **no funcionales** escritos en texto en inglés. 

---


## 📊 Datos 📊

El conjunto de datos utilizado se conforma de 550 requerimientos recopilados de la web que han sido previamente etiquetados como funcionales y no funcionales.


## 🛠️ Preprocesamiento del texto 🛠️

El preprocesamiento del texto incluye: 
- Tokenización
- Lowercasing 
- Eliminación de Stopwords 
- Lematización 


## ⚙️ Ejecutar el Notebook con Jupyter o VS Code ⚙️
1. **Clona el repositorio** 
 ```bash
 git clone https://github.com/Yuritzi15/Word2Vec
 cd repositorio-bow
```


2. **Instala las dependencias**
 ```bash
 pip install -r requirements.txt
```

3. **Ejecuta el notebook**
 ```bash
 jupyter notebook Word2Vec.ipynb.ipyn
 ```

## 🚀 Ejecutar en colab 🚀
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Yuritzi15/Word2Vec/blob/main/Word2Vec.ipynb)
