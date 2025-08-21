Computação em nuvem é a entrega de serviços de computação—incluindo servidores, armazenamento, bancos de dados, rede, software, análise e inteligência—pela Internet ("a nuvem"). Em vez de possuir e manter sua própria infraestrutura de computação, você pode acessar esses serviços de um provedor de nuvem como a Microsoft (Azure), Amazon (AWS) ou Google (GCP).

Principais Vantagens:

Custo-benefício: Elimina a necessidade de comprar hardware e software, reduzindo os custos iniciais. Você paga apenas pelo que usa.
Escalabilidade Global: Permite que você dimensione seus recursos para cima ou para baixo de acordo com a demanda, em qualquer lugar do mundo.
Desempenho: Os serviços são executados em uma rede mundial de datacenters seguros, que são regularmente atualizados para a última geração de hardware.
Segurança: Provedores de nuvem oferecem um amplo conjunto de políticas, tecnologias e controles que fortalecem sua postura de segurança geral.
Velocidade e Agilidade: A maioria dos serviços de nuvem é provisionada em minutos, permitindo que você inove mais rapidamente.
Confiabilidade: A nuvem facilita e barateia o backup de dados, a recuperação de desastres e a continuidade dos negócios.

Modelos de Serviço em Nuvem
Existem três modelos principais de serviço em nuvem:

IaaS (Infraestrutura como Serviço): O modelo mais básico. Você aluga a infraestrutura de TI—servidores (máquinas virtuais), armazenamento e redes—de um provedor de nuvem. Você gerencia o sistema operacional e os aplicativos.
Exemplo: Máquinas Virtuais do Azure (VMs), Armazenamento do Azure.

PaaS (Plataforma como Serviço): Fornece um ambiente para desenvolver, testar, entregar e gerenciar aplicativos de software. A plataforma gerencia a infraestrutura subjacente (hardware e sistemas operacionais), permitindo que você se concentre no desenvolvimento.
Exemplo: Serviço de Aplicativo do Azure, Banco de Dados SQL do Azure.

SaaS (Software como Serviço): Fornece software sob demanda, geralmente por meio de uma assinatura. O provedor de nuvem gerencia tudo (infraestrutura, middleware, software de aplicativo e dados).
Exemplo: Microsoft 365, Gmail, Salesforce.

Modelos de Implantação em Nuvem

Nuvem Pública: Toda a infraestrutura de computação está localizada nas instalações do provedor de nuvem, que a opera e gerencia. Você acessa esses serviços e gerencia sua conta usando a Internet.
Exemplo: Microsoft Azure, AWS, Google Cloud.

Nuvem Privada: Os recursos de computação são usados exclusivamente por uma única empresa ou organização. Pode estar fisicamente localizada no datacenter local da organização ou ser hospedada por um provedor de serviços terceirizado.

Nuvem Híbrida: Combina nuvens públicas e privadas, permitindo que dados e aplicativos sejam compartilhados entre elas. Oferece às empresas maior flexibilidade e mais opções de implantação.

Principais Conceitos do Microsoft Azure (AZ-900)
O Azure é a plataforma de computação em nuvem da Microsoft. O exame AZ-900 se concentra nos seguintes pilares:

1. Conceitos Principais do Azure
Regiões e Zonas de Disponibilidade: O Azure possui uma presença global com datacenters organizados em Regiões. Cada região é um conjunto de datacenters. Dentro de uma região, existem Zonas de Disponibilidade, que são locais físicos separados com energia, refrigeração e rede independentes para garantir alta disponibilidade.

Grupos de Recursos: São contêineres lógicos para agrupar e gerenciar recursos do Azure relacionados (como VMs, contas de armazenamento e redes virtuais).
Azure Resource Manager (ARM): É o serviço de implantação e gerenciamento do Azure. Ele fornece uma camada de gerenciamento que permite criar, atualizar e excluir recursos em sua conta do Azure.

2. Principais Serviços do Azure
Computação:

Máquinas Virtuais (VMs): Servidores virtuais IaaS.

Serviços de Aplicativos: Plataforma PaaS para criar e implantar aplicativos da web e APIs.

Funções do Azure (Azure Functions): Serviço de computação "sem servidor" (serverless) que permite executar código acionado por eventos.

Instâncias de Contêiner do Azure (ACI) e Serviço de Kubernetes do Azure (AKS): Para implantar e gerenciar aplicativos em contêineres.

Armazenamento:

Armazenamento de Blobs: Armazenamento de objetos para grandes quantidades de dados não estruturados.

Armazenamento de Arquivos: Compartilhamentos de arquivos gerenciados na nuvem.

Armazenamento de Discos: Discos para VMs do Azure.

Banco de Dados:

Banco de Dados SQL do Azure: Banco de dados relacional gerenciado (PaaS).

Azure Cosmos DB: Banco de dados NoSQL globalmente distribuído e com vários modelos.

Rede:

Rede Virtual (VNet): Permite que os recursos do Azure se comuniquem com segurança entre si, com a Internet e com redes locais.

Balanceador de Carga (Load Balancer): Distribui o tráfego de entrada entre instâncias de serviço.

Gateway de VPN: Envia tráfego criptografado entre uma VNet do Azure e um local local pela Internet pública.

3. Segurança, Privacidade, Conformidade e Confiança
Azure Active Directory (Azure AD): Serviço de gerenciamento de identidade e acesso baseado em nuvem.

Autenticação Multifator (MFA): Camada adicional de segurança para o logon do usuário.

Grupos de Segurança de Rede (NSGs): Filtram o tráfego de rede para e de recursos do Azure em uma VNet.

Central de Segurança do Azure: Ferramenta para gerenciamento de postura de segurança e proteção contra ameaças.

Azure Policy e Blueprints: Para impor padrões e garantir a conformidade em toda a organização.

Central de Confiabilidade da Microsoft: Recurso para obter informações sobre segurança, privacidade e conformidade da Microsoft.

4. Preços e Gerenciamento de Custos do Azure
Modelos de Preços: Principalmente "pague pelo que usar". Alguns serviços têm preços baseados em níveis ou reservas.

Fatores que Afetam o Custo: Tipo de recurso, uso, localização (região) e largura de banda de saída.

Calculadora de Preços do Azure: Ferramenta para estimar os custos dos serviços do Azure.

Custo Total de Propriedade (TCO): Calculadora para comparar os custos de execução de cargas de trabalho no local versus no Azure.

Gerenciamento de Custos e Cobrança do Azure: Ferramenta para monitorar, controlar e otimizar os gastos no Azure.

Contratos de Nível de Serviço (SLAs): Compromissos da Microsoft sobre o tempo de atividade e a conectividade dos serviços.
