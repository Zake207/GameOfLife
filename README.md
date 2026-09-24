# GameOfLife

## Instalación de Tkinter

Este proyecto utiliza **Tkinter** para la interfaz gráfica. Tkinter forma parte del ecosistema de Python, pero **no se instala mediante `pip` ni mediante `requirements.txt`**. En algunos sistemas operativos es necesario instalarlo como un paquete del sistema antes de ejecutar el proyecto.

### Linux (Ubuntu/Debian)

En sistemas basados en Ubuntu o Debian, instala Tkinter con:

```bash
sudo apt update
sudo apt install python3-tk
```

Una vez instalado, puedes comprobar que funciona correctamente ejecutando:

```bash
python3 -m tkinter
```

Si la instalación es correcta, aparecerá una pequeña ventana de prueba de Tkinter.

### Entorno virtual

Después de instalar Tkinter en el sistema, puedes crear y activar el entorno virtual del proyecto:

```bash
python3 -m venv .venv
```

Activación del entorno:

```bash
source .venv/bin/activate
```

A continuación, instala las dependencias del proyecto:

```bash
pip install -r requirements.txt
```

### Comprobación

Para verificar que Python puede utilizar Tkinter desde el entorno virtual:

```bash
python -m tkinter
```

Si aparece la ventana de prueba, Tkinter está correctamente instalado y el proyecto puede ejecutarse.

### Resumen

Antes de ejecutar **Game of Life**, asegúrate de tener:

1. Python 3 instalado.
2. Tkinter instalado en el sistema.
3. El entorno virtual `.venv` creado y activado.
4. Las dependencias de `requirements.txt` instaladas.

En Ubuntu/Debian, el paso específico para Tkinter es:

```bash
sudo apt install python3-tk
```
