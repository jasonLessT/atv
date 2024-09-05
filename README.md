### Questão 1: Sistema de Gestão Escolar com POO em Python

#### Contextualização:
Você foi contratado por uma escola para desenvolver um sistema simples que simula a gestão de informações de alunos e professores, aplicando os conceitos de Programação Orientada a Objetos (POO). O sistema será usado pela equipe da escola para gerenciar o cadastro de alunos, professores e suas respectivas disciplinas. A solução deve ser capaz de rodar em loop até que o usuário escolha a opção de finalizar o programa. Durante a execução, o sistema permitirá adicionar alunos, professores e disciplinas, além de exibir a lista de registros cadastrados.

O foco dessa atividade é utilizar os quatro pilares da POO:
1. **Abstração**: Criação de classes que representam objetos do mundo real (aluno, professor, disciplina).
2. **Encapsulamento**: Controle de acesso aos dados das classes.
3. **Herança**: Compartilhamento de atributos e métodos entre classes relacionadas.
4. **Polimorfismo**: Uso de métodos com o mesmo nome em diferentes classes com comportamentos distintos.

#### Comando:
Implemente um sistema orientado a objetos em Python que contenha as seguintes funcionalidades:

1. Crie uma classe `Pessoa` com os atributos básicos como nome e idade. A classe `Pessoa` deve ter métodos para exibir as informações básicas.
   
2. Crie duas classes derivadas de `Pessoa`, chamadas `Aluno` e `Professor`. Ambas herdarão os atributos e métodos da classe `Pessoa`, mas devem ter características específicas:
   - **Aluno**: Terá um atributo adicional `matricula` e métodos para exibir as informações de um aluno.
   - **Professor**: Terá um atributo adicional `disciplina` e métodos para exibir as informações de um professor.

3. Crie uma classe `Escola`, que será responsável por gerenciar os objetos de `Aluno` e `Professor`. A classe `Escola` deve permitir:
   - Adicionar um novo aluno.
   - Adicionar um novo professor.
   - Exibir todos os alunos cadastrados.
   - Exibir todos os professores cadastrados.

4. O sistema deve funcionar em um loop infinito até que o usuário selecione a opção de sair, permitindo o uso das opções mencionadas acima por meio de um menu.

#### O que você deve fazer:
1. Implementar as classes `Pessoa`, `Aluno`, `Professor` e `Escola` conforme descrito.
2. Implementar um menu em loop que permita:
   - Cadastrar alunos e professores.
   - Listar os alunos e professores cadastrados.
   - Sair do sistema.

O código deve ser funcional no console, onde o usuário poderá interagir com o sistema, e deve ser possível cadastrar quantos alunos e professores forem necessários até que o usuário decida finalizar.

---


---

### Tabela de Testes:

| Cenário                 | Input                                                         | Resultado Esperado                                                 |
|-------------------------|---------------------------------------------------------------|--------------------------------------------------------------------|
| 1. Adicionar um Aluno    | Nome: "Carlos", Idade: "16", Matrícula: "12345"               | Aluno "Carlos" é adicionado à lista de alunos                      |
| 2. Adicionar um Professor| Nome: "João", Idade: "40", Disciplina: "Matemática"           | Professor "João" é adicionado à lista de professores               |
| 3. Listar Alunos         | Após adicionar Carlos                                         | Lista de alunos exibe "Carlos" com sua matrícula e idade           |
| 4. Listar Professores    | Após adicionar João                                           | Lista de professores exibe "João" com sua disciplina e idade       |
| 5. Escolher opção inválida| Entrada: "6"                                                 | Mensagem de erro "Opção inválida, tente novamente." exibida        |

---
