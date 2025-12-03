# Particionamento e Armazenamento no Azure Cosmos DB

Particionamento é fundamental para escalar coleções e distribuir carga.

## 🔹 Tipos de particionamento
- **Horizontal (sharding)** – Cosmos DB particiona automaticamente.
- **Partition key** – Define como os dados serão distribuídos.

## 🔹 Melhor escolha da chave de partição
- Alta cardinalidade
- Distribuição uniforme
- Evitar hotspots
- Acessos frequentes distribuídos

## 🔹 Armazenamento
Cosmos DB armazena documentos JSON e replica automaticamente entre regiões.

Documentação oficial:  
https://learn.microsoft.com/azure/cosmos-db/partitioning-overview
