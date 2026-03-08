# Trabalho 1 - Aplicação de Informação do Sistema

**Disciplina:** Desenvolvimento de Aplicações Móveis (DAM)
**Aluno:** Martim Machado Ramos A51736
**Data:** 7 de março de 2026
**URL do Repositório:** [publicar posteriormente o link do GitHub]

## 1. Introdução
O objetivo desta aplicação consiste em aprender a procurar e a mostrar as características físicas e de software do telemóvel através de código.

## 2. Visão Geral do Sistema
A aplicação é uma ferramenta simples que mostra um bloco de texto com detalhes do telemóvel, como a marca, o modelo e a versão do sistema Android.

## 3. Arquitetura e Desenho
A aplicação tem apenas um ecrã com uma grande caixa de texto (`MultiLine text Widget`) para mostrar a informação. A recolha dos dados é feita logo que a aplicação arranca.

## 4. Implementação
O código usa um comando específico do Android (`android.os.Build`) para ir buscar os detalhes do sistema. Depois, junta esses dados todos num texto fácil de ler e envia-os para o ecrã.

## 5. Testes e Validação
Foi testada num telemóvel virtual e num telemóvel físico (Xiaomi). No telemóvel físico, a aplicação mostrou corretamente as peças e a marca reais do aparelho, provando que o código funciona.

## 6. Instruções de Utilização
Abre o projeto no Android Studio e corre a aplicação num telemóvel. As informações do sistema vão aparecer imediatamente no ecrã.

# Processo de Desenvolvimento

## 12. Controlo de Versões e Histórico
Neste projeto, devido a algumas dúvidas quanto à criação de um possível repositório (que é o caso deste em questão) todas as alterações realizadas ao longo do projeto ficaram guardadas localmente no disco do meu computador. Mais tarde quando percebi realmente que era necessário criar um repositório para este projeto já tinha feito todas as alterações ao projeto, por isso a existência de um único "commit" dado.

## 13. Dificuldades e Aprendizagens
Aprender a procurar sobre a biblioteca `android.os.Build`.

## 14. Melhorias Futuras
Em vez de mostrar um bloco de texto simples, a informação ficaria muito mais bonita se fosse organizada numa lista bem formatada.

## 15. Declaração de Uso de IA (Obrigatório)
O uso de IA para gerar código era proibido nesta parte do trabalho. A Inteligência Artificial foi usada unicamente para me ajudar a escrever e a rever este documento de texto. Assumo toda a responsabilidade pelo projeto em questão.