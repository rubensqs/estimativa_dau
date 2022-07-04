# estimativa_dau
Estimando a Arrecadação da Dívida Ativa da União com Machine Learning

O presente notebook procura avaliar se é possível, por meio da utilização de modelos de Machine Learn, aprimorar as estimativas de arrecadação da Dívida Ativa da União elaboradas pela Procuradoria-Geral da Fazenda Nacional.

Trata-se de documento integrante de artigo acadêmico homônimo, submetido para publicação na Revista da CGU (ISSN 2595-668X), para o dossiê especial sobre Ciência de Dados na Administração Pública. https://revista.cgu.gov.br/Revista_da_CGU.

As informações de arrecadação, bem como dos parcelamentos e transações tributárias, foram obidos junto à Procuradoria-Geral da Fazenda Nacional, por meio da Lei de Acesso à Informação, pedido nº. 03005.291447/2022-40, disponível para consulta no seguinte endereço: http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?List=0c839f31%2D47d7%2D4485%2Dab65%2Dab0cee9cf8fe&ID=1637685&Source=http%3A%2F%2Fwww%2Econsultaesic%2Ecgu%2Egov%2Ebr%2Fbusca%2FSitePages%2Fresultadopesquisa%2Easpx%3Fk%3D03005%252E291447%252F2022%252D40&Web=88cc5f44%2D8cfe%2D4964%2D8ff4%2D376b5ebb3bef.

Os indicadores macroeconômicos podem ser encontrados no site do Banco Central do Brasil, na ferramenta Sistema Gerenciador de Séries Temporais – SGS (https://www3.bcb.gov.br/sgspub/). Especificamente, foram capturadas as planilhas de códigos: “4380 - PIB mensal - Valores correntes (R$ milhões) – Função: Variação Percentual”; “13522 - Índice nacional de preços ao consumidor - amplo (IPCA) - em 12 meses – Função: Linear”; “4189 - Taxa de juros - Selic acumulada no mês anualizada base 252 - % a.a. – Função: Linear”; “3698 - Taxa de câmbio - Livre - Dólar americano (venda) - Média de período – mensal - Função: Linear”; e “189 - Índice geral de preços do mercado (IGP-M) - Var. % mensal – Função: Linear”.

Este notebook apresenta somente os códigos desenvolvidos em liguagem python para tratamento e exploração dos dados, bem como treinamento e avaliação dos modelos de aprendizado de máquina. Comentários e explicações sobre os achados e as decisões relacionados aos dados estão disponível apenas no texto do artigo acadêmico.
