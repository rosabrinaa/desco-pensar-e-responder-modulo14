# Implementando métodos no Repositório, além dos herdados da interface JpaRepository.

O Spring Data JPA fornece alguns métodos de manipulação de dados, chamados de queries derivadas. Nesta API, há um exemplo de método derivado: trata-se do “findByUserEmail”, do repositório UserRepository. Com isso, foram implementados alguns métodos adicionais, a saber:

ProjetoRepository: buscar pela descrição do projeto;
RecursoRepository: buscar pelo nome do recurso;
TarefaRepository: buscar pelo status da tarefa.
