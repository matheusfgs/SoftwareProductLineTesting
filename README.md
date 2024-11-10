# Software product line testing: a systematic literature review
Empirical Software Engineering 02 September 2024
Volume 29, article number 146, (2024)
https://link.springer.com/article/10.1007/s10664-024-10516-x

# 1.Fichamento de Conteúdo

O artigo apresenta uma revisão ampla e sistemática da literatura sobre o chamado “Teste de Linhas de Produto de Software” (LPS), um paradigma de desenvolvimento que busca otimizar custos, reduzir drasticamente o tempo de lançamento e melhorar a qualidade dos produtos de software derivados. E o LPS é uma abordagem que permite criar uma família de produtos de software com um conjunto de ativos centrais compartilhados, como arquiteturas e  principalmente componentes reutilizáveis, enquanto se adapta a diferentes requisitos de mercado por meio das variabilidades configuráveis. 

Com o grande aumento da adoção do LPS por empresas, tornou-se necessário entender como o teste se desenvolveu neste contexto, especialmente sobre o porquê o teste em LPS envolve desafios específicos: como verificar componentes compartilhados e até mesmo analisar variações de produto.

Para contribuir com uma visão atualizada sobre a área, os autores realizaram uma analise de 118 estudos publicados de 2003 até 2022. Essa revisão teve como objetivo identificar o estado atual das práticas de teste em LPS, destacar os avanços que teve e apontar as lacunas entre as necessidades de teste e as soluções existentes. Sete questões de pesquisa foram formuladas para orientar a análise, cobrindo aspectos como os tipos de estudos focados em teste de LPS e os níveis de teste executados ao longo do ciclo de vida do LPS.

Os resultados indicaram que muitas técnicas têm sido propostas para otimizar o teste em LPS, com foco em questões como o controle de custo e esforço. No entanto, o artigo também destaca que existem áreas pouco exploradas, como testes de regressão e testes de requisitos não-funcionais (como  desempenho e segurança, ambos itens que são estudados durante a Introdução sobre engenharia de software), que são importantes para assegurar a qualidade dos produtos derivados. Outra questão que também foi observada foi que a maioria das abordagens de teste foram feitas e validadas apenas em cenários acadêmicos ou com métodos empíricos limitados, o que pode fazer com que surjam  dificuldades em relação a transição dessas soluções para o uso prático na indústria.

A revisão elaborada e abordada no artigo identificou as principais abordagens de teste, incluindo o teste manual, onde os casos de teste são executados sem automação e feito por desenvolvedores (fato essencial a ser abordado na pesquisa); e o teste automatizado, que usa ferramentas para automatizar a execução dos testes. 

E em relação aos tipos de teste citados e destacados durante o artigo, são discutidos: 

.Os testes de unidade: que focam nos menores componentes de software;

.Os testes de integração: que verifica a interação entre os componentes;

.Os testes de sistema: que avaliam o sistema como um todo, incluindo os atributos não-funcionais;


.Os testes de aceitação: que verificam se o produto final atende à todas expectativas dos clientes.

E Além de discutir os tipos de testes existentes, o artigo também aborda a importância da rastreabilidade entre ativos de teste e outros artefatos do desenvolvimento, assim como o desafio de gerenciar configurações e a necessidade de técnicas que levam em conta tanto as características comuns quanto as variações específicas de cada produto desenvolvido. 

No final, o artigo conclui que, apesar do progresso na área de testes para LPS ao longo das últimas duas décadas, ainda existem várias lacunas que precisam ser abordadas para melhorar a eficácia e a adoção das práticas de teste sobre a indústria.  E essas descobertas fornecem uma base sólida para profissionais e a pesquisadores, os ajudando ao orientar o desenvolvimento de novas técnicas que possam atender de forma mais completa às necessidades de teste no contexto do LPS.

# 2.Fichamento Bibliográfico

.SPL (Software Product Line): É um paradigma de desenvolvimento que permite criar uma família de produtos de software com ativos centrais compartilhados, aproveitando a reutilização de componentes para atender diferentes necessidades de mercado e diminuir o custo e o tempo de desenvolvimento. (página 1)


.Configurable Systems: Sistemas de software projetados para serem adaptáveis e configuráveis de acordo com os requisitos específicos dos usuários, permitindo personalização sem necessidade de reescrever o código principal do sistema. (página 2)

.Non-functional Testing (Teste não-funcional): Teste que verifica atributos de qualidade do software que não estão diretamente relacionados com funcionalidades, como desempenho, segurança, usabilidade e escalabilidade, assegurando que o sistema atende a esses critérios. (página 3)

.Reusable Components (Componentes Reutilizáveis): 
Partes de software, como módulos ou bibliotecas, que são projetadas para serem reutilizadas em diferentes projetos ou produtos, contribuindo para reduzir esforço de desenvolvimento e promover consistência entre sistemas. (página 4)

.SLRs in Software Engineering (Revisões Sistemáticas da Literatura em Engenharia de Software): Métodos estruturados para revisar, coletar e analisar estudos existentes em engenharia de software, visando fornecer uma visão geral sobre o estado da arte de uma área específica e identificar lacunas e tendências de pesquisa. (página 6)

.Software Product Family (Família de Produtos de Software): Conjunto de produtos de software relacionados que compartilham características comuns e variáveis, permitindo o desenvolvimento eficiente de vários produtos baseados em uma infraestrutura comum. (página 9)

.Quality Assessment Criteria (Critérios de Avaliação de Qualidade): Conjunto de métricas ou diretrizes utilizadas para avaliar a qualidade de um produto de software, cobrindo aspectos como confiabilidade, eficiência, segurança e manutenibilidade. (página 12) 

.Domain Engineering (Engenharia de Domínio): Processo de desenvolvimento que identifica, modela e organiza os requisitos comuns e variáveis dentro de um domínio específico, com o objetivo de criar ativos reutilizáveis que facilitem a criação de novos produtos de software no mesmo domínio. (página 16)

.Regression Testing (Teste de Regressão): Tipo de teste que verifica se mudanças no código-fonte, como correções de bugs ou novas funcionalidades, não introduziram novos erros no sistema ou afetaram funcionalidades já existentes. (página 36)

.VarXplorer: Ferramenta utilizada para visualizar e analisar a variabilidade e as configurações em linhas de produtos de software, facilitando a identificação de dependências e a gestão da complexidade de diferentes variantes de produtos. (página 21)

.Testing NFRs (Testing Non-Functional Requirements):
 Processo de teste focado na verificação de requisitos não-funcionais, como desempenho, segurança e usabilidade, garantindo que o sistema atende a esses requisitos essenciais para a experiência do usuário e para a confiabilidade do software. (página 33)

 # 3.Fichamento de citações

 . “The analysis indicates that the SPL testing field has attracted significant attention from researchers in recent years, with an increase in empirically evaluated studies.” (Page 32, RQ1)


. “Creating test assets to address commonality and variability in SPL testing is crucial for enhancing reusability and minimizing faults in core assets.” (Page 33, RQ6)


. “The distribution of studies across these categories indicates that model-based techniques are the most commonly used in the examined studies.” ( Page 33, RQ7)








