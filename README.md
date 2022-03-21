# rust-helloworld

# Comandos

## Instalacao
$sudo curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

//corrige error linker `cc` not found
$sudo apt install build-essential 

## Execucao
$cargo new hello-rust //cria a pasta e o projeto
$cargo init //inicializa o projeto na pasta atual

$cargo run //executa o script que esta na src/main.rs

## Dependencias
https://crates.io/

Adicione a dependencia ao Cargo.toml da seguinte forma
``` 
[dependencies]
ferris-says = "0.2"
```
e rode o comando
$cargo build