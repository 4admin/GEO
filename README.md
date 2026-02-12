# GEO
@author: Daniel Neves dos Santos
data de início: 12/02/2026
#Proposta de Criação do Parque Pedreira em São Paulo

A proposição aqui é demonstrar como a agregação de espaços públicos no extremo da Zona Sul de São Paulo alinhado à uma cosmovisão orientada serviços podem criar um espaço de lazer, cultura e recuperação ambiental em uma área periférica e densamente povoada de uma Metrópole que por anos ignora o potencial da área.

![Área de Parques por Subprefeituras](\fontes\Parques_por_subpref.png) Destacada a Subprefeitura de Cidade Ademar (0,5%)

As áreas destacadas ao longo da Represa Billings no Mapa são:
* Parque 7 Campos (área antigamente ocupada pela Represa Billings que acabou soterrada pelo assoreamento)
* Parque Apurá (parcialmente implantado, mas com as áreas em implantação já mapeadas)
* Praça Johanna Döbereiner (ninguém no bairro conhece esse nome, mas corresponde popularmente ao espaço delimitado entre a Represa Billings e a Rua dos Mandis)
* Aterro Itatinga (área recentemente descontaminada e sem uso)


##Fontes de dados para criação do mapa:

###Cadastro de Praças e Largos (Fonte: Geosampa)
Link WFS: http://wfs.geosampa.prefeitura.sp.gov.br/geoserver/geoportal/wfs

###Mapeamento de Cobertura Vegetal 2017 (Fonte: Geosampa)
Link WFS: http://wfs.geosampa.prefeitura.sp.gov.br/geoserver/geoportal/wfs

###Parques Municipais (mapa 5)
Link WFS: http://wfs.geosampa.prefeitura.sp.gov.br/geoserver/geoportal/wfs

###World UTM Zones (Serviu só pra definir zona de interesse como UTM 23S)
Link: https://hub.arcgis.com/datasets/esri::world-utm-grid/
Arquivo: World_UTM_Grid_6264847149997430067.gpkg

###Malha Municipal Estado de São Paulo (Fonte: IBGE)
Link: https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2024/UFs/SP/SP_Municipios_2024.zip
Arquivo: SP_Municipios_2024.zip

###Google Satelite (Usando a partir do plugin do QGIS: quickmapservices)

Desafios:
Especificar Tabela cada espaço: Nome|Bairro|Área (m²)
Coletar contribuições que dêem publicidade do projeto e colete sugestões dos moradores que permitam a modelagem econômica para concessão ou PPP junto à iniciativa privada.
