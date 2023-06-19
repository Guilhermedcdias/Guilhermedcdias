# Meu Portfólio 👩‍💻

## Sobre Mim 😊

Guilherme, 19 anos, estudante de Desenvolvimento de Software Multiplataforma na FATEC de São José dos Campos. Sou apaixonado por programação e tenho experiência em Python, TypeScript, React, JavaScript, Java, C, PHP e Vue.js. Venci o Hackathon Acadêmico da ETEC e busco desenvolver soluções inovadoras e impactantes. Estou ansioso para contribuir para o avanço tecnológico e utilizar minhas habilidades em projetos desafiadores.

## Projetos Destacados 💼

### [API - 1º Semestre](https://github.com/404-BIS/Sistema-Gestao-Servicos)

<b>Problema: </b> Eu necessito de um sistema para registro e acompanhamento de problemas, onde seja possível enviar solicitações para executores. Os executores têm a opção de aceitar ou rejeitar as solicitações. Caso aceitem, eles devem resolver o problema e, em seguida, atualizar o status do chamado para "resolvido". Além disso, eles devem ter a capacidade de adicionar fotos que demonstrem a resolução do problema ao chamado. Posteriormente, como solicitante, desejo ter a possibilidade de avaliar tanto o serviço prestado quanto o executor responsável.

<b>Solução: </b> Para solucionar esse problema, propõe-se a implementação de um sistema de Helpdesk com três tipos de usuários: o administrador, o executor e o cliente.

A solução é desenvolvida utilizando tecnologias como Flask, HTML, CSS e JS, proporcionando uma plataforma intuitiva e funcional. O sistema oferece as seguintes funcionalidades:

Registro e acompanhamento de problemas: Os clientes podem registrar suas solicitações, descrevendo detalhadamente o problema enfrentado. Cada problema é registrado com um número de identificação único e um status inicial de "pendente".

Atribuição de executores: O sistema atribui de forma automática e sequencial as solicitações pendentes aos executores.

Aceitação e rejeição de solicitações: Os executores têm a opção de aceitar ou rejeitar as solicitações atribuídas a eles. Caso aceitem, eles se comprometem a resolver o problema dentro de um prazo determinado.

Resolução e atualização de status: Os executores que aceitam uma solicitação devem resolver o problema relatado. Após a resolução, eles atualizam o status do chamado para "resolvido". Além disso, eles têm a capacidade de adicionar fotos que demonstrem a resolução do problema ao chamado.

Avaliação do serviço prestado: Após a resolução do problema, os clientes podem avaliar tanto o serviço prestado quanto o executor responsável. Essas avaliações podem ser usadas para melhorar a qualidade do atendimento e identificar áreas de melhoria.

Painel de controle e relatórios: O sistema fornece um painel de controle para o administrador, permitindo o gerenciamento das solicitações, atribuição de executores e monitoramento do desempenho geral. Também são disponibilizados relatórios estatísticos para análise e tomada de decisões

Foi desenvolvido um site, meu papel foi de Product Owner, atuando como intermediário entre o cliente e a equipe de desenvolvimento, com o propósito de criar uma plataforma que facilite o controle de serviços na área de tecnologia da FATEC Profº Jessen Vidal. Utilizando tecnologias como Python (Flask), HTML, CSS e JS, o projeto possibilita a abertura e o encerramento de chamados, agilizando a identificação de problemas dentro do setor. Agradeço a oportunidade de desempenhar esse papel essencial no desenvolvimento do projeto.

<b>Tencologias Utilizadas: </b> 
- <img src="https://img.icons8.com/color/48/000000/flask.png"/> Flask
- <img src="https://img.icons8.com/color/48/000000/mysql.png"/> MySQL
- <img src="https://img.icons8.com/color/48/000000/html-5.png"/> HTML
- <img src="https://img.icons8.com/color/48/000000/css3.png"/> CSS
- <img src="https://img.icons8.com/color/48/000000/javascript.png"/> JavaScript
- <img src="https://img.icons8.com/color/48/000000/figma.png"/> Figma
- <img src="https://img.icons8.com/color/48/000000/slack.png"/> Slack

<b>Soft Skills: </b> 

Ao longo das sprints, desempenhei um papel significativo como Product Owner, fornecendo assistência ao time e solucionando dúvidas e problemas de código. Além disso, como responsável pela comunicação entre o cliente e o time, trabalhei para aprimorá-la, interagindo frequentemente com o cliente para esclarecer as dúvidas da equipe em relação ao projeto.

Durante a aplicação do processo Scrum, busquei promover a transparência, compartilhando com clareza o meu progresso nas tarefas que assumi. Essa transparência permitiu que todos os membros da equipe acompanhassem o andamento do projeto de forma eficiente.

A responsabilidade foi um aspecto que desenvolvi ao cumprir os prazos estabelecidos para a entrega das sprints, honrando os compromissos assumidos. Além disso, trabalhamos diligentemente para entregar aquilo que foi prometido, evidenciando nosso comprometimento e responsabilidade com o sucesso do projeto.

No que diz respeito à resolução de problemas, destaco minha habilidade em lidar com os desafios que surgiram durante o caminho. Esforcei-me para solucionar a maioria dos obstáculos que encontramos, contribuindo para o avanço contínuo do projeto.

Um dos resultados do meu trabalho com a equipe foi o desenvolvimento da capacidade de aprendizagem rápida. Ao adotarmos o processo Scrum, conseguimos entregar um MVP em apenas três semanas, demonstrando nossa habilidade em absorver conhecimento rapidamente e aplicá-lo de forma eficaz.

Em resumo, minha atuação como Product Owner na equipe foi marcada pela contribuição constante, comunicação eficiente com o cliente, transparência nas informações, cumprimento de prazos, habilidade em resolver problemas e capacidade de aprendizagem rápida. Estou satisfeito(a) com os resultados alcançados e acredito ter desempenhado um papel fundamental no sucesso do projeto.

Em resumo tive contribuições no desenvolvimento do front-end, e na criação da lógica do back-end.

### [API - 2º Semestre](https://github.com/MidNight-Tecnology/API-MidAll-2022.2)
<b>Problema: </b>Eu estou em busca de um sistema capaz de proporcionar o cadastro de usuários (funcionários) para minha empresa. Esse sistema deve viabilizar a gestão eficiente dos funcionários, abrangendo a criação, exclusão, edição e visualização de seus perfis. Além disso, é imprescindível que o sistema incorpore um mecanismo de "crawler" para acessar o endpoint do Diário Oficial da União. Por meio desse mecanismo, serão realizadas pesquisas diárias em busca de editais que mencionem meus funcionários. Posteriormente, os arquivos em formato PDF serão baixados, filtrados e armazenados de forma a permitir a visualização dessas informações. Dessa maneira, qualquer funcionário da minha empresa que possua algum registro no Diário Oficial será prontamente identificado e apresentado no sistema de gestão.

<b>Solução: </b> A partir da apresentação do desafio enfrentado pela empresa parceira, MidAll[B], a solução desenvolvida se configura em um Crawler com sistema de gerenciamento de associados, que compreende em um sistema que consiga buscar, ler o arquivo e distinguir o conteúdo referente aos Professores Associados, realizar os cruzamentos essenciais de acordo com as bases de dados de colaboradores que carregam está explicação, registrar todos os processos publicados relacionados aos associados, e emitir relatório diário para que a equipe do Backoffice consiga disparar os e-mails para os docentes citados no Diário Oficial.

Neste projeto, assumi o papel de Master e tive a oportunidade de desempenhar um papel fundamental. Foi desenvolvido um Crawler com um sistema sofisticado de gerenciamento de associados, visando realizar uma série de tarefas complexas e essenciais. O objetivo principal era buscar, ler e distinguir o conteúdo relacionado aos Professores Associados em diferentes fontes de dados, além de realizar cruzamentos relevantes com bases de colaboradores. Através desse processo, foi possível registrar todos os processos publicados envolvendo os associados, oferecendo uma visão abrangente das atividades. Além disso, o sistema emitia relatórios diários, permitindo que a equipe do Backoffice pudesse enviar e-mails aos docentes mencionados no Diário Oficial. Como Master, meu papel consistia em facilitar e promover a aplicação efetiva do framework Scrum no projeto. Trabalhei arduamente para garantir que a equipe compreendesse e seguisse os princípios e práticas do Scrum, além de remover obstáculos, facilitar a colaboração e promover melhorias contínuas ao longo do processo, além de ajudar no desenvolvimento.

<b>Tecnologias Utilizadas:</b>
- <img src="https://img.icons8.com/color/48/000000/javascript.png"/> JavaScript
- <img src="https://img.icons8.com/color/48/000000/css3.png"/> CSS
- <img src="https://img.icons8.com/color/48/000000/html-5.png"/> HTML
- <img src="https://img.icons8.com/officel/48/000000/react.png"/> React
- <img src="https://img.icons8.com/color/48/000000/typescript.png"/> TypeScript
- <img src="https://img.icons8.com/color/48/000000/python.png"/> Python


<b>Soft Skills: </b> Trabalho em Equipe, Comunicação, Transparencia, Responsábilidade, Resolução de problemas e Aprendizagem rápida.

<b>Minhas Contribuições: </b> Ajudei no desenvolvimento do front-end, na criação da lógica do back-end, na criação dos crawlers e alem disso fui Scrum Master.

### [API - 3º Semestre](https://github.com/orgs/CopiloTTeam/repositories)

Desenvolvemos um sistema abrangente que engloba funcionalidades como cadastro de clientes e gestão de títulos com parcelas, além de integração com a API dos correios para facilitar a inserção de dados de endereço. Com recursos avançados, como o processamento automático de parcelas em lote e fora do expediente, o sistema proporciona maior agilidade e eficiência no gerenciamento financeiro. A segmentação em diferentes tipos de usuários, como setores comercial, financeiro e administrativo, permite a criação e a gestão centralizada de títulos e parcelas, adaptando-se às necessidades específicas de cada área. Além disso, a máscara para moedas garante a formatação correta dos valores financeiros, conferindo maior precisão e clareza aos registros. O sistema também oferece a geração de relatórios detalhados, possibilitando a identificação de clientes adimplentes e inadimplentes, com opções de filtragem por data de crédito, pagamento ou vencimento. Com essa solução abrangente, nossos clientes podem aliviar suas preocupações e otimizar o desempenho de suas atividades empresariais.

Neste projeto, desempenhei o papel de Product Owner, atuando como um elo entre a equipe de desenvolvimento e o cliente. Garanti a priorização adequada dos requisitos e validei a conformidade do produto com as expectativas do cliente, buscando sua plena satisfação.

<b>Objetivo:</b> Construir uma aplicação para o gerenciamento de pagamentos de uma empresa. A aplicação Web deve conter um sistema de gerenciamento de funcionario, de cliente, e de pagamentos

<b>Hard Skills: </b> React, Typescript, JavaScript, Java, Node, MySQL e SpringBoot

<b>Soft Skills: </b> Trabalho em Equipe, Comunicação, Transparencia, Responsábilidade, Resolução de problemas e Aprendizagem rápida.

<b>Minhas Contribuições: </b> Como P.O fui responsável por ajudar no backlog e no planejamento das sprints, como desenvolvedor, ajudei com o desenvolvimento do front-end e do back-end.

## Experiência Profissional 💼

### Etec São José dos Campos - Aquarius - Estágio Voluntário (Agosto de 2021 - Dezembro de 2021)

Como um dos responsáveis pela manutenção e operação dos laboratórios de informática, tanto em termos de hardware quanto de software, tive um papel fundamental no seu pleno funcionamento. Contribuí ativamente para a manutenção do servidor, garantindo seu adequado desempenho. Além disso, desempenhei um papel importante na organização do ambiente, assegurando um espaço propício ao trabalho. Não menos relevante, auxiliei na manutenção e otimização da rede da Escola, garantindo seu funcionamento adequado e seguro.
### Performa Comunicação - Estágio em Desenvolvimento de Software Multiplataforma (Julho de 2022 - Fevereiro de 2023)

Desempenhei um papel ativo no desenvolvimento de aplicativos e sites, utilizando minhas habilidades técnicas para criar soluções inovadoras. Além disso, atuei na edição de vídeos, proporcionando uma experiência visual aprimorada. Participei igualmente de testes de software, garantindo a qualidade e a funcionalidade dos produtos desenvolvidos. Além disso, contribuí para a realização de clippings, auxiliando na criação de conteúdos relevantes e impactantes.

### Virtual Market - Estágio em Desenvolvimento de Software Multiplataforma (Março de 2023 - Até o presente momento)

Desempenho um papel fundamental no desenvolvimento de sites, aplicativos e scripts, utilizando uma ampla gama de tecnologias, incluindo PHP, JavaScript, TypeScript, React, Vue.js e AWS Lambda (Node.js). Tenho experiência trabalhando em conjunto com bancos de dados como MongoDB, DynamoDB e MySQL, garantindo a integração eficiente entre o front-end e o back-end. Meu trabalho abrange desde a criação de interfaces amigáveis até a implementação de lógica complexa e o gerenciamento eficiente de dados. Tenho habilidades versáteis para enfrentar os desafios do desenvolvimento web, entregando soluções robustas e de alta qualidade.

## Educação 🎓

### Técnico em Desenvolvimento de Sistemas - ETEC São José dos Campos (2021)


Durante o curso, tive a oportunidade de participar de projetos envolvendo áreas como robótica, hackathons e maratonas de programação, onde pude aplicar meus conhecimentos em programação e trabalhar em equipe para encontrar soluções criativas e inovadoras. Além disso, adquiri habilidades em sistemas embarcados, desenvolvimento de sistemas, banco de dados e design digital, o que me proporcionou uma visão abrangente e sólida do campo da tecnologia. Aprendi também sobre desenvolvimento web, adquirindo conhecimentos valiosos para criar interfaces intuitivas e funcionais. Essas experiências e aprendizados contribuíram para o meu crescimento profissional e me tornaram um desenvolvedor versátil e preparado para enfrentar desafios complexos.

### Superior em Desenvolvimento de Software Multiplataforma - FATEC São José dos Campos (2024)


Durante o curso, estou adquirindo conhecimentos sobre o método Scrum e sua aplicação prática no mundo real por meio do projeto API. Nesse projeto, tenho a oportunidade de trabalhar em parceria com empresas reais vinculadas à Fatec, buscando soluções para problemas reais de programação. Ao longo do curso, estou aprendendo também JavaScript, TypeScript, Java, React e bancos de dados relacionais e não relacionais. Além disso, estou explorando os conceitos de Design Digital, User Experience (UX) e User Interface (UI), aprimorando minhas habilidades na criação de interfaces atraentes e funcionais. Essas experiências e conhecimentos combinados estão me capacitando para enfrentar desafios reais no campo da tecnologia, preparando-me para uma carreira de sucesso como desenvolvedor.

## Contato 📞

- Email: [Guilhermedcdias.2023@gmail.com](mailto:guilhermedcdias.2022@gmail.com)
- LinkedIn: [Guilherme Duarte](https://www.linkedin.com/in/guilherme-duarte-cenzi-dias-9737621b6/)


