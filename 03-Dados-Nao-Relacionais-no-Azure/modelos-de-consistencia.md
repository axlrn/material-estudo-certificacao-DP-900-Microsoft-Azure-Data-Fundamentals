# Modelos de Consistência no Azure Cosmos DB

Consistência define como e quando os dados replicados se tornam iguais entre diferentes regiões.

## 🔹 Os 5 modelos de consistência
1. **Strong** – Maior consistência, menor desempenho.  
2. **Bounded Staleness** – Consistência com atraso configurável.  
3. **Session** – Modelo padrão; forte dentro da sessão do cliente.  
4. **Consistent Prefix** – Ordem garantida, mas dados podem estar atrasados.  
5. **Eventual** – Mais rápido; eventual convergência.

## 🔹 Trade-offs
Mais consistência → mais latência  
Menos consistência → mais performance

Documentação oficial:  
https://learn.microsoft.com/azure/cosmos-db/consistency-levels
