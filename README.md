# Análise de preços de casas
A análise exploratória dos dados está sendo feita com base no curso <a href="https://www.youtube.com/playlist?list=PLZlkyCIi8bMprZgBsFopRQMG_Kj1IA1WG" rel="nofollow">Python do Zero ao DS</a>, ministrado pelo cientista de dados Meigarom Lopes.

Os dados podem ser encontrados no site kaggle.com.
Dataset:houserocket

# O negócio
A House Rocket é uma plataforma digital que tem como modelo de negócio, a compra e a venda de imóveis usando tecnologia.

Você é um Data Scientist contratado para ajudar a encontrar as melhores oportunidades de negócio no mercado de imóveis. O CEO da House Rocket gostaria de melhorar a receita da empresa encontrando otimas oportunidades de negócio.

Sua principal estratégia é comprar boas casas em ótimas localizações com preços baixos e depois revendê-las posteriormente à preços mais altos. Quanto maior a diferença entre a compra e a venda, maior o lucro da empresa e portanto maior sua receita.

Descrição dos campos da tabela.

<ul dir="auto">
<li><code>id</code> - número de identificação do imóvel</li>
<li><code>date</code> - data de venda do imóvel</li>
<li><code>price</code> - preço de venda do imóvel</li>
<li><code>bedrooms</code> - número de quartos</li>
<li><code>bathrooms</code> - número de banheiros, sendo 0.5 referente aos banheiros sem chuveiro (lavabo)</li>
<li><code>sqft_living</code> - metragem (em pé quadrado) da área interna do imóvel</li>
<li><code>sqft_lot</code> - metragem (em pé quadrado) do terreno</li>
<li><code>floors</code> - número de andares</li>
<li><code>waterfront</code> - se o imóvel tem vista para o mar (0: não, 1: sim)</li>
<li><code>view</code> - diz respeito à qualidade da vista do imóvel (0 a 4)</li>
<li><code>condition</code> - diz respeito à condição do imóvel (1 a 5)</li>
<li><code>grade</code> - trata da construção e design do imóvel (1-3: baixa qualidade, 7: qualidade média, 11-13: alta qualidade)</li>
<li><code>sqft_above</code> - metragem (em pé quadrado) do espaço interno que está acima do nível do solo</li>
<li><code>sqft_basement</code> - metragem (em pé quadrado) do espaço interno que está abaixo do nível do solo</li>
<li><code>yr_built</code> - ano de construção do imóvel</li>
<li><code>yr_renovated</code> - ano de reforma do imóvel</li>
<li><code>zipcode</code> - CEP do imóvel</li>
<li><code>lat</code> - latitude</li>
<li><code>long</code> - longitude</li>
<li><code>sqft_living15</code> - média da metragem (em pé quadrado) da área interna do imóvel dos 15 vizinhos mais próximos</li>
<li><code>sqft_lot15</code> - média da metragem (em pé quadrado) do terreno dos 15 vizinhos mais próximos</li>
</ul>
