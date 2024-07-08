### Curso de Python

## Aula 1 - 09/07/2024

# 1. Sobre o Curso
Bem-vindo ao curso de Python! Durante as próximas aulas, exploraremos os fundamentos e as melhores práticas de programação em Python.

# 2. Informações Importantes
Este curso foi desenvolvido para ajudá-lo a se tornar proficiente em Python, uma das linguagens de programação mais populares e versáteis.

# 3. Preparação do Ambiente
Softwares Utilizados Durante o Curso:
    • Python: Download Python
    • PyCharm Community: Download PyCharm Community
Observações:
    • A versão recomendada do Python atualmente é a 3.12.
    • Precisamos instalar o Java JDK pois a IDE PyCharm precisa do Java para executar. A versão LTS atual do Java é a 21.
    • Faça o download, instalação e configuração de acordo com seu sistema operacional.
    • Ao entrar na seção de downloads do PyCharm, temos duas versões disponíveis: Pro e Community. Usamos a versão Community, que é gratuita.
    • Caso tenha dúvidas ou problemas com instalação e configuração de software, recomendo revisar o curso "Programação para Leigos", que é um pré-requisito para este curso e cobre o essencial de computação e informática voltado para a programação.
    • Se você tiver familiaridade com outra IDE e preferir usá-la, fique à vontade. Contudo, o suporte será dado apenas para as ferramentas e conteúdos usados no curso.

# 5. Testando o Ambiente Preparado
    1. Abra o PyCharm.
    2. Crie um novo projeto.
    3. Crie um arquivo teste.py (File → New → Python File).
    4. Adicione o seguinte código:
       python
       Copy code
       print("testando o Python")
    5. Execute o arquivo para verificar se o ambiente está configurado corretamente.

# 6. O que Vamos Aprender Nesta Seção?
Nesta seção, vamos explorar as melhores práticas de programação em Python, incluindo a PEP 8.

# 7. PEP 8 - Boas Práticas
A PEP 8 é o guia de estilo para escrever código Python. Ela estabelece convenções para garantir que o código seja consistente e legível. Aqui estão alguns dos principais pontos:

# Convenções de Formatação
    1. Indentação:
        ◦ Use 4 espaços por nível de indentação. Não use tabulações.
    2. Comprimento das Linhas:
        ◦ Limite as linhas a um máximo de 79 caracteres.
    3. Linhas em Branco:
        ◦ Separe funções e definições de classe com duas linhas em branco.
        ◦ Métodos dentro de uma classe devem ser separados por uma linha em branco.

# Estilo de Nomes
    1. Nomes de Variáveis:
        ◦ Utilize letras minúsculas com palavras separadas por underscores (ex.: minha_variavel).
    2. Nomes de Classes:
        ◦ Utilize o estilo CamelCase (ex.: MinhaClasse).
    3. Nomes de Funções:
        ◦ Utilize letras minúsculas com palavras separadas por underscores (ex.: minha_funcao).

# Importações
    1. Importações Múltiplas:
        ◦ Coloque todas as importações no topo do arquivo.
        ◦ Importe uma biblioteca por linha.
        ◦ Ordem das importações: bibliotecas padrão, bibliotecas de terceiros e, por último, importações locais.

# Espaços em Branco
    1. Ao Redor de Operadores:
        ◦ Use espaços ao redor de operadores de atribuição (ex.: x = 1).
        ◦ Não coloque espaços ao redor de operadores em expressões internas (ex.: x = a+b).
    2. Depois de Vírgulas, Dois Pontos e Pontos e Vírgulas:
        ◦ Use um espaço após cada vírgula, dois pontos e ponto e vírgula.

# Docstrings
    1. Uso de Docstrings:
        ◦ Use docstrings para documentar todas as funções, classes e métodos.
        ◦ Siga as convenções para docstrings de uma linha e multilinhas conforme necessário.

# Comentários
    1. Comentários de Linha Única:
        ◦ Inicie com o símbolo # seguido de um espaço.
    2. Comentários de Bloco:
        ◦ Utilize o símbolo # para cada linha.

# Outras Convenções
    1. Strings:
        ◦ Use aspas simples ou duplas de maneira consistente.
    2. Comparações:
        ◦ Para verificar se uma variável é None, use is (ex.: if foo is None:).

A PEP 8 é fundamental para garantir a legibilidade e a consistência do código Python, facilitando a colaboração entre desenvolvedores e a manutenção do código a longo prazo.
