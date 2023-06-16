# projeto_DIO.ME_cloud_practitioner

RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS 
Data: [15/06/2023] Empresa: Abstergo Industries Responsável: [João Carlos da Silva Oliveira] 
Introdução 
Este relatório apresenta o processo de implementação de ferramentas na empresa [Abstergo Industries], realizado por
[João Carlos da Silva Oliveira]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar
diminuição de custos imediatos. 
Descrição do Projeto 
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A
seguir, serão descritas as etapas do projeto: 
Etapa 1: - [EC2] - [A ferramenta EC2 (Elastic Compute Cloud) da AWS tem foco na oferta de serviços de computação em nuvem, permitindo aos usuários provisionar e gerenciar instâncias virtuais de servidores de forma escalável e flexível. Ela fornece recursos para executar e dimensionar aplicativos em nuvem de maneira eficiente, oferecendo opções de configuração, tais como seleção de tipo de instância, sistema operacional, armazenamento e rede.] 

- Um caso de uso comum para a ferramenta EC2 da AWS é a hospedagem de um aplicativo web. Suponha que uma empresa esteja desenvolvendo um aplicativo web e precise de um ambiente flexível e escalável para implantá-lo. A empresa pode usar o EC2 para provisionar e gerenciar instâncias virtuais que executarão o aplicativo.

Primeiro, a empresa pode criar uma imagem personalizada contendo o sistema operacional e as configurações necessárias para o aplicativo. Em seguida, usando o EC2, eles podem provisionar um conjunto de instâncias virtuais a partir dessa imagem, especificando a capacidade de computação, o armazenamento e a rede necessários.

Conforme a demanda pelo aplicativo aumenta, a empresa pode facilmente escalar verticalmente, adicionando mais instâncias ou ajustando as especificações das instâncias existentes. Isso permite que o aplicativo lide com picos de tráfego e forneça uma experiência contínua aos usuários.

Além disso, o EC2 oferece recursos avançados, como balanceamento de carga e autoescala, que permitem distribuir o tráfego entre várias instâncias e adicionar ou remover instâncias automaticamente de acordo com a demanda, otimizando o desempenho e a disponibilidade do aplicativo.

No geral, o EC2 é uma ferramenta fundamental para hospedar aplicativos web, proporcionando flexibilidade, escalabilidade e confiabilidade necessárias para atender às necessidades dos negócios.] 


Etapa 2: - [Amazon S3] - [O foco da ferramenta Amazon S3 (Simple Storage Service) da AWS é fornecer um serviço de armazenamento em nuvem escalável, seguro e durável. O Amazon S3 é projetado para armazenar e recuperar grandes volumes de dados de forma eficiente, permitindo que as empresas armazenem e acessem facilmente arquivos, documentos, imagens, vídeos e outros tipos de dados.

O principal objetivo do Amazon S3 é oferecer armazenamento altamente disponível e durável para uma ampla variedade de casos de uso, incluindo backup e recuperação de dados, arquivamento, hospedagem de sites estáticos, compartilhamento de arquivos, distribuição de conteúdo e armazenamento de dados para aplicativos.

Através do Amazon S3, as empresas podem criar buckets (recipientes) para organizar e gerenciar seus dados. Cada objeto (arquivo) armazenado no S3 é atribuído a um bucket, e esses objetos podem ser acessados por meio de uma interface de programação (API) ou por meio de uma interface de usuário da AWS.

O Amazon S3 também oferece recursos avançados, como controle de acesso, criptografia de dados, versionamento de objetos, integração com outros serviços da AWS, monitoramento e registro de atividades.

Em resumo, o foco do Amazon S3 é fornecer um armazenamento em nuvem altamente escalável, seguro e durável para atender às necessidades de armazenamento e acesso a dados das empresas de maneira eficiente e confiável.] - [Um caso de uso comum para a ferramenta Amazon S3 é o armazenamento e distribuição de conteúdo estático na web. Empresas que possuem sites ou aplicativos que exibem imagens, vídeos, arquivos de áudio ou qualquer outro tipo de conteúdo estático podem aproveitar o Amazon S3 para armazenar esses arquivos de forma eficiente e confiável.

Ao usar o Amazon S3, os desenvolvedores podem fazer upload dos arquivos para os buckets do S3, que atuam como recipientes de armazenamento. Em seguida, eles podem configurar permissões de acesso adequadas e obter URLs únicas para cada objeto armazenado. Esses URLs podem ser usados para acessar e exibir o conteúdo em sites e aplicativos.

O Amazon S3 possui alta disponibilidade e escalabilidade, o que garante que o conteúdo estático seja rapidamente servido aos usuários finais, independentemente da quantidade de tráfego ou carga de trabalho. Além disso, o S3 oferece recursos avançados de segurança, como criptografia de dados em repouso e em trânsito, permitindo que as empresas protejam seus ativos digitais.

Outro caso de uso comum para o Amazon S3 é o backup e recuperação de dados. Empresas podem fazer o backup de seus dados importantes para o Amazon S3, garantindo a sua segurança e disponibilidade em caso de falhas de hardware, erros humanos ou desastres naturais. O Amazon S3 permite a criação de cópias de segurança automatizadas e pode ser facilmente integrado a outras ferramentas e serviços da AWS para criar soluções de backup abrangentes.

Além disso, o Amazon S3 também é amplamente utilizado para armazenamento de arquivos, compartilhamento de dados entre equipes, armazenamento de logs e eventos, processamento de big data e muitos outros casos de uso.

Em resumo, o Amazon S3 é uma ferramenta versátil que pode ser utilizada para uma variedade de casos de uso, incluindo armazenamento e distribuição de conteúdo estático na web, backup e recuperação de dados, compartilhamento de arquivos e armazenamento de dados para aplicativos, oferecendo alta disponibilidade, escalabilidade e segurança.] 


Etapa 3: - [ EBS (Elastic Block Store)] - [A ferramenta EBS (Elastic Block Store) da AWS tem como foco fornecer armazenamento persistente de bloco para as instâncias do Amazon EC2 (Elastic Compute Cloud). O EBS é projetado para oferecer desempenho, confiabilidade e durabilidade para os aplicativos em execução nas instâncias do EC2.

O EBS permite que você crie volumes de armazenamento que podem ser conectados às instâncias do EC2. Esses volumes atuam como discos virtuais e podem ser usados para armazenar dados de aplicativos, sistemas de arquivos ou bancos de dados. O EBS oferece várias opções de volume com diferentes características de desempenho, como SSD (Solid-State Drive) e HDD (Hard Disk Drive), permitindo que você escolha a opção mais adequada para suas necessidades.

Uma das principais vantagens do EBS é a capacidade de criar snapshots dos volumes. Os snapshots são cópias incrementais dos dados armazenados nos volumes do EBS e são armazenados no Amazon S3. Eles podem ser usados para backup, recuperação de desastres e para criar novos volumes a partir deles.

Além disso, o EBS fornece recursos avançados, como a capacidade de dimensionar o desempenho de um volume, permitindo ajustar a taxa de transferência e a quantidade de IOPS (Input/Output Operations Per Second) de acordo com as necessidades do aplicativo. Também é possível fazer o espelhamento de volumes (RAID), criar volumes criptografados para proteção adicional dos dados e compartilhar volumes entre várias instâncias do EC2.

Em resumo, o foco da ferramenta EBS da AWS é fornecer armazenamento persistente de bloco para as instâncias do EC2, permitindo que você armazene e acesse dados de forma confiável, escalável e segura. O EBS é essencial para muitos aplicativos e cenários de armazenamento na nuvem, oferecendo flexibilidade, desempenho e recursos avançados para atender às necessidades dos usuários.] - [Um caso de uso comum para a ferramenta EBS (Elastic Block Store) da AWS é o armazenamento persistente de dados para aplicativos em execução em instâncias do Amazon EC2 (Elastic Compute Cloud).

Por exemplo, imagine um aplicativo web que requer armazenamento de banco de dados. Ao usar o EBS, você pode criar um volume de armazenamento EBS e conectá-lo à instância do EC2 que executa o banco de dados. Esse volume EBS atua como um disco virtual e pode ser usado para armazenar os dados do banco de dados de forma persistente.

O EBS oferece vantagens significativas nesse cenário. Primeiro, o armazenamento é durável e altamente confiável, garantindo a integridade dos dados. Além disso, o EBS oferece opções de desempenho, como volumes SSD com alto desempenho ou volumes HDD mais econômicos, permitindo ajustar o armazenamento às necessidades específicas do aplicativo.

Outro caso de uso comum é o uso de snapshots do EBS para backups e recuperação de desastres. Com os snapshots, você pode criar cópias incrementais dos volumes do EBS em intervalos regulares e armazená-las no Amazon S3. Esses snapshots podem ser usados para restaurar volumes em caso de falhas, acidentes ou para criar novos volumes a partir deles.

Além disso, o EBS permite que você ajuste o desempenho dos volumes conforme necessário. Você pode aumentar a taxa de transferência e a quantidade de IOPS (Input/Output Operations Per Second) para atender às demandas de carga de trabalho intensiva em I/O.

Em resumo, o EBS é amplamente utilizado para fornecer armazenamento persistente de dados para aplicativos em execução em instâncias do EC2. Ele oferece confiabilidade, desempenho ajustável, recursos de backup e recuperação e integração perfeita com outros serviços da AWS, tornando-o uma escolha popular para armazenamento em nuvem.] 
Conclusão 
A implementação de ferramentas na empresa [Abstergo Industries] tem como esperado [benefícios das ferramentas], o que
aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas
implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa. 

Assinatura do Responsável pelo Projeto: 
João Carlos da Silva Oliveira
