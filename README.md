# Dra. Paula Fabiana Barbosa — Odontologia

Site institucional de apresentação do consultório da Dra. Paula Fabiana Barbosa, com foco em odontologia estética, reabilitação oral e agendamento de consultas.

## Visão geral

A página apresenta a profissional, destaca os principais tratamentos odontológicos e oferece atalhos para contato pelo WhatsApp. O layout utiliza uma identidade visual elegante, com tons azul-marinho, dourado e fundo claro.

## Funcionalidades

- Seção inicial (*hero*) com chamada para agendamento e indicadores de experiência.
- Apresentação de especialidades odontológicas:
  - Lentes de contato dental;
  - Implantes dentários;
  - Harmonização facial;
  - Reabilitação oral.
- Seção de diferenciais, incluindo planejamento 3D, naturalidade, durabilidade e atendimento humanizado.
- Seção “Sobre” com apresentação da dentista.
- Lista adicional de serviços odontológicos.
- Botões de agendamento que direcionam para o WhatsApp.
- Botão flutuante do WhatsApp.
- Perguntas frequentes expansíveis.
- Mapa incorporado do Google Maps e link para abrir a localização.
- Links para Instagram, Facebook e política de privacidade.
- Metadados para mecanismos de busca e compartilhamento em redes sociais.
- Dados estruturados JSON-LD com informações do consultório.
- Ajustes responsivos para diferentes tamanhos de tela.
- Recurso de acessibilidade para pular diretamente ao conteúdo principal.

## Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo da página.
- **CSS3** — layout, identidade visual, animações e responsividade.
- **Google Fonts** — fontes Montserrat e Spectral.
- **Font Awesome 6.5.1** — ícones.
- **Google Maps** — mapa incorporado.
- **WhatsApp** — canal de contato e agendamento.
- **Schema.org / JSON-LD** — dados estruturados para mecanismos de busca.

O arquivo `index.html` inclui estilos CSS internos e carrega também folhas de estilo e um arquivo JavaScript externos.

## Estrutura de arquivos esperada

```text
projeto/
├── index.html
├── accessibility.css
├── specialties.css
├── site.js
├── dr-fabiana.png
├── politicadeprivacidade.html
└── assets/
    └── especialidades/
        ├── lentes.png
        ├── implantes.png
        ├── harmonizacao.png
        └── reabilitacao.png
```

**Importante:** os arquivos CSS, JavaScript e as imagens listados acima são referenciados pelo HTML, mas precisam estar presentes nos caminhos indicados para que todos os recursos funcionem corretamente. A imagem principal do banner é carregada de uma URL externa do GitHub.

## Como executar localmente

O projeto é uma página estática e não exige banco de dados ou etapa de compilação.

1. Coloque `index.html` e os arquivos relacionados na estrutura de pastas indicada acima.
2. Abra `index.html` diretamente no navegador.

Para testar usando um servidor local, entre na pasta do projeto e execute:

```bash
python -m http.server 8000
```

Depois, acesse:

<http://localhost:8000>

O comando requer Python instalado. Um servidor local costuma facilitar os testes de carregamento de arquivos e caminhos relativos.

## Personalização

Antes de publicar ou reutilizar o site, revise:

- **Contato:** telefone e link do WhatsApp, inclusive a mensagem pré-preenchida.
- **Endereço:** endereço exibido, mapa incorporado e coordenadas presentes nos dados estruturados.
- **Informações profissionais:** nome, formação, especialidades e indicadores de experiência.
- **Imagens:** confirme que as imagens existem, têm autorização de uso e correspondem ao conteúdo apresentado.
- **Redes sociais:** URLs do Instagram e Facebook.
- **Política de privacidade:** confirme que `politicadeprivacidade.html` existe e contém o texto adequado.
- **SEO:** título, descrição, URL canônica, imagem de compartilhamento e dados JSON-LD.
- **Horários e serviços:** confira se as informações exibidas estão atualizadas.

Os dados de endereço, contato, horários e serviços estão escritos diretamente no HTML. Ao alterá-los, atualize também os metadados e o JSON-LD para evitar informações divergentes.

## Acessibilidade e experiência do usuário

O HTML inclui idioma `pt-BR`, textos alternativos em imagens, rótulos acessíveis em links relevantes, foco no link “Pular para o conteúdo principal” e perguntas frequentes com elementos nativos `<details>` e `<summary>`. As folhas de estilo externas também fazem parte da apresentação e devem ser mantidas junto ao projeto.

## Publicação

Por ser um site estático, pode ser hospedado em um serviço que ofereça hospedagem de arquivos HTML, CSS, JavaScript e imagens, ou em um servidor web convencional.

Antes de publicar:

1. Teste a página em celular, tablet e computador.
2. Verifique links, imagens, WhatsApp, mapa e redes sociais.
3. Confirme que todos os arquivos locais foram enviados.
4. Valide as informações de contato e os dados estruturados.
5. Revise a política de privacidade e as informações profissionais.
6. Verifique se a URL canônica corresponde ao domínio final.

## Observações

- A página carrega fontes e ícones de serviços externos; esses recursos dependem de conexão com a internet.
- O mapa é incorporado a partir do Google Maps.
- O botão do WhatsApp abre uma conversa com o número configurado no link.
- Este README descreve a estrutura observada em `index.html`. O comportamento completo de `site.js`, `accessibility.css` e `specialties.css` depende do conteúdo desses arquivos.
