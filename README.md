# <a target="_blank" href="https://group-6-trivia-project.surge.sh/">Trivia</a>

No projeto Trivia foi desenvolvido em equipe um jogo de perguntas e respostas baseado no jogo Trivia (tipo um show do milhão americano rs) utilizando React e Redux. As funcionalidades foram desenvolvidas de acordo com as demandas definidas em um quadro Kanban, possibilitando que tivéssemos uma experiência mais próxima do mercado de trabalho.

# Equipe
<a target="_blank" href="https://github.com/duarte-dot">@duarte-dot</a> <br>
<a target="_blank" href="https://github.com/PedroEmmanuelBuerger">@PedroEmmanuelBuerger</a> <br>
<a target="_blank" href="https://github.com/JessicaBiancajbro">@JessicaBiancajbro</a> <br>
<a target="_blank" href="https://github.com/paulofonseca182">@paulofonseca182</a> <br>
<a target="_blank" href="https://github.com/rafaelameireles">@rafaelameireles</a> <br>

## Funcionalidades

<ul>
  <li><b>Login:</b> o usuário pode logar no jogo utilizando seu e-mail. Se o e-mail estiver cadastrado no site Gravatar, sua foto será associada ao perfil da pessoa usuária;</li>
  <li><b>Jogo:</b> na página do jogo, o usuário deverá escolher uma das respostas disponíveis para cada uma das perguntas apresentadas. A resposta deve ser marcada antes do contador de tempo chegar a zero, caso contrário a resposta será considerada errada;</li>
  <li><b>Score:</b> após responder 5 perguntas, o usuário será redirecionado para a tela de score, onde o texto mostrado depende do número de acertos;</li>
  <li><b>Ranking:</b> ao final de cada jogo, o usuário pode visualizar a página de ranking, se quiser;</li>
  <li><b>Configurações:</b> o usuário pode configurar algumas opções para o jogo em uma tela de configuração acessível a partir do cabeçalho do app;</li>
</ul>

## Tecnologias utilizadas

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
  <a target="_blank" href="https://opentdb.com"><li>API de Trivia OpenTDB</li></a>
  <a target="_blank" href="https://br.gravatar.com/"><li>API do Gravatar</li></a>
  <li>Redux</li>
</ul>

## Como rodar o projeto
<ol>
  <li>Clone o repositório: git clone https://github.com/duarte-dot/trivia.git</li>
  <li>Entre na pasta do projeto: cd trivia</li>
  <li>Instale as dependências: npm install</li>
  <li>Entre na branch com css: git checkout main-group-6-css</li>
  <li>Inicie o servidor: npm start</li>
  <li>Acesse a aplicação no seu navegador em: http://localhost:3000</li>
</ol>

Você também pode acessar através do <a target="_blank" href="https://group-6-trivia-project.surge.sh/">link de deploy</a>

## Principais aprendizados

<ul>
  <li>Criar uma store Redux em aplicações React;</li>
  <li>Criar reducers no Redux em aplicações React;</li>
  <li>Criar actions no Redux em aplicações React;</li>
  <li>Criar dispatchers no Redux em aplicações React;</li>
  <li>Conectar Redux aos componentes React;</li>
  <li>Criar actions assíncronas na sua aplicação React que faz uso de Redux.</li>
  <li>Desenvolver uma boa cobertura de testes</li>
</ul>

## Conclusão

O projeto Trivia foi uma oportunidade para a equipe desenvolver um jogo de perguntas e respostas utilizando tecnologias como React, Redux, HTML e CSS. As funcionalidades foram implementadas de acordo com as demandas definidas em um quadro Kanban, permitindo que os membros da equipe tivessem uma experiência mais próxima do mercado de trabalho. Com a criação da store Redux, reducers, actions e dispatchers, além da conexão com os componentes React, a equipe aprendeu a desenvolver uma aplicação robusta e escalável. Além disso, a criação de ações assíncronas na aplicação e a importância de uma boa cobertura de testes foram aprendizados valiosos. A aplicação também fez uso das APIs de Trivia OpenTDB e do Gravatar.
