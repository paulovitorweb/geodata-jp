# geodata-jp
Dataset com arquivos GeoJSON simplificados da cidade de João Pessoa, ideal para uso em projetos web.

## Concepção
Os arquivos são coletados em portais públicos de dados abertos nos formatos shapefile e CSV, transformados para WSG84 EPSG:4326 e convertidos para o formato GeoJSON, simplificados para coordenadas com precisão de 6 casas decimais para ocupar menor espaço de armazenamento e facilitar a transferência de dados via API.

Cada arquivo GeoJSON possui um campo `source` que identifica a fonte dos dados.

## Camadas

| Camada   | Fonte                                                  |
|-----------|-------------------------------------------------------|
| :world_map: Bairros   | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :bicyclist: Ciclovias | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :bus: Corredores   | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :oncoming_bus: Faixas esclusivas de ônibus | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :national_park: Parques   | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :camping: Praças | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :droplet: Rios   | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :seedling: Área rural | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :houses: Comunidades   | Filipeia Mapas da cidade - Prefeitura de João Pessoa¹ |
| :school: Escolas públicas | Catálogo de Escolas do INEP² |

¹ https://filipeia.joaopessoa.pb.gov.br/

² https://inepdata.inep.gov.br/analytics/
