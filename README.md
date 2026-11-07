# Docking Report - Projeto Pyladies 2026
Projeto para desenvolver um pacote python que organiza os resultados de docking de vários ligantes e receptores.

# 📅 Cronograma de Desenvolvimento — Docking Report

**Projeto:** Docking Report — Gerador Automático de Relatórios de Docking Molecular  
**Grupo:** PyLadies  
**Período:** 18/10/2026 a 06/12/2026

## 🎯 Objetivo geral

Desenvolver uma ferramenta em Python capaz de ler arquivos de saída do AutoDock Vina, extrair os valores de energia de afinidade previstos, organizar os resultados em tabelas, gerar gráficos comparativos e produzir um relatório resumido automaticamente.

## 🗓️ Etapas do projeto

### 1. 08/11 — Planejamento e leitura dos arquivos

**Objetivo:** compreender o formato dos arquivos de saída do AutoDock Vina e estruturar o projeto.

- [X] Definir os objetivos e os requisitos mínimos do programa.
- [X] Conhecer a estrutura dos arquivos de saída de Docking Molecular.
- [X] Selecionar ou criar arquivos de exemplo para os testes.
- [X] Identificar as informações que serão extraídas, como número da pose, energia de afinidade e valores de RMSD, quando disponíveis.
- [X] Criar a estrutura inicial do repositório no GitHub.
- [X] Implementar a leitura de um arquivo individual.

**Entrega:** repositório inicial e protótipo capaz de ler um arquivo de saída.

### 2. 16/11 — Extração e organização dos resultados

**Objetivo:** desenvolver o processamento automático de múltiplos arquivos.

- [ ] Implementar a extração das energias de afinidade previstas.
- [ ] Identificar as poses de cada ligante.
- [ ] Processar arquivos de diferentes ligantes e receptores.
- [ ] Organizar os resultados em tabelas utilizando `pandas`.
- [ ] Tratar arquivos vazios, formatos inesperados e dados ausentes.
- [ ] Exportar os resultados para CSV.

**Entrega:** script capaz de processar vários arquivos e gerar uma tabela consolidada.

### 3. 23/11 — Visualização e geração de relatórios

**Objetivo:** transformar os dados extraídos em resultados visuais e interpretáveis.

- [ ] Criar gráficos comparativos com `Matplotlib`.
- [ ] Comparar as energias de afinidade entre ligantes.
- [ ] Identificar automaticamente os melhores valores de afinidade previstos.
- [ ] Gerar um resumo textual dos resultados.
- [ ] Exportar os gráficos em formato PNG.
- [ ] Integrar a leitura, o processamento e a visualização em um único fluxo.

**Entrega:** primeira versão funcional do gerador automático de relatórios.

### 4. 29/11 — Testes, documentação e publicação

**Objetivo:** finalizar o projeto e disponibilizá-lo para a comunidade.

- [ ] Testar o programa com diferentes arquivos de entrada.
- [ ] Corrigir erros e melhorar o tratamento de exceções.
- [ ] Organizar o código em funções reutilizáveis.
- [ ] Incluir arquivos de exemplo e resultados demonstrativos.
- [ ] Documentar as limitações da ferramenta.
- [ ] Revisar o repositório e publicar a versão inicial.

### 5. 06/12 — Encerramento
**Entrega:** versão inicial publicada no GitHub, com código funcional, documentação e exemplos de uso.

## 🧰 Ferramentas

- **Python:** linguagem principal.
- **pandas:** organização e exportação de tabelas.
- **Matplotlib:** geração de gráficos comparativos.
- **Módulos padrão do Python:** leitura de arquivos, manipulação de diretórios e tratamento de erros.
- **Git e GitHub:** controle de versão, colaboração e documentação.
- **Autodock Vina

