# Projeto: Robô Autônomo Seguidor de Linha

Este documento detalha os objetivos, entregas, metodologia e recursos essenciais para o projeto de desenvolvimento e competição de um robô seguidor de linha, culminando na documentação e publicação dos resultados.

## Enunciado do Problema

Este projeto propõe o desenvolvimento, construção e documentação de um robô seguidor de linha com potencial aplicação industrial. A etapa inicial envolve a prototipagem em escala reduzida, empregando a plataforma Arduino. Para validação conceitual, o protótipo será avaliado em um ambiente competitivo. Adicionalmente, será produzida documentação abrangente, incluindo um artigo científico e um guia detalhado, ambos de acesso público e disponíveis online. O hardware e o software a serem utilizados deverão ser de domínio público, de natureza livre e de código aberto.

## Justificativa

-   **Relevância Acadêmica e Popularidade:** a robótica, notadamente o segmento de robôs seguidores de linha, demonstra significativa relevância acadêmica e popularidade, sendo um tema recorrente em eventos como RoboCup, FIRA Brasil, Torneio Sesi de Robótica, FreeBots, Arena Robótica, RoboFEI, IronCup, e em diversas instituições de ensino superior (e.g., UFABC, UFSJ, Poli/USP, IFPR, UFES).
-   **Desenvolvimento de Competências:** o projeto fomenta o desenvolvimento de habilidades essenciais, tais como trabalho em equipe e integração de conhecimentos multidisciplinares.
-   **Introdução a Conceitos de Inteligência Artificial (IA):**
    *   Tomada de decisão
    *   Reconhecimento de padrões (pista/linha)
    *   Algoritmos de controle inteligente
    *   Fundamentação para aprendizado de máquina avançado
-   **Aplicações Práticas e Relevância no Mercado:**
    *   Logística e transporte
    *   Manufatura automatizada
    *   Robótica de serviços (e.g., robôs aspiradores, veículos autônomos)
    *   Exploração e resgate
-   **Impacto Social:** a robótica educacional constitui uma ferramenta transformadora, estimulando o raciocínio lógico, a criatividade e a autonomia, notadamente em contextos de vulnerabilidade social.

## Objetivos

-   **Contexto acadêmico:** analisar a relevância do tema na área de estudo e sua conexão com os objetivos do curso, promovendo o aprofundamento de conhecimentos estratégicos.
-   **Fundamentação teórica:** aplicar conceitos teóricos fundamentais à prática, demonstrando como o projeto impulsiona a inovação e o desenvolvimento técnico.
-   **Soluções tecnológicas:** desenvolver soluções para problemas específicos por meio de aplicações tecnológicas, gerando benefícios tangíveis para os *stakeholders*.
-   **Impacto e resultados:** apresentar os resultados alcançados, as habilidades desenvolvidas durante o processo e a contribuição do projeto para soluções inovadoras e eficientes.

## Entregas

-   Condução da competição de robô seguidor de linha.
-   Documentação completa do projeto, abrangendo:
    *   Código-fonte
    *   Projeto de hardware (esquemáticos, *layouts*, modelos 3D)
    *   Registro visual (fotografias e vídeos da evolução e resultados)
-   Publicação de Artigo Científico em periódicos ou anais de eventos, como:
    *   [Encontro de Atividades Científicas (EAC)](https://eac.pgsscogna.com.br/).
    *   [Zenodo](https://zenodo.org/).
-   Disponibilização online do código, hardware e documentação completa no [GitHub](https://github.com/).
-   Apresentação do trabalho em seminários internos ou eventos acadêmicos.
-   Elaboração de portfólio acadêmico.
-   O trabalho final deve ser **reproduzível** e integralmente documentado.

## Competição

A competição será conduzida presencialmente, com as seguintes datas e locais estabelecidos para o segundo semestre de 2025:

-   **Disputa final:** 03 de Novembro de 2025
-   **Horário:** 19:00h
-   **Local:** saguão principal (entrada do prédio)

Para a execução adequada da competição de robô seguidor de linha, os discentes organizadores serão responsáveis por prover a infraestrutura e a gestão do evento, além de estabelecer as regras:

### Infraestrutura do Evento

*   Montagem e manutenção da pista oficial da competição.
*   Disponibilização de espaço adequado (pista, boxes, área para público).
*   Provisão de pontos de energia (se aplicável).

### Gestão do Evento

*   Processo de inscrição e *check-in* das equipes.
*   Inspeção técnica dos robôs.
*   Cronometragem e apuração de resultados.
*   Organização das rodadas/provas.
*   Definição de juízes/fiscais.
*   Preparação de troféu para os vencedores.

### Comunicação e Suporte Durante o Evento

*   Chamada das equipes.
*   Suporte e esclarecimento de dúvidas.
*   Comunicação de resultados e avisos.

### Segurança do Evento

*   Garantia da segurança da área da competição.
*   Elaboração de plano básico de primeiros socorros.

### Documentação do Evento

*   Registro fotográfico/videográfico da competição.
*   Publicação e divulgação do material em plataformas como YouTube e no site do projeto.

### Plano de Contingência do Evento

*   Identificação de potenciais problemas e definição de procedimentos de mitigação.

### Premiação

*   1º lugar: 40 horas complementares e certificado de mérito
*   2º lugar: 30 horas complementares
*   3º lugar: 20 horas complementares
*   Demais:   10 horas complementares

### Exemplos de Competições

A pesquisa sobre diversas competições nacionais e internacionais pode fornecer *insights* e diretrizes para as regras. Alguns exemplos incluem:

*   [Olimpíada Brasileira de Robótica (OBR)](http://www.obr.org.br)
*   [Torneio Brasil de Robótica (TBR)](http://www.torneiobrasilderobotica.com.br/)
*   [FIRST LEGO League (FLL)](http://www.firstlegoleague.org/)
*   [Torneio de Robótica do IFSP (TRIF)](https://www.ifsp.edu.br/ultimas-noticias/4628-ifsp-abre-inscricoes-para-o-5-torneio-de-robotica)
*   [RoboCup](https://www.robocup.org/)
*   [IronCup](https://events.robocore.net/)

## Lista de Materiais (Bill of Materials - BOM)

Para a reprodução do robô, a seguinte lista de materiais (BOM) detalha os componentes essenciais, incluindo especificações e, quando aplicável, sugestões de fornecedores e custos estimados. Esta seção visa facilitar a aquisição e montagem do hardware.

*   **Microcontrolador:** Arduino Uno R3
    *   Quantidade: 1
    *   Fornecedor Sugerido: [FilipeFlop](https://www.filipeflop.com/produto/arduino-uno-r3/)
    *   Custo Estimado: R$ 80,00
*   **Driver de Motor:** L298N
    *   Quantidade: 1
    *   Fornecedor Sugerido: [Robocore](https://www.robocore.net/loja/drivers-de-motores/driver-ponte-h-l298n)
    *   Custo Estimado: R$ 35,00
*   **Sensores Infravermelhos:** Módulo TCRT5000 (5 vias)
    *   Quantidade: 1
    *   Fornecedor Sugerido: [Eletrogate](https://eletrogate.com/produto/modulo-sensor-infravermelho-5-vias-tcrt5000/)
    *   Custo Estimado: R$ 45,00
*   **Motores DC com Caixa de Redução:** Motor DC 3-6V com caixa de redução (tipo N20)
    *   Quantidade: 2
    *   Fornecedor Sugerido: [Casa da Robótica](https://www.casadarobotica.com/motor-dc-com-caixa-de-reducao-3-6v-n20.html)
    *   Custo Estimado: R$ 25,00 (cada)
*   **Rodas:** Rodas de borracha para robótica (compatíveis com motor N20)
    *   Quantidade: 2
    *   Fornecedor Sugerido: [Robocore](https://www.robocore.net/loja/rodas/roda-de-borracha-34x7mm)
    *   Custo Estimado: R$ 10,00 (cada)
*   **Roda Boba:** Roda boba metálica
    *   Quantidade: 1
    *   Fornecedor Sugerido: [FilipeFlop](https://www.filipeflop.com/produto/roda-boba-metalica/)
    *   Custo Estimado: R$ 15,00
*   **Chassi:** Acrílico cortado a laser (design personalizado)
    *   Quantidade: 1
    *   Fornecedor Sugerido: [Serviço de corte a laser local]
    *   Custo Estimado: R$ 50,00
*   **Bateria:** Suporte para 4 pilhas AA com conector P4
    *   Quantidade: 1
    *   Fornecedor Sugerido: [Eletrogate](https://eletrogate.com/produto/suporte-para-4-pilhas-aa-com-conector-p4/)
    *   Custo Estimado: R$ 8,00
*   **Fios Jumper:** Kit de fios jumper macho-macho e macho-fêmea
    *   Quantidade: 1 kit
    *   Fornecedor Sugerido: [Qualquer loja de eletrônicos]
    *   Custo Estimado: R$ 20,00

## Arquivos de Projeto de Hardware

Os arquivos de projeto de hardware, incluindo esquemáticos eletrônicos, layouts de placa de circuito impresso (PCB) e modelos 3D do chassi, são disponibilizados para facilitar a replicação e modificação do robô. Recomenda-se o uso de software de código aberto para visualização e edição desses arquivos.

*   **Esquemáticos e Layouts de PCB:** (Localização: `hardware/schematics/`)
*   **Modelos 3D do Chassi:** (Localização: `hardware/3d_models/`)

## Arquitetura de Software

A arquitetura de software do robô seguidor de linha é modular, visando clareza, manutenibilidade e extensibilidade. O código-fonte é desenvolvido em C++ para a plataforma Arduino IDE e é organizado em funções e bibliotecas que abstraem as interações com os sensores e atuadores. Os principais módulos incluem:

*   **Módulo de Leitura de Sensores:** Responsável por adquirir os dados dos sensores infravermelhos, convertendo os sinais analógicos em informações digitais sobre a posição da linha.
*   **Módulo de Controle de Motores:** Gerencia a velocidade e direção dos motores DC com base nas decisões do algoritmo de controle.
*   **Algoritmo de Controle:** Implementa a lógica principal para seguir a linha. Pode variar de um controle proporcional (P) simples a um controle PID (Proporcional-Integral-Derivativo) mais avançado para maior precisão e suavidade no movimento.
*   **Módulo de Comunicação (Opcional):** Permite a interação com o robô via serial ou Bluetooth para depuração e ajuste de parâmetros.

## Hardware e Software de Código Aberto

*   Todo o hardware, software e documentação devem aderir aos princípios de **liberdade, abertura, publicidade, didática, reprodutibilidade e acessibilidade**.
*   O hardware pode ser adquirido, mas o **software deve ser integralmente desenvolvido pelas equipes**.
*   A licença **LGPL** deve ser utilizada para o software.
*   A licença **CC-BY-SA 4.0** deve ser utilizada para a documentação e o hardware.

## Metodologia de Projeto

O desenvolvimento do trabalho deve empregar uma metodologia formal de gestão de projetos (e.g., 5W2H), fundamentada em referências como [Gestão de Projetos - Livro Online](https://cm-kls-content.s3.amazonaws.com/201602/INTERATIVAS_2_0/GESTAO_DE_PROJETOS/U1/LIVRO_UNICO.pdf).

Os principais elementos metodológicos a serem elaborados e apresentados incluem:

*   **Escopo do Projeto:**
    *   Definição clara das funcionalidades do robô (requisitos mínimos e bônus).
    *   **Especificações Técnicas do Robô:** pesquisa e seleção de componentes (sensores, microcontrolador, motores, *drivers*, fonte de energia) e abordagem do algoritmo de controle, com justificativa das escolhas (baseada em projetos existentes e competições online).
    *   **Regras da Competição:** pesquisa e definição do regulamento detalhado (dimensões/peso do robô, características da pista, cronometragem, penalidades - fundamentado em regulamentos existentes). A regra existente pode ser utilizada como base, devendo ser formalizada até a terceira semana de aulas.
    *   Definição do Artigo (objetivo, estrutura, público-alvo).
    *   Estrutura Analítica do Projeto (EAP) / *Work Breakdown Structure* (WBS): Detalhamento das tarefas do projeto (robô + artigo).
*   **Gerenciamento de Tempo:** cronograma com tarefas e marcos. Ferramentas como o [GanttProject](https://www.ganttproject.biz/) podem ser utilizadas.
*   **Gerenciamento de Recursos:** definição da equipe, responsabilidades, lista básica de materiais/equipamentos e plano de aquisição.
*   **Gerenciamento da Qualidade:** estabelecimento de critérios de sucesso (robô e artigo) e procedimentos de teste.
*   **Gerenciamento da Comunicação:** [Utilização de ferramentas (e.g., Discord)](./comunicacao.md).
*   **Gerenciamento de Riscos:** identificação preliminar de riscos e elaboração de Plano de Contingência.
*   **Gerenciamento das Aquisições (básico):** planejamento para a obtenção de materiais.

### Relação com a Disciplina

É imperativo que o projeto evidencie sua conexão com a disciplina, visando tornar o aprendizado mais significativo e contextualizado. Exemplos incluem:

-   A programação do robô demanda o desenvolvimento de algoritmos e a aplicação de estruturas de controle, como condicionais (*if/else*) e laços de repetição (*for/while*).
-   Aquisição de proficiência em linguagens de programação como C/C++, Arduino IDE, Python, entre outras.
-   O processamento dos dados dos sensores pode envolver o uso de *arrays*, listas ou outras estruturas de dados.

## Cronograma Sugerido

Um projeto de robótica pode ser segmentado em diversas fases ao longo de um semestre ou ano. A seguir, um cronograma exemplificativo baseado em um projeto real:

-   **Mês 1: Fundamentação**
    *   Pesquisa sobre montagem de robôs.
    *   Pesquisa sobre noções de componentes elétricos e plataforma Arduino.
    *   Organização das equipes e espaços de trabalho.
    *   Pesquisa sobre programação em C/C++ e para Arduino.
    *   Aprofundamento em lógica de programação.

-   **Mês 2: Preparação para Competições**
    *   Análise de regulamentos e inscrições para torneios (e.g., OBR, FLL, TRIF, TBR).
    *   Desenvolvimento do protótipo do robô.
    *   Treinamento intensivo, incluindo atividades em fins de semana.

-   **Mês 3: Projeto e Inovação**
    *   Desenvolvimento de um projeto de inovação (comum em torneios como o FLL).
    *   Sessões de *brainstorming* e dinâmicas para estimular a criatividade e o trabalho em equipe.
    *   Construção do protótipo final e estabelecimento de metas.

-   **Mês 4: Eventos e Finalização**
    *   Realização de um torneio interno para testes.
    *   Participação em eventos e competições externas.
    *   Apresentação dos resultados e projetos finais.

## Divisão de Responsabilidades

-   **Desenvolvimento Web:** criação e manutenção do website da equipe.
-   **Banco de Dados:** desenvolvimento e gestão de um banco de dados para peças, custos, datas, fotografias, vídeos, etc.
-   **Redes:** estabelecimento da infraestrutura de comunicação entre dispositivos (celular, microcontrolador, robô).
-   **Programadores:** desenvolvimento do código do robô, utilizando linguagens como C/C++, Arduino IDE, entre outras.
-   **Construtores:** responsáveis pela montagem física do robô, incluindo estrutura, motores, sensores, etc.
-   **Designers:** responsáveis pelo design do robô, considerando a otimização para o desafio (com documentação pertinente).
-   **Estrategistas:** análise do regulamento e definição das estratégias para a competição.
-   **Documentadores:** registro do processo de desenvolvimento, elaboração de relatórios, captação de imagens (fotografias e vídeos), redação, e divulgação em plataformas como o site e YouTube.
-   **Integração/Organização:** participação na integração de componentes, organização geral do projeto, e apoio na captação de imagens.

## Diário de Bordo do Projeto

-   Recomenda-se a manutenção de um diário de bordo detalhado.
-   É fundamental registrar todas as atividades.
-   Sugere-se dedicar 30 minutos diários para o registro.
-   A postergação do registro pode resultar na perda de informações.
-   A documentação escrita é essencial, não se limitando ao registro mental.
-   Registrar: quem, como, onde, por que, para que, e dúvidas.
-   Considerar o uso de plataformas para o diário.

## Registro da Evolução do Projeto

O registro contínuo da evolução do projeto é fundamental para a documentação final. Recomenda-se designar um **responsável** pela consistência do registro.

*   **Métodos de Registro:** anotações diárias, fotografias (progresso, testes), vídeos (funcionamento, demonstrações).
*   O registro detalhado subsidia a elaboração do relatório final e as apresentações em seminários.
*   A evolução do projeto deverá ser publicada online (usar os modelos: [Fab Academy 2024](https://fabacademy.org/2024/people.html), [Fab Academy 2023](https://fabacademy.org/2023/people.html)).

## Publicação Acadêmica

A publicação dos resultados do trabalho é de suma importância. A qualidade da documentação e das referências é crucial.

*   Seguir as diretrizes do 28º EAC. Para o 2º Semestre, uma publicação ocorrerá no EAC, e outra no Zenodo.
*   O formato de publicação deve seguir o modelo do [Encontro de Atividades Científicas (EAC)](https://eac.pgsscogna.com.br/).
*   Todas as fontes consultadas devem ser devidamente referenciadas ([Guia FURB](https://www.furb.br/web/upl/arquivos/201210081830180.Fontes_2010.pdf?20230627183338)).
*   Todas as figuras, tabelas e imagens devem possuir indicação da fonte ([Guia ESPM](https://normas-abnt.espm.br/index.php?title=Figuras)).
*   **Aspectos Éticos:** é imprescindível o rigor ético em relação a direitos autorais e **plágio**. A citação correta das fontes é obrigatória. A coautoria com docentes que acompanharam o projeto deve ser considerada, se apropriado (consultar professores e coordenador).

## Portfólio Acadêmico

O portfólio constitui parte integrante do projeto da disciplina, sendo individual para cada participante. É uma ferramenta essencial para o início da carreira profissional, contribuindo para a visibilidade, reconhecimento e construção de confiança no trabalho desenvolvido, além de diferenciar o profissional no mercado e ampliar suas oportunidades. Facilita a avaliação e análise das competências, proporcionando uma visão clara das conquistas. Um portfólio bem elaborado reflete a dedicação e a paixão pela área de atuação, funcionando como uma vitrine da marca pessoal.

### Estrutura do Portfólio Online

-   O portfólio deve incluir uma Página Principal (*Landing Page* / *Home Page*).
-   Funciona como um "índice" ou resumo executivo dos trabalhos.
-   Deve ser concisa, objetiva, visualmente atraente e com design limpo.
-   Utilizar frases sucintas e múltiplos links para direcionar o visitante.
-   Criar subpáginas dedicadas para detalhes de cada projeto.
-   As descrições dos projetos devem ser resumidas, claras, lógicas e focadas na metodologia/pesquisa.
-   Hospedar código/arquivos externos (e.g., GitHub) e incluir links diretos.
-   Solicitar *feedback* a docentes e colegas para identificar oportunidades de aprimoramento.
-   O portfólio serve como um "índice" que conterá os endereços do website do projeto, canal do YouTube, DOI do artigo, entre outros.

## Identificação da Equipe e Domínio

-   Definir em conjunto o nome da equipe.
-   Criar uma conta no GitHub com o nome da equipe (e.g., `http://www.github.com/melancia`).
-   Criar um repositório denominado `melancia.github.io` e configurar o GitHub Pages.
-   O site do projeto estará acessível em `http://melancia.github.io`.

## Uso de Ferramentas de Inteligência Artificial (IA) no Projeto

Ferramentas de IA Generativa (e.g., Gemini, Copilot) podem ser utilizadas como auxílio, desde que o uso seja **ético, responsável e transparente**.

*   **IA como suporte, não substituição:** útil para *brainstorming*, sugestões de código/texto, revisão gramatical e resumos (sempre com verificação). Não substitui o pensamento crítico e a análise humana.
*   **Verificação crítica essencial:** **nunca confiar cegamente**. A IA pode gerar informações incorretas ("alucinações"). Todas as informações devem ser verificadas com fontes confiáveis e o conhecimento do usuário.
*   **Plágio e originalidade:** o conteúdo gerado por IA não é de autoria do usuário. A cópia direta constitui **plágio**. Utilizar a IA para ideias, mas a criação e redação finais devem ser originais.
*   **Transparência e citação:** declarar explicitamente o uso de IA (quais ferramentas, para qual finalidade). Referenciar a IA utilizada (a própria ferramenta pode auxiliar nesta citação).
*   **Uso ético:** empregar a IA para auxiliar no aprendizado, com transparência e respeito aos direitos autorais.
*   **Ferramentas de detecção:** instituições acadêmicas utilizam ferramentas para identificar conteúdo gerado por IA e plágio.

## Testes e Validação

A validação do desempenho do robô é realizada através de uma série de testes sistemáticos, garantindo a conformidade com os requisitos de projeto e a otimização do comportamento em pista.

*   **Testes de Unidade:** verificação individual de componentes (sensores, motores) para assegurar seu funcionamento adequado.
*   **Testes de Integração:** avaliação da interação entre os módulos de hardware e software.
*   **Testes de Sistema:** medição do desempenho global do robô na pista, incluindo:
    *   **Tempo de Percurso:** registro do tempo necessário para completar o circuito.
    *   **Precisão no Seguimento de Linha:** análise da capacidade do robô de manter-se sobre a linha.
    *   **Robustez:** avaliação do desempenho em diferentes condições de iluminação e pequenas variações na pista.

## Trabalhos Futuros e Recomendações

Este projeto serve como uma base para futuras pesquisas e desenvolvimentos. As seguintes áreas são sugeridas para trabalhos futuros:

*   **Otimização do Algoritmo de Controle:** implementação e ajuste fino de algoritmos PID avançados ou técnicas de controle adaptativo para melhorar a velocidade e a precisão.
*   **Detecção e Desvio de Obstáculos:** integração de sensores adicionais (e.g., ultrassom, infravermelho de distância) para permitir que o robô detecte e desvie de obstáculos na pista.
*   **Comunicação Wireless Avançada:** desenvolvimento de um sistema de telemetria para monitoramento em tempo real do robô e ajuste de parâmetros via comunicação sem fio.
*   **Visão Computacional:** utilização de câmeras para reconhecimento de padrões mais complexos na pista ou identificação de objetos.
*   **Otimização de Hardware:** redução do tamanho e peso do robô, otimização do consumo de energia e exploração de materiais alternativos para o chassi.

## Glossário

*   **Arduino IDE:** ambiente de Desenvolvimento Integrado para a plataforma Arduino.
*   **BOM (Bill of Materials):** lista de Materiais.
*   **CAD (Computer-Aided Design):** projeto Assistido por Computador.
*   **Chassi:** Estrutura física do robô.
*   **Driver de Motor:** circuito eletrônico que controla a potência e direção dos motores.
*   **EAP (Estrutura Analítica do Projeto):** decomposição hierárquica do trabalho do projeto.
*   **IA (Inteligência Artificial):** campo da ciência da computação que desenvolve máquinas capazes de simular a inteligência humana.
*   **L298N:** circuito integrado com ponte H dupla, comumente usado como driver de motor.
*   **Layout:** disposição física dos componentes em uma placa de circuito impresso.
*   **PCB (Printed Circuit Board):** Placa de Circuito Impresso.
*   **PID (Proporcional-Integral-Derivativo):** tipo de controlador de feedback amplamente utilizado em sistemas de controle.
*   **Robô Autônomo:** robô capaz de operar sem intervenção humana direta.
*   **Robô Seguidor de Linha:** robô projetado para seguir uma linha predefinida no chão.
*   **TCRT5000:** sensor infravermelho de refletância, comumente usado para detecção de linha.
*   **WBS (Work Breakdown Structure):** Estrutura Analítica do Projeto (EAP).

## Recursos Online e Referências

Esta seção consolida links e referências úteis, organizados por categoria:

### Exemplos de Projetos de Robôs e de Trabalhos Acadêmicos

*   **Referências de Equipes de Robótica:**
    *   Ironcup 2018 - Seguidor de linha: [vídeo](https://youtu.be/ET_KOCVGc98)
    *   Robô Sloth, Project Neon (UFABC): [Página](https://projectneon.dev/), [Github](https://github.com/project-neon), [Youtube](https://www.youtube.com/@ProjectNeon), [Instagram](https://www.instagram.com/projectneon/), [Facebook](https://www.facebook.com/ufabc.neon)
    *   Equipe Robocap (UFSJ): [notícia](https://www.ufsj.edu.br/noticias_ler.php?codigo_noticia=6843), [Facebook](https://www.facebook.com/equiperobocapufsj/), [Web](https://equiperobocap.wixsite.com/equiperobocap)
    *   ThundeRatz (Poli/USP): [página](https://thunderatz.org/), [Github](https://github.com/ThundeRatz/), [Robô Tracer](https://thunderatz.org/projects/robots/tracer), [Robô Redondinho](https://thunderatz.org/projects/robots/redondinho), [vídeo Iron Cup 2020](https://youtu.be/w3KJgNGFeb8), [vídeo Summer Challenge 2012](https://youtu.be/p9-iju_-pMw), [Memorial Winter Challenge](https://docplayer.com.br/63261771-Memorial-da-participacao-da-thunderatz-no-winter-challenge-10a-edicao.html), [Blog Natalia Kreuser](https://nataliakreuser.wordpress.com/2015/02/13/urc-conheca-a-equipe-thunderatz/), [Instagram](https://www.instagram.com/thunderatz/), [Wikipedia](https://pt.wikipedia.org/wiki/ThundeRatz)
    *   Trincabotz (CEFET-MG): [site](https://trincabotz.com.br/), [Twitter](https://twitter.com/trincabotz), [Instagram](https://www.instagram.com/trincabotz/), [vídeo IronCup 2020 Artemis](https://youtu.be/Ad8XyKWhwE0), [vídeo WCXII Ártemis](https://youtu.be/z0spzWxJKxU), [vídeo SRC 2018](https://youtu.be/Io-2ewbmxWI), [vídeo Iron cup 2019 Nêmesis e Ártemis](https://youtu.be/7ALRWt8QVME), [vídeo Iron Cup 2023 Perseguidor](https://www.youtube.com/watch?v=_TBno_ChXeY)
    *   Robotic4All (IFPR): [Github](https://github.com/Robotic4All), [Facebook](https://www.facebook.com/Robotic4All), [vídeo Salão Robótica 2019](https://youtu.be/iDTZZb-7LKk), [vídeo Clóvis Robô](https://youtu.be/epmw1bu26Po)
    *   ERUS (UFES): [Github](https://github.com/erufes)
*   **Exemplos de Trabalhos Acadêmicos (Artigos, TCCs, Anais EAC 2023):**
    *   BARONE, H. M. et al. **Programação e Desenvolvimento de Banco de Dados**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br//handle/123456789/72992).
    *   FILENO, J. D. S. et al. **Passo a Passo da Criação de um Robô com Placa de Arduino**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/73782).
    *   MORAES JUNIOR, M. R. D. et al. **Trabalho de Linguagem de Programação**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/73471).
    *   LIMA, M. A. O. et al. **Dando Asas à Criatividade com a Plataforma Arduino**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/71957).
    *   PEREIRA, M. E. et al. **Robô Seguidor de Linha**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/71813).
    *   NERO, J. C. C. D., & Miranda, E. F. **Gerenciamento de Banco de Dados**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/73614).
    *   SILVA, J. V. B. D., & Miranda, E. F. **Carrinho Educativo Controlado por Bluetooth**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/73423).
    *   SOUZA, L. D. A. et al. **Fases da Compilação na Utilização do Arduino Uno**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/72000).
    *   SOUZA, L. D. A. et al. **Utilização do Microcontrolador Arduino para a Construção de um Robô Seguidor de Linha**. [Artigo EAC 2023](https://repositorio.pgsscogna.com.br/handle/123456789/73747).
    *   BANDEIRA, M. S.; CARNEIRO, R. S. (UFRJ, 2021). **Projeto Básico de Robô Seguidor de Linha Controlado por Arduino** (Exemplo de TCC). [PDF](https://app.uff.br/riuff/bitstream/handle/1/22265/TCC%20Matheus%20Bandeira%20e%20Rog%E9rio%20Carneiro_vSemAssinatura%20(1).pdf;jsessionid=C9A837B0A3C48D58A13FE0A8CA14BA4A?sequence=1).

### Guias, Modelos e Ferramentas para Projeto, Documentação e Publicação

*   **Metodologia de Projeto:** [Gestão de Projetos - Livro Online](https://cm-kls-content.s3.amazonaws.com/201602/INTERATIVAS_2_0/GESTAO_DE_PROJETOS/U1/LIVRO_UNICO.pdf).
*   **Registro da Evolução (Modelos Fab Academy):** [2024](https://fabacademy.org/2024/people.html), [2023](https://fabacademy.org/2023/people.html).
*   **Plataformas de Publicação Online:** [EAC](https://eac.pgsscogna.com.br/), [Zenodo](https://zenodo.org/).
*   **Guias de Normatização (Referências, Figuras - ABNT):** [Fontes (FURB)](https://www.furb.br/web/upl/arquivos/201210081830180.Fontes_2010.pdf?20230627183338), [Figuras (ESPM)](https://normas-abnt.espm.br/index.php?title=Figuras).
*   **Modelos de Artigo:** [Modelo (UTFPR)](http://paginapessoal.utfpr.edu.br/tiagolacerda/modelo-artigo-cientifico/MODELO%20PARA%20ELABORAR%20ARTIGO%20CIENTIFICO.doc/view), [Exemplo Curto (Wiley)](https://onlinelibrary.wiley.com/doi/abs/10.1002/pamm.201900373).
*   **Revistas Científicas (Sugestões):** RSC ([UNIFACS](https://revistas.unifacs.br/index.php/rsc/index)), Computação Brasil ([SBC](https://www.sbc.org.br/home/publicacoes-mainmenu/computacao-brasil)), e-Locução ([FAEX](https://periodicos.faex.edu.br/index.php/e-Locucao)), [SciELO](https://www.scielo.br/).
*   **Ferramentas de Controle de Versão e Hospedagem:** [GitHub](https://github.com/).
*   **Gerenciamento de Referências:** [Zotero](https://www.zotero.org/).
*   **Identificador de Autor:** [ORCID](https://orcid.org/).
*   **Ferramentas de Portfólio:** [Google Sites](https://sites.google.com/).
*   **Recursos sobre Git e Github:** [vídeos (R. Ballerini)](https://youtu.be/DqTITcMq68k), [vídeos (ATTEKITA DEV)](https://youtu.be/P9xXbEhqhqA), [vídeos (JOHN)](https://youtu.be/IfrMAmav9dQ), [vídeos (F. Fontoura)](https://youtu.be/UbJLOn1PAKw), [Curso @Curso em vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA), [conta Github @Curso em vídeo](https://youtu.be/1QTi8nIlK1o), [conta Github (MINHASTACK)](https://youtu.be/Prixgo_pXUI), [Git e Github (por Mucharski)](https://youtu.be/-I4Aa8wef8s).
*   **Recursos sobre Documentação e Publicação com GitHub Pages:** [vídeos (DOTCODE)](https://youtu.be/EuTM48lxtsE), [vídeos (P. Dinâmica)](https://youtu.be/5B4bHSiOOO8), [vídeos (R. Galleani)](https://youtu.be/k7rkjVfuB2M), [vídeos (F. Barbosa - Portfólio)](https://youtu.be/fu6mHp4ud4s), [vídeos (F. Barbosa - Portfólio HTML/CSS/JS)](https://youtu.be/EJGMZfeTX-4), [vídeos (E. Mendes - MkDocs)](https://www.youtube.com/live/GW6nAJ1NHUQ).
*   **Recursos sobre MkDocs:** [MkDocs Material (por Wildemberg Sales)](https://youtu.be/M5Ck4lvBn7w), [MkDocs Material (por James Willett)](https://youtu.be/xlABhbnNrfl).
*   **Recursos sobre Portfólio digital:** [modelo exemplo](https://efurlanm.github.io/teach-perfil.html), [vídeos (Como criar Portfólio Digital Acadêmico)](https://youtu.be/gZmSJfgNmw0), [vídeos (COMO CRIAR SEU PORTFOLIO DIGITAL)](https://youtu.be/3yq8k3uZOBw), [vídeos (Como publicar o seu Portfólio)](https://youtu.be/hq05xIDpaYw), [vídeos](https://www.youtube.com/live/_fjuGzLZyRc), [vídeos](https://youtu.be/GIRhSGCgbrY).
*   **Recursos sobre IA para trabalhos acadêmicos:** [Como Escrever Artigos Científicos Com o ChatGPT](https://youtu.be/YjNPo4400Mk), [Use o ChatGPT Para Trabalhos Acadêmicos](https://youtu.be/SareSYAmB9E), [COMO FAZER TCC COM CHATGPT](https://youtu.be/P520jhF4phQ), [COMO USAR O CHATGPT PARA ESCREVER ARTIGOS](https://youtu.be/CZUVD7c2LdM), [ChatGPT: guia de uso para trabalhos científicos](https://youtu.be/RGNOucYHo_M).
*   **Recursos Gerais (Seminário, Relatório, Projeto):** [Página Prof. Luiz Mesquita](https://sites.google.com/site/luizok/semestres-anteriores/semestre-20221/sistemas-digitais-e-microprocessadores), [Artigo Seminário Brasil Escola](https://brasilescola.uol.com.br/redacao/o-seminarioque-e-como-realizalo.htm), [vídeo Seminário (F. Rocha)](https://youtu.be/3l6D0rgEdAI), [vídeo Dicas Apresentação (F. May)](https://youtu.be/Xokn9aWLD08), [artigo relatório Brasil Escola](https://brasilescola.uol.com.br/redacao/o-relatorioque-e-como-faze-lo.htm), [vídeo Elaboração Projeto (A. D. dos Reis)](https://youtu.be/S-4tSLwc_yU), [vídeo GanttProject (C. Schultz)](https://www.youtube.com/@xxultz/search?query=ganttproject).

### Recursos Técnicos Específicos (Robô Seguidor de Linha)

Tutoriais e referências técnicas focadas no robô:

*   [Artigo Robô seguidor de linha (G. Candido)](https://portal.vidadesilicio.com.br/robo-seguidor-de-linha).
*   [Vídeo Robô Seguidor de Linha ANDANDO SOZINHO!](https://www.youtube.com/shorts/Mmm2BA8QPvg).
*   [Vídeo Criando Robô Seguidor de Linha com Arduino](https://www.youtube.com/watch?v=OjdDcRlEti4).
*   [Vídeo Carrinho com Módulo Seguidor de Linha](https://www.youtube.com/watch?v=HjjLJPkaGhc).
*   [Vídeo Obstacle sensor and line sensor arduino (En)](https://www.youtube.com/watch?v=GjL_Zg6N19Q).
*   [Vídeo Como Montar seu Primeiro Robô](https://www.youtube.com/watch?v=eAYiwWx17gk).
*   [Tutorial Robô Seguidor de Linha (Robocore)](https://www.robocore.net/tutoriais/robo-seguidor-de-linha).
*   [Artigo Line Follower Robot Car Arduino (En)](https://circuitbest.com/line-follower-robot-car-with-arduino-uno-l298n-driver-ir-sensor/).
*   [Vídeo DIY Mini Sumo Robot (En)](https://youtu.be/vxSI6JNT5t0).
*   [projeto Speed Line Follower Robot V4 (En)](https://www.hackster.io/drakerdg/speed-line-follower-robot-v4-9f6df1).
*   [Projeto Line Follower Robot (1) (En)](https://www.hackster.io/mindhe_aniket/line-follower-robot-1db5ae).
*   [Projeto Line Follower Robot (2) (En)](https://www.shubhamsuresh/line-follower-robot-ebf129).
*   [Eventos de Robótica (Robocore)](https://events.robocore.net/).
*   [Slide Robô Autônomo Explorador de Labirinto (UFAC)](https://www.slideshare.net/marcosantonio5811/seguidor-de-linha).
*   [Vídeo Robô Seguidor de Linha Completo (RoboCore)](https://youtu.be/KY-BdZ-YDMI).
*   [Vídeo Monte um robô seguidor de linha (WR Kits)](https://youtu.be/C59--0zq_y8).
*   [Site Tudo sobre Arduino (br-arduino.org)](https://br-arduino.org/).
*   [Simulador online (Tinkercad)](https://youtu.be/HQmhucuK6cE).
*   [IDE Arduino (como usar)](https://youtu.be/T1bfWFSJGOA).
*   [Plataforma LEGO Mindstorms](https://www.lego.com/en-us/themes/mindstorms)

<br><sub>Last edited: 2025-07-27 11:50:05</sub>
