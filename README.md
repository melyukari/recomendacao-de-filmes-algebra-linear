# 📐 Sistema de Recomendação de Filmes com Álgebra Linear

Este projeto implementa um sistema de recomendação de filmes utilizando conceitos de Álgebra Linear, especialmente similaridade do cosseno para medir a proximidade entre vetores de preferência.

O objetivo é recomendar filmes com base na similaridade entre usuários ou entre filmes, utilizando representações vetoriais e operações matriciais.

---

## 🧠 Conceitos Matemáticos Aplicados

O projeto utiliza:

- Representação de usuários como vetores
- Produto interno
- Norma de vetores
- Similaridade do cosseno
- Matrizes de avaliações
- Espaço vetorial ℝⁿ

A similaridade do cosseno é definida como:

cos(θ) = (A · B) / (||A|| ||B||)

Onde:
- A e B são vetores de avaliação
- "·" representa o produto interno
- ||A|| e ||B|| são as normas dos vetores

O valor varia entre -1 e 1, indicando o grau de similaridade entre dois perfis.

---

## ⚙️ Metodologia

1. Construção da matriz usuário-filme
2. Transformação das avaliações em vetores numéricos
3. Cálculo da similaridade do cosseno
4. Identificação dos usuários ou filmes mais similares
5. Geração de recomendações com base na maior similaridade

---

## 📊 Funcionamento do Modelo

O sistema:

- Calcula a similaridade entre vetores
- Ordena os usuários/filmes mais próximos
- Recomenda filmes ainda não assistidos com base nas preferências mais similares

Quanto mais próximo de 1 for o valor da similaridade, mais parecidos são os perfis.

---

## 🛠 Tecnologias Utilizadas

- Python
- NumPy
- Operações matriciais
- Conceitos de Álgebra Linear

---

## 📈 Aplicações

Sistemas de recomendação são amplamente utilizados em:

- Plataformas de streaming
- E-commerce
- Redes sociais
- Sistemas de personalização

Este projeto demonstra como conceitos fundamentais de Álgebra Linear são aplicados em problemas reais de ciência de dados.

---

## 📌 Conclusão

A similaridade do cosseno mostrou-se uma métrica eficiente para medir proximidade entre perfis de usuários ou filmes, permitindo gerar recomendações coerentes com as preferências observadas.

O projeto reforça a importância da Álgebra Linear como base matemática para sistemas de recomendação e aprendizado de máquina.

