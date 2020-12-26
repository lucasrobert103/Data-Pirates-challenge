# DataPirates-Challenge
Python scraping code to gather data from website and export the results to JSONL file

## Description
With this program, you can gather all the table information from the brazilian postal codes, and export it to a JSONL file. You can check the website [BuscaCep.Correios](http://www.buscacep.correios.com.br/sistemas/buscacep/buscaFaixaCep.cfm) before we get into the code.

## Installation
Make sure you have installed [Python 3](https://www.python.org/downloads/) in your machine.
I have provided the third-party modules necessary to run the code. Please, download [requirements.txt](https://github.com/lucasrobert103/Data-Pirates-challenge/blob/main/Data-Pirates-Challenge/requirements.txt) and install each one of them. Those modules can be installed as follows:
- in Windows, open the Command Prompt (cmd), type '**pip install /path/to/requirements.txt**'
- in other terminals, please go to [Installing Python Modules](https://docs.python.org/3/installing/index.html) for further instructions

If you have any troubles installing those third-party modules, install them one by one as follows:
- in Windows, open the Command Prompt (cmd), type '**pip install third-party module name**'
- example of the above situation: **pip install webdriver-manager**
- in other terminals, please go to [Installing Python Modules](https://docs.python.org/3/installing/index.html) for further instructions

The **.py** code can be compiled by the program of your preference. For instance, I use [Visual Studio Code](https://code.visualstudio.com/) to run my codes, but make sure that you add the [python extension](https://code.visualstudio.com/docs/languages/python).

## Usage
There are two files in the [project](https://github.com/lucasrobert103/Data-Pirates-challenge/tree/main/Data-Pirates-Challenge). Let's explain them individually.

#### postalCodeSearcher.py
1. download the file
1. run the code
1. the code will loop over all of the UFs found in the website
1. when it terminates, the results will be written to a **out.json** file in the same path directory in which you have the postalCodeSearcher.py

#### shouldExpect.py
1. download the file
1. run the code
1. when the website opens, return to the code and type the UF that you want to get the information about
1. if the UF provided is found, then the code executes and the results will be written to a **expected.json** file in the same path directory in which you have the shouldExpect.py
1. if the UF is not there, all the UF found in the website will be printed and then you try again
1. in the case that you type again a UF which is not there, the code exits

## Note
I wrote the code in Windows. Therefore, the shebang line (first line of the code) tells my computer run Python 3 in my operating system Windows. If you use another OS, Linux or OS X, please change that first line to the one which fits you. Please visit [Automate the Stuff with Python Programming](https://automatetheboringstuff.com/appendixb/) for further explanation.
thanks for this opportunity by: Lucas Robert

Em Português

DataPirates-Challenge
Python scraping code para coletar dados do site e exportar os resultados para o arquivo JSONL

Descrição
Com este programa, você pode reunir todas as informações das tabelas dos códigos postais brasileiros e exportá-las para um arquivo JSONL. Você pode verificar o site BuscaCep.Correios antes de entrarmos no código.

Instalação
Certifique-se de ter instalado o Python 3 em sua máquina. Eu forneci os módulos de terceiros necessários para executar o código. Faça o download do requirements.txt e instale cada um deles. Esses módulos podem ser instalados da seguinte forma:

No Windows, abra o Prompt de Comando (cmd), digite 'pip install /path/to/requirements.txt'
em outros terminais, vá para Instalando Módulos Python para obter mais instruções
Se você tiver problemas para instalar esses módulos de terceiros, instale-os um por um da seguinte maneira:

no Windows, abra o Prompt de Comando (cmd), digite 'pip install nome do módulo de terceiros'
exemplo da situação acima: pip install webdriver-manager
em outros terminais, vá para Instalando Módulos Python para obter mais instruções
O código .py pode ser compilado pelo programa de sua preferência. Por exemplo, eu uso o Visual Studio Code para executar meus códigos, mas certifique-se de adicionar a extensão python.

Uso
Existem dois arquivos no projeto. Vamos explicá-los individualmente.

postalCodeSearcher.py
baixe o arquivo
execute o código
o código irá percorrer todos os UFs encontrados no site
quando terminar, os resultados serão gravados em um arquivo out.json no mesmo diretório de caminho em que você tem o postalCodeSearcher.py
shouldExpect.py
baixe o arquivo
execute o código
quando o site abrir, volte ao código e digite o UF sobre o qual deseja obter as informações
se o UF fornecido for encontrado, o código será executado e os resultados serão gravados em um arquivo expected.json no mesmo diretório de caminho em que você tem o shouldExpect.py
se o UF não estiver lá, todo o UF encontrado no site será impresso e depois tente novamente
no caso de você digitar novamente um UF que não está lá, o código sai
Nota
Escrevi o código no Windows. Portanto, a linha shebang (primeira linha do código) diz ao meu computador para executar o Python 3 no meu sistema operacional Windows. Se você usa outro sistema operacional, Linux ou OS X, altere a primeira linha para aquele que se adequa a você. Visite Automatizar as coisas com a programação Python para obter mais explicações.
