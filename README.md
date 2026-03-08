# DESAFIO-QA-BEEDOO-2026
## Objetivo da aplicação
A aplicação parece ser um sistema simples para cadastro e visualização de cursos.

## Principais fluxos
- Cadastrar curso
- Listar cursos

## Pontos críticos para teste
- Validação dos campos do cadastro
- Funcionamento do botão de salvar
- Atualização da lista de cursos
## Casos de teste

Planilha com cenários e casos de teste:
https://docs.google.com/spreadsheets/d/156ZLHZ_qHbW1OwFCO85XBRI4PMn-WbKRUf39aRbmipk/edit?usp=sharing

## Evidências dos testes
https://drive.google.com/drive/folders/1NVy89PT6C7ELHaHD1UHBOo5O1-NkSFBJ?usp=sharing

## Bugs encontrados

Durante os testes foram identificados alguns comportamentos inesperados:

- O sistema permite cadastrar curso sem preencher o campo "Nome do curso".
- O sistema permite cadastrar curso sem descrição.
- O sistema permite cadastrar curso sem datas de início e fim.

Esses comportamentos indicam ausência de validação de campos obrigatórios.
