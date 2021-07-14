# test-hardware-bot

Teste para desenvolvedores em processo de seleção na [Married Games](https://marriedgames.com.br).

Esse teste consiste em construir um bot crawler que irá coletar dados de hardware como processadores, placa mãe, placa de vídeo...., gerará um banco de dados e então uma saída organizando todos os dados coletatos.

## Objetivo do teste

O teste tem como foco mostrar a criatividade do desenvolvedor em soluções de problemas muito incomuns, que é exatamente a especialidade da [Married Games](https://marriedgames.com.br)

### Problema
É necessário que seja coletado dados de hardware e suas caracteristicas e atributos, precisa listar como um comparativo de alternativas e mostrar quais outros hardware são compatíveis.

## Requisitos mínimos

- Deve usar uma linguagem ou stack de sua escolha.
- Deve considerar uma arquitetura/estrutura modular
- Códido limpo não é opcional
- Pense no problema apresentado e aplique a melhor solução não apenas como desenvolvedor, tente pensar a frente e além, seja criativo.
- Construa um banco de dados (relacional ou não) organizado e otimizado
- Crie uma API rest com autenticação 
- Exporte os dados para uma planilha XLS **OU** use uma API de um site wordpress (fake é claro) para inputar esses dados em um custom post type
- Docker, sim, microserviços, mostre que sabe fazer algo fácil de escalar (não é a toa que a estrutura é modular :P)
- Ao configurar o docker, lembre-se de não fixar nada a uma plataforma, deve rodar em linux, windows ou mac (se rodar em batata está contratado :p)
- Versionamento é importante, será avaliado não apenas commits, mas tbm branchs, fluxos, pull requests e será feito um code review a cada merge, então capriche.
- readme.md não é enfeite ok?

## Requisitos bonus
- Testes unitários, de integração e de componentes.
- Gerar uma interface onde seja possível visualizar as informações em uma interface amigável, contento busca e filtros.
- Dados adicionais e bem apresentados são bem vindos
- Domínio em Kubernetes, GCP/AWS são um diferencial enorme.

Pode usar serviços como Firebase sem problemas caso escolha uma aproximação serveless.
Ao finalizar o teste, entre em contato com o recrutador responsável e envie seu repositório.
