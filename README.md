# Sales Campaign Prototype: Vendor Bonus Calculation

## Overview
This repository contains a complete prototype for calculating vendor bonuses in sales campaigns using simulated data, SAP Datasphere, SAP Analytics Cloud (SAC), and Python automation. The project focuses on learning, engagement, and sharing best practices with the data and sales community.

---

## Objectives
- Demonstrate how to integrate simulated data (Python/CSV) into SAP Datasphere.
- Model complex business rules for sales campaigns.
- Automate bonus calculations based on ranges, segments, and product groups.
- Visualize results and KPIs in interactive dashboards using SAC.
- Share knowledge and engage professionals via LinkedIn and GitHub.

---

## Repository Structure
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

## How to Reproduce the Prototype
1. **Generate simulated data**
   - Run `data_generator.py` to create CSV files for fact and dimension tables.

2. **Import data into SAP Datasphere**
   - Use `datasphere_ingestion.sql` or the Datasphere upload wizard to import CSV files.

3. **Model tables and relationships**
   - Follow the ER diagram in `/documentation/architecture.md` to create tables and relationships in Datasphere.

4. **Implement business rules**
   - See `/documentation/business_rules.md` for campaign rules, scoring ranges, and bonus calculations.

5. **Build dashboards in SAC**
   - Import modeled data and use examples in `/dashboards` to create interactive visualizations.

6. **Share and engage**
   - Use LinkedIn post templates in `/linkedin` to share insights and results.

---

## Collaboration
- Feel free to open Issues for questions, suggestions, or improvements.
- Pull Requests are welcome! Check the contribution guide in `/documentation/contribution.md`.
- Share this repository on your social networks and tag people who might benefit from the content.

---

## License
This project is distributed under the MIT license. See the `LICENSE` file for details.

---

## Contact
For questions, suggestions, or partnerships, reach out via my LinkedIn profile: [https://www.linkedin.com/in/aandradepro/](https://www.linkedin.com/in/aandradepro/)
