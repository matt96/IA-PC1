# IA-PC1
Técnica de optimización: Stochastic Gradient Descent explicada utilizando Jupyter Notebook
### Jupyter notebook

#### Prerequisitos
  - Tener previamente instalado una version de python 3.6 ó 2.7
  - Tener el administrador de paquetes de python pip
  - En caso contrario consultar [Como instarlar pip](https://recursospython.com/guias-y-manuales/instalacion-y-utilizacion-de-pip-en-windows-linux-y-os-x/)
#### Procesos de instalacion

  - Abrir una terminal en su computadora
  - Ingresar los siguientes comando:
    - Para versiones 3.+ de python
      - python3 -m pip install --upgrade pip
      - python3 -m pip install jupyter
    
    - Para versiones 2.7:
      - python -m pip install --upgrade pip
      - python -m pip install jupyter

 ### Ejecutando jupyter notebook
 Jupyter notebook te permite administrar tu proyecto a traves del browser, para ello debes realizar lo siguiente:
 1. Abrir una terminal.
 2. Digirse al directorio raiz de tu proyecto jupyter notebook.
 3. Escirbir el siguiente comando: jupyter notebook
 
 Imediatmente se levantará el servidor de tu poryecto, seguido se abrirá una pestaña en tu browser con el Notebook Dashboard.
 En caso que no quieras que esta acción se realice por defecto, para ello debes hacer lo siguiente:
 
 1. Abrir una terminal.
 2. Digirse al directorio raiz de tu proyecto jupyter notebook.
 3. Escirbir el siguiente comando: jupyter notebook --no-browser
 4. Abrir el el navegador de tu preferencia.
 5. En una nueva pestaña pegar lo siguiente: http://localhost:8888/
 6. Listo el Notebook Dashboard queda listo para usar.
 
 Para mas detalles acerca de la ejecución puede consultar el siguiente link [Corriendo Notebook](https://jupyter.readthedocs.io/en/latest/running.html#running)
 
 ### Paquetes implementados
  - Argparse
  - Scikit-learn
  - Numpy
  - Matplotlib
  - Scipy
  - Easydict
 
 #### Instalción de paquetes
Jupyter permite dentro de tus proyectos instalarte él mismo los paquetes requeridos en tu proyecto,
para esto basta escribir al inicio del codigo los paquetes que requiere,
como se muestra a continuacion:

```python
import sys
!{sys.executable} -m pip install argparse
!{sys.executable} -m pip install -U scikit-learn
!{sys.executable} -m pip install numpy
!{sys.executable} python -mpip install matplotlib
!{sys.executable} -m pip install scipy
!{sys.executable} -m pip install easydict
```
