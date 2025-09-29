# AZ-900 Lab – Armazenamento no Azure

📌 Sobre o Projeto

Este laboratório foi desenvolvido como parte da minha preparação para a certificação Microsoft Azure Fundamentals (AZ-900).O objetivo principal foi aprender a criar e gerenciar contas de armazenamento no Azure, além de compreender os modelos de redundância, camadas de acesso e estratégias de migração para a nuvem.

Durante o projeto, foi criada uma conta de armazenamento chamada: stotraininglab

⚠️ Observações Importantes para Nomeação da Conta

Deve ser único globalmente.

Contém 3 a 24 caracteres.

Somente letras minúsculas e números.

Sem caracteres especiais ou letras maiúsculas.

🗂 Funcionalidades Exploradas

A conta de armazenamento foi configurada para receber e gerenciar diferentes tipos de dados:

Blobs – armazenamento de objetos não estruturados, como imagens e vídeos.

Discos – armazenamento para máquinas virtuais.

Arquivos (Azure Files) – compartilhamentos SMB e NFS na nuvem.

Filas (Queues) – mensagens para comunicação entre componentes.

Tabelas (Tables) – dados estruturados NoSQL.

🔁 Modelos de Redundância Estudados

Analisei os modelos de replicação de dados oferecidos pelo Azure, entendendo seus níveis de proteção e disponibilidade:

Modelo	Descrição	Escopo de Replicação
LRS (Locally Redundant Storage)	Cópias dentro de uma única região	Alta durabilidade local
ZRS (Zone Redundant Storage)	Cópias em zonas de disponibilidade na mesma região	Alta resiliência regional
GRS (Geo-Redundant Storage)	Cópias entre duas regiões diferentes	Continuidade geográfica
GZRS (Geo-Zone Redundant Storage)	Combina ZRS + GRS	Máxima redundância e disponibilidade

🔥 Camadas de Acesso (Access Tiers)

As camadas foram estudadas para entender os custos e performance no armazenamento:

Camada	Uso Ideal	Custo
Quente (Hot)	Dados acessados com frequência	Mais caro para armazenar, mais barato para acessar
Frio (Cool)	Dados acessados raramente	Mais barato para armazenar, mais caro para acessar

📦 Estudo de Caso: Migração para o Azure

Foi explorado o processo de migração de dados e infraestrutura para a nuvem, incluindo cenários como:

Migração completa: servidores, bancos de dados e aplicativos.

Migração parcial: apenas bancos de dados ou aplicativos web.

Migração de servidores físicos usando soluções como:

Data Box Disk – discos físicos enviados à Microsoft para upload.

Data Box – dispositivo de armazenamento robusto para grandes volumes.

Data Box Heavy – para cargas extremamente grandes (petabytes).


🎯 Objetivos de Aprendizado

Compreender tipos de dados suportados pelo Azure Storage.

Aprender sobre redundância e resiliência de dados na nuvem.

Explorar estratégias de migração seguras e escaláveis.

Dominar ferramentas de gerenciamento como AzCopy e Azure Storage Explorer.
