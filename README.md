# 📊 Case Processo Seletivo — Analista de Dados Produto & Growth

## 👨‍💻 Autor

**Antonio Carlos Batista Junior**

E-mail: junior.engenheirobatista@gmail.com

---

# Objetivo

Este projeto foi desenvolvido como parte do processo seletivo para **Analista de Dados — Produto & Growth** do **the news**.

O objetivo foi responder à seguinte pergunta de negócio:

> **"O que está determinando se um usuário volta a jogar o Palavritas e o que podemos fazer para aumentar essa retenção?"**

Para isso foram realizadas análises exploratórias, limpeza dos dados, engenharia de atributos, modelagem estatística e recomendações de Produto baseadas em evidências.

---

# Entregáveis

## 📓 Notebook (Google Colab)

https://colab.research.google.com/drive/1atmctgzJ49EqMKvsSnA8zx96R0aGTLNr

---

## 📄 Relatório Executivo

O relatório executivo em PDF encontra-se neste repositório.

---

# Estrutura da análise

O projeto foi dividido em três etapas principais.

### 1. Diagnóstico e limpeza

- Avaliação da qualidade dos dados
- Tratamento de valores inconsistentes
- Remoção de duplicidades
- Conversão de tipos
- Padronização de variáveis

---

### 2. Análise Exploratória

Foram analisadas as relações entre:

- Horário do jogo
- Palavra do dia
- Device
- Newsletter
- Streak
- Perfil do usuário
- Faixa salarial
- Setor
- Frequência de Food Delivery
- Tempo de conclusão
- Active D30
- Played Next Day

---

### 3. Recomendações de Produto

A partir dos resultados foram propostas melhorias para aumentar retenção e engajamento dos usuários.

Cada proposta apresenta:

- Hipótese
- Ação
- Critério de sucesso

---

# Principais Insights

Os principais achados da análise foram:

- O dispositivo (iOS/Android) apresentou pouca influência na retenção.
- O horário do jogo demonstrou maior associação com o retorno do usuário.
- Usuários com maior streak apresentaram maior probabilidade de voltar no dia seguinte.
- A newsletter mostrou maior relação com o Active D30 do que com o retorno imediato.
- A dificuldade das palavras influencia a experiência, mas não explica sozinha a retenção.

---

# Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Google Colab

---

# Modelagem

Além da análise exploratória, foi desenvolvido um modelo utilizando **Random Forest** para identificar quais variáveis possuem maior importância na previsão do comportamento dos usuários.

O objetivo do modelo não foi realizar previsões em produção, mas apoiar a priorização das hipóteses de Produto.

---

# Resultado esperado

As recomendações apresentadas neste estudo têm como finalidade:

- aumentar a retenção dos usuários;
- incentivar o hábito diário de utilização;
- fortalecer a integração entre newsletter e produto;
- reduzir perda de usuários;
- apoiar decisões de Produto orientadas por dados.

---

# Como executar

1. Abrir o Notebook no Google Colab;
2. Carregar os três arquivos CSV disponibilizados no case;
3. Executar as células na ordem apresentada;
4. Consultar o relatório executivo para a interpretação dos resultados.

   ## 📄 Relatório Executivo

O GitHub pode não conseguir visualizar alguns PDFs diretamente no navegador.

Caso isso aconteça, basta clicar em **Download** para abrir o relatório completo.

📄 Arquivo: `relatorio_case_palavritas.pdf`

---

Obrigado pela oportunidade!

Antonio Carlos Batista Junior
