# Modelo Cuadrático con TensorFlow\.js

Este proyecto implementa una red neuronal con **TensorFlow\.js** para predecir la función cuadrática:

> `y = 2x² - 3x + 1`

El modelo se entrena en el navegador, permite ingresar valores de `x` para obtener predicciones de `y` y muestra un gráfico de pérdida para visualizar el progreso del entrenamiento utilizando **Plotly**.


##  Requisitos previos

* Un navegador web moderno
* Un servidor local (por ejemplo: *Live Server* en VS Code o `http.server` de Python)



##  Instalación y configuración

### Clonar el repositorio

```bash
git clone https://github.com/luciannoFr/seminario-tensorflow-pt6.git
cd seminario-tensorflow-pt6
```

### Servir el proyecto

> Este proyecto usa **CDNs externos** para TensorFlow\.js, Plotly y TailwindCSS.
> No se requieren dependencias adicionales.

#### Con Python:

```bash
python -m http.server 8000
```

#### Con Live Server (VS Code):

1. Instalá la extensión **Live Server**
2. Hacé clic derecho en `index.html`
3. Seleccioná **Open with Live Server**



##  Acceder a la aplicación

Abrí tu navegador en la siguiente URL:
`http://localhost:8000`
(o el puerto que indique tu servidor)


##  Uso

### Entrenar el modelo

* Hacé clic en el botón **Entrenar Modelo**
* Se mostrará un **gráfico de pérdida** con el progreso del entrenamiento

### Hacer predicciones

1. Ingresá valores de `x` separados por comas (ejemplo: `0, 1, 2`)
2. Hacé clic en **Predecir**
3. Se mostrarán los valores predichos de `y`

### Ver resultados

* Los resultados aparecerán debajo del botón **Predecir**
* El resumen de pérdida (inicial, final y reducción porcentual) se mostrará debajo del gráfico
