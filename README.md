# Criptpgrafia

## Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de aprendizado e aprimoramento de habilidades em Rust. O foco é a implementação de um sistema de criptografia que permite ao usuário criptografar e descriptografar mensagens de forma segura.

## Funcionalidades
- Criptografar mensagens
- Descriptografar mensagens
- Implementação própria dos algoritmos de criptografia

## Tecnologias Utilizadas
- **Linguagem:** Rust

## Como Usar
Este projeto foi desenvolvido como uma biblioteca Rust (crate) para ser utilizada em outras aplicações. Para utilizá-la, siga os passos abaixo:

1. Adicione este repositório ao seu `Cargo.toml` como dependência:
   ```toml
   [dependencies]
   criptpgrafia = { git = "https://github.com/Dioque/Criptpgrafia.git" }
   ```

2. Importe a biblioteca no seu código Rust:
   ```rust
   use criptpgrafia::{criptografar, descriptografar};

   fn main() {
       let mensagem = "Olá, mundo!";
       let chave = "minha_senha";
       let criptografado = criptografar(mensagem, chave);
       let descriptografado = descriptografar(&criptografado, chave);

       println!("Mensagem criptografada: {}", criptografado);
       println!("Mensagem descriptografada: {}", descriptografado);
   }
   ```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests com melhorias e sugestões.

## Licença
Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
