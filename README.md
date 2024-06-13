## Repositorio del Curso de Manejo de Datos Faltantes: Detección y Exploración
Curso de Platzi

Este repositorio contiene los archivos y ajustes básicos necesarios para poder tomar el curso en VSCode o cualquier editor de código a nivel local para aquellos que no prefieren usar Deepnote.

Las librerías contenidas en el archivo `requirements.txt` fueron probadas en todas las clases para asegurarse que no arrojaran ningún error durante la ejecución de los Jupyter Notebooks que están divididos cada uno por clase.

### Contenido del repositorio
Cada uno de los archivos `.ipynb` corresponden a cada una de las clases del curso a excepción del notebook 11. Este repositorio contiene:
- Notebooks reproducibles de todas las clases del curso y algunos comentarios explicando el proceso.
- Archivos `csv` y `rda` de los conjuntos de datos utilizados en el curso.
- Archivo `requirements.txt` que contiene las dependencias con su respectiva versión para poder replicar el repositorio sin ningún inconveniente.
- Librería `missing` encapsulada en un archivo `.py` para su facil importación a los notebooks que la necesiten.

**Nota 1:** Algunos métodos propios del objeto DataFrame están ejecutados con otro nombre debido a la diferencia de versiones entre el módulo Pandas utilizado en este repositorio y el módulo Pandas utilizado por el profesor en el curso. Nótese que los métodos utilizados aquí son más recientes y personalmente considero aprender de éstos y no los de las versiones anteriores.

**Nota 2:** Los archivos `.ipynb` no fueron divididos en carpetas correspondientes a los módulos del curso para evitar conflictos de importación de la librería `missing`.

### Inicialización

Descarga este repositorio utilizando git:
```bash
git clone git@github.com:onnymm/missing_data_exploration.git
```

Una vez instalado, crea el ambiente virtual para contener las dependencias en las versiones requeridas por el proyecto:
```bash
python -m venv env
```

Activa el ambiente virtual
```bash
env/Scripts/activate
```

Actualiza pip
```bash
pip install -U pip
```

Instala las dependencias
```bash
pip install -r .\requirements.txt
```

Una vez realizados todos los pasos anteriores, puedes comenzar a utilizar el repositorio. Espero que te sea de mucha ayuda :)

Cualquier sugerencia de cambio / mejora es totalmente bienvenida.