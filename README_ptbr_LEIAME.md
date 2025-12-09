> This document is also available in English: [README.md]
# Protótipo de Apuração e Pagamento de Vendedores em Campanhas de Vendas

## Visão Geral
Este repositório contém um protótipo completo para apuração e cálculo de premiação de vendedores em campanhas de vendas, utilizando dados simulados, SAP Datasphere, SAP Analytics Cloud (SAC) e automação em Python. O projeto foi desenvolvido com foco em aprendizado, engajamento e compartilhamento de boas práticas para a comunidade de dados e vendas.

---

## Objetivos
- Demonstrar como integrar dados simulados (Python/CSV) ao SAP Datasphere.
- Modelar regras de negócio complexas para campanhas de vendas.
- Automatizar cálculos de premiação por faixas, segmentos e grupos de produto.
- Visualizar resultados e KPIs em dashboards interativos no SAC.
- Compartilhar conhecimento e engajar profissionais via LinkedIn e GitHub.

---

## Estrutura do Repositório
```
/dados
  - fato_faturamento.csv
  - dim_vendedor.csv
  - dim_cliente.csv
  - dim_supervisao.csv
  - dim_gerencia.csv
  - dim_diretoria.csv
  - dim_produto.csv
  - dim_grupo_produto.csv
  - fato_meta.csv
  - fato_pontuacao.csv
  - dim_faixa_pontuacao.csv
/scripts
  - gerador_dados.py
  - ingestao_datasphere.sql
/documentacao
  - arquitetura.md
  - regras_negocio.md
  - fluxograma.md
/dashboards
  - exemplos_sac.png
/linkedin
  - post1_planejamento.md
  - post2_modelagem.md
  - post3_regras_negocio.md
  - post4_dashboards.md
  - post5_governanca.md
```

---

## Como Reproduzir o Protótipo
1. **Gerar os dados simulados**
   - Execute o script `gerador_dados.py` para criar os arquivos CSV das tabelas fato e dimensão.

2. **Importar os dados para o SAP Datasphere**
   - Utilize o script SQL `ingestao_datasphere.sql` ou o assistente de upload do Datasphere para importar os arquivos CSV.

3. **Modelar as tabelas e relacionamentos**
   - Siga o diagrama ER em `/documentacao/arquitetura.md` para criar as tabelas e relacionamentos no Datasphere.

4. **Implementar as regras de negócio**
   - Consulte `/documentacao/regras_negocio.md` para detalhes das regras de campanha, faixas de pontuação e cálculos de premiação.

5. **Construir dashboards no SAC**
   - Importe os dados modelados e utilize os exemplos em `/dashboards` para criar visualizações interativas.

6. **Compartilhar e engajar**
   - Utilize os templates de posts em `/linkedin` para divulgar aprendizados e resultados no LinkedIn.

---

## Colaboração
- Sinta-se à vontade para abrir Issues com dúvidas, sugestões ou melhorias.
- Pull Requests são bem-vindos! Veja o guia de contribuição em `/documentacao/contribuicao.md`.
- Compartilhe este repositório em suas redes sociais e marque pessoas que possam se beneficiar do conteúdo.

---

## Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

## Contato
Para dúvidas, sugestões ou parcerias, entre em contato pelo meu perfil no LinkedIn: [https://www.linkedin.com/in/aandradepro/](https://www.linkedin.com/in/aandradepro/)
