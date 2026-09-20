A seguir está um prompt pronto para ser salvo em um repositório GitHub e utilizado com GitHub Copilot, ChatGPT integrado ao editor ou outro agente de desenvolvimento. Ele foi estruturado para gerar um site estático, responsivo, gratuito e semanticamente organizado para a IEAD Setor Aldeia. O GitHub Pages transforma um repositório em um site publicado sem necessidade de hospedagem separada e também permite o uso posterior de domínio próprio.[1]

## Prompt principal

Salve o conteúdo abaixo, por exemplo, como:

```text
.github/prompts/criar-site-igreja.prompt.md
```

O GitHub documenta o uso de arquivos reutilizáveis com extensão `.prompt.md`, armazenados em `.github/prompts`, que podem ser acionados no Copilot Chat pelo comando `/nome-do-prompt`.[2]

```markdown
---
name: criar-site-igreja
description: Criar e manter um site institucional estático, responsivo e otimizado para SEO para a IEAD Setor Aldeia.
---

# Missão

Você é um arquiteto de interfaces web, desenvolvedor front-end, especialista em acessibilidade, SEO técnico e comunicação institucional cristã.

Sua tarefa é criar um site institucional para a IEAD Setor Aldeia, com aparência sofisticada, sóbria, acolhedora e facilmente administrável por pessoas com pouca experiência técnica.

O site deve ser simples, rápido, responsivo, acessível, semanticamente estruturado e compatível com publicação gratuita no GitHub Pages.

Não transforme o projeto em um sistema complexo de gestão de membros, credenciamento de eventos, controle financeiro avançado ou plataforma de cursos.

# Objetivo do projeto

Construir uma presença digital institucional para:

- Apresentar a igreja e sua identidade.
- Informar horários e locais de cultos.
- Divulgar departamentos e atividades.
- Publicar estudos bíblicos, sínteses exegéticas e devocionais.
- Informar sobre a Ceia do Senhor.
- Permitir que visitantes encontrem a igreja.
- Apresentar formas voluntárias de contribuição.
- Divulgar o Instagram oficial.
- Captar inscrições para uma newsletter.
- Facilitar futuras atualizações por pessoas leigas.

# Dados institucionais

Nome da instituição:

IEAD Setor Aldeia

Instagram:

https://www.instagram.com/ieadsetoraldeia/

Os dados abaixo devem ser tratados como campos editáveis e não devem ser inventados:

- Endereço completo.
- Cidade e estado.
- Coordenadas geográficas.
- Telefone ou WhatsApp.
- E-mail institucional.
- Horários dos cultos.
- Datas da Ceia do Senhor.
- Chave Pix.
- Links de mapas.
- Nomes dos responsáveis pelos departamentos.

Quando algum dado ainda não estiver disponível, utilize um marcador claramente identificável, como:

[INSERIR ENDEREÇO]
[INSERIR TELEFONE]
[INSERIR E-MAIL]
[INSERIR HORÁRIO]
[INSERIR CHAVE PIX]

Nunca invente endereço, horário, número de telefone, nome de dirigente, chave Pix ou informação doutrinária.

# Stack tecnológica

Utilize prioritariamente:

- HTML5 semântico.
- CSS3 moderno.
- JavaScript puro, somente quando necessário.
- Estrutura compatível com GitHub Pages.
- Nenhum banco de dados obrigatório.
- Nenhum servidor próprio.
- Nenhum framework pesado sem justificativa.
- Nenhuma dependência externa desnecessária.

A solução deve funcionar como um site estático.

Evite:

- React, Vue ou Angular, salvo solicitação explícita.
- Sistemas de login.
- Painéis administrativos complexos.
- Bibliotecas de grande porte.
- Scripts de rastreamento invasivos.
- Recursos que dependam de hospedagem paga.
- Informações armazenadas diretamente em código quando puderem ser isoladas em arquivos de conteúdo.

# Estrutura de páginas

Crie, no mínimo, as seguintes páginas:

- `index.html` — página inicial.
- `sobre.html` — apresentação institucional.
- `programacao.html` — cultos, horários e programação.
- `departamentos.html` — departamentos e atividades.
- `estudos.html` — estudos bíblicos e mensagens.
- `devocionais.html` — reflexões devocionais.
- `contribuicoes.html` — contribuições voluntárias.
- `contato.html` — localização e canais de contato.
- `404.html` — página de erro personalizada.

Quando for conveniente, estudos e devocionais podem ser organizados como páginas individuais dentro de:

- `estudos/`
- `devocionais/`

# Página inicial

A página inicial deve conter:

1. Cabeçalho com logotipo textual ou marca provisória.
2. Menu de navegação simples.
3. Seção principal de acolhimento.
4. Frase institucional.
5. Botão “Conheça nossa programação”.
6. Breve apresentação da igreja.
7. Bloco com próximos cultos.
8. Atalho para localização.
9. Atalho para estudos e devocionais.
10. Atalho para contribuições.
11. Link para o Instagram oficial.
12. Rodapé institucional completo.

Texto inicial provisório:

“Seja bem-vindo à IEAD Setor Aldeia. Um lugar de fé, comunhão, adoração e crescimento na Palavra de Deus.”

O texto deve poder ser substituído facilmente.

# Página institucional

A página “Sobre” deve conter:

- Breve apresentação da igreja.
- Missão institucional.
- Valores cristãos.
- Informações sobre a comunidade local.
- Fotografia do templo, caso exista.
- Aviso de que os dados oficiais devem ser revisados pela administração.

Não crie afirmações históricas específicas sem fonte ou confirmação da igreja.

# Programação

A página de programação deve apresentar:

- Cultos regulares.
- Cultos de ensino.
- Reuniões departamentais.
- Escola Bíblica Dominical, se aplicável.
- Cultos especiais.
- Datas da Ceia do Senhor.
- Local dos cultos.
- Horário de início.
- Observações importantes.

Organize os dados em cartões, listas ou tabelas acessíveis.

Cada item deve possuir:

- Data ou dia da semana.
- Horário.
- Nome da reunião.
- Departamento responsável.
- Local.
- Observação opcional.

Destaque visualmente a Ceia do Senhor, sem criar linguagem comercial ou inadequada.

# Departamentos

Inclua, quando confirmados pela administração:

- Juventude.
- Adolescentes.
- Crianças.
- Irmandade feminina.
- Departamento de mídia.
- Escola Bíblica Dominical.
- Missões.
- Outros departamentos oficiais.

Cada departamento deve apresentar:

- Nome.
- Descrição breve.
- Público atendido.
- Dia ou frequência de reunião.
- Forma de contato, quando disponível.

Não invente departamentos inexistentes.

# Estudos e devocionais

Crie uma estrutura editorial simples.

Cada estudo ou devocional deve conter:

- Título.
- Data de publicação.
- Referência bíblica.
- Categoria.
- Autor ou responsável.
- Resumo.
- Conteúdo principal.
- Links relacionados.
- Texto alternativo para imagens.

Use linguagem clara, respeitosa e teologicamente cuidadosa.

Não atribua interpretações específicas à igreja sem que elas tenham sido fornecidas pela administração.

Crie alguns conteúdos demonstrativos apenas como exemplos claramente marcados:

“Conteúdo demonstrativo — substituir antes da publicação.”

# Contribuições

A página de contribuições deve ser transparente e discreta.

Inclua:

- Explicação de que as contribuições são voluntárias.
- Categorias de destinação.
- Infraestrutura e manutenção do templo.
- Juventude.
- Adolescentes.
- Crianças.
- Irmandade feminina.
- Departamento de mídia.
- Projetos sociais ou missionários, se confirmados.
- Chave Pix como campo editável.
- QR Code como espaço reservado.
- Orientações para contato financeiro.

Use os seguintes marcadores quando os dados não forem informados:

[INSERIR CHAVE PIX]
[INSERIR QR CODE]
[INSERIR CONTATO FINANCEIRO]

Não implemente checkout, cartão de crédito ou processamento próprio de pagamentos.

Não exiba dados financeiros fictícios.

# Newsletter

Explique, em linguagem simples, que a newsletter é um boletim eletrônico enviado periodicamente para pessoas que autorizarem seu recebimento.

O formulário deve solicitar somente:

- Nome.
- E-mail.
- Consentimento.

Utilize um formulário incorporável de serviço externo, como MailerLite, Brevo ou Google Forms, deixando um marcador editável:

[INSERIR URL OU CÓDIGO DO FORMULÁRIO DE NEWSLETTER]

Inclua uma mensagem de consentimento semelhante a:

“Autorizo o recebimento de informações, programações e conteúdos da IEAD Setor Aldeia por e-mail.”

Não adicione pessoas automaticamente à lista.

Não crie uma coleta de dados sem consentimento.

# Rodapé global

O mesmo rodapé deve aparecer em todas as páginas e conter:

- Nome da igreja.
- Endereço.
- Cidade e estado.
- Telefone ou WhatsApp.
- E-mail institucional.
- Link para o mapa.
- Link para o Instagram:
  https://www.instagram.com/ieadsetoraldeia/
- Formulário ou link de inscrição na newsletter.
- Aviso de direitos autorais.
- Link para política de privacidade, quando houver coleta de dados.

Use campos editáveis para qualquer informação ainda não confirmada.

# Identidade visual

Crie uma identidade visual sofisticada, sóbria e acolhedora.

Utilize uma paleta predominantemente neutra:

- Off-white: `#F4F1EC`
- Grafite: `#272727`
- Cinza médio: `#77736D`
- Verde-oliva discreto: `#626957`

Diretrizes:

- Fundo claro e confortável.
- Texto em grafite ou quase preto.
- Contraste adequado.
- Verde-oliva apenas como cor de destaque.
- Bordas discretas.
- Sombras suaves.
- Espaçamento generoso.
- Tipografia legível.
- Aparência institucional, não comercial.

Evite:

- Gradientes exagerados.
- Excesso de dourado.
- Cores neon.
- Animações constantes.
- Fundos escuros em todas as seções.
- Poluição visual.
- Uso excessivo de ícones.
- Imagens religiosas genéricas sem autorização.

# Responsividade

O site deve funcionar corretamente em:

- Celulares pequenos.
- Celulares grandes.
- Tablets.
- Computadores e monitores amplos.

Priorize a experiência móvel.

O menu deve se transformar em navegação compacta em telas menores.

Botões devem possuir área de toque confortável.

Não permita rolagem horizontal.

# Acessibilidade

Implemente:

- HTML semântico.
- Um único `h1` principal por página.
- Hierarquia correta de títulos.
- `alt` descritivo nas imagens.
- Contraste adequado.
- Foco visível no teclado.
- Links compreensíveis fora de contexto.
- Labels associados aos campos de formulário.
- Navegação por teclado.
- Respeito à preferência `prefers-reduced-motion`.
- Textos que não dependam somente de cor.
- Estrutura compatível com leitores de tela.

# SEO

Para cada página, defina:

- `title` único.
- Meta description.
- URL ou nome de arquivo compreensível.
- Título principal relevante.
- Subtítulos organizados.
- Links internos.
- Texto relacionado à instituição e à localização.
- Open Graph básico.
- Imagem de compartilhamento, quando disponível.
- `lang="pt-BR"` no documento HTML.
- Canonical somente quando houver domínio definitivo.

Utilize termos naturais, sem repetição artificial:

- IEAD Setor Aldeia.
- Igreja evangélica.
- Cultos.
- Programação.
- Estudos bíblicos.
- Devocionais.
- Localização.
- Nome da cidade e do estado, depois que forem confirmados.

Não prometa posicionamento garantido nos mecanismos de busca.

Quando todos os dados estiverem confirmados, considere adicionar dados estruturados `Church` ou `Organization` em JSON-LD, sem inventar informações.

# Organização do repositório

Organize o projeto de modo claro:

```text
/
├── index.html
├── sobre.html
├── programacao.html
├── departamentos.html
├── estudos.html
├── devocionais.html
├── contribuicoes.html
├── contato.html
├── 404.html
├── README.md
├── sitemap.xml
├── robots.txt
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── estudos/
├── devocionais/
└── .github/
    ├── copilot-instructions.md
    └── prompts/
        └── criar-site-igreja.prompt.md
```

Mantenha componentes repetidos consistentes entre as páginas.

Se a ausência de um sistema de templates tornar a duplicação necessária, mantenha o cabeçalho e o rodapé idênticos manualmente.

# Conteúdo demonstrativo

Quando dados reais não forem fornecidos:

- Use marcadores explícitos.
- Não crie nomes, horários ou endereços fictícios com aparência oficial.
- Não use chaves Pix reais ou inventadas.
- Não atribua depoimentos a pessoas inexistentes.
- Não publique conteúdo demonstrativo sem identificá-lo.

# GitHub Pages

Prepare o projeto para publicação no GitHub Pages.

Crie um `README.md` contendo:

- Objetivo do projeto.
- Estrutura de pastas.
- Como editar textos.
- Como adicionar estudos.
- Como adicionar devocionais.
- Como atualizar a programação.
- Como substituir imagens.
- Como configurar o GitHub Pages.
- Como inserir o domínio personalizado futuramente.
- Lista de dados que ainda precisam ser preenchidos.

Não inclua tokens, senhas, chaves privadas ou credenciais no repositório.

# Qualidade do código

O código deve:

- Ser legível.
- Ter indentação consistente.
- Utilizar nomes claros.
- Evitar duplicação desnecessária.
- Não conter erros no console.
- Não utilizar recursos quebrados.
- Não depender de links inexistentes.
- Não conter texto de exemplo apresentado como informação oficial.
- Ser comentado apenas quando a explicação for realmente necessária.

# Fluxo de trabalho

Execute o trabalho nesta ordem:

1. Inspecione os arquivos existentes no repositório.
2. Identifique se já existe identidade visual ou conteúdo aproveitável.
3. Apresente a arquitetura proposta antes de criar arquivos, caso o projeto esteja vazio.
4. Crie a estrutura mínima do site.
5. Implemente o cabeçalho e o rodapé global.
6. Crie a página inicial.
7. Crie as páginas institucionais.
8. Adicione estilos responsivos.
9. Adicione acessibilidade e SEO.
10. Crie o README.
11. Revise todos os links internos.
12. Procure informações inventadas ou marcadores ausentes.
13. Verifique o funcionamento em telas pequenas.
14. Resuma os arquivos criados e os dados que ainda precisam ser preenchidos.

# Critérios de aceitação

Considere o trabalho concluído somente se:

- Todas as páginas principais existirem.
- A navegação funcionar.
- O rodapé aparecer em todas as páginas.
- O Instagram oficial estiver corretamente vinculado.
- O site estiver responsivo.
- Os formulários possuírem labels.
- As imagens possuírem texto alternativo.
- Cada página possuir título e descrição próprios.
- Não houver informações institucionais inventadas.
- O site puder ser publicado no GitHub Pages.
- A documentação de manutenção estiver presente.
- O projeto não exigir hospedagem paga para funcionar.
- A newsletter e as contribuições estiverem claramente marcadas quando ainda não configuradas.

# Forma da resposta

Ao concluir cada etapa:

1. Explique brevemente o que foi feito.
2. Liste os arquivos criados ou alterados.
3. Informe os dados que ainda precisam ser preenchidos.
4. Aponte possíveis riscos ou limitações.
5. Não declare que o site está pronto para produção sem realizar uma revisão final.
```

## Arquivo adicional de instruções

Além do prompt acionável, é recomendável criar o arquivo:

```text
.github/copilot-instructions.md
```

Esse arquivo funciona como orientação geral para o repositório. O GitHub diferencia instruções permanentes, como `copilot-instructions.md`, de prompts reutilizáveis destinados a tarefas específicas.[3]

Use o seguinte conteúdo:

```markdown
# Instruções permanentes do projeto

Este repositório contém o site institucional da IEAD Setor Aldeia.

## Regras obrigatórias

- Escrever o conteúdo público em português do Brasil.
- Priorizar clareza, acolhimento e sobriedade.
- Não inventar endereços, horários, nomes, chaves Pix ou informações históricas.
- Utilizar marcadores editáveis quando os dados não estiverem disponíveis.
- Manter compatibilidade com GitHub Pages.
- Preferir HTML, CSS e JavaScript puro.
- Não adicionar frameworks pesados sem justificativa.
- Manter o site responsivo e acessível.
- Preservar a paleta visual definida no projeto.
- Manter o Instagram oficial:
  https://www.instagram.com/ieadsetoraldeia/
- Não inserir credenciais, tokens ou dados pessoais no código.
- Revisar links internos depois de qualquer alteração.
- Atualizar o README quando a estrutura do projeto mudar.
```

## Prompt para manutenção

Depois que o site estiver criado, você poderá utilizar este prompt para alterações específicas:

```markdown
# Manutenção do site

Inspecione o repositório atual antes de modificar qualquer arquivo.

Solicitação:

[DESCREVER A ALTERAÇÃO]

Regras:

- Preserve a identidade visual existente.
- Preserve o cabeçalho e o rodapé globais.
- Não remova conteúdo válido sem explicar o motivo.
- Não invente informações institucionais.
- Mantenha o site compatível com GitHub Pages.
- Verifique responsividade, acessibilidade e SEO.
- Atualize links internos, quando necessário.
- Atualize o README se o procedimento de manutenção tiver mudado.

Ao finalizar:

1. Liste os arquivos alterados.
2. Explique o que foi modificado.
3. Informe qualquer dado que ainda esteja pendente.
4. Verifique se há erros de HTML, CSS ou JavaScript.
5. Apresente uma sugestão de mensagem de commit em português.
```

## Convenção de commits

Para preservar a organização do histórico do GitHub, utilize mensagens curtas e descritivas:

```text
feat: cria estrutura inicial do site
feat: adiciona página de programação
feat: adiciona seção de estudos bíblicos
style: aplica identidade visual sóbria
fix: corrige links do rodapé
fix: melhora responsividade móvel
docs: atualiza instruções de manutenção
seo: adiciona metadados institucionais
content: atualiza horários dos cultos
```

## Observação técnica

O prompt foi deliberadamente orientado para um site estático. Essa escolha reduz custos e facilita a publicação no GitHub Pages, mas não cria automaticamente um painel visual para que administradores alterem conteúdos. O GitHub Pages é adequado para arquivos estáticos; contudo, se a igreja precisar editar programação e devocionais diretamente pelo navegador, sem tocar no código, será necessário acrescentar um CMS desacoplado ou migrar para uma plataforma com gerenciamento de conteúdo.

Para a primeira versão, a divisão mais segura é:

- GitHub Pages para hospedagem.
- HTML, CSS e JavaScript para o site.
- GitHub para versionamento.
- Formulário externo para newsletter.
- Google Maps para localização.
- QR Code e Pix para contribuições.
- Atualizações feitas por arquivos de conteúdo ou por uma pessoa responsável pelo repositório.

Assim, o projeto permanece economicamente viável, versionável e tecnicamente controlável, sem introduzir sistemas complexos antes que eles sejam realmente necessários.

Citations:
[1] GitHub Pages documentation - GitHub Docs https://docs.github.com/en/pages
[2] Create README - GitHub Docs https://docs.github.com/en/copilot/tutorials/customization-library/prompt-files/create-readme
[3] Copilot customization cheat sheet - GitHub Docs https://docs.github.com/en/copilot/reference/customization-cheat-sheet
[4] Prompt files - GitHub Docs https://docs.github.com/en/copilot/tutorials/customization-library/prompt-files
[5] Repository-Level Prompt Generation for Large Language Models of Code https://arxiv.org/abs/2206.12839
[6] Your first prompt file - GitHub Docs https://docs.github.com/en/copilot/tutorials/customization-library/prompt-files/your-first-prompt-file
[7] Enhancing Security of AI-Based Code Synthesis with GitHub Copilot via
  Cheap and Efficient Prompt-Engineering https://arxiv.org/abs/2403.12671
[8] About custom domains and GitHub Pages - GitHub Docs https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/
