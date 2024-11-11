# DebtCom: Technical Debt-Aware Service Recomposition in SaaS Cloud
Kumar, Satish; Chen, Tao; Bahsoon, Rami; Buyya, Rajkumar. "DebtCom: Technical Debt-Aware Service Recomposition in SaaS Cloud", in IEEE TRANSACTIONS ON SERVICES COMPUTING, VOL. 16, NO. 4, JULY/AUGUST 2023, [10.1109/TSC.2023.3237043](https://doi.org/10.1109/TSC.2023.3237043)  

## 1. Fichamento de Conteúdo

O artigo apresenta o DebtCom, que é uma estrutura inovadora para recomposição de serviços em nuvem no ambiente SaaS, ela integra o conceito de dívida técnica, usando este para guiar nas decisões de recomposições de serviços. No lugar de recompor sempre que ocorre a subutilização ou a sobrecarga dos componentes, ela analisa e determina se é viável ao analisar e considerar os benefícios a longo prazo e os custos acumulados. O DebtCom utiliza o modelo ARFIMA para antecipar as variações nas cargas de trabalho, conseguindo ter proatividade nas decisões. O DebtCom tem uma abordagem alternativa, já que ele considera se a recomposição é realmente necessária, assim se baseando em um modelo de dívida de serviço que mede se os efeitos negativs vão ser temporários e toleráveis. A estrutura é validada pelos autores em um sistema com até 10 serviços abstratos e 100 serviços componentes, que utilizam cargas reais de trabalho. Em conclusão, os resultados mostram que o DebtCom otimiza o uso dos recursos e reduz os custos de operação e a frequência de recomposição, deixando claro sua maior eficiência e sustentabilidade.	

## 2. Fichamento Bibliográfico

- _Technical Debt(dívida técnica) é um termo usado para descrever o custo extra em razão das ações que comprometem os benefícios de longo prazo do software desenvolvido.(pág. 2)_
- _ARFIMA é um modelo estatístico utilizado para previsão de séries temporais que exibe padrões de memória longa e volatilidade variável.(pág. 2)_
- _SaaS é um modelo de distribuição de software em que aplicativos são hospedados por um provedor de serviços na nuvem e disponibilizados aos usuários via internet.(pág. 7)_ 
- _QoS (Quality of Service ou Qualidade de Serviço) é um conjunto de técnicas e métricas usadas para garantir e medir o desempenho e a confiabilidade de um serviço ou aplicação, especialmente em redes e sistemas de computação em nuvem.
- _Time K é um parâmetro utilizado para controlar o intervalo de previsão e a preferência entre benefícios de curto prazo e benefícios de longo prazo na recomposição de serviços em SaaS_

## 3. Fichamento de Citações

- _“The results confirm that, in contrast to the state-of-the-art, DebtCom achieves better utility while having lower cost and number of recompositions, rendering each composition plan more sustainable”_
- _"A bad debt is the service debt that will not be paid off by the time k in the future. That is, by time k, there is no sign of improvement on either the service debt and the overall utility."_
- _"Service debt is a transformation of the technical debt concept particularly for the context of service composition in SaaS cloud."_
- _"The results demonstrate the effectiveness of the service debt model and the superiority of DebtCom over the state-of-the-art approaches."_
- _"We adopt a widely used time series model named Autoregressive Fractionally Integrated Moving Average model (ARFIMA) in the DebtCom framework because our time-series data contains non-standard time series features such as high volatility and long memory patterns."_
