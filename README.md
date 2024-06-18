# KNN

O algoritmo KNN (K-Nearest Neighbors) é um algoritmo de aprendizado de máquina supervisionado usado para classificação e regressão. Ele funciona classificando um novo ponto de dados com base na classe dos seus k vizinhos mais próximos no conjunto de dados de treinamento.

<aside>
💡 É chamado de “Lazy”, pois não aprende nada, apenas armazena informações.

</aside>

## **⚙️ Como funciona**

1. **Definição de K:** Escolhe-se um valor para k, que representa o número de vizinhos mais próximos a serem considerados.
2. **Cálculo da distância:** Calcula-se a distância entre o novo ponto de dados e todos os pontos de dados no conjunto de treinamento.
    1. Distância Euclidiana (mais utilizada)
3. **Seleção dos k vizinhos mais próximos:** Seleciona-se os k pontos de dados mais próximos ao novo ponto de dados, com base na distância calculada.
4. **Classificação:** O novo ponto de dados é classificado com base na classe dominante entre os seus k vizinhos mais próximos.

## ✅ **Vantagens**

- Simples de implementar e de fácil compreensão.
- Versátil, pode ser usado para classificação e regressão.
- Não requer treinamento explícito.

## ❌ **Desvantagens**

- Pode ser computacionalmente caro para grandes conjuntos de dados.
- Sensível à escolha de k.
- Pode ser afetado por dados ruidosos ou desbalanceados.

## 📌 **Aplicações**

- Reconhecimento de padrões
- Classificação de imagens
- Predição de séries temporais
- Filtragem colaborativa
