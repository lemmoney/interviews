# Test Lemoney Node.js 

### O que queremos avaliar? 

1 - Capacidade de resolver problema 

2 - Aplicação de conceitos de programação ( Clean Code - Commit Semântico - Padrões de Projetos - SOLID)

3 - É capaz de questionar/comunicar ( dúvidas - impedimentos -sugestões)


### Qual problema devo resolver?

A Lemoney possui como um de seus projetos o OpenCashback como api de serviço. Que gerência para um contratante sua estrutura de cashback em sua loja. Nesse contexto o desafio é implementar uma pequena aplicação com um front e um back que crie essa dinâmica onde um usuário irá cadastrar via interface um [programa de cashback](#programa-de-cashback), possuindo, um **identificador de produto**, **valor de programa em reais**, **valor do programa em porcentagem**, **status**, **data de início**, **data de fim**. E esse Back deve expor para o mundo um endpoint que ao passarmos o **identificador de produto** e o **valor do Produto** retorne quando de cashback o cliente terá caso compre o mesmo. 

**FRONT**: 

**Requisitos Mínimos**

+ Criar form de criação de programas
+ Listar programas criados 
+ Editar Programas criados
+ Deletar programas criados 

**Liberdades**:

> Escolher o frameworks. bibliotecas e layout livres.
>
> __Sugestão__: Usar Vue.js



**BACK**:

**Requisitos Mínimos**

 + CRUD de programas de cashback
 + Endpoint de quanto de cashback o produto terá

 **Liberdades**: 
> Escolher framework in Node.jS
>
> __Sugestão__: Usar  Fastify com TypeORM


### Observações 

1 - Mesmo sugerindo frameworks específicos você é livre para usar qualquer framework no front e qualquer framework de Node.js no back.  

2  - O projeto deve ser entregue em repositório do github se possível usando uma imagem docker para facilitar a compatibilidade.


 ## Glossário 

 ## Programa de Cashback

 O programa de cashback é um conjunto de regras como valor e data de validade de um cashback. Portanto se tenho um produto que custa R$100,00 vinculado a um programa que me dá 10% de cashback. No final terei um retorno de R$10,00 de cashback.
