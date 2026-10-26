# Oi, eu sou o Gabriel

Sou engenheiro de Controle e Automação formado pela UFOP e hoje trabalho com dados e desenvolvimento de software. Moro no Rio de Janeiro e estou fazendo pós-graduação em Engenharia de Dados na PUC Minas.

Comecei do lado onde o dado nasce. Trabalhei em campo mexendo com sensor, medidor, CLP, sistema supervisório, central de água gelada e quadro elétrico. A parte que mais me prendia vinha depois, quando eu pegava o histórico do medidor ou o log de alarme e tentava entender se uma máquina ia parar. Só que eu fazia isso com planilha e script solto, refazendo tudo na mão toda semana.

Foi daí que veio a vontade de construir as coisas direito, com pipeline, teste e deploy. Hoje meus projetos misturam engenharia de dados, análise, backend e IA aplicada, e todos rodam num servidor que eu mesmo mantenho.

Tem uma coisa que eu trouxe da automação e que não se aprende só na teoria. Eu sei por que uma série de temperatura chega com buraco no meio (a rede caiu), por que um medidor reporta zero quando ninguém desligou nada (é falha de leitura) e o que significa o mesmo alarme tocar três vezes de madrugada pra quem vai atender o chamado às 4h. Isso muda bastante o jeito como eu escrevo validação e como penso um sistema.

## No que estou trabalhando

**[Painel de energia do Brasil](https://energia.gabrielfdev.com)** · [código](https://github.com/dev-gabrielferreira/energy-load-etl)<br>
Pipeline com 26 anos de dados abertos do ONS. São 933 mil medições hora a hora que passam por sete regras de validação, ficam guardadas em Parquet e aparecem num painel que se atualiza sozinho. Foi nele que eu descobri que os maiores saltos de consumo do país vieram de apagões e de jogos da Copa.

**[Data Warehouse de Manutenção Industrial](https://github.com/dev-gabrielferreira/maintenance-warehouse)**<br>
Modelo dimensional com leituras de sensores e ordens de serviço, feito em SQL e dbt com testes de qualidade, pra calcular MTBF, MTTR e custo de manutenção do jeito que um gestor de manutenção pede.

**[Assistente de documentação técnica](https://rag.gabrielfdev.com)** · [código](https://github.com/dev-gabrielferreira/rag-automacao-predial)<br>
Responde dúvidas sobre manuais de automação predial buscando os trechos certos antes de responder, sempre citando a fonte e avisando quando não sabe. Nasceu de procurar parâmetro de controladora num PDF de 200 páginas no meio de um atendimento.

**[Triagem de suporte com IA](https://github.com/dev-gabrielferreira/triagem-suporte-ia)**<br>
Classifica chamados por categoria, urgência e setor e resolve as dúvidas repetidas buscando na base de perguntas frequentes.

**[Extrator de documentos](https://github.com/dev-gabrielferreira/extrator-documentos-ia)**<br>
Tira campos estruturados de documentos em PDF e confere a saída antes de gravar.

Por trás deles tem um projeto que eu gosto muito, um orquestrador que montei pra manter tudo isso de pé. Cada mudança passa por teste automatizado, ambiente de homologação e minha aprovação antes de ir pro ar.

## O que vem agora

Quero reconstruir o projeto de energia no Databricks, com arquitetura medalhão e Delta Lake, e depois treinar um modelo que preveja a carga dos próximos dias. Vou contando o caminho no [LinkedIn](https://linkedin.com/in/dev-gabriel-ferreira).

## Tecnologias

Uso no dia a dia com dados

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

Pra construir e colocar no ar

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

Estudando e praticando agora

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

Do tempo de campo ficou o que não cabe em badge nenhum. SCADA e IHM, CLPs Siemens, Rockwell e Schneider, redes industriais como Modbus, Profinet e BACnet, instrumentação, inversores de frequência e a rotina de manutenção de verdade, com ordem de serviço atrasada e técnico esperando peça.

<details>
<summary>Outras tecnologias que já usei em projeto</summary>

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

</details>

## Vamos conversar

Estou aberto a oportunidades em dados e desenvolvimento, remoto, híbrido ou presencial, e topo mudar de cidade. Se quiser trocar ideia sobre dado industrial, setor elétrico ou algum projeto daqui, me chama.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dev-gabriel-ferreira) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dev.gabrielfer@gmail.com) [![Portfólio](https://img.shields.io/badge/Portfólio-2C5F8A?logo=googlechrome&logoColor=white)](https://gabrielfdev.com)
