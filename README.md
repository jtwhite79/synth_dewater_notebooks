![Synthetic Dewatering Domain](assets/domain.pdf)

# Theory and Practice of Applied Predictive Groundwater Modeling
Materials and tutorials for the synthetic dewatering model of White and others (2025)

Materials are provided in English and Spanish!




## Instrucciones de instalación

**Descarga el repositorio del curso:**

Puedes hacerlo de dos maneras:
 - (1) (más fácil) Descarga el repo como archivo zip desde aquí: [gmdsi-workshop-chile2025](https://github.com/p-ortega/gmdsi-workshop-chile2025). Descomprime la carpeta y trabaja desde ahí.
 - (2) (recomendado; requiere familiaridad con git). Instala git siguiendo las instrucciones aquí: [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Regístrate en GitHub y luego clona el repo [gmdsi-workshop-chile2025](https://github.com/p-ortega/gmdsi-workshop-chile2025).

**Instala Python y las dependencias:**
 - Si ya tienes Python instalado usando Anaconda, puedes saltarte este paso. Si no, instala [miniforge](https://github.com/conda-forge/miniforge?tab=readme-ov-file#download).
 - Si usas __Windows__: ve al menú inicio y abre "Anaconda prompt". Se abrirá una ventana de línea de comandos de anaconda. En __Linux__ o __MacOS__, simplemente usa la terminal estándar. Navega a la carpeta del repo del curso en tu máquina. Hazlo escribiendo "cd *tu ruta de carpeta*" y presionando < enter >. Reemplaza *tu ruta de carpeta* por la ruta donde tienes la carpeta del curso en tu compu.
 - Luego, escribe `mamba env create -f environment.yml` (o `conda env create -f environment.yml` si `mamba` no te funciona). Esto creará un entorno de anaconda llamado "dewater" e instalará las dependencias de python necesarias para el curso. Puede tardar un rato. Si quieres, puedes revisar el archivo *environment.yml* en la carpeta del repo para ver qué dependencias se van a instalar.

**Inicia jupyter notebook**
Vas a tener que hacer este paso cada vez que quieras abrir uno de los notebooks del curso.
Para iniciar el jupyter notebook:
- Windows: abre el Anaconda prompt y escribe `conda activate dewater`
- Mac/Linux: abre una terminal y escribe `conda activate dewater`
- Luego navega a la carpeta donde descargaste el repo del curso y escribe `jupyter notebook`
Se debería iniciar una instancia de jupyter notebook dentro de la carpeta del repo. Usando el navegador, ahora puedes ir a la carpeta "tutorials", abrir uno ¡y ya estás listo!


## Installation Instructions

**Download the course repository:**

You can do this in one of two ways. 
 - (1) (easier) Download the repo as a zip file from here: [GMDSI_notebooks](https://github.com/gmdsi/GMDSI_notebooks). Unzip the folder and work from there.
 - (2) (recommended; requires familiarity with git). Install git following directions here: [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Sign-up for a GitHub account, then clone the repo [GMDSI_notebooks](https://github.com/gmdsi/GMDSI_notebooks).

**Install Python and dependencies:**
 - If you have already installed Python using Anaconda, you can skip this step. If not, install [miniforge](https://github.com/conda-forge/miniforge?tab=readme-ov-file#download).  
 - If you are using __Windows__: go to the start menu and open "Anaconda prompt". An anaconda command line window will open. On __Linux__ or __MacOS__, just use the standard terminal. Navigate to the course repo folder on your machine. You can accomplish this by typing "cd *your folder path*" and pressing < enter >. Replace *your folder path* with the path to the course material folder on your computer.
 - Next, type `mamba env create -f environment.yml` (or `conda env create -f environment.yml` if `mamba` doesn't work for you). This will create an anaconda environment called "dewater" and install the python dependencies required for this course. It may take a while. Should you wish, you can inspect the *environment.yml* file in the repo folder to see what dependencies are being installed.

**Start jupyter notebook**
You will need to do this step any time you wish to open one of the course notebooks.
To start up the jupyter notebook:
- Windows: open the Anaconda prompt and type `conda activate dewater`
- Mac/Linux: open a termainal and type `conda activate dewater`
- Then navigate to folder where you downloaded the course materials repo and type `jupyter notebook`
A jupyter notebook instance should start within the course repo flder. Using the browser, you can now navigate to the "tutorials" folder and open one and you are in business!
