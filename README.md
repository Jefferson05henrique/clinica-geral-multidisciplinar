# Clínica Geral Multidisciplinar

## Visão geral
Este projeto é um site institucional para uma clínica multidisciplinar. A ideia principal é apresentar a marca da clínica, transmitir confiança ao paciente e fornecer informações rápidas sobre especialidades, profissionais, exames, localização e contato.

O site é construído com HTML, CSS e JavaScript puro, sem framework ou backend. Ele funciona como uma landing page profissional, com navegação simples e visual moderno.

---

## Objetivo do projeto
O objetivo é criar uma presença online clara e acessível para a clínica, permitindo que visitantes:

- conheçam a clínica e sua proposta;
- entendam suas especialidades;
- vejam os profissionais;
- identifiquem os exames disponíveis;
- encontrem formas de contato e agendamento;
- naveguem de forma responsiva em celular, tablet e desktop.

---

## Tecnologias utilizadas
- HTML5: estrutura do conteúdo das páginas.
- CSS3: layout, cores, responsividade, tipografia e elementos visuais.
- JavaScript: interações simples, principalmente o menu mobile.
- Google Fonts: utilização de fontes personalizadas para dar mais identidade visual ao projeto.
- Imagens locais: todos os ícones e fotos estão na pasta assets/img.

---

## Estrutura do projeto

```text
CLINICA/
├── index.html                 # Página inicial do site
├── README.md                  # Documentação do projeto
├── assets/
│   └── img/                  # Logos, ícones e imagens do site
├── css/
│   └── style.css             # Estilos gerais e responsividade
├── html/
│   ├── instituto.html        # Página “Sobre o Instituto”
│   ├── contato.html          # Página de contato (ainda vazia)
│   ├── especialista.html     # Página de especialistas (ainda vazia)
│   └── profissionais.html    # Página de profissionais (ainda vazia)
├── javascript/
│   └── menu.js               # Lógica do menu hambúrguer
├── sql/
│   └── (pasta vazia no momento)
└── .git/                     # Configuração do Git do projeto
```

---

## Arquivo por arquivo

### 1. index.html
É a página principal do site e concentra a maior parte da apresentação da clínica.

Ele contém:

- cabeçalho com logo e navegação;
- links para redes sociais;
- banner principal com chamada para ação;
- seção de missão, visão e valores;
- área de especialidades;
- área de exames;
- cards dos profissionais;
- formulário de contato;
- rodapé com informações da clínica.

Essa página é a “home” do projeto e funciona como porta de entrada para todo o conteúdo.

### 2. html/instituto.html
Essa página apresenta a história, a proposta e a localização da clínica.

Ela inclui:

- navegação igual à da home;
- destaque do instituto e seus valores;
- descrição institucional;
- endereço e mapa interativo com embed do Google Maps.

Essa página tem como objetivo reforçar a credibilidade da clínica.

### 3. html/contato.html
Arquivo criado mas ainda vazio. Ou seja, ainda não possui estrutura visual ou conteúdo final implementado.

### 4. html/especialista.html
Arquivo criado mas ainda vazio. Pode ser usado para uma futura página específica de especialistas ou de uma especialidade individual.

### 5. html/profissionais.html
Arquivo criado mas ainda vazio. Em um futuro desenvolvimento, ele pode abrigar a listagem completa dos profissionais com descrições e perfis.

### 6. css/style.css
Este é o arquivo mais importante do visual do projeto.

Ele faz:

- define a paleta de cores da clínica;
- importa fontes externas;
- faz o reset inicial dos elementos;
- estiliza o cabeçalho, menu, banner, cards, formulário e rodapé;
- cria a responsividade para celulares e tablets;
- adiciona o layout específico da página de “Sobre o Instituto”.

Em resumo, este arquivo controla toda a aparência da interface.

### 7. javascript/menu.js
Arquivo de interação simples.

Ele funciona assim:

- acessa o botão do menu hambúrguer;
- seleciona a lista de navegação;
- ao clicar, alterna a classe active para mostrar ou esconder o menu em dispositivos móveis.

Sem esse script, o menu responsivo não funciona corretamente.

### 8. assets/img
Pasta responsável por guardar as imagens utilizadas no site:

- logo;
- ícones de redes sociais;
- imagens de especialidades;
- fotos dos profissionais;
- imagens de exames e identidade visual da clínica.

### 9. sql/
A pasta está vazia no momento. Ela provavelmente foi reservada para armazenar scripts SQL, banco de dados ou estruturas de dados futuras.

---

## Como o site funciona

### Navegação principal
O cabeçalho possui links para:

- Home
- Sobre o Instituto
- Especialidades
- Exames
- Profissionais
- Contato

Esses itens ajudam o usuário a percorrer as principais áreas de informação da clínica.

### Banner inicial
A primeira seção da home é visualmente forte e tem objetivo comercial. Ela mostra:

- o nome da clínica;
- slogan ou mensagem principal;
- botão de ação para agendar consulta.

### Missão, Visão e Valores
A seção MVV apresenta os princípios da clínica, reforçando a imagem de cuidado, qualidade e acolhimento.

### Especialidades
A área de especialidades mostra as áreas de atendimento, como:

- Fisioterapia
- Nutrição
- Psicologia
- Pedagogia

Cada card visualmente comunica uma área de atuação.

### Exames
A seção de exames exibe uma imagem e um botão para visualizar todos os exames. Essa parte é visual e institucional, mas ainda não está conectada a um backend ou página detalhada de exames.

### Profissionais
Os profissionais são apresentados em cards com imagem, nome e área de atuação. Isso ajuda a transmitir credibilidade e a formação da equipe.

### Formulário de contato
O formulário é simples e está no front-end. Hoje ele:

- coleta nome, e-mail e mensagem;
- possui validação HTML básica com required;
- não envia dados para um servidor, pois não há backend configurado.

### Rodapé
O rodapé informa:

- endereço;
- contato telefônico;
- e-mail;
- horário de funcionamento;
- redes sociais;
- copyright.

---

## O que está funcionando no projeto hoje
- Layout da landing page principal concluído
- Navegação principal funcional
- Menu mobile com interação em JavaScript
- Página “Sobre o Instituto” com mapa
- Estilo visual completo e responsivo
- Estrutura de arquivos organizada

---

## O que ainda precisa ser finalizado
Existem alguns pontos que ainda precisam de ajuste para deixar o projeto mais profissional e pronto para uso real:

1. Páginas vazias
   - contato.html
   - especialista.html
   - profissionais.html

2. Links com dados de exemplo
   - Instagram, Facebook e WhatsApp usam URLs de exemplo ou placeholders.
   - O WhatsApp usa: wa.me/SEU_NUMERO

3. Formulário sem backend
   - O action do formulário está em # e não envia dado para nenhum serviço.

4. Link quebrado no rodapé
   - Existe referência a ./html/servicos.html, mas esse arquivo não existe no projeto.

5. SQL sem uso
   - A pasta sql está vazia e ainda não há integração com banco.

---

## Como abrir o projeto
Você pode abrir o arquivo `index.html` diretamente no navegador para visualizar o site.

Se quiser rodar em um servidor local mais profissional, pode usar:

```bash
python -m http.server 8000
```

Depois basta acessar:

```text
http://localhost:8000
```

---

## Dicas de melhoria futura
- criar as páginas de contato, profissionais e especialistas com conteúdo real;
- implementar envio de formulário por backend ou serviço externo;
- substituir textos e dados fictícios por informações reais da clínica;
- incluir páginas separadas para cada especialidade;
- configurar redes sociais e WhatsApp com contato oficial;
- criar estrutura de banco de dados se houver necessidade de agendamento ou cadastro.

---

## Resumo rápido
Este projeto é um site institucional em HTML/CSS/JS para uma clínica multidisciplinar. A estrutura está bem organizada, a home é completa e o visual está bem definido. O ponto principal de evolução é transformar as páginas em desenvolvimento em conteúdo real e conectar algumas áreas que ainda estão em versão mockada.

Se você quiser, no próximo passo posso também criar uma versão aprimorada deste README com:

- documentação técnica mais detalhada;
- guia de manutenção do código;
- checklist de melhorias do projeto;
- documentação para entregar ao cliente ou para portfolio.
