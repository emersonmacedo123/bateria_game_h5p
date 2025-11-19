# bateria_game_h5p

Desenvolvimento de Jogos UaB - Projeto de jogo de bateria usando H5P.

## Estrutura do Projeto

```
bateria_game_h5p/
├── index.html           # Página principal do projeto
├── h5p-conteudos/       # Pasta para conteúdos H5P
│   └── README.md        # Instruções para adicionar conteúdos
├── h5p-player/          # H5P Standalone Player
│   └── README_PT.md     # Documentação em português
└── README.md            # Este arquivo
```

## Como usar

1. Abra o arquivo `index.html` em um navegador web
2. Adicione seus conteúdos H5P na pasta `h5p-conteudos/`
3. Atualize o caminho no `index.html` conforme necessário

## H5P Standalone Player

Este projeto usa o [H5P Standalone Player](https://github.com/tunapanda/h5p-standalone) para exibir conteúdos H5P sem necessidade de servidor backend. O player é carregado via CDN, então não há necessidade de instalação adicional.

## Recursos

- **index.html**: Página HTML pronta com H5P Standalone Player integrado
- **h5p-conteudos/**: Pasta para armazenar seus conteúdos H5P extraídos
- **h5p-player/**: Código-fonte completo do H5P Standalone Player (opcional, apenas se quiser construir localmente)

## Referências

- [H5P.org](https://h5p.org/) - Plataforma para criar conteúdo interativo
- [H5P Standalone Player](https://github.com/tunapanda/h5p-standalone) - Player standalone para H5P

