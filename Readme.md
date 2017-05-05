
# Objetivo

* Instalação de ambiente Python and Django em sistema operacional Linux Ubuntu 14.04.

* O processo de instalação pode ser usado para algumas outras versões operacionais Linux, principalmente Ubuntu.

# Tipos de Instalação

* Instalação com Linux;
* Instalação com Pip.

# Instalação com Linux

* É a instalação de um único ambiente Python e Django na sua máquina intermediada pelo sistema operacional local (Linux), assim você só pode essa configuração para criar seus projetos. Os comandos para essa instalação são:

> sudo apt-get update
> sudo apt-get install python
> sudo apt-get install python-django

* Para verificar se a instalação foi feita com sucesso. Execute os comandos:

> python

* Com esse comando, espera-se que seja aberto um ambiente de codificação python no terminal. Para verificar se o django está instalado, basta executar o comando:

> django-admin --version

* O retorno esperado é o número da versão do Django instalado, que vai ser aproximadamente:

> 1.6.11

# Instalação com PIP

* É a instalação de um único ambiente Python e Django na sua máquina intermediada pelo gerenciador de pacotes do Python (Pip), assim você pode desenvolver seu projeto. Os comandos para sua instalação são:

> sudo apt-get update

* Se estiver com a versão do Python inferior a 3, execute:

> sudo apt-get install python-pip

* Se seu Python for a versão 3, execute:

> sudo apt-get install python3-pip

* Após isso, execute para Python com versão inferior a 3:

> sudo pip install django

* Se for Python 3, instale o Django com o comando:

> sudo pip3 install django

* Para verificar sua instalação, basta executar o comando:

> django-admin --version

* O retorno vai ser o número da versão do Django instalado variável conforme o Python usado.