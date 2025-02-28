Código com testes da API para uso remoto da nuvem AWS, e mais especificamente para pesquisa da ferramenta Amazon Textract.

    1. Teste em Python (Teste01-Python.ipynb):
        No notebook Python há alguns testes da ferramenta por uso direto da biblioteca Boto3 da Amazon, onde várias imagens salvas na nuvem AWS por meio de baldes (S3), foram passadas para a ferramenta Textract à fim de testar as funcionalidades básicas da ferramenta e até onde vai o seu desempenho.

        -- Para execução das células de código do arquivo é necessário ter um SDK Python, o programa AWS CLI, uma conta na Amazon e um usuário IAM para essa conta que tenha as permissões de execução. As bibliotecas necessárias já tem os seus comandos escritos no início do notebook --

        Na 1ª parte do arquivo, são testadas as formas básicas de se buscar informação, e então exibindo o que pôde ser lido.

        Na 2ª parte do arquivo, são testadas várias imagens em condições diferentes com o mesmo texto, para observar até onde a identificação funciona em condições ruins.