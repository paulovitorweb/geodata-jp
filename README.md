# geodata-jp
Dataset com arquivos GeoJSON simplificados da cidade de João Pessoa, ideal para uso em projetos web.

## Fonte
Os arquivos foram coletados no site oficial da prefeitura de João Pessoa - https://filipeia.joaopessoa.pb.gov.br/ - no formato shapefile, transformados para WSG84 EPSG:4326 e simplificados para coordenadas com precisão de 6 casas decimais, para ocupar menor espaço de armazenamento e facilitar a transferência de dados via API.

Cada arquivo GeoJSON possui um campo `source` que identifica a fonte dos dados.

O repositório conta com os seguintes conjuntos de dados:
- Bairros
- Ciclovias
- Corredores
- Faixas exclusivas de ônibus
- Parques
- Praças
- Rios
