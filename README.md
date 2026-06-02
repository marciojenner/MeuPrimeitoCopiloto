# 🚀 Modos do Copiloto (Ask, Edit, Plan, Agent e Study)


## 🛠️ ASK -Pergunte
O modo Ask é para fazer perguntas e entender coisas, sem alterar seu código . Você pode perguntar sobre um arquivo -específico, um erro, uma função, um stack trace ou até conceitos gerais.

O Copiloto lê o contexto do projeto (arquivos abertos, seleção, etc.) e responde como um “mentor técnico” , explicando o que -está acontecendo e por quê. Ele não modifica nada — só analisa e explica.

 **Sugestão:** [prompts/prompt-ask.md](prompts/prompt-ask.md)


## 🛠️ Plan - Plano
Quando você pede algo mais complexo, o Copiloto pode entrar em um modo de planejamento , onde ele pensa e descreve os passos antes de sair da codificação .

Ele:

- divida o problema em etapas
- explica o que vai fazer
- só depois executa

 **Sugestão:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

 ## 🛠️ Agent - Agente
O Agente é o modo mais “autônomo”. Ele pode navegar pelo projeto , criar arquivos , modificar múltiplos pontos e manter o contexto entre passos , como se fosse um dev júnior trabalhando com você.
Você dá um objetivo (ex.: “implementar login com JWT”) e ele decide o que precisa ser feito em vários arquivos para chegar lá.

 **Sugestão:** [prompts/prompt-agent.md](prompts/prompt-agent.md)


