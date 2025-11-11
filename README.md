# exercicioBancoSQL
Exercicios de select's em uma banco db_escola


Parte 1: Questões Simples (SELECT, WHERE, LIKE, ORDER BY)

1. Liste o nome completo e o id_aluno de todos os estudantes cadastrados, ordenando pelo nome do aluno.

![img](image-2.png)
![img](image-3.png)


2. Quais são as siglas e os nome_curso de todos os cursos que possuem exatamente 1200 horas de carga_horaria?
![img](image-4.png)
![img](image-5.png)

3. Exiba o nome e a especialidade de todos os docentes que são especializados em 'Programação'.
![img](image-6.png)
![img](image-7.png)


4. Liste o id_sala, numero_sala e capacidade de todas as salas que são do tipo 'TEORICA'.
![img](image-8.png)
![img](image-9.png)

5. Quais são as sigla_turma que ocorrem no turno 'TARDE'?
![img](image-10.png)
![img](image-11.png)

6. Encontre o id_aluno e o nome do aluno cujo ID é 149.
![img](image-12.png)
![img](image-13.png)

7. Liste o nome_sala e o numero_sala de todas as salas que têm uma capacidade máxima de 30.
![img](image-15.png)
![img](image-16.png)

8. Quais cursos (apenas a sigla) têm 1000 horas de carga horária?
![img](image-17.png)
![img](image-18.png)

9. Liste o nome dos alunos cujo nome começa com a letra 'W'.
![img](image-19.png)
![img](image-20.png)

10. Exiba o nome e a especialidade do docente com id_docente igual a 7.
![img](image-21.png)
![img](image-22.png)

11. Liste todas as siglas de turmas que têm o turno 'NOITE' e cujo id_curso_fk é 2 (TII).
![img](image-23.png)
![img](image-24.png)

12. Liste o nome de todos os alunos que nasceram exatamente em doze de março de dois mil e cinco.
![img](image-25.png)
![img](image-26.png)

13. Quais turmas (siglas) foram alocadas no Lab de Hardware?
![img](image-27.png)
![img](image-28.png)

14. Liste o id_curso e o nome_curso de todos os cursos, exceto aqueles com carga_horaria menor ou igual 800 horas.
![img](image-29.png)
![img](image-30.png)

15. Liste os nomes de todos os docentes que não são especializados em 'Enfermagem'.
![img](image-31.png)
![img](image-32.png)

Parte 2: Questões Moderadas (JOINs Simples)

16. Liste o nome e o id_aluno de todos os alunos que estão matriculados na turma com id_turma_fk igual a 17 (ENF01). (Use tb_alunos e tb_aluno_turma).
![img](image-33.png)
![img](image-34.png)

17. Qual é o nome do curso correspondente ao id_curso = 10?
![img](image-35.png)
![img](image-36.png)

18. Liste o nome dos docentes que estão qualificados para o curso cujo id_curso_fk é 19.
![img](image-37.png)
![img](image-38.png)

19. Encontre a sigla_turma e o turno de todas as turmas que estão alocadas na sala com id_sala_fk igual a 11 (Laboratório de Enfermagem).
![img](image-39.png)
![img](image-40.png)

20. Liste a sigla do curso e o nome_curso para todas as turmas cujo id_turma esteja entre 56 e 60. (Use tb_turmas e tb_cursos).
![img](image-41.png)
![img](image-42.png)

21. Liste a nome_sala de todas as salas que são utilizadas por turmas do turno 'MANHA'.
![img](image-43.png)


22. Liste o id_docente e o nome dos professores que estão qualificados para o curso de 'Redes de Computadores' (id_curso = 5).
![img](image-44.png)
![img](image-45.png)

23. Liste o nome dos alunos que estão matriculados na turma de sigla 'SGT04'.
![img](image-46.png)
![img](image-47.png)

24. Encontre o nome_curso de todas as turmas que estão alocadas na sala 'Laboratório de Hardware'.
![img](image-48.png)
![img](image-49.png)

25. Liste o id_aluno_turma e o id_aluno_fk para todas as matrículas no ADM08.
![img](image-50.png)
![img](image-51.png)

Parte 3: Questões Complexas (Multi-JOINs e Filtros Específicos)

26. Liste o nome do aluno e a sigla_turma para todos os alunos que estão matriculados na turma TI25.
![IMG](image-52.png)
![IMG](image-53.png)

27. Encontre o nome do docente e o nome_curso para as associações onde o docente tem id_docente = 3.
![img](image-54.png)
![img](image-55.png)

28. Liste a sigla_turma e o nome_sala para as turmas do curso 'Administração' que estão alocadas em salas com capacidade igual a 40..
![img](image-56.png)
![img](image-57.png)

29. Liste o nome de todos os alunos que estão matriculados na turma TI26 OU na turma TI30.
![img](image-58.png)
![img](image-59.png)

30. Liste os nomes de todas as salas que são do tipo 'LABORATORIO' E que possuem uma capacidade menor que 35.
![img](image-60.png)
![img](image-61.png)

31. Liste o nome_curso de todos os cursos para os quais a docente 'Diana Prince' está qualificado.
![img](image-62.png)
![img](image-63.png)

32. Qual é a sigla_turma e o nome_curso de todas as turmas que utilizam a sala 'Laboratório de Enfermagem'?
![img](image-64.png)
![img](image-65.png)

33. Liste o nome dos alunos que estão matriculados na turma 'TI29'.

34. Liste o nome do docente e a sigla do curso para as qualificações do docente com id_docente_fk = 5.

35. Liste a sigla_turma e o nome_curso para as turmas que pertencem aos cursos TI (id_curso = 1) OU TII.

36. Liste o nome_curso de todos os cursos, excluindo 'Técnico em Informática' (id_curso = 1).

37. Encontre o nome_sala e a sigla_turma para as turmas do turno 'NOITE' que estão alocadas em salas de tipo 'TEORICA'.

38. Liste o nome do aluno e o id_turma_fk para as matrículas com id_aluno_fk igual a 40 (The Narrator).

39. Liste a sigla_turma e o nome_curso para as turmas cujo curso tenha a carga_horaria de 800 horas.

40. Encontre o nome e a especialidade do docente que tem o id_docente 11.

41. Liste a sigla_turma e o nome_curso para as turmas cujo turno é 'MANHA'. (Use tb_turmas e tb_cursos).

42. Liste o nome_sala e o numero_sala para salas com capacidade diferente de 40.

43. Liste o nome dos alunos que estão matriculados nas turmas que utilizam a sala de id_sala = 7. (Use tb_alunos, tb_aluno_turma, tb_turmas).

44. Liste o nome_curso e a carga_horaria para cursos com carga_horaria maior que 1000 horas.

45. Encontre a sigla_turma e o turno para as turmas cujo id_curso_fk é 8 (Enfermagem) e que estão alocadas na id_sala_fk 11.

46. Liste o nome dos docentes que são especializados em 'Administração'.

47. Liste o id_aluno, nome e data_nascimento para os alunos com 
