# sistema de gestão de condomínios.
Projeto acadêmico desenvolvido em **Java** para disciplina de **Programação Orientada a Objetos**

Sistema simples que simula o gerenciamento de condomínios utilizando o console na linguagem Java, contendo gestão das contas de energia e imóveis.

## Funcionalidades

- Cadastro, consulta de contas
- Cadastro, consulta de imóveis
- Cadastro automático de consumo da conta
- Cadastro automático da tarifa com imposto ou isenção de impostos para conta 
- comparar duas contas pelo nome do mês , para saber quem foi a mais cara das duas
- Busca de contas pelo nome do mês
- Busca de imóveis pelo código de registro numérico
- resumo de uma conta 
- consulta o valor médio das contas de energia nos últimos 12 meses
- consulta o valor da conta mais cara do imóvel nos últimos 12 meses
- consulta com resumo das contas do imóvel que tiveram valor acima da média no período
- consulta com resumo anual para um imóvel

## Estrutura do projeto
- *Contas*_ armazena mês, leitura atual, leitura anterior, consumo, valor, valor imposto , comparar contas .
- *imóvel*_ armazena código de registro numérico,  gerencia o vetor de Contas, consulta Contas.
- *condomínios.*_ gerencia o vetor de imóveis., consulta imóveis.
- *Contasenergia*_ classe principal responsável pelos menus e integração do sistema.

## Estruturas utilizadas

O projeto trabalha com vetores de capacidade fixa:

- **12 contas**
- **10 Imovel**

Atualmente, o programa inicia com **12 contas** e **1 imovel**, deixando espaço para novos cadastros durante a execuçã

## Diagrama de classes

<p align="center">
  <img src="diagrama-classes.jpg" alt="Diagrama de classes do Sistema Gerenciador de Torneios" width="850">
</p>
