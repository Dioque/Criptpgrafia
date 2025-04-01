# 🔐 Pesquisa em Criptografia com Tesseract

## 📌 Sobre a Pesquisa
Este repositório contém materiais de estudo e desenvolvimento para uma pesquisa sobre criptografia baseada em transformações do **Tesseract**. O objetivo principal é explorar como as trocas de faces e suas propriedades geométricas podem ser aplicadas para criar um sistema de criptografia inovador. A pesquisa ainda está em andamento e servirá como base para o desenvolvimento de um futuro projeto.

### 🌱 O Conceito
O Tesseract é formado por dois cubos: um interno e um externo, conectados de maneira dinâmica. Além disso, possui quatro formas que chamaremos de (D). Quando uma das faces do cubo interno toma posição, ela substitui a face correspondente do cubo externo, e a face que estava naquela posição se move para outro lugar. Cada forma (D) é composta por dois quadrados: um maior, pertencente ao cubo externo, e um menor, pertencente ao cubo interno. Os vértices desses quadrados são conectados de maneira correspondente, ou seja, o vértice A do quadrado menor se liga ao vértice A do quadrado maior, assim como ocorre com os vértices B, C e D.

A ideia é usar as trocas dessas faces, seus comportamentos, composições e propriedades para atribuir valores binários (**1s e 0s**) a diferentes posições do Tesseract. Dessa forma, cada troca de face modificará toda a estrutura criptográfica, alterando a disposição dos bits de forma imprevisível.

## 📖 Estrutura da Pesquisa
A pesquisa envolve diversos conceitos matemáticos e computacionais fundamentais para entender a abordagem da criptografia no Tesseract. Para compreender melhor o funcionamento, disponibilizamos materiais de estudo dentro do repositório.

### 🔹 Fundamentos Necessários
- **Álgebra Linear**: Espaços vetoriais, combinações lineares, matrizes.
- **Álgebra de Lie**: Transformações contínuas e grupos de Lie.
- **Teoria dos Números**: Importante para sistemas criptográficos.
- **Criptografia de Reticulado**: Técnicas modernas de criptografia.
- **Fractais**: Possíveis aplicações na geração de padrões de chave.

### 🔹 Implementação da Criptografia
1. **Gerar uma chave privada** (sequência longa de 1s e 0s).
2. **Criar um sistema de codificação de texto**.
3. **Converter a mensagem secreta em uma sequência de 1s e 0s** usando o sistema de codificação.
4. **Garantir que o tamanho da mensagem binária seja compatível com a chave privada** (se necessário, complementar com sequências aleatórias de 1s e 0s).
5. **Aplicar transformações do Tesseract** para embaralhar os dados de forma segura.
6. **Ofuscação de código** como proteção extra.

## 🛠️ Tecnologias e Recursos
- **Linguagem:** Rust
- **Ofuscação de Código:** Implementação para dificultar engenharia reversa.
- **Repositório de Materiais**: Livros, vídeos e cursos relacionados à pesquisa.

## 📚 Materiais de Estudo
- **[Repositório de Materiais](/Pesquisa/Material/)**; 

## 🚀 Próximos Passos
Este repositório continuará sendo atualizado com novos avanços e experimentações. Quem quiser acompanhar e contribuir, sinta-se à vontade para explorar os materiais e compartilhar ideias! 💡

📌 **Nota:** Este repositório é um espaço de pesquisa. Ainda não há uma implementação final do projeto, mas a base teórica está sendo construída para dar suporte ao desenvolvimento futuro.
