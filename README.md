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




 
 
 
