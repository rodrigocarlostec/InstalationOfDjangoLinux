
# Objetivo

* Instalação de ambiente Python and Django em sistema operacional Linux Ubuntu 14.04.

* O processo de instalação pode ser usado para algumas outras versões operacionais Linux, principalmente Ubuntu.

# Tipos de Instalação

* Instalação Estática;
* Instalação com Ambientes Dinâmicos.

# Instalação Estática

* É a instalação de um único ambiente Python e Django na sua máquina, assim você só pode essa configuração para criar seus projetos. Os comandos para essa instalação são:

> sudo apt-get update
> sudo apt-get install python
> sudo apt-get install python-django

* Para verificar se a instalação foi feita com sucesso. Execute os comandos:

> python

* Com esse comando, espera-se que seja aberto um ambiente de codificação python no terminal. Para verificar se o django está instalado, basta executar o comando:

> django-admin --version

* O retorno esperado é o número da versão do Django instalado, que vai ser aproximadamente:

> 1.6.11

# Instalação Estática

* É a instalação de vários ambientes Python e Django na sua máquina, assim você só pode trocar a configuração de desenvolvimento por projeto. Essa é a mais recomendada. Os comandos para sua instalação são:

> sudo apt-get update

> 