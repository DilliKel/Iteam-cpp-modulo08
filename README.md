# Módulo 08 — Linguagem de Programação C++

> Repositório de exercícios, projetos e materiais do **Módulo 08** do curso de Capacitação em Desenvolvimento Full Stack do **ITEAM**.

**Professora:** Érika Dilliany Gaya Rabêlo dos Santos  
**Carga horária:** 40 horas  
**Turma:** [@RKayky](https://github.com/RKayky) · [@DilliKel](https://github.com/DilliKel) · [@iany-jess](https://github.com/iany-jess)

---

## Estrutura do Repositório

```
modulo08/
├── material/                          # PDFs das aulas e apostila
├── exercicios/
│   ├── aula03-entrada-saida/          # cin, cout, iomanip
│   ├── aula05-repeticao/              # for, while, do-while
│   └── aula06-excecoes/               # try/catch/throw + revisão integrada
├── Projeto-Bolao-Copa-2026/           # Projeto prático (aula 10/06)
└── .gitignore
```

---

## Exercícios por Aula

### Aula 3 — Entrada e Saída de Dados
| Arquivo | Descrição |
|---------|-----------|
| [exercicios/aula03-entrada-saida/idade.cpp](exercicios/aula03-entrada-saida/idade.cpp) | Leitura de idade com `cin` e formatação de saída com `iomanip` |

### Aula 5 — Estruturas de Repetição
| Arquivo | Descrição |
|---------|-----------|
| [exercicios/aula05-repeticao/tabuada5.cpp](exercicios/aula05-repeticao/tabuada5.cpp) | Tabuada do 5 com laço `for` |
| [exercicios/aula05-repeticao/testeryan.cpp](exercicios/aula05-repeticao/testeryan.cpp) | Verificação simples de senha com `if/else` |

### Aula 6 — Exceções e Revisão Integrada
| Arquivo | Descrição |
|---------|-----------|
| [exercicios/aula06-excecoes/login.cpp](exercicios/aula06-excecoes/login.cpp) | Sistema de login com 3 tentativas, `try/catch/throw` e validação de campos vazios |

---

## Projeto Principal

### Bolão da Copa 2026
Projeto prático desenvolvido na aula de 10/06/2026. Programa de console em C++ para bolão de apostas da Copa do Mundo com suporte a múltiplos apostadores, pontuação automática e ranking.

**Acesse:** [Projeto-Bolao-Copa-2026/](Projeto-Bolao-Copa-2026/) — veja o [README completo do projeto](Projeto-Bolao-Copa-2026/README.md).

---

## Progresso do Curso

| Aula | Tema | Exercício entregue |
|------|------|--------------------|
| 1 | Introdução ao C++ | — |
| 2 | Variáveis, Tipos e Operadores | — |
| 3 | Entrada/Saída (`cin`/`cout`/`iomanip`) | `idade.cpp` |
| 4 | Condicionais (`if/else`, `switch`) | — |
| 5 | Repetição (`for`, `while`, `do-while`) | `tabuada5.cpp`, `testeryan.cpp` |
| 6 | Exceções (`try/catch/throw`) | `login.cpp` |
| 7 | Funções (valor e referência) | aplicado em `bolao.cpp` |
| 8 | Ponteiros e Alocação Dinâmica | — |
| 9 | POO — Classes e Objetos | — |
| 10 | Herança e Polimorfismo | — |
| 11 | Templates, STL e Arquivos | — |

---

## Material de Apoio

| Arquivo | Conteúdo |
|---------|----------|
| [material/Apostila-Modulo08.pdf](material/Apostila-Modulo08.pdf) | Apostila completa do módulo (aulas 1–11) |
| [material/Slides-Aula-08.06.2026.pdf](material/Slides-Aula-08.06.2026.pdf) | Slides — Aulas 1, 2 e 3 |
| [material/Slides-Aula-09.06.2026.pdf](material/Slides-Aula-09.06.2026.pdf) | Slides — Aulas 4, 5, 6 e 7 |
| [material/Slides-aulas-11~12.06.2026.pdf](material/Slides-aulas-11~12.06.2026.pdf) | Slides — Aula 8 (Ponteiros) |
| [material/Atv-Pratica-aula-10.06.2026.pdf](material/Atv-Pratica-aula-10.06.2026.pdf) | Enunciado da atividade prática (Bolão) |

---

## Como Compilar

```bash
# Qualquer exercício
g++ exercicios/aula06-excecoes/login.cpp -o login

# Projeto principal
g++ Projeto-Bolao-Copa-2026/bolao.cpp -o bolao
```

**Requisito:** GCC instalado ([MinGW-w64](https://www.mingw-w64.org/) no Windows).
