# Site Econometria Aplicada à Finanças 2025.2

Site oficial da disciplina **Econometria Aplicada à Finanças** do Mestrado Profissional em Administração do IFMG Campus Formiga.

## Descrição

Website desenvolvido com [Quarto](https://quarto.org) contendo:
- Programa completo da disciplina
- Cronograma detalhado das aulas
- Instruções para configuração do ambiente computacional
- Materiais de apoio e recursos didáticos
- Informações sobre avaliações e projeto empírico

## Tecnologias

- **Quarto**: Sistema de publicação científica
- **HTML**: Formato de saída principal
- **CSS**: Estilização customizada
- **GitHub Pages**: Hospedagem (diretório `docs/`)

## Estrutura

```
├── _quarto.yml       # Configuração do projeto Quarto
├── index.qmd         # Página inicial
├── programa.qmd      # Programa da disciplina
├── cronograma.qmd    # Cronograma das aulas
├── ambiente.qmd      # Ambiente computacional
├── styles.css        # Estilos customizados
├── docs/             # Site renderizado (GitHub Pages)
├── slides/           # Apresentações das aulas
└── arquivos/         # Materiais auxiliares
```

## Comandos Úteis

```bash
# Renderizar o site
quarto render

# Visualizar localmente
quarto preview

# Renderizar e publicar
quarto publish
```

## Acesso

O site é automaticamente publicado via GitHub Pages no diretório `docs/` após cada renderização.

---
**Autor:** Prof. Dr. Washington Santos da Silva  
**Período:** 2025.2  
**Instituição:** IFMG Campus Formiga