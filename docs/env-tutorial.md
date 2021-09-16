# Manual de instalación Python 2.7 y entorno preconfigurado

## Python 2.7
Descargar [Python 2.7.13](https://www.python.org/downloads/release/python-2713/) (p ej: `Windows x86-64 MSI installer`)

Instalar teniendo en cuenta:
1. La ruta de instalación sea `C:\Python27`
2. Chequear la opción de `Add python.exe to Path`

![Add python.exe to Path](https://github.com/enriquezmartin/PES/blob/master/docs/Add%20pythonexe%20to%20Path.png?raw=true)

Comprobar la correcta instalación de Python ejecutando un `cmd`.
Para ello ir a Inicio, escribir `cmd` y abrirá la consola de comando en la cual se deberá escribir:
```bash
python
```
Si todo va bien, el resultado será:

![Cmd Python test](https://github.com/enriquezmartin/PES/blob/master/docs/Cmd%20Python%20test.png)

## Entorno Python con bibliotecas ya instaladas
Descargar el [entorno preconfigurado](https://drive.google.com/file/d/1kOefkwJMPH0ITv2jqcJI8_D1ZfNMFQTG/view?usp=sharing)

Copiar el archivo pes.zip en el disco `C:`

Descomprimir con la opción `Extraer aquí` (en el disco `C:`) para que la estructura de carpetas que se cree sea de la siguiente forma:
```bash
C:\pes\entorno
C:\pes\repo
C:\pes\activar_entorno.bat
```
![Directorio resultante](https://github.com/enriquezmartin/PES/blob/master/docs/Directorio%20resultante.png?raw=true)

## [Jupyter Notebook](https://jupyter.org/)
Ejecutar el archivo `C:\pes\activar_entorno.bat`

En la línea de comandos que se abre, ejecutar:
```bash
jupyter lab
```
Como se muestra en la figura:
![Jupyter lab](https://github.com/enriquezmartin/PES/blob/master/docs/Jupyter%20lab.png)

Luego de esperar unos segundos levantará el Jupyter:
![Jupyter Running](https://github.com/enriquezmartin/PES/blob/master/docs/Jupyter%20Running.png)

Y en el navegador:
![Jupyter on browser](https://github.com/enriquezmartin/PES/blob/master/docs/Jupyter%20on%20browser.png)

Ya está todo listo para ejecutar los notebooks

Los archivos que se pueden ejecutar tienen la extensión [.ipynb](https://fileinfo.com/extension/ipynb)

Cada celda se puede ejecutar clickeando el botón `Play`
![Jupyter on browser Play](https://github.com/enriquezmartin/PES/blob/master/docs/Jupyter%20on%20browser%20Play.png)

### __¡A codear!__


## Enlaces a la documentación de las bibliotecas utilizadas
- [matplotlib==2.2.3](https://matplotlib.org/2.2.3/)
- [numpy==1.16.6](https://docs.scipy.org/doc/numpy-1.16.1/reference/)
- [scipy==1.1.0](https://docs.scipy.org/doc/scipy-1.1.0/reference/)
- [opencv==2.4.13](https://docs.opencv.org/2.4/)
- [ipywidgets==7.6.4](https://ipywidgets.readthedocs.io/en/7.6.4/)
