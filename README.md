# resumo_labDIO_10
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

adquirimos uma compreensão detalhada sobre diferentes formas de gerenciar e automatizar recursos na nuvem Azure. Inicialmente, vimos o Azure Portal, uma interface gráfica eficiente para tarefas manuais, mas que não é ideal para criação de recursos em larga escala, já que esse processo pode se tornar demorado.

Em seguida, exploramos o Cloud Shell, uma poderosa ferramenta de linha de comando que pode ser acessada diretamente no ambiente de nuvem. Ele oferece suporte tanto para PowerShell quanto para Bash, permitindo que o usuário escolha o ambiente de sua preferência para trabalhar. Porém, para utilizar o Cloud Shell, é necessário possuir uma Storage Account configurada, pois ela armazena os arquivos e scripts necessários.

Aprendemos a utilizar os comandos da CLI (Command-Line Interface) presentes na aba de recursos, o que facilita a automação e repetição de tarefas, uma vez que podemos criar recursos por meio de scripts. Descobrimos também a possibilidade de exportar templates de recursos já existentes, como uma VNet (Virtual Network), permitindo sua replicação em diferentes ambientes e cenários via linha de comando, o que proporciona mais agilidade no processo.

Outro ponto importante foi o Azure Bicep, uma linguagem declarativa que simplifica a criação de infraestrutura como código (IaC). Comparado ao ARM (Azure Resource Manager), o Bicep oferece uma sintaxe mais simples e fácil de usar, o que nos ajuda a economizar tempo e minimizar erros ao provisionar recursos na nuvem.

Por fim, exploramos o Azure Arc, uma solução que amplia as capacidades de gerenciamento do Azure para ambientes híbridos e multi-nuvem, permitindo gerenciar recursos em datacenters locais e outras plataformas de nuvem com o mesmo controle que usamos no Azure.

Esse conteúdo foi essencial para entendermos como otimizar a criação e gerenciamento de recursos no Azure de maneira mais eficiente e automatizada.
