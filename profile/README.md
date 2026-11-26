<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0:006633,100:003366&height=120&section=header"/>

<div align="center">
  <img width="10%" src="assets/unb.png"/>
</div>

<div align="center">

<h2 align="center"><strong>Privacidade de Dados e Identidade Soberana em Sistemas de Inteligência Artificial:</strong></h2>

Um Estudo orientado à Legislação Brasileira

</div>

<!-- <p align="center">
  <img src="./assets/banner.svg" width="40% alt="Banner" />
</p> -->

</br>

Organização oficial do Trabalho de Conclusão de Curso (TCC) em **Engenharia de Software** pela **Universidade de Brasília (UnB)** - Faculdade de Ciências e Tecnologias em Engenharia (**FCTE**). Para acesso aos repositórios de código ou a qualquer recurso privado, favor contatar os autores. 

|                                   Aluno                                     | Matrícula |
| --------------------------------------------------------------------------- | --------- |
| [Eduardo Matheus dos Santos Sandes](https://github.com/DiceRunner714)       | 221008024 |
| [Vinícius de Oliveira Santos](https://github.com/ViniciussdeOliveira)       | 202017263 |

| Orientadora e Coorientador                                                                        |
| ------------------------------------------------------------------------------------------------- |
| [Profª. Dra. Milene Serrano](https://sigaa.unb.br/sigaa/public/docente/portal.jsf?siape=1984257)  |
| [Profº. Dr. Maurício Serrano](https://sigaa.unb.br/sigaa/public/docente/portal.jsf?siape=1984262) |

## Resumo

A crescente adoção de sistemas de Inteligência Artificial (IA) intensificou as discussões relacionadas à privacidade de dados, ao tratamento de informações pessoais e à necessidade de conformidade com regulamentações específicas. Nesse contexto, este trabalho apresenta um estudo exploratório sobre Privacidade de Dados e Identidade Autossoberana em sistemas de IA, orientado pela legislação brasileira, com ênfase na Lei Geral de Proteção de Dados Pessoais (LGPD), no Marco Legal da Inteligência Artificial e no Programa de Privacidade e Segurança da Informação (PPSI). A pesquisa fundamenta-se na Engenharia de Requisitos, utilizando o NFR *Framework* como abordagem para modelagem de Requisitos Não Funcionais, tendo a privacidade como critério central de qualidade. A metodologia adotada caracteriza-se como exploratória, de natureza aplicada e abordagem híbrida (qualitativa e quantitativa), complementada por quatro provas de conceito: anonimização de dados no treinamento de um modelo *Random Forest*; um assistente local baseado em *Retrieval-Augmented Generation* (RAG) com Identidade Autossoberana; um chat com mascaramento de dados pessoais e criptografia ponta a ponta; e uma carteira de Identidade Autossoberana ancorada em *Blockchain*, integrada a um agente financeiro de IA. Como resultado, foi elaborado um grafo de interdependência de metas flexíveis, conhecido na literatura especializada como *Softgoal Interdependency Graph* (SIG), para o requisito de Privacidade de Dados. Posteriormente, esse grafo foi refinado segundo as diretrizes da LGPD, do PPSI e do Marco Legal da IA, permitindo identificar operacionalizações, relações de contribuição e conflitos entre requisitos. As provas de conceito evidenciaram que a anonimização combinada reduziu a acurácia em menos de 1 ponto percentual; que os princípios da Identidade Autossoberana podem ser aplicados em sistemas de IA executados localmente, e que é possível conciliar mascaramento de dados pessoais, criptografia e auditoria minimizada. Além disso, a POC4 mostrou que a definição de metas de conformidade antes da implementação auxilia o aumento do índice de privacidade do PPSI ($iPriv$) e que o uso de *Blockchain* de fato constitui uma boa base para a implementação da Identidade Autossoberana. Também foram evidenciados conflitos entre privacidade e acurácia, soberania e usabilidade, e imutabilidade e eliminação de dados. Conclui-se que a modelagem orientada a requisitos não funcionais, aliada à validação por provas de conceito, constitui uma estratégia viável para incorporar a privacidade desde a concepção de sistemas de IA alinhados à legislação brasileira, embora não elimine questões de viés e opacidade dos modelos.


## Abstract

The increasing adoption of Artificial Intelligence (AI) systems has intensified discussions related to data privacy, to the processing of personal information, and the need for compliance with specific regulations. In this context, this paper presents an exploratory study on Data Privacy and Self-Sovereign Identity (SSI) in AI systems, guided by Brazilian legislation, with an emphasis on the General Data Protection Law (LGPD), the Artificial Intelligence Legal Framework, and the Privacy and Information Security Program (PPSI). The research is grounded in Requirements Engineering, using the NFR Framework as an approach for modeling Non-Functional Requirements, having privacy as the central quality criterion. The adopted methodology is characterized as exploratory, applied, and hybrid (qualitative and quantitative), complemented by four proofs of concept (POCs): data anonymization in training a Random Forest model; a local assistant based on Retrieval-Augmented Generation (RAG) with Self-Sovereign Identity; a chat featuring personal data masking and end-to-end encryption; and a Self-Sovereign Identity wallet anchored in Blockchain, integrated with a financial AI agent. As a result, a Softgoal Interdependency Graph (SIG) was developed for the Data Privacy requirement. Subsequently, this graph was refined according to the guidelines of the LGPD, PPSI, and the AI Legal Framework, allowing for the identification of operationalizations, contribution relationships, and conflicts between requirements. The proofs of concept demonstrated that combined anonymization reduced accuracy by less than 1 percentage point; that Self-Sovereign Identity principles can be applied to locally executed AI systems; and that it is possible to reconcile personal data masking, encryption, and minimized auditing. Furthermore, POC4 showed that defining compliance goals prior to implementation helps increase the PPSI privacy index ($iPriv$) and that the use of Blockchain indeed constitutes a solid foundation for implementing Self-Sovereign Identity. Conflicts between privacy and accuracy, sovereignty and usability, and immutability and data elimination were also highlighted. The study concludes that non-functional requirements oriented modeling, combined with validation through proofs of concept, constitutes a viable strategy for incorporating privacy from the design phase in AI systems aligned with Brazilian legislation, although it does not eliminate issues of model bias and opacity.

## Repositórios

- Monografia e Slides (Em Breve)

#### Provas de Conceito

- [TCC-PoC1-Random-Forest-com-Dados-Anonimizados](https://github.com/TCC-Eduardo-Sandes-e-Vinicius-Santos/TCC-PoC1-Random-Forest-com-Dados-Anonimizados)
- [TCC-PoC2-RAG-com-Identidade-Autossoberana](https://github.com/TCC-Eduardo-Sandes-e-Vinicius-Santos/TCC-PoC2-RAG-com-Identidade-Autossoberana) (Diponível Em Breve)
- [TCC-PoC3-Chat-com-Mascaramento-de-PII](https://github.com/TCC-Eduardo-Sandes-e-Vinicius-Santos/TCC-PoC3-Chat-com-Mascaramento-de-PII) (Diponível Em Breve)
- [TCC-PoC4-Carteira-SSI-com-Agente-Financeiro](https://github.com/TCC-Eduardo-Sandes-e-Vinicius-Santos/TCC-PoC4-Carteira-SSI-com-Agente-Financeiro) (Diponível Em Breve)

## Conteúdos

- Drive (Diponível Em Breve)
- [Vídeo da Apresentação TCC1](https://youtu.be/RBxmzexJ8sc?si=n-jsECU__l2gzZgi)
- Vídeo da Apresentação TCC2 (Apresentação Em Dezembro)

---

</br>

<div align="center">
  <img width="7%" src="assets/fcte.png"/>
</div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0:006633,100:003366&height=120&section=footer"/>
