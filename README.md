# Introdução

Este guia é uma visão sobre o que o mercado está utilizando de tecnologias, e artigos para te guiar à entender sobre a disciplina de SRE(Site Reability Engineer), cultura DevOps, entre outros temas.

### SRE(Site reability engineer) ###
É uma disciplina que em resumo, junta “N” posições dentro de uma cadeira, dentre elas: sysadmin, monitoramento, arquitetura, sustentação, desenvolvimento, segurança, redes e algumas outras.
Para você entender melhor recomendo você ler esse artigo do velho e bom Chico, ele faz um relato muito bom sobre essa disciplina que começou no Google e hoje existe em praticamente todas as empresas: https://www.linkedin.com/pulse/o-sysadmin-do-futuro-ou-presente-francisco-freire/?trackingId=PaFsDjOSQD%2BzRSGM0qcGbA%3D%3D.

Livro oficial do Google sobre o tema SRE: https://sre.google/sre-book/table-of-contents/.

### Cultura DevOps ###
DevOps é uma cultura muito atual no mercado, e como o nome diz, junta os times de desenvolvimento e operações, possuindo até algumas desmembrações como DevSecOps(desenvolvimento+segurança+operações). A cultura DevOps tem como premissa, promover a colaboração entre os times envolvidos no desenvolvimento, manutenção do software e segurança. Erroneamente muitas empresas criam um cargo denominado “Analista DevOps”, “Especialista DevOps”, “Engenheiro DevOps”, entre ouras aberrações... porém DevOps é uma cultura e não um cargo.
Artigos que descrevem melhor a cultura DevOps:
- https://www.redhat.com/pt-br/topics/devops
- https://aws.amazon.com/pt/devops/what-is-devops/
- https://azure.microsoft.com/pt-br/overview/what-is-devops/

### Cloud Computing ###
Pegando esses conceitos da disciplina de SRE e cultura DevOps, chegamos no assunto Cloud Computing, que basicamente hoje é utilizada em larga escala pelas empresas(pequenas, médias e grandes), além de startups, fintechs, entre outras; por basicamente não necessitar de provisionamento de infraestrutura física em datacenters, que possuem um custo alto na compra de equipamentos (storages, servidores, ferramentas de backup, rede etc.), e necessitar de um time com diversos skills para gerenciar esse ambiente, além do custo da manutenção deste ambiente. A cloud resolve este problema pois tem 3 conceitos de serviços básicos: IaaS (Infraestrutura como um serviço), PaaS (Plataforma como um Serviço) e SaaS (Software como um Serviço).
Além disto, podemos ter cloud privadas, públicas e hibridas, mas aqui vamos focar nas clouds públicas(principais) que são: AWS (Amazon Web Services), Azure (Microsoft), GCP (Google Cloud Plataform) e OCI (Oracle Cloud Infrastructure).
Aqui vou deixar alguns conteúdos free para estudo que vai ajudar nos conceitos básicos de cloud.
A Microsoft possui o Learn, que possui conteúdo free para suas certificações, onde basta você acessá-lo (pode usar sua conta Hotmail, outlook, gmail) e ir realizando os módulos. Para iniciar, recomendo a [AZ-900](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900) que é a certificação inicial da Microsoft e vai lhe passar uma visão geral de cloud e logicamente do Azure, da prórpia Microsoft.

A Microsoft oferece $200 de crédito para você utilizar, e com isso conseguir brincar com o ambiente em cloud.Basta clicar neste [link](https://azure.microsoft.com/pt-pt/free/) e se cadastrar.

A Amazon possui o programa AWS Training and Certification, e para iniciar recomendo realizar o “[Cloud Foundations Learning Plan](https://explore.skillbuilder.aws/learn/public/learning_plan/view/82/cloud-foundations-learning-plan)", o curso AWS Cloud Practitioner Essentials que é similar ao AZ-900 da Microsoft, porém com um outro formato.

E para ajudar a AWS também oferece um nível gratuito com diversos produtos para agregar no seu conhecimento sobre Cloud, basta clicar [aqui](https://aws.amazon.com/pt/free/?trk=ps_a134p000003yhQ3AAI&trkCampaign=acq_paid_search_brand&sc_channel=ps&sc_campaign=acquisition_BR&sc_publisher=google&sc_category=core&sc_country=BR&sc_geo=LATAM&sc_outcome=Acquisition&sc_detail=aws%20free&sc_content=Cost_e&sc_matchtype=e&sc_segment=454435137297&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|AWS|Core|BR|EN|Text&s_kwcid=AL!4422!3!454435137297!e!!g!!aws%20free&ef_id=Cj0KCQjwlOmLBhCHARIsAGiJg7nIDdaeVvS1ghdrB1O1UdQy93TYt1w-l00qtKELL-I6qjiX-VyNpD4aAgHIEALw_wcB:G:s&s_kwcid=AL!4422!3!454435137297!e!!g!!aws%20free&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all) e fazer seu cadastro

Estes cursos vão ajudar você ter uma visão geral de cloud pública, serviços que elas oferecem, forma de cobrança, monitoramento dos serviços, tudo isso free, e de um modo básico, excelente para quem deseja iniciar.

### Tecnologias ###
Hoje o mercado utiliza diversas tecnologias, a cloud é uma delas, porém você vai ouvir muito falar esteiras CI/CD, linguagens de programação, monitoramento(observability), tipos de aplicações (serverless x microservices), Infraestrutura como código, entre outras. Vou elencar aqui as principais utilizadas que ando vendo no momento:

**CI/CD:** 

- Jenkins:
- Azure DevOps:
- Gitlab:

**Linguagens de programação:** 

- Python:
- Dotnet core:
- Bash:

**Monitoramento (Observability)** 

- Prometheus:
- NewRelic:

**Tipo de Aplicações:** 

- Serverless:
- Microservice:

**Orquestradores:**

- Docker:
- Kubernetes:

**Versionamento de código:** 

- GIT:

**Infraestrutura como código** 

- Terraform:
- Ansible:

Um site que uso bastante para agregar no meu conhecimento é o Katacoda, ele provisiona um ambiente virtual, sem custo, que permite você realizar exercícios sobre as tecnologias, sem necessidade de configuração em seu equipamento.


## Links auxiliares ##

- [Cloud Native](https://landscape.cncf.io/): Basicamente mostra o que está sendo usado de tecnologia, e o que é tendência.
- [Katacoda](https://www.katacoda.com/): Site free, com cursos de nível variado de diversas tecnologias.
- [12 factors](https://12factor.net/pt_br/): Guia muito importante, que todo software ou aplicação deveria seguir.
- [Geniol](https://www.geniol.com.br/logica/): Interessante site, para testar e treinar raciocinio lógico através de jogos.
- [pixelastic](https://pixelastic.github.io/pokemonorbigdata/): Outro teste de lógica, porém mais voltado a BigData.

