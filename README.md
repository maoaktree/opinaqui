## Opinaqui 📝

# Opinaqui: Aplicativo para realização de pesquisas de campo sem conexão com a internet.
O Opinaqui é uma plataforma para pesquisas de campo. Com ele você pode realizar suas entrevistas mesmo sem conexão com a internet. Com uma interface bastante amigável, o Opinaqui armazena todos os questionários preenchidos no próprio dispositivo, permitindo a sincronização com a nuvem apenas quando houver conexão. Otimize!

## Tecnologias Utilizadas
Linguagem: Dart

Framework: Flutter

Arquitetura: Clean Architecture

Gerenciamento de Estado: Riverpod (uma biblioteca de gerenciamento de estado que detecta erros de programação em tempo de compilação e não em tempo de execução, remove o aninhamento para ouvir/combinar objetos, garante que o código seja testável).

Banco de Dados: Drift (biblioteca de persistência reativa para Flutter e Dart, construída sobre sqlite. Flexível, rico em recursos, modular, seguro, rápido, reativo e com suporte multiplataforma).

## Funcionalidades
Inserção do Questionário: Através da leitura do código UUID ou QR Code, fornecido no servidor do cliente, os dados do questionário são enviados para o App através da API.
Gestão de Questionários: Dentro do app, é possível inserir diversos questionários, repondê-los - armazenando os dados das entrevistas realizadas e sincronizando esses dados coletados com o servidor.
Atualização em Tempo Real: Utilizando Riverpod para atualização das telas que fazem as pesquisas de maneira interativa e dinâmica.

## Processo de Desenvolvimento
O desenvolvimento do Opinaqui foi estruturado em várias etapas que incluíram:

Planejamento: Identificando as necessidades do usuário, planejando as funcionalidades e o design.

Design de Arquitetura: Implementação da Clean Architecture para garantir um código escalável e manutenível.

Integração com API: Desenvolvimento da funcionalidade de inserção do código UUID e consumo da API para puxar os dados do formulário cadastrado no software WEB.

Gestão de Estado: Utilização da biblioteca Riverpod para gerenciar o estado do aplicativo e permitir atualizações em tempo real nas telas e otimização das respostas durante o preenchimento dos questionários.

Banco de Dados: Utilização do Drift com o pacote drift do Flutter para gerenciamento de dados.

Testes e Otimização: Testes de funcionalidades e otimização do desempenho.

Lançamento: Preparação e lançamento do aplicativo na Play Store.

## Habilidades Adquiridas
O desenvolvimento do Opinaqui permitiu-me adquirir e aprimorar várias habilidades, incluindo:

Proficiência em Dart e Flutter.
Experiência na implementação da Clean Architecture.
Gerenciamento de estado com Riverpod.
Integração de APIs e gerenciamento de dados em tempo real.
Planejamento e execução de um projeto de aplicativo completo.

## Conheça o App
Opinaqui está disponível na Play Store. Baixe agora e experimente uma nova era no gerenciamento de eventos e controle de portaria.

[![Play Store](https://img.shields.io/badge/Play%20Store-%230077B5.svg?logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=br.com.opinaqui.off.app)

---
## 👤 Autora

Mari de Carvalho, desenvolvedora Mobile.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/maridecarvalho)
