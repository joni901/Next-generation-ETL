# 📑 Relatório Final: Análise de Evasão de Clientes (Churn)

## 1️⃣ Introdução
O objetivo desta análise é compreender os fatores que influenciam a evasão de clientes (Churn) em uma empresa de telecomunicações.  
A evasão ocorre quando o cliente encerra o contrato com a empresa, impactando diretamente a receita e sustentabilidade do negócio.  
A análise busca identificar padrões e comportamentos associados ao churn para embasar ações de retenção.

---

## 2️⃣ Distribuição das Variáveis

### 🔹 Evasão de Clientes (Churn)
- Não evadiram (0): **73,5%**  
- Evadiram (1): **26,5%**  

➡️ Aproximadamente 1 em cada 4 clientes cancela o serviço, percentual significativo que merece atenção.

### 🔹 Tipo de Contrato (Contract)
- Mês a Mês: 55,0%  
- Dois Anos: 24,1%  
- Um Ano: 20,9%  

➡️ A maioria tem contrato de curta duração, aumentando a probabilidade de evasão.

### 🔹 Método de Pagamento (PaymentMethod)
- Cheque eletrônico: 33,6%  
- Cheque enviado por correio: 22,9%  
- Transferência bancária (automática): 21,9%  
- Cartão de crédito (automático): 21,6%  

➡️ Cheque eletrônico é o mais utilizado e também associado a maior evasão.

### 🔹 Serviços de Internet e Adicionais
**Serviço de Internet (InternetService)**  
- Fibra Óptica: 44,0%  
- DSL: 34,4%  
- Sem Internet: 21,7%  

➡️ Fibra óptica apresenta maior propensão à evasão.

**Serviços Extras (DeviceProtection, TechSupport, StreamingTV, OnlineSecurity, OnlineBackup)**  
- Pouco contratados, padrão consistente: maior parte dos clientes não percebe valor adicional.

**Gênero (Gender)**  
- Masculino: 50,5%  
- Feminino: 49,5%  

➡️ Distribuição equilibrada, sem impacto direto.

**Múltiplas Linhas (MultipleLines)**  
- Não contratado: 48,1%  
- Contratado: 42,2%  
- Sem telefone: 9,7%  

➡️ Contratação equilibrada, sem grande impacto isolado no churn.

### 🔹 Variáveis Numéricas Relevantes
- **SeniorCitizen (Idosos):** pouco impacto isolado no churn.  
- **Partner (Tem parceiro) e Dependents (Dependentes):** distribuição equilibrada.  
- **Tenure (Tempo de permanência):** clientes que não evadiram têm tempo médio maior → forte indicador de risco.  
- **Charges.Monthly e Charges.Total:** clientes que evadiram têm mensalidades ligeiramente maiores; clientes que não evadiram têm cobranças totais maiores, compatível com maior tempo de permanência.  
- **Serviços binários (PhoneService, PaperlessBilling, Conta_Diaria):** isoladamente não explicam a evasão.

---

## 3️⃣ Insights Principais
- Contrato mês a mês é o maior risco → clientes sem vínculo longo têm maior chance de churn.  
- Fibra óptica apresenta maior evasão → pode indicar preço ou problemas de serviço.  
- Cheque eletrônico é método de pagamento mais usado e com maior evasão → risco associado.  
- Serviços extras pouco contratados → clientes não percebem valor adicional.  
- Tenure é crítico → clientes recentes têm maior risco.  
- Cobranças mensais mais altas podem gerar insatisfação.  
- Evasão de 26,5% → relevante, exige ações de retenção.

---

## 4️⃣ Recomendações
1. Incentivar contratos de 1 ou 2 anos com descontos ou benefícios.  
2. Criar campanhas de retenção para clientes que utilizam cheque eletrônico.  
3. Aumentar percepção de valor nos serviços adicionais (pacotes de segurança e suporte técnico).  
4. Investigar a experiência de clientes de fibra óptica, pois podem estar insatisfeitos.  
5. Implementar modelos de previsão de churn para identificar clientes em risco antes que cancelem.  
6. Fidelização de clientes novos: contratos mais longos com descontos.  
7. Gestão de preço: analisar clientes com mensalidades altas para entender percepção de custo-benefício.  
8. Campanhas segmentadas: direcionadas a clientes com tenure menor ou altos gastos mensais.  
9. Explorar comunicação e pacotes de valor agregado para serviços adicionais.
