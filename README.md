Desafio DIO – Phishing Facebook (Ambiente Educacional)

Este repositório faz parte de um desafio educacional da DIO, com o objetivo de compreender como funcionam ataques de engenharia social, especificamente phishing, utilizando ferramentas de segurança ofensiva em ambiente controlado.

Aviso:
Este projeto possui finalidade exclusivamente educacional. A utilização dessas técnicas fora de ambientes de laboratório ou sem autorização é ilegal.

Ferramenta Utilizada

SEToolkit (Social-Engineer Toolkit)
Ferramenta utilizada para simulação de ataques de engenharia social em estudos de segurança da informação e pentest.

Etapas do Processo
1. Inicialização do SEToolkit

O SEToolkit foi iniciado com privilégios de root, conforme exigido pela ferramenta.

sudo setoolkit

Em seguida, foi selecionada a opção:

Social-Engineering Attacks

2. Website Attack Vectors

Após isso, foi selecionada a opção responsável por ataques baseados em páginas web:

Website Attack Vectors

3. Credential Harvester Attack Method

Para realizar a captura das credenciais digitadas pelo usuário, foi utilizada a opção:

Credential Harvester Attack Method

4. Clonagem da Página do Facebook

O SEToolkit foi configurado para clonar a página de login do Facebook, criando uma página falsa visualmente idêntica à original.

Resultado

Foi criada uma página falsa de login do Facebook

As credenciais inseridas pelo usuário são capturadas

Os dados coletados são exibidos diretamente no terminal

Objetivo do Desafio

Compreender o funcionamento de ataques de phishing

Aprender a identificar ataques de engenharia social

Aplicar conceitos básicos de segurança da informação

Demonstrar conhecimento prático em ambientes controlados

Conclusão

Este desafio demonstra como ataques de phishing podem ser executados por meio de engenharia social, reforçando a importância da conscientização em segurança digital, validação de URLs, atenção a páginas falsas e uso de autenticação em dois fatores
