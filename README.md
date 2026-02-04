# Fundo Mágico

Projeto desenvolvido durante a imersão **"Do 0 ao programador contratado"** do canal **Dev em Dobro**.

O **Fundo Mágico** é uma aplicação web interativa que permite aos usuários descreverem um estilo de background e, através de integração com IA, gera automaticamente o código HTML e CSS correspondente, exibindo uma prévia em tempo real.

## Funcionalidades

- **Input Descritivo:** Campo para o usuário digitar o tipo de fundo que deseja (ex: "Um gradiente suave entre amarelo e lilás").
- **Integração com IA (n8n):** Conexão via Webhook para processar a descrição e retornar os estilos.
- **Preview Dinâmico:** O background gerado é aplicado instantaneamente na tela de visualização.
- **Gerador de Código:** Exibe os códigos HTML e CSS prontos para serem copiados.

## Tecnologias Utilizadas

  - HTML5
  - CSS3 (com Reset e Responsividade)
  - JavaScript
  - **n8n:** Plataforma de automação de fluxo de trabalho (Workflow Automation) utilizada para criar o Webhook que conecta o front-end à inteligência artificial.
