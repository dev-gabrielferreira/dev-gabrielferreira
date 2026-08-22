# 💫 Sobre mim

Sou Engenheiro de Controle e Automação pela UFOP, voltado e se especializando, em Engenharia de Dados.

Nos últimos anos eu trabalhei no lugar onde os dados nascem: Instalações físicas(em campo), sensores, medidores, hidrômetros, CLPs, sistemas supervisórios, centrais de água gelada, quadros elétricos. Meu trabalho sempre foi pegar dado bruto (histórico de medidor, série temporal de telemetria, log de alarme) e transformar em alguma coisa que ajudasse a decidir se uma máquina ia parar ou não. Só que eu fazia isso na ponta final, com planilha, script solto e muito retrabalho manual toda semana.

Agora eu quero construir a infraestrutura que resolve isso na origem. Estou cursando a pós-graduação em Engenharia de Dados na PUC Minas e montando em público um portfólio de pipelines com dados reais do setor elétrico brasileiro.

Tem uma coisa que eu levo pra área e que é difícil de aprender por metódos teoricos. Quase todo mundo estuda dado como abstração; eu aprendi olhando o sensor. Sei por que uma série de temperatura chega com buraco no meio (a rede caiu), por que um medidor às vezes reporta zero (não é consumo zero, é falha de leitura) e o que significa o mesmo alarme disparando três vezes de madrugada pra quem vai atender o chamado às 4h. Isso muda bastante a forma como eu escrevo validação de dado.

## 🌐 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dev-gabriel-ferreira) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dev.gabrielfer@gmail.com) [![Portfólio](https://img.shields.io/badge/Portfólio-2C5F8A?logo=googlechrome&logoColor=white)](https://gabrielfdev.com)

---

## 🛤️ O que estou construindo

Uma trilha de projetos onde cada um puxa o anterior. A ideia é que no final eles contem uma história só, do dado cru do sensor até o lakehouse, em vez de virarem cinco tutoriais soltos com nomes diferentes. Os dados são abertos e brasileiros, do ONS e da ANEEL, mais telemetria industrial simulada com os padrões de falha que eu vi acontecer em campo.

| # | Projeto | O que resolve | Status |
|---|---------|---------------|--------|
| 1 | [`energy-load-etl`](#) | ETL batch da carga do sistema elétrico, com validação, Parquet e dashboard | 🚧 em desenvolvimento |
| 2 | [`maintenance-warehouse`](#) | Modelagem dimensional de manutenção industrial: star schema, SCD2, dbt e arquitetura medalhão | ⏳ planejado |
| 3 | [`aws-energy-datalake`](#) | Data lake em S3 com ingestão diária orquestrada no Airflow e consulta via Athena | ⏳ planejado |
| 4 | [`iot-telemetry-streaming`](#) | Telemetria de sensores em near real time com Kafka, janelas temporais e detecção de anomalia | ⏳ planejado |
| 5 | [`energy-lakehouse-databricks`](#) | Histórico completo de geração e carga em PySpark e Delta Lake, com jobs agendados | ⏳ planejado |

Todo projeto que eu publico aqui tem diagrama de arquitetura no topo do README, sobe com um comando só, tem verificação de qualidade de dado e uma seção contando o que deu errado no caminho. Enquanto não tiver essas quatro coisas, o repositório continua privado. Prefiro dois projetos terminados de verdade a cinco em construção permanente.

---

## 💻 Stack

O que eu uso hoje nos projetos de dados:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

Onde os dados ficam e rodam:

![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

Backend e visualização, que é de onde eu venho e continua sendo útil (Spark e Kafka rodam na JVM, e saber Java ajuda mais do que eu imaginava):

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

E o que eu sei de campo, que não cabe em badge nenhum: SCADA e IHM, CLPs Siemens, Rockwell e Schneider, redes industriais (Modbus, Profinet, BACnet), instrumentação, inversores de frequência e a rotina de manutenção preditiva de verdade, aquela com ordem de serviço atrasada e técnico esperando peça.

<details>
<summary>Outras tecnologias que já usei em projeto</summary>

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

</details>

---

## 🤖 IA aplicada

Antes de virar a chave para dados eu construí alguns serviços com LLM e coloquei no ar em VPS própria, com Docker e proxy reverso. Continuam de pé, e olhando hoje eles são bem mais trabalho de dado do que de IA: ingestão de documento não estruturado, pipeline de embedding, busca semântica e API documentada.

**[rag-automacao-predial](https://github.com/dev-gabrielferreira/rag-automacao-predial)**
Assistente que responde dúvidas sobre manuais de automação predial recuperando os trechos certos antes de gerar a resposta, sempre citando a fonte e se abstendo quando o contexto não dá base. Nasceu de uma dor real: procurar parâmetro de controladora em PDF de 200 páginas no meio do atendimento.

**[triagem-suporte-ia](https://github.com/dev-gabrielferreira/triagem-suporte-ia)**
Classifica chamado de suporte por categoria, urgência e setor, e resolve as dúvidas recorrentes por busca semântica na base de FAQ. API REST documentada em OpenAPI.

**[extrator-documentos-ia](https://github.com/dev-gabrielferreira/extrator-documentos-ia)**
Extração de campos estruturados a partir de documento não estruturado, com validação de saída. É ingestão de dado, só que a fonte é PDF em vez de tabela.

---

## 📊 Estatísticas

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=dev-gabrielferreira&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=dev-gabrielferreira&theme=dark&hide_border=false&layout=compact&langs_count=6&hide=html,css)

---

Estou aberto a oportunidades de engenharia de dados, presenciais ou remotas, e disponível para mudança de cidade. Se você chegou até aqui e quer trocar ideia sobre dado industrial, pipeline ou o setor elétrico, me chama no [LinkedIn](https://linkedin.com/in/dev-gabriel-ferreira).

---

## 📊 Estatísticas

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=dev-gabrielferreira&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=dev-gabrielferreira&theme=dark&hide_border=false&layout=compact&langs_count=6&hide=html,css)
