# H5P Standalone Player

Esta pasta contém o H5P Standalone Player, uma biblioteca JavaScript que permite exibir conteúdos H5P sem a necessidade de um servidor H5P.

## O que está incluído

Este é o código-fonte completo do [H5P Standalone Player](https://github.com/tunapanda/h5p-standalone) versão 3.x.

## Uso

O projeto já está configurado para usar o H5P Standalone Player através de CDN no arquivo `index.html`. Isso significa que você não precisa compilar ou construir nada nesta pasta.

### Alternativa: Construir localmente (opcional)

Se você preferir hospedar os arquivos do player localmente em vez de usar o CDN:

1. Instale as dependências:
   ```bash
   yarn install
   ```

2. Construa o projeto:
   ```bash
   yarn build
   ```

3. Atualize o arquivo `index.html` para usar os arquivos locais da pasta `dist/` em vez do CDN.

## Documentação

Para mais informações sobre como usar o H5P Standalone Player, consulte:
- [README oficial](./README.md)
- [Repositório GitHub](https://github.com/tunapanda/h5p-standalone)
