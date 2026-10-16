![Clayton Tavares Dan — IA, dados e infraestrutura conectados para resolver problemas reais.](assets/capa.svg)

## Tecnologia por dentro. Soluções na prática.

Sou **Clayton Tavares Dan**, também **ctdan**. Meu interesse por tecnologia vai além de usar uma ferramenta: gosto de entender como ela funciona, onde estão seus limites e como pode se conectar a outras peças para resolver um problema real. Entre infraestrutura, dados, automação e inteligência artificial, é nessa ligação entre sistemas que boa parte do meu trabalho acontece.

Transito entre a operação e a investigação técnica: administrar serviços, conectar APIs, organizar conhecimento e descobrir por que uma integração funciona em um cenário e falha em outro. O que me prende a atenção não é apenas colocar algo para rodar, mas entender suas dependências, verificar seu comportamento e conseguir mantê-lo depois.

**Meu GitHub é uma bancada aberta.** Aqui reúno projetos que exploro, forks que uso para estudar e adaptar ferramentas e experimentos que ajudam a transformar uma ideia em algo concreto. Nem tudo precisa nascer como um projeto próprio: muitas vezes, o caminho mais útil é aproveitar o que já existe, compreender o código e ajustar o ponto que não atende à necessidade.

Tenho interesse especial em **IA aplicada à operação**, **infraestrutura self-hosted**, **conhecimento pesquisável** e **automação de rotinas**. São áreas que se complementam: a infraestrutura sustenta os serviços, os dados fornecem contexto e as integrações permitem que ferramentas e agentes participem do trabalho de verdade.

[Explorar repositórios](https://github.com/claytontavaresdan?tab=repositories)

## O que conecto

![Infraestrutura, IA e agentes, dados e contexto, integrações. Diagnóstico, observabilidade e recuperação em todas as camadas.](assets/mapa.svg)

### 🖥️ Infraestrutura própria e serviços self-hosted

Trabalho com **Linux, Proxmox VE, Docker e Tailscale**, conectando virtualização, containers, redes privadas e serviços que precisam conversar entre si. Gosto do controle que o self-hosting oferece: entender onde os dados ficam, quais componentes sustentam uma aplicação e como investigar quando alguma parte deixa de responder como deveria.

Meu interesse não termina na instalação. Acesso remoto, observabilidade, persistência de dados, backups e recuperação fazem parte do mesmo problema. Uma aplicação disponível agora não significa uma operação recuperável depois; por isso, considero dependências, caminhos de acesso e possibilidades de reversão tão importantes quanto a configuração inicial.

Ferramentas como **MeshCentral** entram nesse contexto de acesso e administração remota. A ideia é reduzir a distância entre perceber um problema e ter contexto para investigá-lo — sem tratar cada serviço como uma ilha.

### 🧠 Inteligência artificial além da conversa

Exploro **LLMs, agentes, Hermes Agent, MCP e gateways de modelos** como partes de uma estrutura de trabalho, não apenas como interfaces de chat. Meu interesse está em conectar modelos a ferramentas e fontes de informação para apoiar investigação, consulta e execução de tarefas com limites claros.

Também me envolvo com o que acontece entre o cliente e o modelo: compatibilidade entre APIs, tradução de mensagens, streaming, chamadas de ferramentas, roteamento e comportamento de fallback. Uma resposta pode chegar com HTTP 200 e ainda assim estar vazia, incompleta ou incompatível com o que o cliente espera. Gosto de investigar esse comportamento real, em vez de confiar apenas no status da requisição.

Para mim, o valor de um agente está no conjunto: contexto adequado, ferramentas úteis, escopo de ação e uma forma de conferir o resultado. Automatizar uma resposta é diferente de concluir uma tarefa; essa diferença orienta o que procuro construir e testar.

### 🗄️ Dados que se transformam em contexto

Trabalho com **PostgreSQL, busca semântica e RAG** para aproximar informação acumulada dos problemas que precisam ser resolvidos. Documentação e históricos de atendimento carregam conhecimento que costuma ficar disperso: sintomas, tentativas anteriores, soluções e detalhes de ambiente que fazem diferença no diagnóstico.

Meu interesse é tornar esse material consultável e útil sem precisar recomeçar cada investigação do zero. Isso envolve mais do que armazenar textos ou gerar embeddings: é necessário preservar contexto, distinguir fontes e recuperar informações que tenham relação com a pergunta feita.

Vejo o RAG como apoio à investigação, não como garantia de verdade. Encontrar um caso parecido ajuda a formular uma hipótese; confirmar se ela vale para o ambiente atual continua exigindo evidência. A conexão entre memória operacional, busca e validação é uma das partes que mais me interessam nessa área.

### ⚙️ Automação e integração com propósito

Uso **Python, Bash e APIs** para conectar sistemas, reduzir tarefas repetitivas e criar rotinas que deixem resultados verificáveis. Prefiro começar pela necessidade: o que precisa acontecer, quais dados entram, o que pode falhar e como saber se a tarefa terminou corretamente.

Essa abordagem passa por sincronização de informações, consultas operacionais, coleta de evidências e integração entre ferramentas de suporte e infraestrutura. Também alcança problemas próximos da operação de loja, como suporte a **PDVs Linux**, comunicação entre componentes e investigação de serviços e periféricos.

Nem toda rotina precisa de um agente, e nem toda integração precisa virar uma aplicação nova. Quando um recurso nativo, uma consulta ou um script pequeno resolve com clareza, prefiro esse caminho. Automatizar deve reduzir esforço e pontos de falha — não criar uma segunda operação só para manter a primeira.

### 🔎 Diagnóstico, confiabilidade e continuidade

Gosto de investigar a diferença entre o que um sistema deveria fazer e o que ele está fazendo. Logs, respostas de APIs, comportamento do processo e testes reproduzíveis ajudam a separar sintoma de causa e a evitar mudanças feitas por tentativa.

Procuro olhar também para o que vem depois da correção: a alteração resolveu o cenário original? Afetou algum dependente? Existe um caminho de retorno? O aprendizado ficou registrado de forma útil? São perguntas que aproximam uma correção pontual de uma melhoria que pode ser mantida.

## Como abordo um problema

```text
                        PROBLEMA REAL
                              |
                    entender o contexto
                  ambiente / impacto / limites
                              |
                   investigar e reproduzir
                   logs / dados / evidencias
                              |
                   escolher o menor ajuste
                 recurso nativo / script / codigo
                              |
                     testar o resultado
                 caso original / efeitos / falhas
                              |
                   documentar o que fica
                 decisao / limites / recuperacao
                              |
                    observar e aprender
```

**Contexto antes da mudança.** Primeiro, entender o alvo, suas dependências e o impacto. Um sintoma parecido não significa a mesma causa, principalmente quando ambientes e versões são diferentes.

**Ajustes pequenos, resultados observáveis.** Prefiro corrigir o necessário e verificar o efeito a acumular mudanças que dificultem saber o que resolveu o problema. Um teste precisa observar o resultado da tarefa, não apenas a execução de um comando.

**Conhecimento que continua útil.** Registrar uma solução ajuda mais quando inclui o cenário, os limites e a forma de verificar. Assim, a próxima investigação parte de algo concreto, e não de uma lembrança vaga de que “isso já aconteceu”.

## O que procuro nas ferramentas

- **Controle e clareza:** saber o que está executando, onde os dados ficam e quais são as dependências.
- **Integração:** APIs e interfaces que permitam conectar ferramentas sem depender de trabalho manual para cada etapa.
- **Observabilidade:** distinguir tarefa concluída, falha, degradação e ausência de trabalho a fazer.
- **Manutenção simples:** menos peças desnecessárias e documentação suficiente para entender o que ficou.
- **Aplicação real:** tecnologia que ajude a investigar, operar ou resolver algo além da demonstração.

> Uma resposta HTTP 200 não encerra a investigação. O resultado precisa funcionar.

---

**Sobre os repositórios:** parte deste espaço é formada por forks usados para estudo, adaptação e experimentação. A autoria dos projetos pertence aos respectivos mantenedores; manter um fork não significa reivindicar sua criação. O perfil reúne meus interesses e minha forma de trabalhar, não um catálogo de produtos próprios.
