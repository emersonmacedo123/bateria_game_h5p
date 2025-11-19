# H5P Conteúdos

Esta pasta é destinada aos conteúdos H5P do jogo.

## Como adicionar conteúdo H5P

1. Faça o download ou crie um arquivo `.h5p` usando uma ferramenta de autoria H5P
2. Extraia o conteúdo do arquivo `.h5p` (é um arquivo ZIP)
3. Coloque os arquivos extraídos nesta pasta
4. Atualize o caminho `h5pJsonPath` no arquivo `index.html` para apontar para a pasta do seu conteúdo

## Estrutura esperada

```
h5p-conteudos/
├── seu-conteudo/
│   ├── h5p.json
│   ├── content/
│   └── ...
```

## Referências

- [H5P.org](https://h5p.org/) - Crie e compartilhe conteúdo interativo
- [H5P Standalone Player](https://github.com/tunapanda/h5p-standalone) - Documentação do player
