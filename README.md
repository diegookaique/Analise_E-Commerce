# 🛒 Análise de Dados E-commerce: Aprofundamento de Analytics

---

### 🌟 A Contação de Histórias
Este projeto concentra-se na integração e análise inicial de dados de transações e clientes de um e-commerce. O principal objetivo é consolidar informações de duas fontes distintas para criar uma base de dados robusta, permitindo uma compreensão clara do comportamento do cliente e dos padrões de compra. Através da junção de dados de transações (`TB_TRANSACOES_PROJETO_ECOMM.csv`) e dados pessoais dos clientes (`TB_CLIENTES_PROJETO_ECOMM.csv`), criamos uma visão unificada essencial para futuras análises aprofundadas. O operador `JOIN` foi escolhido especificamente para combinar apenas os registros que possuem correspondência entre ambas as tabelas, garantindo consistência e evitando dados ausentes para uma análise mais precisa.

---

### 📊 Principais Descobertas e Insights
Até o momento, as principais realizações incluem:

*   **Integração de Dados:** Combinação eficiente de registros de transações e informações de clientes em um único DataFrame (`result_df`) utilizando SQL.
*   **Consistência e Gerenciamento de Dados:** Utilização de um banco de dados SQLite temporário para gerenciar a integração, facilitando consultas SQL e assegurando a integridade dos dados.
*   **Base para Análise:** Criação e exportação de um conjunto de dados consolidado (`dados_ecommerce_final.csv`), que serve como fundamento para análises futuras, como:
    *   Identificação de categorias de produtos populares.
    *   Análise da distribuição geográfica das vendas.
    *   Correlação entre dados demográficos dos clientes (gênero, cargo) e seus hábitos de compra.
    *   Estudo de tendências de preços por categoria de produto ou tipo de cartão.

(Aguarde por análises visuais e insights mais detalhados em futuras atualizações para dashboards! Lembre-se de usar `DISTINCT` ao criar métricas relacionadas a clientes no dashboard, para evitar dados repetidos devido a múltiplas transações.)

---

### 🛠️ Stack Tecnológico
*   **Ferramentas Principais:** Google Colab
*   **Linguagens de Análise:** Python, SQL (SQLite)
*   **Bibliotecas:** pandas, sqlite3
*   **Fontes de Dados:** Arquivos CSV (TB_TRANSACOES_PROJETO_ECOMM.csv, TB_CLIENTES_PROJETO_ECOMM.csv)
*   **Saída:** Arquivo CSV consolidado (`dados_ecommerce_final.csv`), Dashboard (a ser desenvolvido com PowerBI ou Looker Studio)

---

### 🚀 Como Ver o Projeto
Este projeto é um notebook do Google Colab. Para explorá-lo, basta abrir o notebook no Google Colab, executar as células e observar o processo de tratamento de dados e os resultados.

---

**Gostou da Análise?** Conecte-se para trocarmos experiências e ideias sobre projetos de dados!

🔗 **Meu LinkedIn:** [https://www.linkedin.com/in/diego-kaique-9ba3697b]

📧 **Contato:** [kaique_0208@hotmail.com]
