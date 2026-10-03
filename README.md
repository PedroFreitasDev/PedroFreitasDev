<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=00D4AA&center=true&vCenter=true&width=620&lines=%3E+Iniciando+pipeline%3A+pedro_freitas.py;%3E+Extraindo+dados+brutos...;%3E+Transformando+em+Engenheiro+de+Dados...;%3E+Status%3A+Pronto+para+um+est%C3%A1gio+%E2%9C%94" alt="Typing SVG" />

# `pipeline: pedro_freitas`

**Futuro Engenheiro de Dados** · Ciência da Computação @ UNIFEOB · Formatura 2027

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro_Freitas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-freitas-b3b43a261)
[![Email](https://img.shields.io/badge/Email-pedrodefreitas13@hotmail.com-00D4AA?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:pedrodefreitas13@hotmail.com)
![Status](https://img.shields.io/badge/status-open__to__internship-success?style=for-the-badge)

</div>

```mermaid
flowchart LR
    S[("🧑‍💻 SOURCE<br/>Pedro Freitas")] --> E["🟢 EXTRACT<br/>quem sou"]
    E --> T["🟡 TRANSFORM<br/>stack & skills"]
    T --> L["🔵 LOAD<br/>projetos"]
    L --> V["🟣 SERVE<br/>contato"]
    V --> H{{"🎯 sua_empresa"}}
```

---

## 🟢 STAGE 1 · `EXTRACT` — quem sou

```python
pedro = {
    "nome":       "Pedro Freitas",
    "formacao":   "Ciência da Computação — UNIFEOB (5º semestre, formatura 2027)",
    "foco":       "Engenharia de Dados",
    "objetivo":   "Estágio em Dados",
    "gosto_de":   ["pipelines", "ETL/ELT", "modelagem de dados", "dados limpos e confiáveis"],
    "mentalidade": "dado bruto não é problema, é matéria-prima",
}
```

> Gosto de pegar dados bagunçados, entender de onde vêm, limpar, modelar e entregá-los prontos para gerar decisão.

---

## 🟡 STAGE 2 · `TRANSFORM` — stack

| Camada | Ferramentas | Status |
|:--|:--|:--|
| **Linguagem** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | ✅ `success` |
| **Consulta & Modelagem** | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ✅ `success` |
| **Manipulação de dados** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | 🔄 `running` |
| **Transformação (ELT)** | ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) | 🔄 `running` |
| **Containers** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | 🔄 `running` |
| **Versionamento** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) | ✅ `success` |

<details>
<summary><b>📋 Ver log de execução</b></summary>

```log
[2026-10-01 08:00:01] INFO  task=python_fundamentals      status=SUCCESS  (scripts, automações, bots)
[2026-10-01 08:00:02] INFO  task=sql_modeling             status=SUCCESS  (modelagem, joins, consultas otimizadas)
[2026-10-01 08:00:03] INFO  task=pandas_dataframes        status=RUNNING  (limpeza e transformação de dados)
[2026-10-01 08:00:04] INFO  task=dbt_models               status=RUNNING  (modelos, testes e documentação)
[2026-10-01 08:00:05] INFO  task=docker_containers        status=RUNNING  (ambientes reproduzíveis)
[2026-10-01 08:00:06] WARN  task=first_data_internship    status=PENDING  aguardando oportunidade... 👀
```

</details>

---

## 🔵 STAGE 3 · `LOAD` — projetos

| Projeto | Descrição | Stack |
|:--|:--|:--|
| 🧾 [**Sistema-de-Gestao**](https://github.com/PedroFreitasDev/Sistema-de-Gestao) | Sistema de gestão de usuários e produtos via terminal, com CRUD e organização dos dados. | `Python` |
| 🌐 [**PI-DesenvolvimentoWEB-Unifeob-2025**](https://github.com/PedroFreitasDev/PI-DesenvolvimentoWEB-Unifeob-2025) | Projeto integrador em equipe resolvendo um problema real, com integração front-end ↔ back-end. | `HTML` `Bootstrap` `JS` |

### 🗺️ Próximos deploys (roadmap)

- [ ] 🛠️ **Pipeline ETL end-to-end** — extrair dados de uma API pública, tratar com Pandas e carregar em banco SQL
- [ ] 🧱 **Projeto dbt** — camadas `staging → intermediate → marts` com testes de qualidade de dados
- [ ] 🐳 **Ambiente de dados com Docker** — banco + pipeline rodando com um único `docker compose up`
- [ ] 📊 **Modelagem dimensional** — esquema estrela (fato + dimensões) a partir de dados reais

---

## 📈 Métricas do pipeline

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PedroFreitasDev&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PedroFreitasDev&layout=compact&theme=tokyonight&hide_border=true" />
  <br/>
  <img height="165" src="https://streak-stats.demolab.com?user=PedroFreitasDev&theme=tokyonight&hide_border=true" />
</div>

---

## 🟣 STAGE 4 · `SERVE` — vamos conversar?

```sql
SELECT contato, link
FROM   pedro_freitas.canais
WHERE  interesse = 'vaga_de_estagio_em_dados';
```

| contato | link |
|:--|:--|
| 💼 LinkedIn | [linkedin.com/in/pedro-freitas-b3b43a261](https://www.linkedin.com/in/pedro-freitas-b3b43a261) |
| 📧 E-mail | [pedrodefreitas13@hotmail.com](mailto:pedrodefreitas13@hotmail.com) |

<div align="center">

```
✔ Pipeline finalizado com sucesso · 0 erros · 1 dev pronto para aprender e entregar
```

<sub>Obrigado pela visita! Se chegou até aqui, a próxima task é sua: <code>send_message()</code> 🚀</sub>

</div>
