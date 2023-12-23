# 3Dmultiplasjanelas

# Cena 3D em Múltiplas Janelas usando Three.js

## Introdução
Este projeto demonstra uma abordagem única para criar e gerenciar uma cena 3D em várias janelas do navegador usando Three.js e localStorage. É projetado para desenvolvedores interessados em gráficos web avançados e técnicas de gerenciamento de janelas.

## Recursos
- Criação e renderização de cena 3D com Three.js.
- Sincronização de cenas 3D em várias janelas do navegador.
- Gerenciamento dinâmico de janelas e sincronização de estado usando localStorage.

## Instalação
Clone o repositório e abra o arquivo `index.html` em seu navegador para começar a explorar a cena 3D.

```
git clone https://github.com/bgstaal/3Dmultiplasjanelas
```

## Uso
A lógica principal da aplicação está contida em `main.js` e `WindowManager.js`. A cena 3D é renderizada em `index.html`, que serve como ponto de entrada da aplicação.

## Estrutura e Componentes
- `index.html`: Ponto de entrada que configura a estrutura HTML e inclui a biblioteca Three.js e o script principal.
- `WindowManager.js`: Classe principal que gerencia a criação de janelas, sincronização e gerenciamento de estado em várias janelas.
- `main.js`: Contém a lógica para inicializar a cena 3D, lidar com eventos de redimensionamento de janelas e renderizar a cena.
- `three.r124.min.js`: Versão minificada da biblioteca Three.js usada para renderização de gráficos 3D.

## Funcionalidades Detalhadas
- `WindowManager.js` gerencia o ciclo de vida de várias janelas do navegador, incluindo criação, sincronização e remoção. Ele utiliza localStorage para manter o estado entre as janelas.
- `main.js` inicializa a cena 3D usando Three.js, gerencia os eventos de redimensionamento da janela e atualiza a cena com base nas interações da janela.

## Contribuições
Contribuições para aprimorar ou expandir o projeto são bem-vindas. Sinta-se à vontade para fazer um fork do repositório, fazer alterações e enviar pull requests.

## Licença
Este projeto é de código aberto sob a Licença MIT.
