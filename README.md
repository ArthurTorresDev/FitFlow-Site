# FitFlow Studio

Site estático desenvolvido como trabalho acadêmico do 1º semestre de Análise e Desenvolvimento de Sistemas, em 2026. Este foi o primeiro projeto de página web produzido pela equipe na faculdade: uma oportunidade de praticar estruturação com HTML, estilização com CSS e organização de arquivos para publicação na web.

## Sobre o projeto

O FitFlow é uma proposta de plataforma de bem-estar com conteúdos de yoga, pilates e mindfulness. O site apresenta a ideia do serviço e reúne informações sobre a equipe, depoimentos, planos ilustrativos e canais de contato.

O projeto é um protótipo acadêmico de front-end. Não possui servidor ou banco de dados; por isso, o formulário não envia mensagens e a seleção de planos não realiza pagamentos ou assinaturas.

## Páginas

- **Início (`index.html`):** apresentação do FitFlow, práticas de bem-estar, profissionais, depoimentos e chamada para conhecer os planos.
- **Planos (`venda.html`):** apresentação dos planos Essencial, Zen Pro e Imersão VIP, além de atalhos para dúvidas e outras opções.
- **Contato (`contatos.html`):** apresentação dos professores, formulário demonstrativo e perguntas frequentes.

## Tecnologias e recursos

- HTML5 para a estrutura das páginas.
- CSS3 para o layout e a apresentação visual.
- Google Fonts para tipografia.
- Imagens locais na pasta `img/`.
- GitHub Pages para hospedagem estática.

Não há etapa de compilação nem instalação de dependências. O site utiliza fontes externas do Google Fonts, que dependem de conexão com a internet para carregar.

## Estrutura do repositório

```text
.
├── index.html
├── venda.html
├── contatos.html
├── estilo.css
├── img/
└── Trabalho1 Landing Page.txt
```

## Visualização local

Abra `index.html` no navegador ou inicie um servidor local a partir da pasta raiz do projeto:

```bash
python3 -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Publicação no GitHub Pages

Os arquivos publicados ficam na raiz do repositório, com `index.html` como página inicial. Para ativar o site:

1. Envie os arquivos deste projeto para um repositório no GitHub.
2. No repositório, acesse **Settings > Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch que contém o projeto e a pasta **/(root)**; salve a configuração.
5. Aguarde a publicação e use o endereço exibido em **Settings > Pages**.

As alterações nos arquivos publicados serão disponibilizadas após o GitHub Pages concluir uma nova implantação.

## Equipe

Participantes e contribuições conforme o enunciado do trabalho:

- **Arthur Massambe Torres:** cabeçalho, banner, elementos informativos e componentes da página de planos.
- **Heitor Muniz Clemente de Oliveira:** conteúdo “Sobre nós” e depoimentos na página inicial.
- **José Carlos Albino Junior:** estruturação e navegação entre páginas, rodapés e conteúdo da página de planos.
- **Kathlyn Percínio Souza:** página de contato e perguntas frequentes.
- **Felipe João Alves Carneiro:** página de contato e perguntas frequentes.

## Contexto acadêmico

Este repositório registra um exercício introdutório de desenvolvimento web. A organização e a implementação refletem o aprendizado da equipe no primeiro semestre; recursos como formulários funcionais, integração de pagamentos e persistência de dados não fazem parte do escopo desta versão.