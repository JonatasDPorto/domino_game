# Documento de Requisitos - Jogo de Dominó

## 1. Visão Geral
O objetivo deste projeto é desenvolver um jogo de dominó online que permita aos jogadores competir entre si em partidas normais ou em campeonatos. O jogo terá funcionalidades de gerenciamento de amigos, criação de salas privadas, e um sistema de ranking baseado em troféus. O usuário começa com uma quantidade inicial de dinheiro virtual que pode ser usado para participar de partidas e campeonatos.

## 2. Requisitos Funcionais

### 2.1. Gerenciamento de Amigos
- **Adicionar Amigos**: O usuário deve ser capaz de adicionar outros usuários como amigos, seja por nome de usuário ou ID único.
- **Remover Amigos**: O usuário deve ser capaz de remover amigos de sua lista.
- **Listar Amigos**: O usuário deve ter a capacidade de visualizar a lista de amigos adicionados.

### 2.2. Criação e Gerenciamento de Salas
- **Criar Sala Privada com Código**: O usuário pode criar uma sala privada que gera um código único. Este código pode ser compartilhado para que outros jogadores possam entrar na sala.
- **Adicionar Bots à Sala**: O criador da sala deve ter a opção de adicionar bots para preencher lugares vagos.
- **Copiar Código da Sala**: O código da sala privada pode ser copiado para a área de transferência para facilitar o compartilhamento.
- **Chamar Amigo para Sala**: O criador da sala pode convidar amigos da sua lista de amigos para se juntar à sala privada.

### 2.3. Modo Campeonato
- **Criação de Campeonatos**: O sistema deve permitir a criação de campeonatos com diferentes níveis de dificuldade. Cada nível tem um custo de entrada e oferece uma quantidade diferente de troféus como recompensa.
- **Entrada em Campeonatos**: O usuário pode gastar seu dinheiro virtual para entrar em campeonatos.
- **Ganho de Troféus**: Cada vitória em uma partida de campeonato concede troféus ao usuário. O número de troféus depende do nível de dificuldade do campeonato.
- **Ranking por Troféus**: Os usuários são classificados em um ranking global com base no número total de troféus acumulados.
- **Custos de Entrada**: Cada campeonato tem um custo de entrada em dinheiro virtual, variando conforme a dificuldade.

### 2.4. Economia do Jogo
- **Dinheiro Inicial**: Cada usuário começa o jogo com 10.000 unidades de dinheiro virtual.
- **Ganhos em Partidas**: As partidas, tanto normais quanto de campeonato, oferecem prêmios em dinheiro virtual. A quantidade varia com base no tipo e nível da partida.
- **Gastos em Campeonatos**: O usuário pode gastar dinheiro virtual para entrar em campeonatos, com diferentes custos dependendo da dificuldade.
- **Compra de Moedas**: O usuário pode comprar moedas adicionais com dinheiro real através de uma loja integrada ao jogo.

## 4. Requisitos de Implementação

### 4.1. Plataforma
- **Multiplataforma**: O jogo deve ser desenvolvido para funcionar em dispositivos móveis (iOS, Android).

### 4.2. Integrações
- **Sistema de Autenticação**: Implementar autenticação de usuários via e-mail/senha ou login social (Google, Facebook).
- **Notificações**: Notificações push para eventos importantes, como convites para partidas ou campeonatos.
