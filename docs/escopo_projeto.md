1. Problema de Negócio Abordado
Desperdício massivo de alimentos próprios para consumo devido à ausência de logística ágil e de comunicação eficiente, gerando fricção no processo de doação de insumos com curto prazo de validade para combater a fome e a escassez em ONGs e cozinhas comunitárias (alinhado à ODS 2 da ONU).

2. Público-Alvo

Doadores: Feirantes, supermercados, restaurantes e produtores rurais que possuem excedentes, estoques esteticamente imperfeitos ou produtos próximos do vencimento e necessitam de um canal de doação ultra-rápido.

Beneficiários/Receptores: ONGs, abrigos e cozinhas comunitárias que atendem populações em situação de vulnerabilidade e precisam de abastecimento ágil de suprimentos.

3. Escopo das Intenções e Dados Coletados

Intenções Tratadas (NLU/Conversacional):

Registrar/Anunciar Doação: Capturar ofertas de alimentos em linguagem informal.

Solicitar/Consultar Insumos: Permitir que ONGs sinalizem demandas ou recebam alertas de disponibilidade.

Confirmar/Agendar Resgate: Coordenar a retirada e entrega do lote entre o doador e a ONG correspondente.

Dados Coletados via Chat (Regex/Extração):

Item/Produto: Tipo de alimento doado (ex.: "tomates", "pães", "arroz").

Quantidade: Volume ou peso (ex.: "30 kg", "5 caixas", "10 Litros").

Data/Prazo de Validade: Tempo limite para consumo/retirada (ex.: "vence em 24h", "até amanhã").

Localização: Endereço ou ponto de coleta para o matchmaking logístico via KNN.
