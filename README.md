# Testes Automatizados - Faculdade Projeção

## Descrição

Este repositório contém os scripts e a documentação referentes ao projeto de testes automatizados desenvolvidos para o site da Faculdade Projeção, como parte da disciplina de Métricas e Qualidade de Software do curso de Tecnologia em Análise e Desenvolvimento de Sistemas (TADS).

O projeto tem como objetivo validar funcionalidades e fluxos de navegação do portal institucional por meio de testes funcionais automatizados utilizando Selenium IDE.

## Objetivos

* Verificar o correto funcionamento dos links e páginas do site da Faculdade Projeção;
* Automatizar a validação de fluxos de navegação da aplicação;
* Reduzir a necessidade de testes manuais repetitivos;
* Identificar possíveis falhas de navegação e redirecionamento;
* Documentar os resultados obtidos durante a execução dos testes.

## Escopo dos Testes

Os testes contemplam funcionalidades relacionadas ao ambiente da Faculdade Projeção, incluindo:

* Registro e validação de diplomas;
* Calendários acadêmicos;
* Fale Conosco;
* Núcleo de Extensão;
* Mídias institucionais;
* Página Institucional;
* Unidades da Faculdade;
* Notícias;
* Cursos de Tecnologia;
* Cursos de MBA na área de Gestão.

Não fazem parte do escopo os conteúdos relacionados ao Colégio Projeção e aos Cursos de Extensão externos ao ambiente da Faculdade.

## Tecnologias Utilizadas

| Tecnologia      | Versão                         |
| --------------- | ------------------------------ |
| Selenium IDE    | 3.17.4                         |
| JavaScript      | Utilizado nos scripts de apoio |
| Mozilla Firefox | 151.0.3                        |
| GitHub          | Controle de versão             |
| Windows         | 11                             |

## Ambiente de Teste

* Sistema Operacional: Windows 11
* Navegador: Mozilla Firefox 151.0.3
* Ferramenta de Teste: Selenium IDE 3.17.4
* URL Base: https://projecao.br/faculdade

## Casos de Teste Implementados

| ID     | Caso de Teste        |
| ------ | -------------------- |
| CT-001 | Diplomas             |
| CT-002 | Calendários          |
| CT-003 | Fale Conosco         |
| CT-004 | Extensão             |
| CT-005 | Mídias               |
| CT-006 | Institucional        |
| CT-007 | Unidades             |
| CT-008 | Notícias             |
| CT-009 | Cursos de Tecnologia |
| CT-010 | MBA - Gestão         |

## Estratégia de Validação

Os scripts utilizam validações baseadas em:

* Verificação de textos presentes nas páginas (`assert text`);
* Confirmação de carregamento correto dos conteúdos;
* Registro das URLs acessadas por meio de comandos JavaScript (`execute script`) e logs (`echo`);
* Validação dos fluxos de navegação definidos no roteiro de testes.

## Resultados Obtidos

| Métrica                   | Resultado |
| ------------------------- | --------- |
| Casos de Teste Planejados | 18        |
| Casos de Teste Executados | 18        |
| Casos Aprovados           | 18        |
| Casos Reprovados          | 0         |
| Casos Bloqueados          | 0         |
| Taxa de Sucesso           | 100%      |

## Observações

Durante a execução foi identificado que a execução simultânea de todos os scripts pode ocasionar comportamentos inconsistentes, mesmo sem falhas nos testes individuais.

Por esse motivo, recomenda-se executar os testes de acordo com as suítes definidas no projeto, garantindo maior estabilidade e confiabilidade nos resultados.

## Estrutura do Repositório

```text
/
├── script/
│   ├── acessar_faculdade_projecao.side
│   
│   
│   
├── docs/
│   ├── Plano_de_Teste.pdf
│   ├── Roteiro_de_Teste.pdf
│   └── Evidencias/
└── README.md
```

## Autor

Marcos Vinícius Ribeiro Gonçalves

Curso: Tecnologia em Análise e Desenvolvimento de Sistemas (TADS)

Disciplina: Métricas e Qualidade de Software

Turma: TADS 4AM

Ano: 2026
