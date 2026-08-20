# WayFinder
A WayFinder analisou por muitos anos como melhorar a experiência dos alunos e visitantes em uma universidade.
# 🧭 WayFinder

> Sistema interativo de orientação e navegação desenvolvido para facilitar a localização de ambientes dentro de uma universidade.

O **WayFinder** foi criado para melhorar a experiência de alunos, visitantes e demais usuários que precisam encontrar salas e espaços dentro do campus. A aplicação apresenta uma planta interativa do prédio e permite localizar ambientes, visualizar rotas e acompanhar o percurso até o destino.

## ✨ Funcionalidades

* 🗺️ **Mapa interativo** da universidade
* 🏢 **Navegação entre andares**
* 🔎 **Busca de salas e ambientes**
* 🏷️ **Filtros por categoria**
* 📍 Indicador de **"Você está aqui"**
* 🧭 **Cálculo e exibição de rotas**
* 🚶 **Animação do percurso** até o destino
* ♿ **Modo de acessibilidade**
* 🌙 **Tema claro e escuro**
* 🕐 **Relógio em tempo real**
* 🖥️ **Modo totem**, com retorno automático à tela inicial após um período sem interação

## 🎯 Objetivo

O principal objetivo do WayFinder é tornar a circulação dentro da universidade mais simples e intuitiva.

Em vez de depender de placas ou pedir informações para encontrar determinado ambiente, o usuário pode pesquisar o local desejado e visualizar no mapa o caminho necessário para chegar até ele.

## 🗺️ Como funciona

1. O usuário acessa o WayFinder.
2. Pesquisa uma sala ou ambiente ou utiliza os filtros disponíveis.
3. O sistema identifica o local correspondente.
4. O ambiente é destacado no mapa.
5. O WayFinder calcula o percurso a partir da posição atual.
6. A rota é apresentada visualmente no mapa.
7. Quando necessário, o sistema orienta a mudança de andar.
8. No modo de animação, um indicador acompanha visualmente o percurso até o destino.

O sistema também possui um modo de espera para utilização em totens: depois de um período sem interação, a interface retorna à tela inicial para o próximo visitante.

## ♿ Acessibilidade

O projeto conta com um modo específico de acessibilidade. Quando ativado, a visualização da rota é adaptada para facilitar sua identificação e o sistema pode reproduzir o percurso de forma visual.

A aplicação também permite navegação por teclado em determinados controles da interface.

## 🏫 Estrutura do mapa

Os ambientes são organizados por:

* Andar
* Bloco
* Categoria
* Nome
* Identificação da sala

Entre os tipos de ambientes representados estão salas de aula, laboratórios, auditório, banheiros e saídas de emergência.

## 🛠️ Tecnologias

O projeto foi desenvolvido utilizando tecnologias web, com a aplicação concentrada no arquivo principal:

* **HTML5** — estrutura da aplicação
* **CSS3** — interface, temas e responsividade visual
* **JavaScript** — lógica, busca, filtros, mapa, rotas e animações
* **SVG** — representação e renderização do mapa e das rotas

## 📂 Estrutura do projeto

```text
WayFinder/
├── index.html
└── README.md
```

O `index.html` concentra a interface, estilos e lógica necessários para o funcionamento da aplicação.

## 🚀 Como executar

Como o projeto é baseado em tecnologias web e possui um arquivo `index.html`, pode ser executado localmente de forma simples.

### 1. Clone o repositório

```bash
git clone https://github.com/yzgabriel/WayFinder.git
```

### 2. Entre na pasta

```bash
cd WayFinder
```

### 3. Abra o projeto

Abra o arquivo `index.html` em um navegador moderno.

Também é possível utilizar uma extensão de servidor local, como o Live Server, durante o desenvolvimento.

## 🔗 Repositório

[GitHub — WayFinder](https://github.com/yzgabriel/WayFinder)

## 📌 Status

**Em desenvolvimento.**

O projeto pode receber novas funcionalidades, melhorias de interface, ajustes no mapa e aprimoramentos de acessibilidade.

## 👨‍💻 Autor

Desenvolvido pela equipe **WayFinder**.

---

⭐ Se este projeto foi útil ou interessante para você, considere deixar uma estrela no repositório.
!!**gerado via claude para fins educacionais**!!
