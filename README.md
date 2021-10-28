# Intrudução

Este guia é uma visão minha sobre tendencias do mercado, tecnologias, e artigos para te guiar à entender sobre o cargo de SRE(Site Reability Engineer), cultura DevOps, e sobre tecnologias utilizadas por grandes empresas e startups no momento.

### SRE(Site reability engineer) ###
É um cargo que em resumo, junta “N” posições dentro de uma cadeira, dentre elas: sysadmin, monitoramento, arquitetura, sustentação, desenvolvimento, segurança, redes e algumas outras.
Para você entender melhor recomendo você ler esse artigo do velho e bom Chico, ele faz um relato muito bom sobre esse cargo que começou no Google e hoje tem em praticamente todas as empresas: https://www.linkedin.com/pulse/o-sysadmin-do-futuro-ou-presente-francisco-freire/?trackingId=PaFsDjOSQD%2BzRSGM0qcGbA%3D%3D.

Livro oficial do Google sobre o tema: https://sre.google/sre-book/table-of-contents/.

### Cultura DevOps ###
DevOps é uma cultura muito atual hoje no mercado que como o nome diz, junta desenvolvimento e o time de operações e já tem algumas outras desmembrações como DevSecOps(desenvolvimento+segurança+operações) e visa promover a colaboração entre os times envolvidos no desenvolvimento, manutenção do software e segurança. Erroneamente muitas empresas criam um cargo denominado “Analista DevOps”, “Especialista DevOps”, “Engenheiro DevOps”, entre ouras aberrações, porém DevOps é uma cultura e não um cargo.
Artigos que descrevem melhor a cultura DevOps:
- https://www.redhat.com/pt-br/topics/devops
- https://aws.amazon.com/pt/devops/what-is-devops/
- https://azure.microsoft.com/pt-br/overview/what-is-devops/

### Cloud Computing ###
Pegando esses conceitos de cargos e cultura DevOps, chegamos no assunto Cloud Computing, que basicamente hoje é utilizada em larga escala pelas empresas, por basicamente não necessitar de provisionamento de infraestrutura física em datacenters, que possuem um custo alto na compra de equipamentos (storages, servidores, ferramentas de backup, rede etc.), e necessitar de um time com diversos skills para gerenciar esse ambiente. A cloud resolve este problema pois tem 3 conceitos de serviços: IaaS (Infraestrutura como um serviço), PaaS (Plataforma como um Serviço) e SaaS (Software como um Serviço).
Além disto, podemos ter cloud privadas, públicas e hibridas, mas aqui vamos focar nas clouds públicas(principais) que são: AWS (Amazon Web Services), Azure (Microsoft), GCP (Google Cloud Plataform) e OCI (Oracle Cloud Infrastructure).
Aqui vou deixar alguns conteúdos free para estudo que vai ajudar nos conceitos básicos de cloud.
A Microsoft possui o Learn que possui conteúdo free para suas certificações, onde basta você acessá-lo (pode usar sua conta Hotmail) e ir realizando os módulos. Para iniciar recomendo a AZ-900 que é a certificação inicial da Microsoft e vai lhe passar uma visão geral de cloud e do Azure da Microsoft:
https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900.

A Microsoft oferece $200 de crédito para você utilizar em sua conta se cadastrando no link a seguir, e com isso conseguir brincar com o ambiente em cloud: https://azure.microsoft.com/pt-pt/free/.

A Amazon possui o programa AWS Training and Certification, e para iniciar recomendo realizar o “Cloud Fountations Learning Plan”, o curso AWS Cloud Practitioner Essentials que é similar ao AZ-900 da Microsoft, porém com um outro formato. Segue link: https://explore.skillbuilder.aws/learn/public/learning_plan/view/82/cloud-foundations-learning-plan.

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

Outro documento muito importante é os “12 fatores” que todo software ou aplicação deveria seguir, que pode ser lido no artigo: https://12factor.net/pt_br/.

## Links auxiliares ##

- Cloud Native:
- [Katacoda](https://www.katacoda.com/): Site free, com cursos de nível variado de diversas tecnologias.

