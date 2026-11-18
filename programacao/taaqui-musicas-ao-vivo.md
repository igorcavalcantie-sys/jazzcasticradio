# Músicas para o ao vivo (WebDJ da Taaqui)

## O problema
Na automação, a Taaqui deixa usar a biblioteca dela, que é grande. No **WebDJ** (o programa para entrar ao vivo), as músicas precisam vir de você. Então: de onde tirar, de forma legal e com qualidade?

**O que já sabemos:**
- O WebDJ **não acessa** a biblioteca da Taaqui. Para o ao vivo, é preciso baixar e subir as músicas.

Os dois caminhos abaixo se combinam.

- Também **não existe** modo de entrar só com o microfone por cima da automação (confirmado com o suporte). Por isso o Caminho 1 (voice tracking) é a alternativa para os dias sem ao vivo.

> **ECAD: resolvido.** As músicas que você sobe e toca no WebDJ durante o ao vivo já ficam cobertas pela Taaqui, sem custo extra (confirmado por você na prática). A escolha da fonte abaixo é, então, questão de **qualidade de áudio e segurança**.

---

## Caminho 1: voice tracking ("ao vivo gravado")

É como a maioria das rádios do mundo mantém programas apresentados todo dia sem o locutor estar lá.

**Como funciona:**
1. Na Taaqui, monte a playlist do programa (ex.: Unwind de quarta) com músicas da **biblioteca**.
2. Grave suas falas como arquivos separados (`Unwind_Qua_Fala1.mp3`, `Fala2`…), com 30–90s cada, já sabendo qual música vem antes e depois.
3. Suba as falas no **painel de áudio** (o mesmo onde ficam spots e vinhetas).
4. Encaixe as falas entre as músicas da playlist e programe o horário.

**Vantagens:**
- Usa a biblioteca da Taaqui, sem precisar baixar música.
- Você grava com calma, refaz o que errar e escolhe a melhor take. **Cada fala é treino de locução.**
- O Unwind vai ao ar todo dia, mesmo nos dias em que você estiver trabalhando ou cansado.

**Dica para soar ao vivo:** fale do *dia* sem prender a data ("quarta-feira, meio da semana…"), cite a música anterior e a seguinte pelo nome, e grave no mesmo dia ou na véspera.

**Limitação:** não tem interação em tempo real.

**Por que isso importa ainda mais agora:** como o ao vivo exige baixar e subir tudo, o voice tracking é o jeito de manter o Unwind no ar todo dia sem esse trabalho. Reserve o esforço do WebDJ para as 2–3 noites ao vivo da semana. Por isso o ideal é misturar: voice tracking na maioria dos dias e ao vivo de verdade em 2–3 noites por semana.

---

## Caminho 2: montar um acervo próprio para o WebDJ

### Onde conseguir música de forma legal
| Fonte | O que é | Observação |
|---|---|---|
| **Bandcamp** | compra direta de artistas e selos, MP3/FLAC sem DRM | ótimo para jazz, soul e independentes; o artista recebe a maior parte |
| **iTunes Store** (app Música no Mac / iTunes no Windows) | compra de faixas em AAC sem DRM | não confunda com o *Apple Music* (assinatura), cujos downloads não servem |
| **Qobuz / lojas de download em alta qualidade** | compra em FLAC | verifique a disponibilidade da loja de download no Brasil |
| **Seus CDs** | importar para o computador | qualidade alta, e você já tem o disco |
| **Domínio público / Creative Commons** (Musopen, Free Music Archive, Jamendo) | música liberada | bom para trilhas de fundo e descobertas |

### O que NÃO usar
- **Downloads do Spotify, Deezer, YouTube Music ou Apple Music:** são protegidos (DRM) e só tocam dentro do app.
- **Conversores "YouTube para MP3":** violam os termos do YouTube, entregam qualidade ruim (dá para ouvir na transmissão) e muitos sites desse tipo espalham vírus.

### Trabalhar menos: o acervo é reaproveitável
Se a cada ao vivo você baixa e sobe tudo do zero, o trabalho nunca acaba. A saída é tratar o acervo como **estoque**:
- Monte pastas fixas por edição (Blues de Sexta, Fora do Jazz…) e **reaproveite**: uma pasta de ~60 faixas rende muitas semanas trocando a ordem e misturando 3–4 músicas novas.
- Mantenha no WebDJ o que você mais usa (dentro do limite de armazenamento) e só suba as novidades da semana.
- Faça as compras/downloads em **lote**, uma vez por mês, e não na véspera de cada programa.
- Guarde tudo também num HD externo ou na nuvem, para não perder o acervo se o notebook der problema.

### Comprar com inteligência (orçamento enxuto)
Você não precisa de milhares de músicas. Para o ao vivo, **200–300 faixas bem escolhidas** cobrem semanas de programa, porque a automação segue tocando a biblioteca da Taaqui no resto do tempo.

- Compre por **programa**: ~60 faixas para Fora do Jazz, ~60 para Blues de Sexta etc.
- Priorize faixas que **você tem história para contar**, já que o ao vivo é onde você fala.
- Faça uma lista de desejos e compre 10–20 por mês.

### Organização das pastas (no Acer)
```
Jazzcastic_AoVivo/
├── 00_Vinhetas/        (abertura, encerramento, meio de programa, ID)
├── 01_Spots_Chamadas/  (chamadas da rádio, spots de parceiros)
├── Unwind_Seg_Pedidos/
├── Unwind_Ter_Disco/
├── Unwind_Qua_ForaDoJazz/
├── Unwind_Qui_DNA/
├── Unwind_Sex_Blues/
├── Sab_Samba/
└── Dom_CeuEJazz/
```
- Nome dos arquivos: `Artista - Música (Ano).mp3`
- Formato: **MP3 320 kbps** é o equilíbrio ideal para subir (confirme o que o WebDJ aceita).
- **Volume igualado:** músicas de épocas diferentes têm volumes muito diferentes (um jazz de 1959 é bem mais baixo que um rock de 2003). Normalize o volume do acervo antes de subir (a função *Loudness Normalization* do Audacity resolve; mire em torno de −14 LUFS). Assim o ouvinte não leva susto de volume.

### Antes de cada ao vivo (checklist)
- [ ] Playlist do dia montada no WebDJ, na ordem do "relógio" (ver `grade-ao-vivo.md`)
- [ ] 2 músicas de reserva, caso uma fala se estenda ou alguma faixa dê problema
- [ ] Vinhetas e chamadas carregadas
- [ ] Roteiro de tópicos impresso ou aberto no tablet (Galaxy Tab)
- [ ] Teste de microfone gravado e ouvido no DT 770
- [ ] Notificações do celular e do computador desligadas
- [ ] Story das 18h45 publicado
