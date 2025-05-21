# Resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# Módulo 1: Introdução a nuvem:

Durante o módulo do curso, aprendi sobre as diferenças entre nuvens, como:

- Nuvem Pública: Nuvem pública são nuvens de serviços remotos disponibilizados por provedores terceirizados (como AWS, Azure, GCP) através da internet. Os recursos (servidores, armazenamento, aplicativos) são compartilhados entre múltiplos clientes, e geralmente o modelo de cobrança é "pague pelo que usar".

- Nuvem Privada: Nuvem privada é uma infraestrutura de nuvem dedicada a uma única organização. Ela pode ser hospedada no data center da própria empresa (on-premises) ou em um data center de um provedor terceirizado, mas os recursos são exclusivos para o uso daquela organização. Isso oferece maior controle e segurança, mas geralmente envolve custos iniciais e de manutenção mais elevados.

- Nuvem Híbrida: Uma nuvem híbrida combina elementos de nuvens públicas e privadas, permitindo que dados e aplicativos sejam compartilhados entre elas. Isso oferece flexibilidade para aproveitar os benefícios de cada tipo de nuvem, como escalabilidade da nuvem pública para cargas de trabalho variáveis e segurança da nuvem privada para dados sensíveis.

Alem disto, aprendi sobre CapEx e OpEx:

CapEx (Despesas de Capital): São gastos com bens de capital, ou seja, investimentos em ativos de longo prazo que a empresa utilizará por um período superior a um ano para gerar receita. Estes ativos geralmente têm um valor significativo.
alguns exemplos: Compra de máquinas e equipamentos, Investimentos em tecnologia da informação (servidores, softwares com licenças permanentes) ou até grandes reformas ou melhorias em ativos existentes que aumentam sua vida útil ou capacidade produtiva.

O CapEx representa um investimento no futuro da empresa, visando aumentar a capacidade, a eficiência ou a vida útil dos seus ativos.

OpEx (Despesas Operacionais): São os gastos do dia a dia necessários para manter as operações normais da empresa e gerar receita no período corrente (geralmente em um ano ou menos).
alguns exemplos: Salários e encargos dos funcionários, Contas de serviços públicos (água, luz, telefone, internet), Assinaturas de softwares e serviços em nuvem (geralmente pagos periodicamente) ou Aluguel de escritórios e instalações.

Os gastos de OpEx são reconhecidos como despesas no período em que ocorrem, sendo diretamente lançados na demonstração do resultado do exercício (DRE), reduzindo o lucro da empresa naquele período.

O OpEx é essencial para o funcionamento contínuo do negócio.

# Módulo 2: Beneficios da Nuvem:

## Benefícios da Nuvem

* Alta disponibilidade
* Escalabilidade
* Elasticidade
* Confiabilidade
* Previsibilidade
* Segurança
* Governança
* Gerenciabilidade

- Alta disponibilidade: O Azure oferece acordos de nível de serviço (SLAs) que garantem diferentes níveis de disponibilidade, minimizando o tempo de inatividade do sistema ao longo do ano.
  
- Escalabilidade: A escalabilidade refere-se á capacidade de ajustar recursos para atender certa demanda. Antecipando picos de tráfego, como a Black Friday, as empresas podem escalar seus clusters no Azure, garantindo a capacidade do sistema para lidar com o aumento da demanda e evitar interrupções.

- Elasticidade: A elasticidade é a capacidade do sistema de alocar e desalocar recursos automaticamente em resposta a demanda em tempo real. Quando a demanda diminui, ele automaticamente libera os recursos extras. Isso garante que você pague apenas pelos recursos que realmente está usando no momento.

- Confiabilidade: Por conta da descentralização de servidores no mundo todo, a nuvem contem uma infraestrutura confiável, acasso aconteça catastrofes em uma região que um servidor está, trazendo indisponibilidade dele mesmo, vai haver outra regiões do mundo para suportar a demanda.

- Previsibilidade: O Azure disponibiliza recursos para prever o custo e desempenho dos serviços.

- Segurança: A Nuvem oferece ferramentas de segurança como por exemplo: Microsoft Defender for Cloud. Ele previne certas ameaças contra o sistema.(Há certa implementações de seguranças devem ser realizadas pelo cliente).

- Governança: A auditoria baseada em nuvem pode ajudar a sinalizar recursos que esteja fora da conformidade, com padrões corporativos, podendo manter a nuvem atualizada, protegida e gerenciada.

- Gerenciabilidade: gerenciar seu ambiente nuvem e seus recursos, Por exemplo: Portal WEB, Interface de linha de comando, API's ou PowerShell.

Tudo em nuvem de ser organizado, é importante otimizar os investimentos e evitar gastos desnecessários, a migração e a operação de recursos na nuvem exigem análises claras, organização estruturada e a definição clara de objetivos estratégicos.

# Módulo 3: Tipos de Serviços na nuvem:

- IaaS (Infraestrutura como serviço)
- PaaS (Plataforma como serviço)
- SaaS (Software como serviço)

  - IaaS:
    Na Infraestrutura como serviço o cliente tem como responsabilidade quase toda infraestrutura do Servidor/Sistema, a nuvem apenas detem a parte fisica de Host, Datacenter e Rede.
  - PaaS:
    Plataforma como serviço a nuvem define o sistema operacional e divide com o cliente a responsabilidade com a implementação de aplicativos e controles de rede, por exemplo.
  - SaaS:
    Com Software como serviço o cliente praticamente toma conta apenas das informações e dados do Servidor/Sistema, Compartilha a infraestrutura de identidade com a nuvem, e a nuvem toma conta das outras responsabilidades(SaaS podem ser serviços prontos de Assinatura)


![image](https://github.com/user-attachments/assets/eb46a338-bde1-4118-b600-dfcca3dedc2e)

# Módulo 4: Componentes de arquitetura Azure:

- Pares de Regiões em Nuvem:
Pares de regiões em nuvem são uma arquitetura projetada para fornecer alta disponibilidade dentro de uma determinada região. Trata-se de datacenters interligados localizados em regiões próximas, com o objetivo de reduzir os riscos de indisponibilidade de sistemas na nuvem devido a falhas de rede ou infraestrutura. Por exemplo, em um estado do Brasil pode haver três datacenters interconectados. Caso um deles fique inoperante, os outros dois continuam mantendo a operação, embora isso possa resultar em um aumento na latência.

- Regiões soberanas do Azure:
  As Regiões Soberanas do Azure são regiões específicas da infraestrutura de nuvem da Microsoft projetadas para atender a requisitos rigorosos de segurança, conformidade e soberania de dados. Essas regiões são isoladas das regiões comerciais padrão e destinam-se a organizações governamentais ou instituições altamente reguladas, como as dos Estados Unidos e China. Acesso restrito e controle sobre os dados armazenados, com foco na soberania e privacidade de dados.

- Assinaturas do Azure:
  Uma assinatura no Azure é uma unidade lógica de serviços e recursos em nuvem, associada a uma conta do Azure. Ela serve para organizar recursos, controlar acesso e gerenciar cobrança.
  -Isolamento de ambientes: separa desenvolvimento, teste e produção.
  
  -Gerenciamento de recursos: facilita o controle e a governança.

  -Limites e cotas: cada assinatura tem seus próprios limites de uso.

  -Cobrança separada: útil para distribuir custos por projeto, cliente ou setor.
  
  (uma conta pode haver varias assinaturas, uma assinatura deve responder para apenas uma conta).


# Módulo 5: Computação e rede Azure:
- A computação do Azure é um serviço sob demanda que fornece recursos de computação como discos, processadores, memória, rede e sistemas operacionais.
- A azure tem conjuntos de disponibilidades de VM, ou seja:
   ![image](https://github.com/user-attachments/assets/d5002c93-4130-4e82-aa9e-a2e7fece70e1)

  Resumidamente você pode configurar suas maquinas virtuais de forma "duplicada" em varios Rack's dentro de dominios de falhas, quando um dominio para de funcionar outro vai suportar o funcionamento das VMS em ordem horizontal.

Área de trabalho virtual do Azure é um virtualização de área de trabalho e aplicativo executada na nuvem.
- Beneficios:
  - Reduz o risco de que o recurso seja deixado para trás.
  - implantação reais de várias sessões.
  - Cria um ambiente de virtualização da área de trabalho sem precisar executar outros servidores de gateway.

Serviços de contêineres do Azure fornece um ambiente leve e virtualizado que não exige o gereciamento do sistema operacional e pode responder a alterações sob demanda.
  - Instâncias de Contêiner do Azure: uma oferta de PaaS que executa um contêiner ou pod de contêineres no Azure.
  - Aplicativos de Contêiner do Azure: uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar.
  - Serviço de Kubernetes do Azure: um serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes de contêineres.
 
- Azure functions: Uma oferta de PaaS que dá suporte a operações de computação sem servidor.
"como se fosse low code"

"lift-and-shift"




Contêineres:

- Os aplicativos e serviços são empacotados em um contêiner que fica na parte superior do sistema operacional do host. Vários contêineres podem ficar em um sistema operacional do host.

Serviços de Aplicativo do Azure:
  -Trabalha com .NET, .NET Core, Node.js, Java, Python ou PHP.
  -Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade.

Serviços de rede do Azure:

- A Rede Virtual do Azure (VNet) permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as redes locais.
- Pontos de extremidade públicos, acessíveis de qualquer lugar com acesso à Internet.
- Pontos de extremidade privados, acessíveis somente de dentro da sua rede.
- O ExpressRoute estende as redes locais para o Azure por meio de uma conexão privada facilitada por um provedor de conectividade.

![image](https://github.com/user-attachments/assets/943581c6-b750-481d-8b20-d549d7f6e058)


DNS do Azure

- Facilidade de uso para gerenciar seus recursos externos e do Azure com um único serviço DNS.
- As redes virtuais personalizáveis permitem que você use nomes de domínio privados e totalmente personalizados em suas redes virtuais privadas.

# Módulo 7: Language Studio e Serviço de Bot do Azure:
Durante este módulo, aprendi sobre os recursos de inteligência artificial voltados para linguagem natural e automação de conversas que o Azure oferece, como o Azure Language Studio e o Azure Bot Service.

Azure Language Studio
O Language Studio é uma plataforma baseada na nuvem que permite experimentar, treinar e implementar modelos de linguagem natural com facilidade. Ele faz parte do Azure AI Language, que oferece vários recursos de processamento de linguagem natural (NLP), como:

- Análise de sentimentos: detecta o tom emocional de um texto (positivo, neutro ou negativo).

- Extração de entidades: identifica informações relevantes em um texto, como nomes, datas, localizações, etc.

- Reconhecimento de linguagem: identifica automaticamente o idioma do conteúdo textual.

- Classificação personalizada de texto: permite treinar modelos para classificar texto de acordo com categorias definidas.

- Extração de frases-chave: identifica os principais tópicos de um texto.

Essas funcionalidades permitem automatizar processos, extrair valor de grandes volumes de texto e melhorar a interação homem-máquina. O uso do Language Studio é facilitado por uma interface gráfica no portal do Azure, sem necessidade de escrever código inicialmente, o que agiliza a prototipação de soluções de IA.

Azure Bot Service
O Azure Bot Service é uma plataforma que permite criar, hospedar, gerenciar e integrar bots inteligentes com outros serviços do Azure e canais de comunicação, como Microsoft Teams, Facebook Messenger, Telegram e páginas web.

Principais características:

- Criação rápida de bots com templates: permite iniciar bots básicos com fluxos predefinidos.

- Suporte a linguagem natural via LUIS ou Azure Language Studio: os bots podem entender intenções e extrair informações contextuais dos usuários.

- Compatibilidade com o Bot Framework: framework da Microsoft que oferece bibliotecas e SDKs para desenvolver bots personalizados em linguagens como C# e Node.js.

- Escalabilidade e gerenciamento simplificado: integração nativa com recursos de escalonamento, autenticação e monitoramento do Azure.

Com o Bot Service, é possível desenvolver soluções como assistentes virtuais, chatbots de atendimento ao cliente, automações de FAQ e integração com sistemas corporativos para obter informações automatizadas.
