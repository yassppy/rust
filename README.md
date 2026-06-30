# rust

Rust es un lenguaje de programación de sistemas centrado en la seguridad, 
la velocidad y la concurrencia. Es conocido por su seguridad de memoria 
sin necesidad de garbage collector, lo cual le permite ser tan rápido 
como C/C++ pero con muchas menos probabilidades de bugs críticos.

Se utiliza en:
- Backend de alto rendimiento (APIs, microservicios críticos)
- Software embebido y sistemas (kernels, drivers, IoT)
- Blockchain (Solana, Polkadot)
- Herramientas internas de ciencia de datos/ML (Polars, tokenizers de 
  Hugging Face, Candle) — aunque el lenguaje principal para hacer ML 
  sigue siendo Python

## Aprender rust

- https://doc.rust-lang.org/stable/book/index.html
- https://github.com/Hunterdii/30-Days-Of-Rust

## Instalar rust

Instalar rust con FlyEnv e instalar el toolchain más rápido que visual studio de Windows
```shell
rustup toolchain install stable-x86_64-pc-windows-gnu
rustup default stable-x86_64-pc-windows-gnu
```
