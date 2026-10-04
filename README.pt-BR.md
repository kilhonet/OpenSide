# OpenSide

**Um assistente de IA gratuito para Windows: escreva no chat o que você precisa e a IA faz no Chrome ou Edge que você já usa — da pesquisa aos cliques e à digitação.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/openside?lang=pt)

![Tela do OpenSide](images/openside-en.png)

> A interface do programa não tem tradução para português; ela é exibida em inglês. Os nomes de botões e opções abaixo aparecem como na tela.

## Visão geral

Muito trabalho na web exige muitos cliques e pouco raciocínio: juntar numa tabela os preços de várias lojas, preencher o mesmo formulário várias vezes, publicar num blog, procurar o e-mail certo na caixa de entrada.

O OpenSide permite entregar esse trabalho com uma linha de chat. Escreva a tarefa na caixa "What can I do for you?" e a IA abre os sites no seu navegador, lê as páginas, clica nos botões e digita o texto até concluir; depois conta o resultado em poucas frases. Os dados coletados podem chegar como arquivo do Excel.

Ele não usa um navegador separado — trabalha **no Chrome ou Edge que você já está usando**. Os sites em que você já está conectado não pedem novo login e, como a IA trabalha na própria aba, você pode continuar usando as outras abas enquanto isso. Vinculando o Telegram, você também pode passar tarefas e receber os resultados pelo celular quando estiver fora.

Para a IA, entre com uma conta do ChatGPT que você já tenha ou informe uma chave de API do Claude, da OpenAI ou do Gemini.

## Principais recursos

- **Tarefas web por chat** — descreva a tarefa; a IA pesquisa, clica, digita e navega entre páginas por você e depois informa o resultado.
- **Seu navegador, seus logins** — ele se conecta ao Chrome ou Edge que você usa, então os sites em que você está conectado funcionam na hora.
- **Trabalho repetitivo** — entregue de uma vez tarefas que se repetem, como preencher formulários ou coletar dados em muitas páginas.
- **Salvar no Excel** — os dados coletados chegam como arquivo do Excel (.xlsx), ou em CSV se você pedir.
- **Controle remoto pelo Telegram** — envie tarefas pelo Telegram no celular e receba respostas e arquivos. Não é preciso criar um bot.
- **Anexar arquivos** — anexe imagens, textos ou CSV para a IA ler, ou para ela enviar a um site.
- **Lembra o que você viu** — quando ativado, registra as páginas que você lê e os aplicativos que usa, e os aproveita em perguntas como "aquele artigo que li ontem".
- **Boa em sites populares** — publicar no Naver Blog, Tistory e Blogger, Gmail, Google Docs e Planilhas, Notion, Slack, YouTube, Naver Real Estate e outros são tratados com métodos próprios de cada site, mais rápidos e precisos.
- **Várias contas de IA** — cadastre o login do ChatGPT (Codex) e chaves de API do Claude, OpenAI e Gemini, e alterne entre elas direto no chat.
- **Modo escuro · 9 idiomas** — coreano, inglês, japonês, chinês, russo, italiano, francês, espanhol e árabe.

## Download / Instalação

| Edição | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/openside?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/openside?lang=pt&nosetup) |

O instalador abre o OpenSide assim que a instalação termina. Na edição portátil, descompacte o ZIP e execute `OpenSide.exe`. As duas edições têm os mesmos recursos; só muda o valor inicial de **Run at startup** — ativado no instalador e desativado na portátil.

## Como usar

### Primeiros passos

1. Execute o OpenSide. Na primeira vez, a página de configuração da conexão abre sozinha no seu navegador (Chrome ou Edge).
2. Nessa página, marque a caixa **Remote debugging**. Se a página não abriu, digite `chrome://inspect/#remote-debugging` (no Edge, `edge://inspect/#remote-debugging`) na barra de endereços do navegador.
3. Quando o navegador mostrar um pedido de conexão, clique em **Allow**. Essa configuração só precisa ser feita uma vez.
4. Em seguida, **Preferences** abre em **Account**. Clique em **Add**, escolha a IA que vai usar (por exemplo **Sign in to Codex**) e entre na página que abre no navegador. Quando aparecer "Sign-in complete", feche essa janela e volte ao OpenSide.
5. Escreva uma tarefa na caixa de chat ("What can I do for you?") e pressione **Enter**. Por exemplo: "Me diga os títulos dos 5 avisos mais recentes do kilho.net".
6. Enquanto a IA trabalha, o andamento aparece linha por linha. Ao terminar, o resultado aparece como resposta e o andamento se recolhe numa única linha "Ns of work", que você pode clicar para expandir de novo.

### Organização da tela

| Elemento | O que faz |
|---|---|
| Título do chat | O título da conversa atual. Vem da sua primeira mensagem; clique para editar (**Enter** salva · **Esc** cancela) |
| **Recent sessions** | Suas conversas anteriores (as 15 mais recentes). Escolha uma para continuar |
| **New chat** | Começa uma nova conversa |
| **Settings** | Abre a janela **Preferences** |
| Clipe (**Attach files**) | Anexa arquivos à mensagem. Eles aparecem abaixo da caixa de texto; remova um com × |
| Caixa de texto · **Send** | Escreva a tarefa e envie. Enquanto a IA trabalha, **Send** vira **Stop** |
| Ícone **Remote control** | Liga e desliga o controle remoto pelo Telegram. Fica verde quando ligado |
| Ícone de olho (**Context**) | Aparece só quando o registro de páginas está ligado. Clique para pausar ou retomar o registro |
| Anel de uso | Uso de uma conta **Sign in to Codex**. Passe o mouse para ver quanto resta |
| Conta · modelo · nível de raciocínio | Escolha a conta de IA, o modelo e o quanto ela pensa nesta conversa |

### O que fazer quando…

**Juntar informações de vários sites numa tabela**
Diga o que coletar e como quer receber, por exemplo "Procure o preço do notebook modelo A em três lojas e coloque no Excel". Ao terminar, aparece no chat um cartão **⬇ Download**. Clique para escolher onde salvar (a pasta Downloads, de início); depois, **Open file** e **Open folder** abrem na hora. O arquivo do Excel mantém intactos valores com zero à esquerda, como `007` ou números de telefone. Se precisar de um arquivo para outro programa, diga "em CSV" — ele é gravado para que caracteres acentuados apareçam corretamente.

**Preencher o mesmo formulário várias vezes**
Diga algo como "Envie uma inscrição para cada pessoa desta lista". A IA preenche de uma vez os campos, caixas de seleção e listas suspensas, e confere se o resultado apareceu antes de seguir, então nunca clica duas vezes num botão de envio. Se a lista estiver num arquivo, anexe o arquivo.

**Quando você só quer que ela olhe, e quando quer que conclua**
Se você disser "compare" ou "só escreva um rascunho", a IA não faz nada que não possa ser desfeito, como enviar, pagar, excluir ou publicar. Se disser "envie" ou "faça o pedido", ela leva a tarefa até o último botão sem perguntar de novo. É bom deixar claro na mensagem até onde ela deve ir.

**Publicar num blog**
Diga algo como "Escreva isto como post no Naver Blog e publique". No Naver Blog, Tistory e Blogger, título, corpo, subtítulos, imagens e tags entram com métodos adequados a cada site. Anexe as imagens que quiser incluir.

**Trabalhar com e-mail, documentos e ferramentas de trabalho**
Diga coisas como "Ache no Gmail o e-mail de orçamento da semana passada e resuma", "Leia os valores da coluna B da minha planilha do Google", "Adicione as anotações de hoje à página de atas no Notion" ou "Me diga as últimas mensagens do canal #avisos no Slack". Ele trabalha com as contas já conectadas no seu navegador. Se houver várias contas do Google conectadas, diga qual e ele trabalha nessa conta.

**Pesquisar no YouTube, X e LinkedIn**
Diga coisas como "Resuma a transcrição deste vídeo do YouTube", "Resuma as reações nos comentários deste vídeo", "Junte posts recentes sobre este assunto no X" ou "Ache as vagas desta empresa no LinkedIn".

**Juntar anúncios de imóveis**
Diga algo como "Coloque no Excel os anúncios de jeonse do apartamento ○○ no Naver Real Estate" e ele transforma os anúncios numa tabela.

**Encontrar imagens**
Diga algo como "Ache 10 fotos de ○○ e junte os endereços" e ele coleta as URLs das imagens nos resultados de busca.

**Usar outras abas enquanto ela trabalha**
A IA só se mexe na aba em que está trabalhando, então você pode continuar seu trabalho em outras abas do mesmo navegador. A aba dela continua funcionando mesmo em segundo plano, como se estivesse na frente. Se você passar a próxima tarefa na mesma conversa, ela continua na aba em que estava, mesmo que você esteja olhando outra. Uma conversa nova começa na aba que você está vendo.

**As abas que ela abre e as suas**
A IA só abre uma aba nova quando precisa de duas páginas ao mesmo tempo, e fecha as abas que abriu antes de responder. Ela não fecha as abas que você abriu. Se quiser organizar suas abas, peça diretamente, por exemplo "Feche todas as abas do kilho.net".

**Quando é preciso um código de verificação ou a aprovação no app do banco**
Quando uma etapa precisa de uma pessoa — um código enviado ao celular, a aprovação no app do banco, um CAPTCHA de texto —, a IA traz essa aba para a frente e diz numa linha o que fazer. Faça no navegador ou digite o código na caixa de chat, e a IA continua. A IA marca sozinha as caixas "Não sou um robô" e só passa para você quando aparece um desafio de escolher imagens. Se um cadastro precisar de um link ou código enviado por e-mail e o Gmail estiver conectado no navegador, a IA abre a caixa de entrada e encontra.

**Acrescentar algo enquanto ela trabalha**
Você pode escrever na caixa de chat mesmo enquanto a IA trabalha. Sua mensagem vai direto para a tarefa em andamento. Use para mudar a direção ("escreva os preços em wons") ou para responder algo que ela perguntou. Para fazê-la parar, clique em **Stop**.

**Fazer ela ler arquivos do seu PC ou enviá-los a um site**
Anexe arquivos com o clipe e envie, e a IA os lê. Ela vê o conteúdo das imagens (png, jpg, gif, webp) e lê e usa os arquivos de texto e CSV. Dá para anexar vários de uma vez, e os arquivos originais nunca são alterados. Diga algo como "Anexe a foto que enviei a um post neste fórum" e a IA cuida também da janela de envio de arquivos do site.

**Fazer ela sempre ler uma pasta definida**
Se anexar toda vez é trabalhoso, adicione a pasta em **Preferences** → **Files** → **Folders the AI may read** (**Add folder...**). Aí você pode dizer coisas como "Com a lista de clientes da minha pasta de dados, …". A IA só lê essa pasta e nunca grava nela. Adicione só as pastas necessárias.

**Encontrar uma página vista antes**
Ative **Record pages I read and apps I use** em **Preferences** → **Context**, e o OpenSide registra o texto das páginas que você lê e as janelas dos aplicativos que você usa. Aí você pode dizer coisas como "Resuma de novo o artigo de investimentos que li ontem" ou "Compare os prós e contras dos hotéis que vi há pouco". Os registros ficam 30 dias, e páginas com campo de senha não são registradas. Escreva os sites e aplicativos que não devem ser registrados separados por vírgula (ex.: `bank.com, kakaotalk.exe`). Para pausar o registro, clique no ícone de olho na tela do chat; para apagar tudo, clique em **Delete all**. Esse recurso começa desativado.

**Encontrar um site visitado antes**
Diga algo como "Abra aquele site da floricultura que visitei da última vez" e ele procura no histórico do navegador e abre.

**Passar tarefas pelo celular (Telegram)**
1. Em **Preferences** → **Remote**, clique em **Link now**. Aparecem um QR code e um código de vínculo, válidos por 10 minutos.
2. Aponte a câmera do celular para o QR. Quando o Telegram abrir, toque em **Iniciar**. Se o Telegram estiver instalado no PC, você também pode clicar em **Open on this PC**.
3. Quando o Telegram mostrar uma mensagem dizendo que está conectado, pronto. Agora envie uma tarefa como mensagem de texto no Telegram, e o OpenSide no seu PC faz e manda a resposta.

Os arquivos gerados e pedidos como "digite o código de verificação" também chegam ao celular. Responda com o código no Telegram e ele vai para a tarefa em andamento. Se a resposta for longa, o começo chega como mensagem e o texto completo como arquivo. O Telegram só aceita texto, então mande palavras em vez de fotos. O OpenSide precisa estar aberto no PC para trabalhar, então vale ativar **Run at startup** quando usar o controle remoto. Para desligar o controle remoto por um tempo, clique no ícone **Remote control** na tela do chat; para desconectar de vez, clique em **Unlink**.

**Usar várias contas de IA**
Em **Preferences** → **Account**, clique em **Add** para ver os tipos disponíveis.

| Tipo | Como funciona |
|---|---|
| **Sign in to Codex** | Entra com uma conta do ChatGPT |
| **Claude API key...** · **Gemini API key...** | Informe uma chave de API |
| **OpenAI API key...** | Informe uma chave de API e uma **Base URL (.../v1)**. Mudando o endereço, dá para usar outros serviços que funcionam do mesmo jeito que a OpenAI |

Ao salvar uma conta com chave de API, ele busca na hora a lista de modelos para conferir. Escolha a conta das conversas novas com **Set default** e dê um clique duplo numa conta para renomeá-la. Durante uma conversa, você pode trocar a conta, o modelo e o nível de raciocínio direto na parte de baixo da tela do chat. Um nível de raciocínio mais alto pensa mais a fundo; um mais baixo responde mais rápido.

**Ver quanto uso resta**
Com uma conta **Sign in to Codex**, aparece um anel de uso na parte de baixo da tela do chat. Ele enche conforme você usa; passe o mouse para ver o que resta em cada período. Quando estiver quase no fim, troque para outra conta.

**Continuar uma conversa anterior**
Clique em **Recent sessions** para ver suas 15 últimas conversas com quando foram usadas. Escolha uma e continue. Para dar um título mais claro, clique no título no topo.

**O que ela lembra sozinha**
Cada vez que termina uma tarefa, a IA guarda o que foi confirmado — como usar um site, fatos que você contou — e usa nas conversas seguintes. Quanto mais tarefas você passa no mesmo site, menos ela se atrapalha.

**Manter aberto depois de fechar a janela**
Clicar no × da janela não encerra o programa; o OpenSide vai para a área de notificação (bandeja). Clique no ícone da bandeja para trazer a janela de volta. Para sair de vez, clique com o botão direito no ícone e escolha **Quit**. **Run at boot** nesse mesmo menu é a mesma opção que **Run at startup** em **Preferences**; ligada, o OpenSide inicia discretamente na bandeja quando o Windows inicia. Só uma cópia do OpenSide roda por vez; abri-lo de novo traz para a frente a janela já aberta.

**Manter a janela do OpenSide na frente**
Para deixar o OpenSide ao lado do navegador enquanto acompanha, coloque **Always on top** em **On** em **Preferences** → **General**. A posição e o tamanho da janela são lembrados, então ela abre no mesmo lugar da próxima vez.

**Chrome ou Edge — em qual ela trabalha**
O OpenSide trabalha no navegador em que **Remote debugging** está ativado. Se os dois estiverem ativados, ele usa primeiro o navegador padrão do Windows. Para trabalhar no outro, ative só naquele navegador.

**Depois de reiniciar o navegador**
Se for preciso conectar, o OpenSide mostra a janela **A browser connection is needed** com os passos em ordem. Siga-os e clique em **Connect**. Clicar no endereço dessa janela copia o endereço, então é só colar na barra de endereços.

## Configuração

Clique em **Settings** para abrir a janela **Preferences**. As mudanças valem na hora.

| Aba | Opções |
|---|---|
| **General** | **Always on top** · **Theme** (Auto · Light · Dark) · **Language** (Auto ou um dos 9 idiomas) · **Run at startup** |
| **Account** | Adicionar, excluir e entrar em contas de IA · escolher a conta padrão |
| **Remote** | Vincular ou desvincular o Telegram |
| **Context** | Ligar o registro de páginas e aplicativos · pausar · sites e aplicativos que não são registrados · apagar tudo |
| **Files** | Pastas que a IA pode ler |

Com **Language** em **Auto**, o OpenSide segue o idioma de exibição do Windows; como o português não está entre os idiomas do programa, a tela aparece em inglês. Escolhendo árabe, a tela passa a ser lida da direita para a esquerda. O andamento e as respostas da IA seguem o idioma da sua mensagem. Com **Theme** em **Auto**, ele segue o modo de aplicativo do Windows (claro ou escuro).

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Google Chrome ou Microsoft Edge
- Uma conta do ChatGPT, ou uma chave de API do Claude, OpenAI ou Gemini
- Conexão com a internet

## Atualizações

Por segurança e para evitar falsos positivos de antivírus, o OpenSide **não** se atualiza sozinho. Ao iniciar, ele verifica se há uma versão nova e avisa; se você optar por baixá-la, ele abre a página de download e fecha o programa. As versões novas são publicadas manualmente após verificação interna e anunciadas na [página do OpenSide](https://kilho.net/openside). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

## Licença

O OpenSide é **freeware**. Use onde quiser — no escritório, em casa, em órgãos públicos ou na escola — de graça e sem restrições, e redistribua livremente. O custo de uso da IA segue o plano da sua própria conta de IA ou chave de API.

## Links

- Site: <https://kilho.net/openside>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
