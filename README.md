# FullStack Challenge

Olá, esse é um teste focado em boas práticas de desenvolvimento, conhecimento de *design patterns* e orientação à objetos.

O objetivo é avaliar a experiência do desenvolvedor em escrever código de fácil manutenção, acoplamento baixo e altíssima coesão.

Sempre mantendo em mente o princípio K.I.S.S.

## O Problema

A empresa *Cachinhos de Ouro* precisa desenvolver um sistema para gerenciar seus clientes, produtos e pedidos realizados.

## Estrutura de dados

Foi especificado que o sistema deveria seguir o padrão de domínios abaixo:

* Clientes;
* Produtos;
* Pedidos;

Cada domínio compreende uma série de campos básicos entre eles.

#### Clientes

Os campos básicos do domínio **Cliente** são os seguintes:
* email (unique)
* name
* password
* cpf (integer)

#### Produtos

Os campos básicos do domínio **Produtos** são os seguintes:
* sku (unique)
* product_name

#### Pedidos

Os campos básicos do domínio **Pedidos** são os seguintes:
* order_id
* order_stamp
* client_id

### Entity Relationship

O sistema deve possuir relação entre os domínios, de forma a facilitar a busca e compreensão da modelagem de dados utilizada.

## Pré-requisitos técnicos

Os pré-requisitos técnicos para o desenvolvimento dessa tarefa são:

* Usar Laravel como framework para o backend;
* Usar um framework front-end;
* Usar banco de dados relacional (MySQL ou PostgreSQL) para persistir as informações;
* Cobertura de testes unitário e integração no backend;
* Criar documentação explicativa e sucinta para rodar o projeto.

## Avaliação

Para prosseguirmos com a avaliação, você deve enviar uma cópia de seu código. Há duas formas de realizar isso facilmente:

* Fazer um *fork* do repositório e enviar um *Pull Request* com suas alterações;
* Criar um repositório no *Github* para o usuário desenvolvedor@precopratico.com.br;

Caso opte pela criação do *Pull Request*, lembre-se de deixá-lo explicativo, apontando quais são os passos necessários para rodar a aplicação.

## Dicas

* Aproveite os melhores recursos das ferramentas utilizadas. Diversificando a implementação e mostrando seu domínio sobre cada uma delas;
* Opte por escrever o código mais limpo e claro possível. *Uncle Bob* e seu *Clean Code* tem um lugar especial em nossos corações.
* Mostre algo inovador e surpreendente para nós. Estamos cansados do feijão com arroz básico.

Qualquer dúvida técnica, envie uma mensagem para [desenvolvedor@precopratico.com.br](desenvolvedor@precopratico.com.br).

Você terá quatro dias para realizar essa tarefa após receber o nosso contato.

Boa Sorte!
