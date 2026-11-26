# Rhiza Bank — mensagens para o Lovable (uma página por mensagem)

Regras gerais (valem para todas as páginas):
- Referência visual: `design-reference/<pagina>-N.jpg` (desktop 1440px) e `design-reference/<pagina>-mobile-N.jpg` (mobile 524px). Siga fielmente.
- Imagens prontas em `public/images/` e logos em `public/brand/`. Use exatamente esses arquivos.
- Botões sem destino definido: mostrar o toast "No site final, este botão ..." já criado.
- Títulos com palavras destacadas: as palavras verdes usam o gradiente #00A547 → #00F56A (background-clip: text).

---

## 1. HOME ( / )

Construa a Home seguindo `design-reference/home-1.jpg` a `home-6.jpg` (desktop) e `home-mobile-1.jpg` a `home-mobile-5.jpg` (mobile). Troque o logo provisório do menu e do rodapé por `public/brand/logo-menu-rhiza-bank.png` (versão verde+branco com "BANK").

Seções, em ordem:

1. **Carrossel principal** (card de vidro grande, 1267x676, raio 38px, borda verde 1.5px; no desktop os slides vizinhos aparecem como faixas atrás nas laterais). Setas redondas cinza (#DEDEDE, 48x46) abaixo. Troca automática a cada 6s.
   - Slide 1: título Inter Bold 50px "**Seu** imóvel, **seu** carro, **seu** negócio." (Seu/seu em #101010, o resto em gradiente verde), subtítulo Inter 23px "Sem juros. No seu tempo.", botão verde "Simule agora" (301x57) → /consorcio#simulador. Imagem à direita: `/images/home-hero-imovel-carro.jpg`.
   - Slide 2: título em gradiente verde "Planeje hoje, conquiste em breve.", subtítulo "Planejamento inteligente, atendimento humano e transparência total em cada etapa.", imagem `/images/consorcio-hero-casal-cartao.jpg`.
   - Slide 3: título em gradiente verde "Venda mais. Receba na hora. Pague menos.", subtítulo "A maquininha feita para quem leva o negócio a sério.", imagem `/images/rhiza-pay-hero-maquininhas.jpg`.
2. **Simulador** (card verde #1EC85F, 1268x662, raio 32px). À esquerda, imagem `/images/home-simulador-mulher-cartao.jpg` (a mulher ultrapassa o topo do card). À direita: "Conquiste / seu **imovel**" (Inter 60px branco, "imovel" bold); botões "Simular consórcio" (branco) e "Como funciona" (contorno branco); dois campos com label Inter Medium 16 #333F51: "Qual bem você deseja adquirir?" (select: Imóvel, Veículo, Moto, Maquinário, Capital de Giro) e "Em quantos meses deseja pagar?" (select: 20, 36, 48, 60, 80, 100, 120, 150, 180, 200); valor grande "**R$** 60.000" (Inter 60 branco) e um slider (trilho cinza #D9D9D9 com bolinhas nas pontas e marcador branco em forma de pino) de R$ 20.000 a R$ 150.000, passo 1.000, que atualiza o valor. "Simular consórcio" mostra um toast: "Simulação ilustrativa: {bem}, crédito de R$ X em N meses ≈ R$ Y/mês (taxa de administração estimada de 15%)". "Como funciona" → /consorcio#como-funciona. Abaixo do card: "Atendimento humano, de verdade. Transparência em tudo que você contrata. Soluções que crescem com você." (Inter Bold 16 #333F51, centralizado).
3. **Pensado para acompanhar sua rotina**: título Inter 48 ("Pensado" e "sua rotina" Light, "para acompanhar" Bold). Imagem central `/images/home-app-celular-cartao.png` (fundo transparente). Rótulo à esquerda "Tudo **organizado em um só lugar**" e à direita "Mais **vantagens. Menos tarifas**" (Inter 32). Linhas verdes finas decorativas saindo pela direita.
4. **Tudo o que seu dia precisa. / E o que seus sonhos pedem.** (Inter 48, segunda linha bold). Carrossel de 3 cards com o do meio maior e elevado: `/images/home-carrossel-maquininha.jpg`, `/images/home-carrossel-emprestimo.jpg` (centro), `/images/home-carrossel-pix.jpg` (as imagens já têm o rótulo). Setas para girar. Botão "Conheça nossa história" → /franquias.
5. **Cartão Rhiza Life**: "Cartão **Rhiza Life**" (Inter 38, "Rhiza Life" verde), "**Menos de R$2,00 por dia.** Médico, desconto em farmácia, energia mais barata e muito mais" (Inter 40), "Você contrata hoje. Já usa amanhã. **Sem burocracia.**" (Inter 24). Foto `/images/home-life-mulher-cartao.jpg` à esquerda (com fade para o fundo) e grade 3x2 de cards de vidro com brilho verde na borda (281x349, ícone de linha + texto Inter 16 centralizado cinza): Médico 24h no celular para você e para toda a família, em qualquer horário. / Até 70% de desconto em farmácias em mais de 30 mil redes parceiras / Até 30% a menos na conta de energia sem instalar nada, direto na sua fatura. / Teleconsulta Pet, com veterinário online sempre que precisar. / Atestados e receitas digitais sem sair de casa, válido em qualquer lugar. / Consultas presenciais em rede de parceiros para quando precisar. (Referência visual dos cards: `/images/home-life-beneficio-1..6.jpg`.) Botão "Faça parte do Rhiza Life" → /rhiza-life. Faixa de logos de parceiros: `/images/home-logos-parceiros.jpg`.
6. **A maquininha que entende de negócio** (segunda linha em gradiente verde, Inter 48) + "Venda mais, receba na hora e pague menos" (Inter Bold 20). Imagem central `/images/home-maquininhas-par.png` com 4 itens com check verde: esquerda "Pix sem taxa na maquininha. **Sem taxa. Sem espera. O dinheiro cai na hora.**" e "Todas as bandeiras. **Débito, crédito e parcelamento, aceita tudo, sem burocracia.**"; direita "Antecipação de recebíveis. Vendeu parcelado, precisa do dinheiro agora? **A Rhiza adianta pra você.**" e "Planos personalizados. **Para o comerciante que vende pouco e para quem vende muito.** Taxa que faz sentido pro seu volume." Botão "Conheça Rhiza Pay" → /rhiza-pay.
7. **Estamos em expansão** ("expansão" verde, Inter 38): "**Que tal uma unidade Rhiza na sua cidade, no seu nome?** A estrutura é nossa. **O negócio é seu.** Investimento acessível, suporte completo e um portfólio de produtos que as pessoas já precisam: consórcio, crédito, conta digital e benefícios. **Tudo com a estrutura da Rhiza por trás.**" Botão "Quero conhecer" → /franquias. Mapa `/images/home-mapa-expansao.jpg`.
8. **Impacto social**: "Cada produto vendido **alimenta uma família** no Brasil e na África." (Inter 40, destaque verde) + banner `/images/home-banner-impacto.jpg` (já contém o texto "1C = 5P"), raio 38px, borda verde. No mobile, abaixo do banner: "A cada consórcio vendido, 5 pratos de comidas são doados." e botão "Quero saber mais" (toast).

Mobile: tudo empilhado e centralizado como nas referências mobile; carrosséis com swipe; simulador com campos lado a lado e valor centralizado (48px).

---

## 2. CONSÓRCIO ( /consorcio )

Referências: `consorcio-1..4.jpg` e `consorcio-mobile-1..5.jpg`.
1. Hero (card de vidro): "Planeje hoje, conquiste em breve." (gradiente verde, Inter Bold 50) + "Planejamento inteligente, atendimento humano e transparência total em cada etapa." Imagem `/images/consorcio-hero-casal-cartao.jpg`.
2. Banner da casa `/images/consorcio-casa-banner.jpg` (raio 16) e, sobreposto, `/images/consorcio-homem-cartao-celular.jpg` com forma verde. Texto à esquerda: "O que é **consórcio**" (Inter 40, "consórcio" verde) + "Um grupo de pessoas contribui mensalmente para um fundo comum. Todo mês, alguém é contemplado e recebe uma carta de crédito para comprar à vista, com poder de negociação e sem pagar juros." / "Você paga apenas uma taxa de administração, informada antes de qualquer assinatura. Sem surpresa, sem cláusula escondida."
3. Grade 2x2 de fotos (`/images/consorcio-foto-1..4.jpg`, raio 16, borda verde) + "Para que serve o **consórcio Rhiza**": **Imóvel:** Casa própria, terreno ou imóvel comercial. Sem comprometer o orçamento com juros de financiamento. / **Veículo:** Carro novo, seminovo ou frota. Crédito aprovado no valor contratado, livre para usar em qualquer concessionária. / **Moto:** Mobilidade, trabalho ou lazer. Parcelas acessíveis, sem entrada pesada. / **Maquinário:** Renove ou amplie equipamentos, sem comprometer o fluxo de caixa. / **Capital de Giro:** Crédito para o negócio crescer sem recorrer a linhas de juros elevados.
4. Simulador (id="simulador"): mesmo componente da Home, versão sem foto (título à esquerda, campos/valor/slider à direita). Abaixo: "Atendimento humano, de verdade. Transparência em tudo que você contrata. Soluções que crescem com você."
5. (id="como-funciona") "Como funciona a **contemplação**": "Por sorteio mensal, qualquer participante pode ser contemplado desde o primeiro mês. Ou por lance, oferecendo um percentual do crédito para antecipar a contemplação." / "O crédito mantém o valor atualizado. Você usa quando contemplado, sem perder poder de compra."
6. Foto `/images/consorcio-cartoes-na-mao.jpg` + "Por que fazer com a **Rhiza**": "Atendimento de pessoas reais, sem enrolação e sem empurrar produto. As informações, taxa, prazo, regras, cancelamento, vêm antes da assinatura, não depois." / "Quem já é correntista tem condições diferenciadas e experiência ainda mais integrada." Botões "Simular consórcio" (→ #simulador) e "Fale com um especialista" (toast WhatsApp).
7. FAQ em acordeão (card cinza-claro) "Dúvidas Frequentes": O consórcio tem juros? (resposta: "Não. O consórcio não cobra juros. Você paga a taxa de administração, que remunera a gestão do grupo, e o fundo de reserva, que garante a segurança financeira do consórcio. Tudo informado com antecedência e sem surpresa.") / Posso ser contemplado logo no início? / O que acontece depois que sou contemplado? / Posso cancelar o consórcio? / Preciso ter conta na Rhiza para contratar o consórcio? (para as sem resposta no design, escreva uma resposta curta e marque com um comentário TODO no código para revisão).

---

## 3. PRODUTOS ( /produtos )

Referências: `produtos-1..4.jpg` e `produtos-mobile-1..4.jpg`.
1. Hero: "Tudo que você precisa. Em um só lugar." (gradiente verde) + "Conta, crédito, maquininha e benefícios, com **atendimento de verdade.**" Imagem `/images/produtos-hero-cartoes-maquininha.jpg`.
2. Seções alternadas (texto/imagem, título Inter Bold 40 verde, botão verde):
   - Conta Digital — `/images/produtos-conta-digital-celular-cartao.jpg` — "Gratuita para pessoa física e jurídica. Abertura 100% digital em minutos. **Pix, TED, boleto, cartão físico e virtual. Sem taxa, sem burocracia.**" / "**Para empresas:** gestão financeira, emissão de cobranças e controle de caixa integrados." — "Abrir minha conta grátis" (toast)
   - Empréstimo Pessoal — `/images/produtos-foto-1.jpg` — "**Crédito rápido, condições claras e parcelas que cabem no orçamento.** Você vê o custo total antes de assinar. **Sem surpresa.**" — "Simular meu empréstimo" (toast)
   - Capital de Giro — `/images/produtos-foto-2.jpg` — "**Fôlego para o seu negócio crescer, pagar fornecedores ou aproveitar uma oportunidade.** Sem exigências impossíveis." — "Fale com um especialista" (toast)
   - Financiamento — `/images/produtos-foto-3.jpg` — "**Imóvel, veículo ou equipamento.** Simulação completa antes de qualquer decisão, parcela, prazo, taxa e custo total às claras." — "Simular meu financiamento" (toast)
   - Maquininha Rhiza Pay — `/images/produtos-maquininha.jpg` — "Todas as bandeiras, Pix sem taxa e dinheiro na hora. Para quem vende parcelado, antecipação de recebíveis disponível. **Planos personalizados por volume.**" — "Conhecer Rhiza Pay" → /rhiza-pay
   - Clube de Benefícios Rhiza Life — `/images/produtos-foto-4.jpg` — "Médico 24h, farmácia com até 70% de desconto, energia mais barata e veterinário online. Por menos de R$2 por dia. **Sem carência, sem espera.**" — "Conhecer Rhiza Life" → /rhiza-life
3. "Como a **Rhiza** trabalha": "Atendimento humano. Pessoas reais, sem script e sem pressão." / "**Transparência total. Tudo informado antes da assinatura.**" / "Soluções que crescem com você. Do Pix diário ao planejamento do seu patrimônio." — botão "Abrir minha conta grátis".
No mobile use as fotos `/images/produtos-mobile-foto-1..4.jpg` (recortes horizontais).

---

## 4. RHIZA LIFE ( /rhiza-life )

Referências: `rhiza-life-1..3.jpg` e `rhiza-life-mobile-1..3.jpg`.
1. Hero: "Saúde, economia e bem-estar por **menos de R$2 por dia**" (preto + gradiente verde) / "**Contrate hoje. Use amanhã.** Sem carência, sem burocracia." Imagem `/images/rhiza-life-hero-mulher-cartao.jpg`.
2. `/images/rhiza-life-mulher-cartao-verde.jpg` + "O que é o Rhiza Life?" (verde): "O Rhiza Life é o clube de benefícios da Rhiza. Por R$49 por mês, você e sua família têm acesso a médico, farmácia, energia mais barata e muito mais, **sem carência, sem processo de aprovação e sem lista de exceções escondidas.**" (no mobile usar `/images/rhiza-life-mobile-foto-1.jpg`).
3. "O que está incluso": carrossel de cards (centro maior com descrição): Médico 24h no celular — "Consulta, receita e atestado a qualquer hora, para toda a família. Sem sair de casa, válido em qualquer lugar do Brasil."; Desconto em Farmácias; Veterinário online. Referência visual: `/images/rhiza-life-carrossel-incluso.jpg`.
4. "Por que o **Rhiza Life existe?**" + `/images/rhiza-life-foto-1.jpg`: "Plano de saúde é caro. Consulta particular pesa no bolso. O Rhiza Life não substitui um plano, resolve a maioria das situações do dia a dia com um custo que cabe em qualquer orçamento."
5. "Como Contratar" (verde): "Pelo app Rhiza ou com um atendente. Preenche o cadastro, confirma o pagamento e já usa. Sem análise de saúde, sem documento além do básico." Botões "Contratar Rhiza Life" (toast) e "Fale com um especialista" (toast).

---

## 5. RHIZA PAY ( /rhiza-pay )

Referências: `rhiza-pay-1..4.jpg` e `rhiza-pay-mobile-1..3.jpg`.
1. Hero: "Venda mais. Receba na hora. Pague menos." (gradiente verde) / "A maquininha feita para quem leva o negócio a sério." Imagem `/images/rhiza-pay-hero-maquininhas.jpg`.
2. Cinco blocos: banner de foto largo (1267x360, raio 16, borda verde) + título verde centralizado (Inter Bold 40) + texto:
   - `/images/rhiza-pay-foto-1.jpg` — Pix sem taxa — "**Aceita Pix direto na maquininha, sem taxa e sem espera.** O dinheiro cai na hora."
   - `/images/rhiza-pay-foto-2.jpg` — Todas as bandeiras — "Débito, crédito à vista e parcelado. **Nenhuma venda perdida por limitação de bandeira.**"
   - `/images/rhiza-pay-foto-3.jpg` — Antecipação de recebíveis — "Vendeu parcelado e precisa do dinheiro agora? A Rhiza adianta. **Sem empréstimo, sem burocracia.**"
   - `/images/rhiza-pay-foto-4.jpg` — Planos personalizados — "Taxa que faz sentido para o seu volume. **Quem vende R$5 mil não paga igual a quem vende R$50 mil.**"
   - `/images/rhiza-pay-foto-5.jpg` — Gestão integrada — "Recebimentos, extratos e relatórios direto no app Rhiza. **Tudo em um lugar só.**"
3. Botões "Solicitar minha Rhiza Pay" (toast) e "Fale com um especialista" (toast).
No mobile use `/images/rhiza-pay-mobile-foto-1..5.jpg`.

---

## 6. FRANQUIAS ( /franquias )

Referências: `franquias-1..3.jpg` e `franquias-mobile-1..3.jpg`.
1. Hero com foto de fundo `/images/franquias-hero-fachada.jpg` (card 1267x615, raio 38): "O negócio é seu. A estrutura é nossa." (branco, Inter Bold 40) / "**Estrutura completa**, suporte contínuo e um modelo feito para durar." Linhas verdes decorativas.
2. Seções alternadas foto/texto (títulos verdes Inter Bold 40):
   - `/images/franquias-foto-1.jpg` — O que é a franquia Rhiza — "**Não é revenda de produto financeiro.** É a implantação de uma presença bancária local, com conta digital, consórcio, crédito, benefícios e maquininha, tudo integrado. O cliente não contrata um produto. Passa a ter um banco de confiança na sua cidade."
   - `/images/franquias-foto-2.jpg` — Por que esse modelo funciona — "Franquias financeiras comuns dependem de um produto, campanhas constantes e volume alto. Quando o mercado muda, a operação sente na hora." / "**A Rhiza foi estruturada diferente.** Portfólio diversificado, foco em relacionamento e receita recorrente. **A base de clientes cresce e a receita cresce junto, não só quando uma nova venda acontece.**"
   - `/images/franquias-foto-3.jpg` — O que a Rhiza oferece — "Tecnologia, sistemas, produtos regulados, marca nacional e suporte diário. **O franqueado começa com uma estrutura que levaria anos para construir sozinho e não fica sem apoio depois da inauguração.**" / "Com o tempo, constrói presença institucional, base fidelizada e um ativo real que valoriza junto com o ecossistema Rhiza."
   - `/images/franquias-foto-4.jpg` — Para quem é — "Para quem pensa em construção, não em resultado imediato. Para líderes com credibilidade local que querem um ativo próprio com suporte sólido." / "**Experiência no setor financeiro não é requisito. Visão de longo prazo é.**"
3. Mapa `/images/franquias-mapa.jpg` + "Como funciona a entrada": "**Começa com uma conversa. Sem pressão, sem compromisso imediato.** Você entende o modelo, avalia a aderência do seu perfil e tira todas as dúvidas antes de qualquer formalização." Botão "Falar com a equipe Rhiza" (toast WhatsApp).
No mobile use `/images/franquias-mobile-foto-1..4.jpg`.

---

## 7. DÚVIDAS ( /duvidas )

Referências: `duvidas-1..4.jpg` e `duvidas-mobile-1..4.jpg`.
Hero: "Perguntas Frequentes" (gradiente verde) / "**Encontre respostas rápidas sobre nossos produtos, serviços e modelo de negócio.** Se precisar de mais ajuda, fale com a gente pelo WhatsApp." Imagem `/images/duvidas-hero-homem-cartao.jpg`.
Seis cards de acordeão (fundo #F3F4F6, raio 16, título Inter Bold 24, perguntas Inter Bold 16, separadores lilás claros, ícone +/×), primeiro item de cada um aberto:
- Sobre o Rhiza Bank: O que é o Rhiza Bank? ("O Rhiza Bank é um banco digital que oferece soluções financeiras completas para pessoas e empresas: conta digital, consórcio, maquininha de pagamento, clube de benefícios e muito mais. Nascemos para democratizar o acesso a serviços financeiros com transparência, taxas justas e atendimento humano.") / O que torna o Rhiza Bank diferente dos outros bancos? / Como a Rhiza Bank contribui para causas sociais?
- Consórcio: O que é consórcio e como funciona na Rhiza? ("Consórcio é uma forma planejada de conquistar um bem, seja imóvel, veículo, moto, maquinário ou capital de giro, sem pagar juros. Um grupo de pessoas contribui mensalmente e, a cada mês, um ou mais participantes são contemplados por sorteio ou lance. Na Rhiza, você ainda conta com simulação rápida e atendimento personalizado.") / Existe taxa de juros no consórcio? / Como sei quando serei contemplado? / Posso usar o consórcio para capital de giro?
- Conta Digital: Como abro minha conta no Rhiza Bank? ("Pelo aplicativo, em poucos minutos. Baixe o app, informe seus dados e envie a documentação solicitada. A abertura é 100% digital, gratuita e sem burocracia.") / A conta tem mensalidade ou tarifas? / Posso abrir conta como pessoa jurídica?
- Rhiza Pay: Quais formas de pagamento a maquininha aceita? ("Débito, crédito, parcelamento e Pix, todas as bandeiras, sem burocracia.") / O Pix na maquininha tem taxa? / O que é antecipação de recebíveis? / Os planos são fixos ou posso escolher?
- Rhiza Life: O que é o Rhiza Life? ("É o nosso clube de benefícios por menos de R$2,00 por dia. Com ele você tem acesso a médico online 24h, descontos em farmácias, redução na conta de energia, teleconsulta veterinária e muito mais, para você e sua família.") / Tem carência para usar os benefícios? / Os descontos em farmácia valem em qualquer lugar? / Como funciona o desconto na conta de energia?
- Franquias: Por que devo me tornar um franqueado da Rhiza Bank? ("Porque você estará à frente de um modelo de negócio que une resultado financeiro e impacto real na vida das pessoas. O mercado está pronto para algo novo e a Rhiza é essa novidade. Você entra com o espírito empreendedor. Nós entramos com a estrutura.") / Quais são os requisitos para ser um franqueado? / Como funciona o suporte para os franqueados?
Para as perguntas sem resposta no design, escreva respostas curtas e coerentes com o resto do site e marque com um comentário TODO para revisão.
