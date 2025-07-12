# Inception / Kick-off

## Visão do Produto
Desenvolver uma aplicação web intuitiva que permita carregar ficheiros CSV de vendas e stock, processar esses dados e gerar dashboards interativos (vendas por mês, top 5 produtos, estado de stock), com filtros por data e produto e opção de exportação de gráficos.

## Stakeholders
- **Cliente / Utilizador Final**: equipa de gestão financeira e de operações  
- **Product Owner (PO)**: responsável por validar requisitos e aceitação  
- **Scrum Master**: garante cumprimento do processo Scrum  
- **Equipa de Desenvolvimento**: front-end, back-end, DevOps, UX/UI  

## Objetivos de Alto Nível
1. Permitir upload de ficheiros CSV com validação automática.  
2. Processar e armazenar os registos numa base de dados relacional.  
3. Criar três dashboards iniciais:  
   - Vendas por mês  
   - Top 5 produtos  
   - Estado de stock  
4. Disponibilizar filtros por intervalo de datas e por produto.  
5. Exportar cada gráfico para PDF ou PNG.

## Âmbito Inicial
### Incluído
- Formulário de upload de CSV com validação de colunas mínimas (data, produto, quantidade, valor)  
- Processamento em batch e persistência na base de dados  
- Implementação dos três dashboards básicos  
- Filtragem dinâmica nos dashboards  
- Funcionalidade de exportação de gráficos (PDF/PNG)  

### Excluído (fora do MVP)
- Conexão direta a sistemas ERP  
- Alertas automáticos por e-mail/Teams  
- Controlo de acessos e comentários colaborativos  
- Agendamento automático de relatórios

## Critérios de Sucesso
- Upload e processamento de CSV testados com dados reais de amostra  
- Dashboards visíveis e filtráveis no navegador  
- Exportação de gráfico verificada em PDF e PNG  
- Feedback positivo do PO nas primeiras demos internas
