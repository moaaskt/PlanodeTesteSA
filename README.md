# Plano de Teste <p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

E-COMMERCE SA 

*versão 0.1*

## Indice 

1. [Introdução](#introdução)
2. [Requisitos a testar](#Requisitos-a-Testar)
3. [Telas Do sistema](#Lista-de-Telas-do-Sistema)
4. [Lista de Casos de Uso](#Lista-de-Casos-de-Uso)
5. [Tipos de teste](#Tipos-de-teste)
6. [Métodos da Classe](#Métodos-da-Classe)
7. [Persistência de Dados](#Persistência-de-Dados)
8. [Integração dos Componentes](#Integração-dos-Componentes)
9. [Tempo de Resposta](#Tempo-de-Resposta)
10.[Recursos](#Recursos)
11.[Ambiente de Teste](#Ambiente-de-teste)
12.[Ferramenta de teste](#Ferramenta-de-teste)
13.[Cronograma](#Cronograma)

## Histórico das alterações

   Data    | Versão |    Descrição   | Autores(a)
-----------|--------|----------------|-----------------
16/05/2023 |  0.1   | Release incial | Moacir Silva,Breno,Vitor


## Introdução

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

## Requisitos a Testar

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


## Lista de Telas do Sistema

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


## Lista de Casos de Uso

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








## Tipos de teste

Nesta seção, descrevemos os tipos de testes que serão utilizados nas iterações do eCommerce, levando em consideração os requisitos, tipo da aplicação e recursos disponíveis.

1. Teste de interface de usuário:
   - Verificar a usabilidade do site, incluindo a navegabilidade, a aparência visual e a interação do usuário com os elementos da interface.
   - Testar a consistência do design e a correta exibição de elementos em diferentes dispositivos e navegadores.
   - Validar a funcionalidade dos botões, campos de entrada, formulários e fluxos de navegação.

2. Teste de desempenho:
   - Avaliar o tempo de resposta do sistema ao lidar com diferentes cargas de usuários.
   - Medir a velocidade de carregamento de páginas e recursos, como imagens e scripts.
   - Identificar gargalos de desempenho e otimizar o tempo de resposta do sistema.

3. Teste de carga:
   - Simular uma carga pesada de usuários e verificar o comportamento do sistema.
   - Avaliar se o sistema é capaz de lidar com um grande número de transações simultâneas.
   - Monitorar o consumo de recursos (CPU, memória, largura de banda) durante a carga.

4. Teste de estresse:
   - Realizar testes extremos para determinar o limite de capacidade do sistema.
   - Verificar como o sistema se comporta sob condições de alto estresse, como picos repentinos de tráfego ou grandes volumes de dados.
   - Identificar falhas de desempenho, estabilidade ou recuperação após situações de estresse.

5. Teste de segurança e controle de acesso:
   - Verificar a robustez da aplicação contra ameaças de segurança, como ataques de injeção, cross-site scripting (XSS) e falsificação de solicitação entre sites (CSRF).
   - Testar a eficácia dos mecanismos de autenticação e autorização, garantindo que apenas usuários autorizados tenham acesso a recursos sensíveis.
   - Avaliar a integridade dos dados e a confidencialidade das informações do usuário.

6. Teste de instalação:
   - Validar o processo de instalação do aplicativo eCommerce em diferentes ambientes (por exemplo, servidores de produção, ambientes de desenvolvimento, ambientes de teste).
   - Verificar se todos os componentes necessários são instalados corretamente e se a configuração está adequada.
   - Testar a compatibilidade com diferentes sistemas operacionais, versões de banco de dados ou outras dependências.



## Métodos da Classe

 Nesta seção, são apresentados os testes de funcionalidade realizados na classe "CarrinhoDeCompras", verificando se ela retorna os resultados esperados.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se a classe "CarrinhoDeCompras" calcula corretamente o valor total dos produtos adicionados.
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
            Equipe de testes
        </th>
    </tr>
</table>
<br/>


 Nesta seção, são apresentados os testes de funcionalidade realizados na classe "Produto", verificando se ela retorna os resultados esperados.
<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se a classe "Produto" calcula corretamente o desconto aplicado com base no preço original e no percentual de desconto.
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
            Equipe de testes
        </th>
    </tr>
</table>
<br/>



## Persistência de Dados

Nesta seção, descrevemos os testes de persistência de dados e do banco de dados realizados para verificar se os dados não se perdem ao desligar o programa e se o programa é capaz de se recuperar em caso de falha ou fechamento repentino.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se os dados são preservados ao desligar o programa e se o programa consegue se recuperar em caso de falha ou fechamento repentino.
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
            Unidade ( )
        </th>
        <th>
            Aceitação (x)
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
            Caixa preta ( )
        </th>
    </tr>
    <tr>
        <th>
            Responsável(is)
        </th>
        <th colspan="4">
            Equipe de testes
        </th>
    </tr>
</table>
<br/>

## Integração dos Componentes

Nesta seção, são apresentados os testes de funcionalidade realizados para verificar a integração entre as classes e métodos, garantindo que eles sejam capazes de executar uma sequência de ações do programa de forma correta.

<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se as classes e métodos são capazes de se integrar adequadamente para realizar uma sequência de ações do programa.
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
            Equipe de testes
        </th>
    </tr>
</table>
<br/>

## Tempo de Resposta
<br/>
<table>
    <tr>
        <th>
            Objetivo
        </th>
        <th colspan="4">
            Verificar se o tempo de resposta das ações do programa está dentro dos limites aceitáveis definidos.
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
            Unidade ( )
        </th>
        <th>
            Aceitação (x)
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
            Equipe de testes
        </th>
    </tr>
</table>
<br/>
  
## Recursos

Nesta seção, descrevemos os recursos necessários para a execução dos testes no contexto do eCommerce, incluindo recursos humanos, ambiente de teste e ferramentas de automatização.

### Recursos Humanos

- Equipe de testes: composta por um testador responsável pela execução dos testes e um desenvolvedor para auxiliar na configuração do ambiente de teste.


### Ferramentas de Automatização

- Cypress: ferramenta de automação de testes de interface de usuário.
- Mocha: framework de testes JavaScript para a execução de testes unitários.
- Chai: biblioteca de asserção para auxiliar na escrita de testes unitários.



### Ambiente de teste 

### Ambiente de Teste - Hardware

- Computador:
  - Processador: Intel Core i7-9700K 3.6GHz
  - Memória RAM: 16GB DDR4
  - Armazenamento: SSD 500GB

### Ambiente de Teste - Software

- Sistema Operacional: Windows 10 Professional 64 bits
- Navegadores:
  - Google Chrome: versão 98
  - Mozilla Firefox: versão 97
- Servidor Web: Apache Tomcat 9.0.58
- Banco de Dados: MySQL Server 8.0.27
- Linguagem de Programação: Java JDK 11.0.12
- IDE: Eclipse 2021-09 (ou outra IDE de sua escolha)




### Ferramenta de teste

- Cypress: Framework de automação de testes de interface de usuário. É utilizado para testar a funcionalidade e a usabilidade do eCommerce, simulando a interação do usuário com a aplicação por meio de scripts automatizados.

- JUnit: Framework de testes unitários para a linguagem de programação Java. É utilizado para escrever e executar testes unitários nas classes e métodos do eCommerce, verificando se cada unidade de código funciona conforme o esperado.

- Postman: Ferramenta de teste de API que permite enviar solicitações HTTP para o eCommerce e verificar as respostas recebidas. É utilizado para testar a integração e o comportamento das APIs do eCommerce.

- JMeter: Ferramenta de teste de desempenho que simula cargas de trabalho e avalia o desempenho do eCommerce em diferentes cenários de uso. É utilizado para testar a capacidade de resposta, escalabilidade e estabilidade do sistema em condições de alta carga.

- SonarQube: Plataforma de análise estática de código que verifica a qualidade e a conformidade do código-fonte do eCommerce. É utilizado para identificar possíveis problemas, como vulnerabilidades, duplicações de código e más práticas de programação.


## Cronograma

Tipo de teste      | Duração | data de início | data de término
-------------------|---------|----------------|-----------------
planejar teste     |   2hrs  | 29/03/2023     | 29/03/2023
projetar teste     |   12hrs | 19/04/2023     | 26/04/2023
implementar teste  |    nd   |     nd         | nd
executar teste     |    nd   |     nd         | nd
avaliar teste      |    nd   |     nd         | nd

