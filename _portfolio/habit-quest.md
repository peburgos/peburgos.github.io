---
title: "Habit Quest"
excerpt: "Aplicativo para incentivar a prática de atividades físicas através do uso da gamificação"
date: 2022-02-16T23:20:02-05:00
toc: true
toc_label: "Índice"
sidebar:
  - title: "Período"
    text: "Segundo semestre de 2020"
  - title: "Responsabilidades"
    text: "Realizar processos de UX/UI e aplicar conceitos de Interação Humano-Computador para entregar a interface de um produto a ser lançado no mercado"
header:
  image: /assets/images/Habit Quest/cover-habitquest.png
  teaser: /assets/images/Habit Quest/preview-habitquest.png
  caption: "Crédito da imagem: [**Freepik**](https://Freepik.com)"
related: false
categories:
  - portfolio

carrossel-finalizado:
  - url: /assets/images/Habit Quest/finalizado - tela de inicio.png
    image_path: /assets/images/Habit Quest/finalizado - tela de inicio.png
  - url: /assets/images/Habit Quest/finalizado - tela de leaderboard.png
    image_path: /assets/images/Habit Quest/finalizado - tela de leaderboard.png
  - url: /assets/images/Habit Quest/finalizado - tela de progressão.png
    image_path: /assets/images/Habit Quest/finalizado - tela de progressão.png
  - url: /assets/images/Habit Quest/finalizado - tela de estatísticas.png
    image_path: /assets/images/Habit Quest/finalizado - tela de estatísticas.png
  - url: /assets/images/Habit Quest/finalizado - tela de coleção.png
    image_path: /assets/images/Habit Quest/finalizado - tela de coleção.png
  - url: /assets/images/Habit Quest/finalizado - tela de conquistas.png
    image_path: /assets/images/Habit Quest/finalizado - tela de conquistas.png

---
Esse projeto foi desenvolvido durante a disciplina de Projeto Integrado II do curso de Sistemas e Mídias Digitais da Universidade Federal do Ceará.

O principal conceito do aplicativo é o **uso de gamificação como forma de trazer uma progressão visual dos benefícios em se construir e manter o hábito de praticar atividades físicas.**

Colaborei com os demais membros principalmente durante o processo de ideação e definição, posterior a isso nos comunicamos para compartilhar os progressos obtidos nas pesquisas e no protótipo enquanto eles se dedicavam no desenvolvimento da implementação do aplicativo.

**As imagens a seguir são as telas do aplicativo com o design finalizado, e em seguida a descrição sobre processo utilizado na construção delas**

{% include gallery id="carrossel-finalizado" caption="Telas finalizadas do aplicativo Habit Quest" %}


{% comment %}
# Objetivos
{% endcomment %}

# 1 - Entendendo a necessidade do público
---
Depois de que a equipe coletivamente definiu o público a ser trabalhado, busquei esse conversar com esse público para entender qual necessidade poderia ser trabalhada dentro do nosso escopo.



## Etapa de entrevista

Nosso perfil buscado foram pessoas que praticam ou praticavam exercícios físicos e se interessam por jogos digitais, buscando entender porque esse público parou de praticar atividades físicas e quais os estímulos que faziam eles continuarem jogando jogos digitais.

Recrutamos participantes para a entrevista estruturada através de um grupo de alunos no Facebook do curso Sistemas e Mídias Digitais da Universidade Federal do Ceará, e realizei a entrevista com 6 pessoas através do Messenger e Whatsapp. Os participantes também foram consultados se teriam interesse em participar de testes de usabilidade posteriormente.

<figure>
	<a href="/assets/images/Habit Quest/entrevista.png"><img src="/assets/images/Habit Quest/entrevista.png"></a>
	<figcaption><a href="https://docs.google.com/document/d/e/2PACX-1vTCXsbuzGsIBDZwuu5nsYMbqUBYWnxvW9focmPjdmnDTgGETXX-QWDBm3slpT_doKapVeld1kXPI8Tk/pub" title="Acesse os dados da entrevista completa">Acesse os dados da entrevista completa</a></figcaption>
</figure>

## Insights obtidos

Descobrimos que um dos principais motivos de desistência e desmotivação para esse público é a **falta recursos visuais que lhe apresentassem de forma clara a progressão** em seu exercício, faltando também **feedbacks mais imediatos sobre a sua performance** .

Também concluímos que o produto a ser criado deveria ser um aplicativo voltado para manutenção de hábitos, pois **o importante** para o nosso público **é a continuar praticando a atividade ao longo do tempo** e não sobre manter uma prática específica.


# 2 - Wireframes e teste de usabilidade

---

Depois de identificar as principais necessidades, construí sketchs para explorar possibilidades e ideias para algumas telas.

Depois dessas explorações foi construído o wireframe para ser utilizado no testes de usabilidade com usuários para validar a interface o mais cedo quanto possível e minimizar riscos no desenvolvimento. Considerando quais seriam os fluxos mais importantes a serem testados, escolhi priorizar o wireframe da tela de "Início" e "Coleção" para o teste, já que essas são mais importantes para as principais funcionalidades a serem utilizadas no aplicativo.

<figure class="half">
    <a href="/assets/images/Habit Quest/baixaFidelidade - home2.png"><img src="/assets/images/Habit Quest/baixaFidelidade - home2.png"></a>
    <a href="/assets/images/Habit Quest/médiaFidelidade - home.png"><img src="/assets/images/Habit Quest/médiaFidelidade - home.png"></a>
    <figcaption>Rascunho e wireframe da tela de "Início"</figcaption>
</figure>


## Avaliação de usabilidade

Partindo dessas explorações montei um wireframe no Figma para testar com os usuários as principais funcionalidades do aplicativo:

- ver quais são os seus hábitos em outro dia
- editar quais são os dias de um determinado hábito
- adicionar um novo hábito
- alterar a visibilidade de uma conquista no seu perfil

O teste de usabilidade contou com 5 participantes, dentre os 6 que foram previamente contatados na etapa de entrevista. O teste foi realizado de forma remota e não moderada usando a plataforma Maze.

## Resultados do teste de usabilidade

Testar o mais cedo quanto possível nos permitiu minimizar os impactos que teriam ocorridos devido aos ajustes necessários caso os testes tivessem sidos realizados com o recurso já implementado.

Os dados obtidos pelo teste foram **essenciais** para identificar quais as **informações** que deveriam ou não serem **priorizadas** para serem exibidas durante os fluxos das funcionalidades do app e quais eram as interações que deveriam ser simplificadas para serem mais intuitivas ao usuário.

Por exemplo, **com base nos dados sobre o teste no fluxo de editar os dias de um hábito repensei a forma de interação** tanto para chegar na edição quanto como ativar elas, **buscando simplificar e tornar esse uso mais intuitivo"**

### Exemplos de dados utilizados para diagnosticar pontos de confusão no fluxo de edição de dias

<figure class="half">
    <a href="/assets/images/Habit Quest/MazeImg1.png"><img src="/assets/images/Habit Quest/MazeImg1.png"></a>
    <a href="/assets/images/Habit Quest/MazeImg2.png"><img src="/assets/images/Habit Quest/MazeImg2.png"></a>
    <figcaption>Dados obtidos pelo Maze indicando problemas de usabilidade em partes do fluxo</figcaption>
</figure>

<figure>
	<a href="/assets/images/Habit Quest/MazeReport.png"><img src="/assets/images/Habit Quest/MazeReport.png"></a>
	<figcaption><a href="https://app.maze.co/report/9afd1akehg6qvd/#intro" title="Confira o relatório completo do teste de usabilidade no Maze">Confira o relatório completo do teste de usabilidade no Maze</a></figcaption>
</figure>

# 3 - Ajustes e refinamento de telas

---

Depois de analisar cuidadosamente os dados obtidos no teste, as telas foram ajustadas para ficarem mais alinhadas com o modelo mental dos usuários, além de também aplicar a identidade visual que vinha sendo desenvolvida enquanto isso.

Confira abaixo o protótipo de alta fidelidade feito no Figma.

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2F8qhv2lhPyvyf8EFGG4y8W7%2FHabit-Quest%3Fnode-id%3D610%253A898" allowfullscreen></iframe>


# 4 - Aprendizados durante o projeto

---

Uma das maiores dificuldades do projeto foi a realização das pesquisas de forma remotas devido ao impacto do distanciamento social decorrente da pandemia.  

A realização das entrevista via mensagem de texto foi algo pensado para se encaixar melhor nas possíveis limitações de falta de internet ou tempo para responder ela, entretanto muitos detalhes sobre o contexto acabaram não sendo captados.

Como forma de resolver isso, nas próximas vezes talvez seja melhor tentar primeiro entrevistar por vídeo ou áudio e posteriormente transcrever o que foi dito, e apenas caso necessário ou caso o participante se sinta melhor optar pelo texto.

Ter uma mulher como participante durante a etapa de entrevista também foi algo extremamente  rico pro desenvolvimento de um projeto voltado a pessoas interessadas em jogos digitais.

Muitos problemas nem sequer teriam sido levantados e documentados sem essa participação, tais como a toxicidade em jogos multiplayer. Outro exemplo disso é o avatar utilizado como identificação entre usuários no aplicativo, que também teria que ser mais representativo.

Assim, ficou bem claro pra mim o quão importante é incluir e buscar ativamente uma diversidade maior de participantes o mais cedo no desenvolvimento quanto possível.

Outro ponto que pode ser melhorado é a condução do teste de usabilidade. Por não conhecer tanto sobre na época, acabei optando pelo não moderado ao invés do moderado (através do meet, zoom, ou outra ferramenta do tipo).

Dessa forma teria obtido resultados mais ricos por ajudar o participante a organizar seus próprios pensamentos (sem guia-lo, obviamente), além de melhorar a experiência do participante de não se sentir tão abandonado durante o processo.
