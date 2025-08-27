# Gerenciamento de estoque de floricultura com POO 
## Descrição
Desenvolvimento de um sistema de gerenciamento de insumos de uma Floricultura, como trabalho de conclusão da disciplina "UC4" do curso "Técnico em Desenvolvimento de Sistemas"

## Informações
**Equipe:** Luan Almada e Pedro Vitor  
**Disciplina:** UC4 - Analisar Programação Estruturada e Orientada a Objetos  
**Professor:** Tarik Ponciano 

## O programa
<h4><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="20px"/> Desenvolvido em Python </h4>

### Fluxo da aplicação:

1. Verificação de usuários autorizados:
    - Login
        - Se gerente - Cadastrar novo funcionário *  **_(a implementar)_**
2. Menu de navegação
    1. Listar produtos
    2. Cadastrar novo produto
    3. Editar produto
    4. Excluir produto
    5. Registrar chegada de insumos
    6. Calcular promoção
    7. Verificar estoque* **_(a implementar)_**
    8. Sair  
    _ Verificar validade de produtos * **_(a implementar)_**  
    _ Verificar viabilidade de entrega * **_(a implementar)_**

### Classes utilizadas:
- ### Produto 
    **Atributos:** ID + Nome + Preço + Quantidade em estoque 
    **Métodos:**
    - Registro de chegada de insumo;
    - Calculo de preço promocional;
    - Verificação de estoque e necessidade de reposição* **_(a implementar)_**;
    - Getters e setters;

- ### Flor(Produto)
    **Atributos:**  Atributos herdados + Tempo de vida útil + Data da colheita  
    **Métodos:**
    - Métodos herdados
    - Verificar viabilidade entrega
    - Getters e setters;

- ### Funcionario    
    **Atributos:**  id + nome + senha  
    **Métodos:**
    - Login
    - Getters e setters;

- ### Gerente(Funcionario)
    **Atributos:** Atributos herdados + cargo="gerente"
    **Métodos:**  
    - Métodos herdados
    - Cadastrar Funcionario * **_(a implementar)_**

## Requisitos propostos na atividade (resumo)
1. Classes e Estrutura
    - O projeto deve conter pelo menos 3 classes;
    - Pelo menos 1 classe pai (superclasse) e 1 classe filha (subclasse);
    - No mínimo 3 atributos;
    - No mínimo 2 métodos próprios.
    - Utilizar getters e Setters para todos os atributos.

2. Herança
    - A classe filha deve herdar atributos e métodos da classe pai.

3. Polimorfismo
    - Utilizar polimorfismo para que métodos herdados possam ser redefinidos e alterandos para atender necessidades específicas.

4. Aplicativo
    - Sistema acessível via terminal;
    - Menu de opções para executar operações que modifiquem e/ou utilizem os dados armazenados nas classes.
    - Uso adequado dos métodos para acesso e modificação de informações (evitar manipulação direta de atributos fora das classes).

5. Boas Práticas
    - Código organizado e comentado.
    - Nomenclaturas seguindo convenções de programação.
    - Uso coerente de POO: encapsulamento, herança, polimorfismo.
