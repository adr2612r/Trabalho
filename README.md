# Sistema de Gerenciamento Acadêmico

Projeto simples para gerenciamento de alunos, cursos e matrículas utilizando banco de dados relacional. O sistema permite armazenar informações básicas de alunos, cursos e suas matrículas, além de realizar consultas para facilitar o acompanhamento acadêmico.

---

## Índice

- [Descrição](#descrição)  
- [Estrutura do Banco de Dados](#estrutura-do-banco-de-dados)  
- [Instalação](#instalação)  
- [Criação das Tabelas](#criação-das-tabelas)  
- [Uso](#uso)  
- [Exemplos de Consultas](#exemplos-de-consultas)  
- [Tecnologias](#tecnologias)  
- [Contribuição](#contribuição)  
- [Licença](#licença)  
- [Autor](#autor)

---

## Descrição

Este projeto modela o sistema acadêmico básico com tabelas para armazenar dados de alunos, cursos e matrículas. Permite registrar alunos em cursos, acompanhar suas matrículas e realizar consultas importantes para gestão acadêmica.

---

## Estrutura do Banco de Dados

As principais tabelas são:

- **alunos**: informações dos alunos (id, nome, idade, email, criado_em)  
- **cursos**: dados dos cursos oferecidos (id, nome, carga_horaria)  
- **matriculas**: relação entre alunos e cursos com a data da matrícula (id, id_aluno, id_curso, data_matricula)

---

## Instalação

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seuusuario/sistema-academico.git
