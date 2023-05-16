# Plano de Teste

E-COMMERCE SA 

*versão 0.1*

## Histórico das alterações

   Data    | Versão |    Descrição   | Autor(a)
-----------|--------|----------------|-----------------
16/05/2023 |  0.1   | Release incial | Moacir Neto


## 1 - Introdução

O presente plano de teste tem como objetivo garantir a qualidade e o bom funcionamento do nosso e-commerce, proporcionando uma experiência positiva aos usuários e clientes. O e-commerce em questão é uma plataforma online de vendas de produtos, onde os clientes podem realizar compras, efetuar pagamentos e acompanhar o status de seus pedidos. O objetivo principal é assegurar que todas as funcionalidades do e-commerce estejam em conformidade com os requisitos estabelecidos e que o sistema esteja livre de erros, oferecendo uma navegação intuitiva, segurança na transação e eficiência nas operações.

## Objetivos do Teste
- Verificar a funcionalidade correta de todas as principais características do e-commerce, como busca de produtos, adição ao carrinho, finalização de compra, pagamento e rastreamento de pedidos.
- Avaliar a usabilidade do sistema, garantindo que a navegação seja intuitiva e amigável para os usuários.
- Testar a segurança do e-commerce, protegendo as informações dos clientes e garantindo a integridade das transações.
- Avaliar o desempenho do e-commerce, verificando a capacidade de lidar com um grande número de acessos simultâneos e processar transações de forma eficiente.
- Identificar e corrigir quaisquer problemas, falhas ou erros encontrados durante os testes.

## Escopo do Teste
- Teste de funcionalidade: Verificar todas as funcionalidades principais do e-commerce, como registro de usuário, login, pesquisa de produtos, adição ao carrinho, finalização de compra, pagamento, cancelamento de pedidos, rastreamento de pedidos, entre outras.
- Teste de usabilidade: Avaliar a usabilidade do sistema, incluindo a facilidade de navegação, organização dos elementos na página, clareza das informações e facilidade de uso em dispositivos móveis.
- Teste de segurança: Avaliar a segurança do e-commerce, incluindo a proteção de informações pessoais dos clientes, a segurança das transações, a prevenção de ataques e a confidencialidade dos dados.
- Teste de desempenho: Verificar a capacidade do e-commerce em lidar com uma carga elevada de acessos e transações, avaliando o tempo de resposta, a escalabilidade e a estabilidade do sistema.



Também é possível apresentar aqui o programa que será testado.

## 2 - Requisitos a Testar

Requisitos a testar subdivididos em casos de uso e requisitos não-funcionais.

### Casos de uso:

| Identificador do caso de uso | Nome do caso de uso                                       |
| ---------------------------- | --------------------------------------------------------- |
| UC1                          | Realizar compra                                           |
| UC2                          | Acompanhar o status do pedido                             |

### UC1 - Realizar compra

- Verificar se o usuário consegue adicionar produtos ao carrinho de compras corretamente.
- Garantir que o usuário consiga visualizar o carrinho de compras e fazer ajustes necessários.
- Testar o fluxo de finalização da compra, incluindo a inserção de informações de entrega e pagamento.
- Verificar se o sistema processa o pagamento corretamente e conclui a compra.

### UC2 - Acompanhar o status do pedido

- Testar se o usuário consegue acessar sua conta no e-commerce.
- Verificar se o usuário pode navegar até a seção de pedidos.
- Testar a seleção de um pedido específico pelo usuário.
- Garantir que o usuário possa visualizar as informações detalhadas do pedido, incluindo status de entrega e histórico de atualizações.

## Requisitos Não-Funcionais

| Identificador do requisito | Nome do requisito                    |
| -------------------------- | ------------------------------------ |
| Req1                       | Desempenho                           |
| Req2                       | Segurança                            |

### Req1 - Desempenho

- Testar se o e-commerce é capaz de lidar com uma carga de acessos simultâneos sem comprometer o desempenho.
- Avaliar se o sistema atende ao critério de aceitação de processar, no mínimo, 100 transações por minuto sem falhas ou atrasos significativos.

### Req2 - Segurança

- Verificar se o e-commerce utiliza criptografia para proteger informações confidenciais, como dados de pagamento.
- Testar as medidas de prevenção de ataques, como SQL Injection e Cross-Site Scripting (XSS), para garantir a segurança das informações dos clientes e das transações realizadas.


## 3 - Lista de Telas do Sistema

1. Tela de login
2. Tela de registro de usuário
3. Tela de catálogo de produtos
4. Tela de detalhes do produto
5. Tela de carrinho de compras
6. Tela de finalização da compra
7. Tela de pagamento
8. Tela de confirmação de compra
9. Tela de histórico de pedidos
10. Tela de detalhes do pedido
11. Tela de perfil do usuário
12. Tela de configurações de conta
13. Tela de busca de produtos
14. Tela de promoções e ofertas
15. Tela de suporte ao cliente
16. Tela de notificações


## 4 -  Lista de Casos de Uso

| Identificador do caso de uso | Nome do caso de uso                                   |
| ---------------------------- | ----------------------------------------------------- |
| UC1                          | Realizar compra                                       |
| UC2                          | Acompanhar o status do pedido                         |
| UC3                          | Gerenciar catálogo de produtos                        |
| UC4                          | Administrar estoque                                   |
| UC5                          | Gerenciar promoções e descontos                       |
| UC6                          | Processar pagamentos                                  |
| UC7                          | Gerenciar pedidos                                     |
| UC8                          | Gerenciar clientes                                    |
| UC9                          | Configurar preferências de entrega e frete             |
| UC10                         | Suporte ao cliente                                   |
| UC11                         | Gerenciar relatórios e estatísticas                   |








## 4 - Tipos de teste

Esta seção deve conter os tipos de testes escolhidos para cada iteração do projeto.
Pode-se definir inicialmente apenas os tipos de testes que serão usadas na próxima iteração, mas é possível também já registrar eventuais tipos de teste que se espera utilizar nas demais iterações. 
Com base no guia de testes, indique os tipos de testes que melhor se adéquam aos requisitos, tipo da aplicação e seus recursos disponíveis e, caso necessário complemente ou forneça mais detalhes da técnica e dos critérios de completude sugeridos no guia para cada tipo de teste indicado.

- Teste de interface de usuário;
- Teste de performance;
- Teste de carga;
- Teste de stress;
- Teste de segurança e controle de acesso;
- Teste de instalação;
- Entre outros.

### 4.1 - Métodos da Classe 

Para teste de funcionalidade.
Aqui deve-se verificar se cada classe retorna o esperado.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.2 - Persistência de Dados

Para teste de integridade de dados e do banco de dados.
Aqui deve-se verificar se os dados não se perdem ao desligar o programa. Se o programa consegue se recuperar em caso de falha ou fechamento repentino.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se dados são mantidos após súbito desligamento do programa .
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema (x)
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.3 - Integração dos Componentes

Para teste de funcionalidade.
Aqui deve-se verificar se as classes e métodos conseguem fazer a integração entre elas para uma sequência de ações do programa.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            (x) manual
        </th>
        <th colspan="2">
            (x) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração (x)
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca (x)
        </th>
        <th colspan="2">
            Caixa preta (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.4 - Tempo de Resposta

Para teste de funcionalidade.
Aqui deve-se verificar se o tempo de respostas das ações do programa são consideradas aceitáveis.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            ( ) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.5 - Animação

Para teste de funcionalidade (para games, principalmente, mas não somente).
Aqui deve-se verificar se as animações existentes no programa são disparadas quando devem e se seguem uma sequência lógica.
Se possível usar teste automatizado.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            descreva aqui o objetivo
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            ( ) manual
        </th>
        <th colspan="2">
            ( ) automática
        </th>
    </tr>
    <tr>
        <th>
            Estágio do teste
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade ( )
        </th>
        <th>
            Aceitação ( )
        </th>
    </tr>
    <tr>
        <th>
            Abordagem do teste
        </th>
        <th colspan="2">
            Caixa branca ( )
        </th>
        <th colspan="2">
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Programador(es) ou equipe de testes
        </th>
    </tr>
</table>
<br/>

### 3.6 - Efeitos Sonoros


## 4 - Recursos

Esta seção deve descrever os recursos humanos, de ambiente de teste (hardware e software) e de ferramentas de automatização de testes necessários para execução dos testes que devem ser descritos nas subseções que seguem.

### 4.1 - Ambiente de teste - Software e Hardware

Descreva aqui o hardware e sua configuração, e o software. Por exemplo, o sistema operacional, browsers, servidor web, etc.
### 4.2 - Ferramenta de teste

Descreva aqui as ferramentas específicas de teste usadas no projeto.


## 5 - Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
projetar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
implementar teste  |         | dd/mm/aaaa     | dd/mm/aaaa
executar teste     |         | dd/mm/aaaa     | dd/mm/aaaa
avaliar teste      |         | dd/mm/aaaa     | dd/mm/aaaa
