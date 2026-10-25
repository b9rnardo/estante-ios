<p align="center">
  <img src="images/icon.png" width="112" alt="">
</p>

<h1 align="center">Estante para iPhone e iPad</h1>

<p align="center">
  Leitor de EPUB e PDF que busca livros em acervos abertos, guarda tudo no aparelho
  e lembra onde você parou. Com destaques, notas e dicionário.
</p>

<table>
  <tr>
    <td align="center"><img src="images/iphone-estante.webp" width="240" alt="A estante, com o livro em andamento no topo e as capas"><br>Estante</td>
    <td align="center"><img src="images/iphone-leitor.webp" width="240" alt="O leitor com Dom Casmurro aberto e trechos destacados"><br>Leitor</td>
    <td align="center"><img src="images/iphone-busca.webp" width="240" alt="Resultados da busca por Machado de Assis"><br>Busca</td>
  </tr>
</table>

Este repositório distribui a Estante pelo **SideStore** e pelo **AltStore**, que
instalam apps fora da App Store com o seu próprio Apple ID. Não há conta, anúncio
nem nuvem: busca, downloads, estante e leitor ficam no aparelho.

## Sumário

- [O que ela faz](#o-que-ela-faz)
- [Antes de começar](#antes-de-começar)
- [Instalar com o SideStore (recomendado)](#instalar-com-o-sidestore-recomendado)
- [Instalar com o AltStore](#instalar-com-o-altstore)
- [Instalar direto pelo arquivo .ipa](#instalar-direto-pelo-arquivo-ipa)
- [Renovar a cada 7 dias](#renovar-a-cada-7-dias)
- [Usar a Estante](#usar-a-estante)
- [Seus livros no app Arquivos](#seus-livros-no-app-arquivos)
- [Adicionar catálogos e fontes](#adicionar-catálogos-e-fontes)
- [Problemas comuns](#problemas-comuns)
- [Segurança e privacidade](#segurança-e-privacidade)

## O que ela faz

- **Busca em acervos abertos**: Project Gutenberg, Standard Ebooks, Internet
  Archive, arXiv, Archive of Our Own e Syosetu, numa busca só.
- **Catálogos OPDS**: Calibre, Calibre-Web, Kavita, Komga, COPS e outros, inclusive
  no seu computador, pela rede de casa.
- **Leitor de EPUB e PDF** com tema claro, sépia ou escuro, tamanho e fonte do
  texto.
- **Destaques em quatro cores, notas e marcadores**, exportáveis em Markdown.
- **Dicionário** do Wikcionário: selecione uma palavra e veja a definição.
- **Busca no livro**, que ignora acentos e mostra o trecho de cada resultado.
- **Estante organizada**: progresso de leitura, filtros (Lendo, Não começados,
  Lidos), coleções e importação dos seus próprios EPUBs e PDFs.

## Antes de começar

Você vai precisar de:

- um **iPhone ou iPad com iOS 15** ou mais recente;
- um **computador** (Mac, Windows ou Linux) e um cabo, **só para a primeira
  instalação**;
- um **Apple ID**. Pode ser gratuito. O mais recomendado é criar um **Apple ID
  secundário só para isso**, separado da sua conta principal (iCloud, compras,
  fotos).

Com um Apple ID gratuito, a Apple impõe três limites, para qualquer app instalado
assim:

- a assinatura vale **7 dias** e precisa ser renovada (veja
  [Renovar a cada 7 dias](#renovar-a-cada-7-dias));
- no máximo **3 apps** ao mesmo tempo, e o SideStore ou o AltStore conta como um;
- no máximo **10 apps diferentes instalados por semana** (renovar não conta).

## Instalar com o SideStore (recomendado)

Com o SideStore, o computador só entra na primeira vez. Depois o próprio iPhone
instala, atualiza e renova os apps.

### 1. Instale o SideStore pelo computador

1. Baixe o **iloader**, só pelo site oficial [iloader.app](https://iloader.app) ou
   pelo [GitHub do projeto](https://github.com/nab138/iloader).
2. Conecte o iPhone ao computador pelo cabo, desbloqueie a tela e toque em
   **Confiar** quando o iPhone perguntar. Digite o código do iPhone.
3. Abra o iloader, entre com o Apple ID e escolha instalar o **SideStore** no
   aparelho.
4. Espere terminar. O iloader instala o SideStore e já coloca nele o **arquivo de
   pareamento**, que permite ao SideStore instalar apps sem o computador.

### 2. Prepare o iPhone

1. **Ative o Modo de Desenvolvedor** (iOS 16 ou mais recente): **Ajustes ›
   Privacidade e Segurança › Modo de Desenvolvedor**. O iPhone reinicia; depois,
   toque em **Ativar**.
2. **Confie no seu Apple ID**: **Ajustes › Geral › VPN e Gerenciamento de
   Dispositivos**, toque no seu e-mail em **App do Desenvolvedor** e depois em
   **Confiar**. Sem isso, o SideStore mostra "Desenvolvedor Não Confiável" e não
   abre.
3. **Instale o LocalDevVPN**, gratuito na App Store. Abra e toque para conectar. Ele
   cria uma conexão interna no próprio iPhone, que o SideStore usa para instalar e
   renovar apps. Sua internet não passa por ele.

### 3. Entre no SideStore

1. Com o iPhone no **Wi-Fi** e o **LocalDevVPN conectado**, abra o SideStore.
2. Na aba **Settings**, toque em **Sign in with Apple ID** e entre com **o mesmo
   Apple ID que você usou no iloader**.
3. Se a conta tiver verificação em duas etapas, use o código que aparece num aparelho
   Apple seu. Se o único aparelho for esse iPhone, o código aparece nele mesmo:
   anote, feche o aviso e digite no SideStore.

O SideStore não tem tradução para português, então os nomes aparecem em inglês.

#### Se o login falhar com o erro -80045

Em outubro de 2026, uma mudança no login da Apple passou a dar esse erro para muita
gente, e o SideStore ainda não lançou uma correção oficial. O contorno abaixo tem
funcionado. Tudo fica na aba **Settings**; role a lista até encontrar cada item.

1. Toque em **User Customizations** e desligue **On-Device Anisette**. Confirme
   quando o SideStore pedir para reiniciar.
2. Abra o SideStore de novo, toque em **Anisette Servers** e escolha **SideStore
   (New)**. No fim dessa tela, desligue a **auto rotation**.
3. Volte em **User Customizations** e toque em **Reset adi.pb**. **Desmarque** a
   opção de manter os headers ("keep headers") e confirme em **Reset & Sign Out**.
4. Feche o SideStore de vez (deslize o app para cima na troca de apps) e abra de
   novo.
5. Faça login. Pode demorar um pouco. **Não peça o código por SMS**: esse envio tem
   falhado com "Could not connect to iCloud". Use o código de um aparelho Apple.

Se ainda falhar, troque o servidor do passo 2 por **jkcoxson** e tente de novo.
Algumas contas continuam recusadas mesmo assim; nesse caso, instale a Estante
[direto pelo arquivo .ipa](#instalar-direto-pelo-arquivo-ipa), com o iloader.

Acompanhe a correção em [SideStore#1675](https://github.com/SideStore/SideStore/issues/1675)
e [SideStore#1658](https://github.com/SideStore/SideStore/issues/1658).

### 4. Adicione a source da Estante e instale

1. No SideStore, abra a aba **Sources** e toque em **+**.
2. Cole o endereço:

   ```
   https://github.com/b9rnardo/estante-ios/releases/latest/download/source.json
   ```

3. Abra a aba **Browse**, toque na **Estante** e instale.
4. A Estante aparece na tela de início. Versões novas chegam como atualização no
   SideStore.

Depois de instalar, o LocalDevVPN pode ser desligado: ele só é necessário para
instalar, atualizar e renovar.

## Instalar com o AltStore

O AltStore faz o mesmo, mas a renovação depende do **AltServer**, um programa que
fica aberto no computador.

1. Baixe o AltServer em [altstore.io](https://altstore.io) e abra. No Windows,
   instale antes o **iTunes** e o **iCloud** baixados do site da Apple (as versões da
   Microsoft Store não servem).
2. Conecte o iPhone pelo cabo e toque em **Confiar**. No Mac, selecione o iPhone no
   Finder e ative **Mostrar este iPhone quando estiver no Wi-Fi**: é isso que permite
   renovar sem cabo depois.
3. No ícone do AltServer (barra de menus no Mac, bandeja no Windows), escolha
   **Install AltStore**, depois o seu aparelho, e entre com o seu Apple ID.
4. No iPhone, ative o **Modo de Desenvolvedor** e confie no seu Apple ID, como nos
   passos [do SideStore](#2-prepare-o-iphone).
5. No AltStore, abra **Sources**, toque em **+**, cole o mesmo endereço da source e
   instale a Estante em **Browse**.

O AltStore renova sozinho quando o iPhone está no mesmo Wi-Fi que o computador, com
o computador ligado e o AltServer aberto. Sources não funcionam no AltStore PAL (o
da União Europeia), que só aceita apps autenticados pela Apple.

## Instalar direto pelo arquivo .ipa

Sem SideStore nem AltStore: o iloader instala o arquivo direto no aparelho.

1. Baixe o `Estante-<versão>.ipa` em [Releases](https://github.com/b9rnardo/estante-ios/releases).
2. Conecte o iPhone ao computador, abra o iloader e escolha **Importar IPA**.
3. Selecione o arquivo e espere terminar. Prepare o iPhone como
   [no passo 2](#2-prepare-o-iphone) (o LocalDevVPN não é necessário aqui).

O jeito é mais simples, mas nada renova sozinho: a cada 7 dias, conecte o iPhone e
instale o `.ipa` de novo, por cima. Versões novas também são instaladas assim. Não
instale a Estante pelos dois caminhos: o SideStore só renova os apps que ele mesmo
instalou.

Quem já tem SideStore ou AltStore também pode instalar o `.ipa` em **My Apps › +**.

## Renovar a cada 7 dias

Com um Apple ID gratuito, a Estante para de abrir quando a assinatura vence. **Os
livros e as notas continuam no aparelho**: renovando, ela volta como estava. Só não
apague o app antes de renovar, senão os dados vão junto.

**No SideStore:**

1. Ligue o **LocalDevVPN**, com o iPhone no Wi-Fi.
2. Abra o SideStore e toque em **My Apps › Refresh All**. Isso renova a Estante e o
   próprio SideStore.
3. Depois disso, pode desligar a VPN.

Em **My Apps** aparece quantos dias faltam para cada app vencer. Para não precisar
lembrar, deixe o LocalDevVPN ligado e ative **Background Refresh** em **Settings**:
o SideStore renova sozinho quando o iPhone está no Wi-Fi.

**No AltStore:** deixe o computador ligado, com o AltServer aberto e no mesmo Wi-Fi,
ou abra o AltStore e toque em **My Apps › Refresh All**.

**Pelo iloader:** instale o `.ipa` de novo, por cima.

## Usar a Estante

<table>
  <tr>
    <td align="center"><img src="images/iphone-selecao.webp" width="240" alt="Uma palavra selecionada e a barra com cores, nota, dicionário, copiar e buscar"><br>Selecionar texto</td>
    <td align="center"><img src="images/iphone-dicionario.webp" width="240" alt="Cartão do dicionário com a definição de mascate"><br>Dicionário</td>
    <td align="center"><img src="images/iphone-notas.webp" width="240" alt="Painel de notas com quatro destaques"><br>Notas</td>
  </tr>
</table>

**Buscar e baixar.** Digite no campo do topo da estante. A busca **Todas** consulta
os acervos ao mesmo tempo e agrupa os resultados; os botões abaixo do campo mostram
um acervo só. Toque em **EPUB** ou **PDF** para baixar para a estante. Livros que já
estão nela mostram **Ler**.

**Importar seus arquivos.** Toque em **+** na estante e escolha EPUBs ou PDFs no app
Arquivos.

**Ler.**

- Deslize para os lados (ou toque nas bordas) para virar a página.
- Toque no meio do texto para mostrar ou esconder as barras.
- A barra de baixo mostra o progresso e pula para qualquer ponto do livro.
- **Aa** muda o tema (claro, sépia, escuro), o tamanho e a fonte do texto. No PDF,
  muda o zoom e, para um livro com letras difíceis de ler, a fonte: **Serifada** ou
  **Sem serifa** redesenham o texto no mesmo lugar, só naquele livro.
- O ícone de lista abre o **Sumário** e as abas **Marcadores** e **Notas**.
- A lupa busca no livro inteiro.

**Destacar e anotar.** Toque e segure numa palavra e ajuste a seleção. A barra da
Estante aparece no pé da tela: escolha uma das quatro cores, escreva uma nota, abra
o dicionário, copie ou busque o trecho no livro. Toque num destaque para trocar a
cor, editar a nota ou apagar. Em **Notas**, **Exportar** abre o menu de compartilhar
(Salvar em Arquivos, AirDrop, Notas…).

**Organizar.** Filtre por **Lendo**, **Não começados** e **Lidos**, ordene por
leitura recente, título, autor ou progresso e crie coleções em **+ Nova coleção**.
O **⋯** sobre cada capa marca como lido, muda as coleções, edita título, autores e
capa ou remove o livro.

**No iPad**, a estante mostra mais capas por linha e o leitor usa a tela inteira:

<table>
  <tr>
    <td align="center"><img src="images/ipad-estante.webp" width="260" alt="A estante no iPad"><br>Estante</td>
    <td align="center"><img src="images/ipad-leitor.webp" width="260" alt="O leitor no iPad com destaques em quatro cores"><br>Leitor</td>
    <td align="center"><img src="images/ipad-escuro.webp" width="260" alt="O leitor no iPad no tema escuro, com o painel de aparência aberto"><br>Tema escuro</td>
  </tr>
</table>

A Estante segue o modo claro ou escuro do aparelho. O tema do leitor é escolhido à
parte, em **Aa**.

## Seus livros no app Arquivos

A estante fica no app **Arquivos**, em **No Meu iPhone › Estante › data** (no iPad,
**No Meu iPad**):

- `library.json`: os livros, o progresso, os marcadores, os destaques e as notas;
- `books/`: os arquivos EPUB e PDF;
- `covers/`: as capas;
- `settings.json`: os catálogos OPDS e as coleções.

**Backup.** Copie a pasta `data` para o iCloud Drive, ou para o computador com o
aparelho conectado: no Mac, pelo Finder (selecione o aparelho, aba **Arquivos**); no
Windows, pelo app Dispositivos Apple ou pelo iTunes, em compartilhamento de arquivos.

**Levar a estante de outro aparelho.** Feche a Estante, copie o conteúdo da pasta
`data` do outro aparelho para essa pasta e abra de novo. A cópia substitui a estante
atual. As fontes ligadas e as preferências do leitor são escolhidas de novo.

Apagar o app apaga essa pasta junto. Faça uma cópia antes.

## Adicionar catálogos e fontes

<table>
  <tr>
    <td align="center"><img src="images/iphone-fontes.webp" width="240" alt="Lista de acervos na janela Fontes"><br>Fontes</td>
    <td align="center"><img src="images/iphone-adicionar-fonte.webp" width="240" alt="Campos para adicionar um catálogo OPDS ou uma fonte por link ou arquivo"><br>Adicionar</td>
    <td align="center"><img src="images/iphone-estante-escuro.webp" width="240" alt="A estante em modo escuro"><br>Modo escuro</td>
  </tr>
</table>

Toque no ícone de **Fontes**, no canto superior direito da estante.

- **Escolha os acervos** que entram na busca **Todas**.
- **Adicionar catálogo OPDS**: dê um nome e cole o endereço do catálogo (Calibre,
  Calibre-Web, Kavita, Komga, COPS…). Para catálogo com senha, use
  `https://usuário:senha@endereço/opds`. Na primeira vez que a Estante acessar um
  catálogo na sua rede de casa, o iOS pede permissão para a **rede local**: toque em
  **Permitir**.
- **Adicionar fonte**: uma fonte que não vem com a Estante, num arquivo `.js`. Cole
  um link para o arquivo ou toque em **Importar arquivo…** e escolha-o no app
  Arquivos. A fonte roda isolada: só busca na internet e devolve resultados, sem
  acesso à estante, às notas ou às preferências. A lixeira ao lado dela a remove.
  Adicione só fontes em que você confia.

## Problemas comuns

**"Desenvolvedor Não Confiável" ao abrir o SideStore ou a Estante.** Vá em **Ajustes
› Geral › VPN e Gerenciamento de Dispositivos**, toque no seu e-mail e em
**Confiar**. Se aparecer **Verificar App**, toque nele com o iPhone na internet. Se o
seu e-mail não estiver lá, a instalação não terminou: instale de novo pelo iloader.

**"Modo de Desenvolvedor necessário".** Ative em **Ajustes › Privacidade e Segurança
› Modo de Desenvolvedor**, deixe o iPhone reiniciar e toque em **Ativar**.

**O SideStore não entra no Apple ID ("failed to sign in").**

- Confira o Wi-Fi e se **Ajustes › Geral › Data e Hora › Automaticamente** está
  ligado: um horário errado faz a Apple recusar o login.
- Use a senha normal do Apple ID, não uma senha de app.
- Num Apple ID novo, entre uma vez em [appleid.apple.com](https://appleid.apple.com)
  e em [developer.apple.com](https://developer.apple.com) pelo Safari e aceite os
  termos que aparecerem.
- Com o erro **-80045**, siga [o contorno acima](#se-o-login-falhar-com-o-erro--80045).

**Erro de pairing no SideStore.**

1. Abra o **LocalDevVPN** e veja se está conectado, com o iPhone no Wi-Fi. Feche o
   SideStore de vez e abra de novo.
2. Se continuar, conecte o iPhone ao computador, abra o iloader, clique em
   **Gerenciar Arquivo de Pareamento** e em **Colocar** ao lado do SideStore. Espere
   a mensagem de sucesso e abra o SideStore de novo.
3. Se o iloader não conseguir, clique em **Apagar pareamento armazenado** nas
   configurações dele, conecte o iPhone de novo, toque em **Confiar** e repita o
   passo 2.

**A Estante parou de abrir.** A assinatura de 7 dias venceu. Veja
[Renovar a cada 7 dias](#renovar-a-cada-7-dias). Seus livros continuam lá.

**Erro de limite de apps ao instalar.** O Apple ID gratuito permite 3 apps
instalados assim ao mesmo tempo, e o SideStore ou o AltStore conta como um. Remova
outro app em **My Apps** para liberar espaço.

**Um arquivo `.js` chegou como `.txt` pelo AirDrop.** O iPhone trata o arquivo como
texto e troca o final do nome, e a Estante só aceita `.js`. No app Arquivos:

1. Se o nome aparece sem o final, toque em **⋯ › Opções de Visualização** e ative
   **Mostrar Todas as Extensões**.
2. Toque e segure no arquivo, escolha **Renomear** e troque `.txt` por `.js`.
3. Confirme quando o iPhone perguntar se quer usar ".js".

Pelo iCloud Drive o nome não muda. Também dá para arrastar o arquivo pelo Finder,
com o iPhone conectado, para cima de **Estante** na aba **Arquivos**.

**Um download longo parou.** O iOS suspende apps em segundo plano. Obras do Syosetu,
montadas capítulo por capítulo, só avançam com a Estante aberta na tela; o botão
mostra o andamento.

**O dicionário não aparece.** Ele consulta o Wikcionário e precisa de internet.
Quando a palavra não tem verbete, o cartão oferece procurar direto no site.

## Segurança e privacidade

- A Estante não tem conta, anúncios nem servidor próprio. Os livros, as notas e as
  preferências ficam só no aparelho.
- Ela só se conecta aos acervos que você busca (e aos sites de onde baixa os livros e
  as capas) e, para o dicionário, ao Wikcionário. A rede local só é usada para abrir
  catálogos OPDS da sua casa.
- O SideStore e o AltStore assinam a Estante com o seu Apple ID; a senha vai direto
  para a Apple. Use um Apple ID secundário e baixe o SideStore, o iloader e o
  AltStore só dos sites oficiais ([sidestore.io](https://sidestore.io),
  [iloader.app](https://iloader.app), [altstore.io](https://altstore.io)).
- O arquivo de pareamento dá ao SideStore o mesmo acesso de um computador em que
  você confiou. Não compartilhe esse arquivo.
- Uma atualização do iOS às vezes quebra o SideStore até sair uma correção. Os apps
  continuam abrindo até a assinatura vencer. Antes de atualizar o iOS, veja se o
  SideStore já funciona na versão nova.
