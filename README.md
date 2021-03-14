# Instalando o Software Jupyter
***
Siga os pasos abaixo e instale o `JupyterLab` ou o clássico `Jupyter Notebook` em seu computador em minutos!

> `Conteúdo fornecido pelo Jupyter`

## Clone o repositório

Para facilitar o seu uso e aprendizado na plataforma jupyter, clone esse repositório através da seguinte linha de comando:
```
git clone https://github.com/Alyssonmach/ipynb-tutorial.git
```

## Configurando o `Python`

O Jupyter é uma ferramenta desenvolvida para funcionar essencialmente com a linguagem de programação Python (embora seja compátivel com outras linguagens). Desse modo, para que o seu funcionamento ocorra perfeitamente, é necessários que o Jupyter esteja configurado em sua máquina corretamente. Abaixo, segue alguns links de instalação para os sistemas operacionais mais comuns:
- [Guia de instalação no Windows](https://docs.python.org/3/using/windows.html)
- [Guia de instalação no Linux](https://docs.python-guide.org/starting/install3/linux/)
- [Guia de instalação no MacOS](https://docs.python.org/3/using/mac.html)

## Começando com o `JupyterLab`
> *O [guia de instalação](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) fornece detalhes mais precisos*

### Instale com o conda

Se você usa o `conda`, pode instalar usando a seguinte linha de comando:
```
conda install -c conda-forge jupyterlab
```

### Instale com o pip

Se você usa o `pip`, pode instalar usando a seguinte linha de comando:
```
pip install jupyterlab
```

Se estiver instalando usando `pip install --user`, você deve adicionar o diretório bin de nível de usuário à sua variável de ambiente `PATH` para iniciar o jupyter lab. Se estiver usando um derivado do Unix (*FreeBSD*, *GNU* / *Linux*, *OS X*), você pode fazer isso usando o comando `export PATH="$HOME/.local/bin:$PATH"`.

## Começando com o `Jupyter Notebook`

### Instale com o conda

Recomendamos instalar o Jupyter Notebook clássico usando o gerenciador de pacotes conda. As distribuições [miniconda](https://docs.conda.io/en/latest/miniconda.html) ou [miniforge](https://github.com/conda-forge/miniforge/) conda incluem uma instalação mínima de conda.  
Você pode instalar usando a seguinte linha de comando:
```
conda install -c conda-forge notebook
```

### Instale com o pip

Se você usa o `pip`, pode instalar usando a seguinte linha de comando
```
pip install notebook
```

Parabéns, você instalou o Jupyter Notebook! Para executar o notebook, execute o seguinte comando no Terminal (Mac / Linux) ou Prompt de Comando (Windows):
```
jupyter notebook
```

> *Veja [rodando os notebooks](https://jupyter.readthedocs.io/en/latest/running.html#running) para mais detalhes*

### Começando com o `Google Colaboratory`

Caso você não queria optar por rodar os códigos em servidor local, o [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) oferece gratuitamente um ambiente de acesso Jupyter.
