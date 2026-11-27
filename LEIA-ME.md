# Nariah Studio · Vitrine (versão 2)

Direção visual e movimento, feitos em 26/11/2026 a partir da versão original.

Para ver o site, abra o `index.html` com dois cliques. Ele precisa ficar junto da pasta `fotos/`. A versão original continua intacta em `../Site - Versão Original`.

## O que mudou

- **Primeira dobra:** é a única entrada animada do site, em sequência:
  - o cabeçalho aparece;
  - o título sobe linha por linha, revelado por máscara;
  - o texto e os botões aparecem em seguida;
  - a foto abre em arco de baixo para cima, com um leve ajuste de zoom.
- **Toque e clique:** botões, filtros, tamanhos e cards encolhem 3% ao serem pressionados.
- **Cards de produto (só com mouse):**
  - a segunda foto da peça aparece com um fade suave;
  - surge uma seta discreta;
  - o nome muda para cacau.
- **Ao rolar a página (navegadores compatíveis):**
  - o cabeçalho fica mais sólido;
  - a foto do topo desce um pouco mais devagar que o resto da página;
  - as fotos editoriais (destaques, Nathalia e Nariah Lovers) se revelam por recorte;
  - a assinatura NARIAH do rodapé sobe.
- **Página da peça:** o painel abre com a mesma curva de gaveta usada no iOS.
- **Acabamento:**
  - numeração editorial das seções (01 a 04);
  - preços com números alinhados;
  - cor de seleção de texto e anel de foco da marca;
  - a palavra NARIAH em tamanho gigante no rodapé.
- **Acessibilidade:** com "reduzir movimento" ativado, ficam só os fades e os deslocamentos são desligados. Com "reduzir transparência", os efeitos de vidro viram fundo sólido.

## Ajustes de 26/11/2026 (segunda rodada)

- **Título da primeira dobra:** "for Modern Women" fica sempre numa linha só. O tamanho se ajusta à largura da tela.
- **Foto da primeira dobra:** mais centralizada nela, com um leve zoom no fim da entrada.
- **NARIAH no cabeçalho e no rodapé:** agora usa a fonte Prata, a mais próxima do N do monograma.
- **Cabeçalho:** vidro fosco de verdade, com desfoque do que passa por baixo.
- **Textos ao rolar:** títulos, parágrafos, citação, benefícios do grupo e rodapé sobem de um leve desfoque quando entram na tela.
- **Ajuda com tamanhos:** virou um botão em destaque, na cor manteiga. Ele abre o WhatsApp com a mensagem já escrita.
- **NARIAH gigante do rodapé:** ao passar o mouse pelo rodapé, as letras escurecem. Sobre a palavra, elas sobem em onda e ficam cacau.

## Referência

Princípios de design engineering e motion de Emil Kowalski (github.com/emilkowalski/skills):

- **Curvas:** ease-out forte `cubic-bezier(0.23, 1, 0.32, 1)` e curva de gaveta `cubic-bezier(0.32, 0.72, 0, 1)`.
- **Clique:** resposta ao toque em menos de 200ms.
- **Animação só onde importa:** uma entrada orquestrada só na primeira dobra, em vez de uma animação em cada seção.
- **Performance:** só `transform`, `opacity` e `clip-path` são animados.
- **Hover:** os efeitos de hover só valem onde há mouse.

## Ajustes de 27/11/2026 (sacola e novas peças)

- **Catálogo com 13 peças:**
  - Blusa Frente Única e Top Costas Abertas entram com o selo "Novo".
  - Top Ombro e Calça Cós Cruzado (Azul Navy) entram como mostruário, com o selo "Esgotado". Ao abrir, todos os tamanhos ficam riscados, o botão vira "Peça esgotada" e aparece "Consultar reposição pelo WhatsApp".
- **Fotos novas:** Icon na cor Cacao (agora a cor da capa) e Top Regulável na cor Coral.
- **Sacola:**
  - ícone no cabeçalho com contador;
  - "Adicionar à sacola" na página da peça, mantendo a compra direta de uma peça pelo WhatsApp;
  - a sacola fica salva no navegador;
  - nome e observação opcionais;
  - o pedido completo vai numa única mensagem para o WhatsApp.
