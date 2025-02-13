# resumo-do-lab

- Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
  
# 📌 Principais Tópicos Abordados:
- **Fundamentos da Computação em Nuvem**: Conceitos essenciais, benefícios, modelos de serviço e os principais provedores do mercado.  
- **Serviços da Azure**: Implementação e gerenciamento de máquinas virtuais, soluções de armazenamento, redes, bancos de dados e outros recursos essenciais.  
- **Gerenciamento e Monitoramento**: Utilização do **Azure Portal, Azure CLI e ferramentas de automação** para otimizar a administração de recursos na nuvem.

# 📌 Criação de uma Máquina Virtual
- Processo passo a passo para provisionar uma VM na Azure, incluindo escolha da imagem, configuração de rede, segurança e escalabilidade.
- Comparação entre IaaS (Infraestrutura como Serviço), PaaS (Plataforma como Serviço) e SaaS (Software como Serviço),LRS e GRs, destacando suas aplicações e vantagens.

# 📌 Configurando uma Instância de Banco de Dados na Azure
- A Azure oferece diversas opções para hospedar bancos de dados na nuvem, permitindo escalabilidade, segurança e gerenciamento simplificado. A configuração de uma instância de banco de dados na Azure envolve os seguintes passos:

# Tipos de Banco de Dados
- Azure SQL Database (SQL Server gerenciado na nuvem).
- Azure Database for MySQL (Banco de dados MySQL gerenciado).
- Azure Database for PostgreSQL (PostgreSQL gerenciado).
- Azure Cosmos DB (Banco de dados NoSQL altamente escalável).

# Conexão ao Banco de Dados
- Utilizar Azure Data Studio, SQL Server Management Studio (SSMS) ou clientes MySQL/PostgreSQL.
- Conectar via String de Conexão fornecida no Azure Portal.
- Implementar SSL/TLS para conexões seguras.

# 📌 Construindo Arquiteturas no Azure

# Criação de um Grupo de Recursos e Implementação de uma VNet no Azure

- No portal do Azure, vá para "Grupos de Recursos" e clique em "Criar".
Escolha uma assinatura, defina um nome e selecione uma região.
Confirme e crie o grupo de recursos.

- No portal do Azure, acesse "Virtual Networks" e clique em "Criar".
Escolha o grupo de recursos recém-criado.
Defina um nome para a VNet e escolha uma região compatível.

- Revise as configurações e clique em "Criar" para provisionar a VNet.
