<p>
<picture>
  <source media="(max-width: 600px)" srcset="assets/profile-mobile.svg" />
  <img src="assets/profile.svg" width="100%" alt="Marcos Macedo, desenvolvedor Full Stack. Demonstração animada de qrSvg, da minha biblioteca pix-brcode. O QR Code abre o projeto." />
</picture>
</p>

Crio aplicações web e APIs com **Vue, Node.js e TypeScript**. Desenvolvi as plataformas de pedidos da Embraza Gringos e da Qbombom e publiquei a pix-brcode para quem precisa integrar Pix a uma aplicação.

[Conheça meu portfólio](https://marcedoafk.github.io/) · [Converse comigo no LinkedIn](https://www.linkedin.com/in/antonio-marcos-9305bb2b4/)

## Projetos em destaque

**[pix-brcode ↗](https://www.npmjs.com/package/@m4rquin/pix-brcode)**  
Biblioteca TypeScript para gerar, ler e validar Pix copia e cola. Também gera QR Codes em SVG e funciona no navegador e em Node.js, sem dependências externas.

<details>
<summary>Ver exemplo e funções da biblioteca</summary>

```ts
import { qrSvg } from '@m4rquin/pix-brcode';

const url = 'https://github.com/marcedoafk/pix-brcode';
const svg = qrSvg(url);
```

O QR Code da abertura foi gerado com essa função e aponta para o repositório.

| Função | O que faz |
| :--- | :--- |
| `generate` | Cria o Pix copia-e-cola. |
| `parse` | Lê os campos do código. |
| `validate` | Verifica o CRC. |
| `qrSvg` | Gera um QR Code em SVG. |

</details>

**[Embraza Gringos ↗](https://embrazagringos.com.br/)**  
Desenvolvi o fluxo de pedidos da hamburgueria, da montagem da sacola ao acompanhamento da entrega ou retirada.

**[Qbombom Sorvetes ↗](https://qbombomararipe.com.br/)**  
Criei a experiência de compra da sorveteria. O cliente escolhe os adicionais de cada produto e confere a combinação no carrinho antes de pedir.

## Sobre mim

Sou de Araripe, no Ceará, e curso Análise e Desenvolvimento de Sistemas. Nos projetos de delivery, aprendi a pensar no que acontece depois do clique em “Pedir”. Na pix-brcode, o desafio foi escrever testes e exemplos para que outro desenvolvedor consiga usar a biblioteca por conta própria.

Trabalho com Vue nas interfaces, Fastify e Express nas APIs, e Docker, Linux e Nginx na infraestrutura.
