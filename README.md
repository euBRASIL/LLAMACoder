<a href="https://www.llamacoder.io">
  <img alt="Llama Coder" src="./public/og-image.png">
  <h1 align="center">Llama Coder</h1>
</a>

<p align="center">
  Claude Artifacts de código aberto – gere pequenos aplicativos com um único prompt. Desenvolvido por Llama 3 405B e Together.ai.
</p>

## Pilha de tecnologia

- [Llama 3.1 405B](https://ai.meta.com/blog/meta-llama-3-1/) from Meta for the LLM
- [Together AI](https://dub.sh/together-ai/?utm_source=example-app&utm_medium=llamacoder&utm_campaign=llamacoder-app-signup) for LLM inference
- [Sandpack](https://sandpack.codesandbox.io/) for the code sandbox
- Next.js app roteador com Tailwind
- Helicone para observabilidade
- Plausível para análise de sites

## Clonagem e execução

1. Clonar o repositório: `git clone https://github.com/Nutlope/llamacoder`
2. Crie um arquivo `.env` e adicione seu [Together AI API key](https://dub.sh/together-ai/?utm_source=example-app&utm_medium=llamacoder&utm_campaign=llamacoder-app-signup): `TOGETHER_API_KEY=`
3. Run `npm install` and `npm run dev` para instalar dependências e executar localmente

## Tarefas futuras

- [ ] Experimente um reescritor de prompts e execute-o também
- [ ] Melhore a abertura do toast como um modal para compartilhamento
- [ ] Adicione compartilhamento para que as pessoas possam pegar seus aplicativos e compartilhá-los publicamente
- [ ] Adicione a capacidade de ativar e desativar componentes do Shadcn e outros
- [ ] Lance suporte para diferentes temas – de alguma forma, passe variáveis ​​para os componentes
- [ ] Adicione imagens originais dinâmicas para as gerações específicas e inclua o prompt
- [ ] Adicione mais imagens originais dinâmicas para o Playwright
- [ ] Aborde o problema da capacidade de publicar o mesmo aplicativo repetidamente
- [ ] Tente o raciocínio em cadeia para ver se funciona melhor no geral
- [ ] Incentive as melhores práticas criando a área de entrada e texto e tendo pílulas para gerar aplicativos com bons prompts
- [ ] Adicione mais personalização em termos de alteração do prompt, temperatura, etc...
- [ ] Salve versões anteriores para que as pessoas possam alternar entre as versões geradas
- [ ] Seria legal mostrar um "destaque" aplicativos" no site em /featured. Tenha uma rota dinâmica /id/${prompt} que possa exibir vários aplicativos de exemplo interessantes no sandbox, prontos para uso
- [ ] Suporte a mais linguagens, começando com Python; confira o E2B
- [ ] Tente o raciocínio em cadeia para ver se funciona melhor no geral
- [ ] Tente ajustar um modelo menor com bons prompts do 405b ou GPT-4/Claude
- [ ] Adicione o modo escuro ao site como um todo, uma bela mudança de design
- [ ] Exiba melhor os erros no codesandbox para o usuário, para que as pessoas saibam o que está errado
- [ ] Pense em como fazer o 405B se corrigir sozinho (às vezes, ele cria importações)
- [ ] Nova rota para updateCode que envia apenas o código gerado mais recentemente + a solicitação de modificação
- [ ] Corrija o bug em que, se um usuário edita o código e faz uma alteração, ele não usa o código editado
- [ ] Adicione limitação de taxa com o Redis upstash se o tráfego ficar muito alto
- [ ] Tente adicionar uma biblioteca de componentes consistente como shadcn
- [ ] Aplicar diferenças de código diretamente em vez de pedir ao modelo para gerar o código do zero
- [ ] Adicionar a capacidade de enviar coisas como uma captura de tela para começar a partir daí
