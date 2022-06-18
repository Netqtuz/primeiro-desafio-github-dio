 # Objetos fundamentais 🧩
  - ### BLOBS: 
    #### Blob tem metadados dentro, os arquivos ficam gravados dentro desse blob, se guarda dentro do blob: tipo do objeto, tamanho da string ou do arquivo, uma \0 e o conteúdo de fato do arquivo.
 - ### TREES:
   #### Elas armazenam blobs dentro dela, é uma crescente, o blob sendo o bloco mais básico da composição, ela guarda o nome do arquivo, diferente do blob.
 - ### COMMITS:
   #### É o objeto que vai juntar tudo e vai ligar tudo, apontando para tudo abaixo dele, escreve algo que da significado a tudo que está abaixo seus arquivos, trees e blobs, possui um SHA1 de seus metadados.