# Avaliação de estratégias para gerenciamento da Dívida Técnica em Projetos de Software

* Matheus Eduardo Marinho de Miranda Hermenegildo
* Miguel Amaral Lessa Xavier
* Orientador: Lesando Ponciano dos Santos

## Introdução

* A área da Engenharia de Software tratada neste trabalho é a _Avaliação de estratégias para gerenciamento da Dívida Técnica em Projetos de Software_
* O problema que este trabalho busca resolver é o de _Quais são as melhores estratégias de gerenciamento da dívida técnica em projetos de software?  E quais são as estratégias para identifica-las_
* A resolução deste problema é relevante pois, uma vez que claros os métodos de identificação de dívida técnica, projetos de software poderão realizar uma gerência mais eficiente de recursos como tempo de desenvolvimento, necessidade de retrabalho e possíveis custos no mesmo e na manutenção do software.
* O objetivo geral deste trabalho é _Avaliar estratégias eficazes para gerenciamento da dívida técnica desde a fase de identificação até a gestão de recursos para soluciona-la, visando aumentar a manutenibilidade._
* Os objetivos específicos deste trabalho são: (1) Identificar estratégias eficazes para identificar dívidas técnicas; (2) Identificar qual é o melhor método de gerenciar recursos para resolver dívidas técnicas; (3) Examinar como a comunicação e o alinhamento entre as equipes técnicas e os stakeholders influenciam as estratégias de gestão da dívida técnica em projetos de software.

## Fundamentação Teórica

1. O conceito principal associado a este trabalho é o de _Technical debt_ (dívida técnica). Cuja definição neste trabalho é a de "Comparar decisões e escolhas em projetos de software com dívidas financeiras, se referindo a artefatos de software incompletos, inadequados ou imaturos, que podem causar baixa qualidade e custos elevados em estágios mais avançados do projeto" (https://dl.acm.org/doi/10.1145/157710.157715) conforme definido na conferência OOPSLA'92, pelo autor Ward Cunningham.
2. O conceito secundário associado a este trabalho é o de _Skin in the game_. A sua definição neste trabalho é a de "Colocar a pele em jogo na hora de tomar decisões relacionadas a dívida técnica, não tomando decisões arriscadas sem antes pensar e analisar suas consequências" conforme definido no trabalho Technical Debt Monitoring Decision (https://dl.acm.org/doi/10.1145/3664805) Making with Skin in the Game pelo autor, Suwichak Fungprasertkul.
3. O conceito terciário associado a este trabalho é o de dívida técnica auto-admitda (SATD). A dívida técnica autoadmitida é um tipo de dívida técnica que é explicitamente reconhecida pela equipe de desenvolvimento no momento em que é criada. Ela ocorre quando decisões conscientes são tomadas para implementar uma solução subótima ou incompleta com o objetivo de atender a um requisito imediato, sabendo que será necessário revisitá-la e melhorá-la no futuro. Os desenvolvedores estão cientes de que estão introduzindo uma dívida técnica e documentam essa escolha e há uma intenção clara de resolver a dívida posteriormente. conforme definido no trabalho Towards Automatically Addressing Self-Admitted Technical Debt: How Far Are We? (https://doi.org/10.1109/ASE56229.2023.00103), pelo autor Antonio Mastropolo.

## Trabalhos Relacionados

1. O trabalho mais relacionado é _Got Technical Debt?Surfacing Elusive Technical Debt in Issue Trackers_ (https://doi.org/10.1145/2901739.2901754), publicado no ano de 2016, pois traz métodos de classificação para identificação de dívidas técnicas em projetos de software.
2. O segundo trabalho mais relacionado é _Towards Automatically Addressing Self-Admitted Technical Debt: How Far Are We?_ (https://doi.org/10.1109/ASE56229.2023.00103), publicado no ano de 2023, por propor um novo método para gerenciar dívidas técnicas, com o uso de issue trackers auto-admitidos por desenvolvedores.
3. O terceiro trabalho mais relacionado é _Technical Debt Monitoring Decision Making with Skin in the Game_ (https://doi.org/10.1145/3664805) , publicado no ano de 2024,  por trazer uma proposta de gerência de prioridades para dívidas técnicas baseada em contexto do projeto e decisões de stakeholders.

## Materiais e Métodos

* O tipo de pesquisa adotado neste trabalho é "quantitativa", pois ela trata de atributos quantitativos relacionados a dívida técnica em projetos de código aberto. 
* Os materiais utilizados neste trabalho são: projetos de código aberto e seus respectivos _issue trackers_ que utlizam a plataforma Github (https://github.com) para versionamento de código; dados dos issues reportados pelos programadores; comentários SATD deixados por desenvolvedores; 
* Os métodos empregados neste trabalho são: análise de commits que alteram parte significativa do código para sanar issues reportados em issue trackers do projeto; análise de issues reportados em issue trackers de projetos (https://doi.org/10.1145/2901739.2901754); reunião com stakeholders e planing poker (https://dl.acm.org/doi/10.1145/3664805); análises de comentários SATD (https://doi.org/10.1109/ASE56229.2023.00103);
* As métricas de avaliação são: taxa de retrabalho causado por dívida técnica; taxa de issues relacionados à dívida técnica; resultados coletados em validação de dívidas técnicas;
* As etapa de execução do trabalho são: (1) coletar de dados de projetos de código aberto no github; (2) analisar os issues reportados em issue trackers; (3) analisar resultados obtidos em reuniões entre desenvolvedores e stake holders; (4) analisar comentários SATD. A partir dessas etapas as questões de pesquisa podem ser respondidas e os objetivos são atingidos.
