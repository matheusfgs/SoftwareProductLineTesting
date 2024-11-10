# Software product line testing: a systematic literature review
Empirical Software Engineering 02 September 2024
Volume 29, article number 146, (2024)
https://link.springer.com/article/10.1007/s10664-024-10516-x

# Fichamento de Conteúdo

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

