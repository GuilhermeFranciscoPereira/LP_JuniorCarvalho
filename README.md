<div align="center">

# <img src="assets/icon.png" alt="" width="40" align="top"> Junior Carvalho <img src="assets/icon.png" alt="" width="40" align="top">

> Visite o site: [Junior Carvalho - Landing Page](https://junior-carvalho.vercel.app)

</div>

<br>

## Sobre o projeto

Landing page criada para demonstração, utilizando o personagem ficticio "Junior Carvalho", que vende relógios de luxo com procedência e atendimento direto pelo WhatsApp.

A página conta uma história com a rolagem: um Rolex Submariner em 3D gira e se desmonta peça por peça para mostrar o que confere antes de oferecer qualquer relógio. Em seguida, os relógios disponíveis aparecem um de cada vez, com a foto oficial de cada modelo dentro da sua própria sala em 3D, a história do modelo à esquerda e a ficha técnica à direita.

Cada relógio tem também a sua página: a foto oficial do relógio escolhido sai do meio da sala e acompanha a rolagem, de um lado para o outro, virando para os textos que contam a história, o desenho, o movimento e a ficha técnica completa, com uma galeria de fotos que se abre em tela cheia.

O conceito visual é o da relojoaria: preto, dourado champanhe e creme, índices de mostrador, ponteiros e números romanos em todos os detalhes.

<br>

## Prévia

<img src="assets/desktop-inicio.jpg" alt="Tela inicial: “Junior Carvalho” ao lado de um Rolex Submariner em 3D, de aço, com luneta e mostrador pretos" width="100%">

<table>
  <tr>
    <td width="50%">
      <img src="assets/desktop-abertura.jpg" alt="Abertura: relógio bicolor com pulseira Oyster, luneta serrilhada, data e indicador de reserva de marcha">
      <p align="center"><b>A abertura</b><br><sub>Um relógio que ganha corda conforme o site carrega</sub></p>
    </td>
    <td width="50%">
      <img src="assets/desktop-desmontado.jpg" alt="Relógio desmontado em camadas com legendas de cada peça">
      <p align="center"><b>Peça por peça</b><br><sub>O Submariner se desmonta com a rolagem, com legenda em cada peça</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="assets/desktop-submariner.jpg" alt="Foto do Rolex Submariner numa sala azul profunda com feixes de luz">
      <p align="center"><b>Disponíveis</b><br><sub>A foto de cada relógio na sua sala, com história e ficha técnica</sub></p>
    </td>
    <td width="50%">
      <img src="assets/desktop-royal-oak.jpg" alt="Foto do Audemars Piguet Royal Oak diante de uma parede de ladrilhos azuis">
      <p align="center"><b>Seis salas</b><br><sub>A câmera atravessa um portal temático entre um relógio e outro</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="assets/desktop-detalhe.jpg" alt="Página do Rolex GMT-Master II: a foto do relógio no centro da sala, com a história, os destaques e o nome do modelo">
      <p align="center"><b>A página de cada relógio</b><br><sub>Abre na mesma sala da galeria, com o relógio no centro</sub></p>
    </td>
    <td width="50%">
      <img src="assets/desktop-detalhe-coracao.jpg" alt="Royal Oak à direita, virado para o texto sobre o calibre 4302">
      <p align="center"><b>Acompanha a rolagem</b><br><sub>O relógio atravessa a sala e vira para cada texto, mostrando a espessura da caixa</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="assets/desktop-detalhe-fotos.jpg" alt="Faixa de fotos oficiais do Royal Oak: mostrador, luneta e movimento">
      <p align="center"><b>Galeria de fotos</b><br><sub>Faixa que anda com a rolagem e abre cada foto em tela cheia</sub></p>
    </td>
    <td width="50%">
      <img src="assets/desktop-detalhe-ficha.jpg" alt="Ficha técnica completa do Santos de Cartier numa sala clara">
      <p align="center"><b>Ficha técnica completa</b><br><sub>Caixa, movimento, mostrador e pulseira, com os dados oficiais</sub></p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="assets/desktop-sobre.jpg" alt="Seção Com quem você está comprando, com texto e foto do Junior">
      <p align="center"><b>Com quem você está comprando</b><br><sub>Texto do Junior, números e a foto revelada numa moldura de arco</sub></p>
    </td>
  </tr>
</table>

### No celular

<img src="assets/mobile.jpg" alt="Seis telas da versão mobile: abertura, início com o Submariner em 3D, relógio desmontado, salas do Submariner e do Santos e página do GMT-Master II" width="100%">

<br>

## Destaques

- **Fotos reais nas salas**: cada relógio disponível aparece com a foto oficial do modelo, recortada e iluminada dentro da sua sala em 3D, com sombra, halo e um reflexo que passa pelo metal.
- **Uma página para cada relógio**: história, desenho, movimento e uso no pulso, galeria de fotos com ampliação e ficha técnica completa, com a foto do relógio flutuando pela sala e virando de um lado para o outro com a rolagem. Abre na mesma aba, sem recarregar: a sala da galeria continua e o relógio só muda de lugar; voltar leva de novo à sala daquele relógio.
- **Rolex Submariner 3D feito em código**: caixa Oyster com alças escovadas e flancos polidos, protetores da coroa, luneta Cerachrom, mostrador laqueado com as inscrições, rehaut gravado, lente cíclope, ponteiros Mercedes e pulseira Oyster, gerados no navegador, sem modelos baixados. Os ponteiros vão para a hora de quem visita.
- **História guiada pela rolagem**: o relógio gira, se desmonta com legendas e se monta de novo, de frente.
- **Abertura que acompanha o carregamento real**: um relógio desenhado em CSS ganha corda (trilho dos minutos e reserva de marcha) conforme as fontes e a primeira imagem ficam prontas, e acerta os ponteiros na hora de quem visita.
- **Interesse em um toque**: cada relógio abre o WhatsApp com a mensagem pronta.
- **Leve**: a primeira tela é uma imagem renderizada da própria cena 3D, e o 3D só carrega na primeira interação, entrando por cima dela no mesmo quadro. O relógio é montado em pequenas etapas, a iluminação vem pré-calculada (34 KB) e as fotos são WebP no tamanho certo.
- **Mesma proporção em qualquer tela**, sem rolagem lateral, testada do celular a monitores largos.
- **Acessível**: respeita "reduzir movimento", tem navegação por teclado e textos alternativos.
- **Pronta para o Google**: metadados e imagem de compartilhamento por página, sitemap, robots e dados estruturados (organização, produtos e perguntas frequentes).

<br>

## Tecnologias

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org) [![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org) [![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org) [![GSAP](https://img.shields.io/badge/GSAP-0AE448?style=for-the-badge&logo=greensock&logoColor=black)](https://gsap.com) [![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)

</div>

| Camada | Escolha |
| --- | --- |
| Framework | Next.js 16 (App Router), com todas as páginas geradas de forma estática |
| Interface | React 19 + TypeScript |
| 3D | Three.js com React Three Fiber |
| Animações | GSAP (ScrollTrigger e SplitText) e rolagem suave com Lenis |
| Estilos | CSS Modules |
| Imagens e fontes | `next/image` e `next/font` |
| Hospedagem | Vercel |

<br>

## Código-fonte

> [!NOTE]
> O código-fonte deste projeto é **privado**. Este repositório serve apenas como apresentação do trabalho.

<br>

## Direitos

As fotos dos relógios são imagens oficiais das marcas, usadas apenas para ilustrar os modelos. Rolex, Audemars Piguet, Patek Philippe e Cartier são marcas de seus respectivos titulares. Todos os direitos reservados: não é permitido reproduzir ou reutilizar este conteúdo sem autorização.

<!-- Desenvolvido por: Guilherme Francisco Pereira-->
