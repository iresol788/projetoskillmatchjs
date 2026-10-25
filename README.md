# projetoskillmatchjs
Projeto Candidato em busca de uma Vaga, de desenvolvimento HTML, CSS, JavaScript, node.js pertinente com suas habilidades. E a Função é Analisar Vagas.
Sou Ires Oliveira, e este é o SkillMatch.JS, um simulador de compatibilidade entre candidatos e vagas de emprego desenvolvido em JavaScript e Node.js. O objetivo é mostrar de forma prática quais vagas combinam mais com o perfil de um profissional e indicar o que estudar para se qualificar ainda mais.
 
 
 
 Metodologias e Conceitos Utilizados
 
1. Programação Orientada a Objetos — Classes
 
Usei classes para organizar os dados de forma clara:
 
- Classe Candidato: armazena nome, área de interesse, habilidades e tempo de experiência.
- Classe Vaga: representa uma oferta de emprego com empresa, cargo e requisitos.
 
2. Herança
 
Criei a classe VagaComCompatibilidade, que herda características da classe Vaga e adiciona novas funcionalidades — como calcular a porcentagem de compatibilidade e classificar o resultado. Isso evita repetição de código e facilita manutenção.
 
3. Métodos de Array — Funcionalidades Principais
 
-  .filter() : separa as habilidades que o candidato possui das que faltam.
-  .map() : percorre todas as vagas e calcula a compatibilidade de cada uma.
-  .reduce() : encontra a vaga com a maior compatibilidade entre todas.
-  .every() : verifica se o candidato atende 100% dos requisitos de todas as vagas.
- Laço  for : usado no lugar do  includes()  para verificar se uma habilidade está presente na lista.
 
4. Lógica de Classificação e Recomendação
 
O sistema calcula a porcentagem de correspondência e classifica em:
 
- ≥ 80%: Alta compatibilidade
- ≥ 50%: Média compatibilidade
- < 50%: Baixa compatibilidade
 
Ao final, mostra a melhor vaga para o candidato e sugere quais habilidades estudar para aumentar suas chances.
 
 
 
✅ Resultado
 
O programa retorna de forma organizada:
 
- Perfil do candidato
- Análise de cada vaga com requisitos atendidos e faltantes
- Porcentagem e classificação de compatibilidade
- A melhor correspondência encontrada
- Recomendação personalizada de estudos
 
 
 
Em resumo: O SkillMatch.JS é um projeto prático que une lógica de programação, orientação a objetos e manipulação de listas para resolver um problema real: ajudar profissionais a identificarem onde estão e o que precisam aprender para conquistar uma vaga.

