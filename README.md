# AmbientesAnaconda

Neste repositório estão armazenados as listas de pacotes dos ambientes que utilizo no Anaconda. Estes arquivos são úteis para replicar os ambientes em diferentes máquinas.

## Uso

Na máquina onde o ambiente será criado, executar o seguinte comando (com o Anaconda devidamente instalado):

    conda create --name AMBIENTE --file AMBIENTE.txt

Onde ``AMBIENTE`` refere-se ao nome do ambiente a ser criado.

Caso seja necessário adicionar o canal `conda-forge`, utilize o comando a seguir:

    conda config --add channels conda-forge
