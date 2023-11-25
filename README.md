# Requisitos Funcionais
[x] O usuário deve podere criar uma nova transação;
[x] O usuário deve poder obter um resumo da sua conta;
[x] O usuário deve poder listar todas as transações que já ocorreram;
[x] O usuário deve poder visualizar uma transação única;


# Regras de Negócio
[x] A transação pode ser do tipo:
    - Crédito: que somará o valor
    - Débito: que irá subtrair
[] Deve ser possível identificar o usuário entre as requisições;
[] O usuário só pode visualizar suas próprias transações;


# Requisitos Não Funcionais








# Cookies
São formas de manter o contexto entre requisições


# Testes automatizados

- Unitário: Testa exclusivamente uma unidade da aplicação, ouseja, uma pequena parte de forma isolada

- Integração: Testa a comunicação entre duas ou mais unidades

- e2e (ponta a ponta): Simula um usuário operando a aplicação
    - Pirâmede de teste:
        - e2e (Não dependem de tecnologia e de arquitetura para serem realizados) obs: Devem ser poucos
        - Integração devem ter mais que o e2e
        - Unitário devem ter muitos

- Para fazer um teste, instalou o vitest

- 3 pontos importantes na hora de realizar um teste
    - Chamada: Nome para o teste deve estar bem descrito para não ser confundido
    - Fazer a chamada HTTP para criar uma nova transação
    - Validação

# OBS
- Um teste jamais deve depender de outro para ser executado. Caso isso seja necessário, os teste devem estar dentro da mesma operação