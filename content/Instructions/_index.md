---
title: "Instructions"
date: 2020-06-12T02:53:34-05:00
pre : "<i class='fa fa-check-circle'></i> "
draft: false
chapter : false
weight : 1
---

Los set de tutoriales están escritos en [Python](https://www.python.org/)
y se pueden utilizar de 2 maneras:

### Using Google's Colab

El método ideal para acceder a estos cuadernos y recursos es a través de
[My Binder](https://mybinder.org/) or 
[Google Colab](https://colab.research.google.com/).

Simplemente puede hacer clic en la * insignia * para abrirla en **MyBinder** or
**Google Colab**:

[![Binder](https://mybinder.org/badge_logo.svg)]({{%siteparam "mybinder_repo_url"%}})

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]({{%siteparam "google_colab_repo_url"%}})

Simplemente presione sobre él y lo redireccionará al sitio web dedicado al alojamiento.
estos cuadernos.

### Obtener el repositorio en su computadora

El primer método para acceder al conjunto de cuadernos y recursos es mediante
*clonación* de todo el repositorio en su computadora. De esa manera, lo harás
ser capaz de:

- Instale los paquetes de Python necesarios
- Ejecute cada cuaderno por sí solo y compruebe los resultados usted mismo.

Para que esto funcione, primero deberá:

1. ***Clone your repository to specified directory***

    - Go to your `Documents` directory (or any other directory)

        ```bash
        # Let's go to your Documents folder
        cd $HOME/Documents
        ```

    - Clone the directory : Keep in mind that you **don't** have to clone it
      into `Documents`, but you can choose *any* other directory.

        ```bash
        git clone https://github.com/vcalderon2009/2021_06_Deep_Learning_tutorial.git
        ```

    - Go into the directory

        ```bash
        cd ./2021_06_Deep_Learning_tutorial
        ```

    - Checkout the `master` branch

        ```bash
        git checkout master
        ```

2. **Create a new Python environment**
    
    - The next step is to create a new Python environment for the project

        ```bash
        make create_environment
        ```

        This will create the necessary Python environment for the project.
        If you have [Anaconda](https://www.anaconda.com/) installed on your
        computer, this command will create a new Python environment with
        the name `2021_06_Deep_Learning_tutorial`.

    - If using *Anaconda*, you will have to activate the environment:

        ```bash
        conda activate 2021_06_Deep_Learning_tutorial
        ```

        or if you're using [venv](https://docs.python.org/3/library/venv.html),
        you can activate it as:

        ```bash
        workon 2021_06_Deep_Learning_tutorial
        ```

        assuming you have it properly installed.

    - Install the necessary packages

        Now that the Python environment exists, you will need to
        **install the packages** into the environment:

        ```bash
        make requirements
        ```

3. **Accessing the notebooks**

    - You can finally access the notebooks of the project by:

        ```bash
        # Going into the `notebooks` directory
        cd notebooks

        # Start jupyter lab
        jupyter lab
        ```

> You can now look through the different notebooks and play around with them!
