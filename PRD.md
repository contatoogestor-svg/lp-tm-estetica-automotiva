# PRD — Landing Page TM Estética Automotiva

**Versao:** 1.0
**Data:** 09/03/2026
**Agente:** Aria (@architect)
**Status:** Aguardando aprovacao

---

## 1. Objetivo

Landing page de captacao de leads via Google Ads para a TM Estetica Automotiva.
Foco em conversao: visitante → contato via WhatsApp.

## 2. Stack Tecnica

| Item | Tecnologia |
|------|-----------|
| HTML | HTML5 semantico |
| CSS | Tailwind CSS (CDN) |
| JS | Alpine.js (interatividade leve) |
| Icones | Lucide Icons |
| Fontes | Google Fonts (Montserrat + Inter) |
| Deploy | GitHub Pages + subdominio |
| Dominio | lp.tmesteticaautomotiva.com.br (CNAME → GitHub Pages) |

## 3. Referencia Visual

- **Site referencia:** frisonsig.com
- **Estilo:** Dark theme premium, fundo preto (#000000), tipografia branca
- **Efeitos:** Parallax suave, contadores animados, transicoes smooth
- **Identidade:** Manter paleta atual da TM (preto, branco, dourado/amarelo dos destaques)

## 4. Estrutura das Secoes

### S1 — Header (fixo no topo)
- Logo TM Estetica Automotiva (esquerda)
- Menu: Servicos | Sobre | Depoimentos | Contato
- Botao CTA: "Solicite um Orcamento" → WhatsApp
- Fundo: preto semi-transparente com blur (glassmorphism)
- Mobile: hamburger menu

### S2 — Hero
- Titulo: "Protecao e Brilho que seu veiculo merece"
- Subtitulo: "Especialistas em PPF, Ceramic Coating e Estetica Automotiva em Florianopolis"
- Botao CTA primario: "Fale Conosco no WhatsApp" → WhatsApp
- Botao CTA secundario: "Conheca Nossos Servicos" → ancora secao servicos
- Fundo: imagem hero de alta qualidade com overlay gradiente escuro
- Placeholder: imagem de carro com PPF/acabamento premium

### S3 — Servicos
- Titulo: "Conheca Nossos Servicos"
- Grid 3x2 (desktop) / 1 coluna (mobile)
- Cada card com:
  - Imagem placeholder do servico
  - Nome do servico
  - Descricao curta
  - Botao: "Saiba Mais" → WhatsApp com mensagem pre-definida por servico

**Servicos:**

| # | Servico | Descricao |
|---|---------|-----------|
| 1 | PPF Full | Proteja a pintura do seu carro contra riscos e impactos com nossa pelicula de protecao de alta tecnologia. |
| 2 | Polimento | Revitalize a aparencia do seu veiculo com nossos polimentos especializados, removendo riscos e restaurando o brilho original da pintura. |
| 3 | Cristalizacao | Aumente o brilho e a profundidade da pintura do seu veiculo com o nosso processo de cristalizacao, garantindo um acabamento impecavel. |
| 4 | Higienizacao | Proteja o interior do seu carro com nosso tratamento UV e mantenha o ambiente interno limpo e fresco com nossa higienizacao profissional. |
| 5 | Lavagem Premium | Oferecemos uma lavagem completa e detalhada, utilizando produtos de alta qualidade para garantir que seu carro esteja sempre impecavel. |
| 6 | Ceramic Coating | Proporcione uma camada de protecao avancada com nosso revestimento ceramico, que defende a pintura contra sujeira, manchas e danos ambientais. |

### S4 — Numeros do Negocio
- Fundo diferenciado (gradiente sutil ou imagem com overlay)
- 3 contadores animados em linha (scroll-triggered):
  - **+20** Anos de Experiencia
  - **+500** Veiculos Atendidos
  - **+200** PPFs Instalados
- Animacao: contagem de 0 ate o numero ao entrar na viewport

### S5 — Videos de Trabalhos Realizados
- Titulo: "Veja Nossos Trabalhos"
- Carousel/slider horizontal com thumbnails
- Ao clicar: abre embed do Instagram em modal ou redireciona
- Videos (6 itens):
  1. https://www.instagram.com/tmesteticaautomotiva/reel/DU_Saz3kZy2/
  2. https://www.instagram.com/tmesteticaautomotiva/reel/DUg2HjiER0J/
  3. https://www.instagram.com/tmesteticaautomotiva/reel/DUZQAZOka8m/
  4. https://www.instagram.com/tmesteticaautomotiva/reel/DTWNBNeEUmw/
  5. https://www.instagram.com/p/DSoABYskcnM/
  6. https://www.instagram.com/p/DSVz-AAkZDa/
- Alternativa tecnica: thumbnails estaticos com link para Instagram (evita peso de embed)

### S6 — Quem Somos
- Titulo: "Quem Somos"
- Texto institucional sobre a TM Estetica Automotiva
- Destaque: 20 anos de experiencia, especialistas em PPF
- Imagem: foto do espaco/equipe (placeholder)
- Layout: 2 colunas (texto + imagem) desktop, empilhado mobile

### S7 — Depoimentos de Clientes
- Titulo: "O que nossos clientes dizem"
- Carousel com 3 depoimentos reais:

**Depoimento 1:**
- Nome: Fabio Duncan
- Avaliacao: 5 estrelas
- Data: 21/01/2025
- Texto: "Quero deixar registrado o excelente atendimento que recebi na TM Estetica Automotiva. O profissionalismo, atencao aos detalhes e qualidade do servico sao impressionantes. Meu carro ficou impecavel, muito acima das expectativas! A equipe e extremamente atenciosa e demonstra um grande cuidado em tudo o que faz. Recomendo de olhos fechados e, com certeza, voltarei mais vezes. Parabens pelo trabalho!"

**Depoimento 2:**
- Nome: Artur Brandes de Azevedo Ferreira
- Avaliacao: 5 estrelas
- Data: 22/01/2025
- Texto: "Servico e atendimento de alta qualidade e profissionalismo. Contratei um servico para protecao preventiva das partes plasticas externas do carro, pois o carro fica muito tempo exposto ao sol. Na contratacao foi explicado de forma clara as opcoes existentes e os beneficios de cada uma, assim como os diferentes produtos existentes para essa finalidade e a importancia da escolha para a conservacao da estetica do veiculo a longo prazo. Resultado excelente."

**Depoimento 3:**
- Nome: Thiago Silva
- Avaliacao: 5 estrelas
- Data: 21/01/2025
- Texto: "Pra mim foi uma experiencia incrivel... varios servicos executados no meu carro que eu nem sabia que era possivel e eles deixaram simplesmente impecavel. E deu pra perceber que o Tito tem total conhecimento tecnico de todos os processos. Indico demais a TM."

### S8 — Footer
- Logo TM
- Informacoes de contato:
  - Endereco: R. Profa. Otilia Cruz, 198 A - Jardim Atlantico, Florianopolis - SC, 88095-080
  - Telefone/WhatsApp: (48) 99652-7898
- Redes sociais (icones):
  - Instagram: https://www.instagram.com/tmesteticaautomotiva/
  - Facebook: https://www.facebook.com/people/TM-Est%C3%A9tica-Automotiva/61557152052905/
  - YouTube: https://www.youtube.com/@tmest%C3%A9ticaautomotiva
- Link Google Maps do endereco
- Copyright: © 2026 TM Estetica Automotiva. Todos os direitos reservados.

### Botao Flutuante WhatsApp
- Canto inferior direito, fixo
- Icone WhatsApp verde
- Ao clicar: abre WhatsApp com mensagem pre-definida
- WhatsApp URL: https://wa.me/5548996527898?text=Ol%C3%A1!%20Vim%20pelo%20site%20e%20gostaria%20de%20solicitar%20um%20or%C3%A7amento.

## 5. SEO e Performance

- Meta tags: title, description, og:image, og:title, og:description
- Schema markup: LocalBusiness
- Lazy loading em imagens
- Minificacao inline (CSS/JS no proprio HTML)
- Lighthouse target: 90+ em todas as categorias

## 6. Google Ads — Quality Score

- Conteudo relevante para keywords: PPF Florianopolis, estetica automotiva, ceramic coating, polimento automotivo
- CTA claro e acima da dobra
- Mobile-first (responsivo)
- Velocidade de carregamento rapida (CDN, sem frameworks pesados)
- Pagina unica (sem redirecionamentos)

## 7. Arquivos do Projeto

```
LP/
├── index.html          # Pagina unica com tudo inline
├── assets/
│   ├── images/         # Imagens (hero, servicos, equipe)
│   │   └── placeholder # Placeholders ate receber fotos reais
│   └── favicon.ico     # Favicon TM
├── PRD.md              # Este documento
└── README.md           # Instrucoes de deploy
```

## 8. Entregaveis

1. LP funcional em HTML unico com Tailwind CDN
2. Responsiva (mobile-first)
3. Botao WhatsApp flutuante
4. Contadores animados
5. Carousel de depoimentos
6. Secao de videos com links Instagram
7. Deploy no GitHub Pages
8. Configuracao CNAME para subdominio
