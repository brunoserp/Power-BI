<h1>Dashboard de Monitoramento de Emissões de CO2 - Projeto "Melhora Mundial"</h1>

<p>
A <strong>OurTech</strong>, comprometida com a sustentabilidade e o impacto ambiental, lançou o plano <em>"Melhora Mundial"</em>, com o objetivo de identificar e mitigar pontos de emissão de CO2 em seus processos produtivos. Este plano visa alinhar a produção da empresa às metas globais de redução de emissões, garantindo um futuro mais sustentável.
</p>

<p>
O dashboard desenvolvido concentra-se em mapear a relação entre a produção de diferentes produtos e as emissões de CO2 associadas. Os dados simulam uma análise detalhada das operações de <strong>OurTech</strong>, abordando aspectos como:
</p>

<ul>
    <li><strong>Vendas (Unidades):</strong> Quantidade de produtos vendidos em diferentes períodos.</li>
    <li><strong>Receita Total:</strong> Valor gerado pela venda de produtos.</li>
    <li><strong>Emissões de CO2 (kg):</strong> Quantidade de dióxido de carbono emitida na produção e transporte dos produtos.</li>
</ul>

<p>
A análise é fundamental para identificar produtos ou categorias que possuem maior impacto ambiental, permitindo priorizar iniciativas de redução de emissões. Com essas informações, a empresa pode, por exemplo:
</p>

<ul>
    <li>Revisar processos de fabricação de produtos mais intensivos em emissões.</li>
    <li>Otimizar a logística para diminuir emissões no transporte.</li>
    <li>Investir em tecnologias mais limpas para produção e distribuição.</li>
</ul>

<h2>Fórmulas DAX Utilizadas no Dashboard</h2>
<p>
No desenvolvimento deste dashboard, foram utilizadas as seguintes funções DAX: <strong>SUM</strong>, <strong>SUMX</strong>, <strong>CALCULATE</strong>, <strong>FILTER</strong>, <strong>ALL</strong>, <strong>EARLIER</strong>, <strong>DIVIDE</strong>, <strong>SELECTEDVALUE</strong> e <strong>PREVIOUSMONTH</strong>.    
Abaixo estão alguns exemplos das análises realizadas:
</p>

<ul>
    <li><strong>Qual é a cidade com maior emissão de CO2 (co2 emission)?</strong><br>
        Agrupamos os dados pela coluna <code>city</code> e calculamos a soma de <code>co2 emission</code>, identificando a cidade com o maior valor.
    </li>
    <li><strong>Qual é o total de vendas (sales) para cada categoria (category) em cada mês?</strong><br>
        Extraímos o mês da coluna <code>date</code>, agrupamos os dados por <code>category</code> e mês, e calculamos o total de vendas para cada combinação.
    </li>
    <li><strong>Qual é o produto (product) com o maior volume de vendas (quantity) em 2023?</strong><br>
        Filtramos os dados para o ano de 2023 usando a coluna <code>date</code>, somamos os valores de <code>quantity</code> por <code>product</code> e identificamos o maior valor.
    <li><strong>Crie uma medida para calcular a porcentagem de vendas de cada cidade (city) em relação ao total de vendas global.</strong><br>
        Utilizamos a coluna <code>sales</code> para calcular a participação de cada cidade no total global.
    </li>
    <li><strong>Qual é a cidade com o maior total de vendas (sales) e qual é a sua emissão de CO2 (co2 emission)?</strong><br>
        Identificamos a cidade com o maior valor de <code>sales</code> e analisamos a emissão de <code>co2 emission</code> associada.
    </li>
    <li><strong>Crie uma medida para calcular o total de vendas por categoria (category) e, em seguida, calcule a variação percentual das vendas de cada categoria em relação ao mês anterior.</strong><br>
        Desenvolvemos cálculos para vendas mensais e calculamos a variação percentual ao longo do tempo para cada categoria.
    </li>
    <li><strong>Qual seria a redução nas emissões de CO2 (co2 emission) se o total de vendas (sales) fosse reduzido em 10% para cada cidade?</strong><br>
        Simulamos a redução de 10% nas vendas e calculamos o impacto direto na emissão de <code>co2 emission</code>.
    </li>
</ul>

<p>
Essas fórmulas ilustram como o uso de DAX pode enriquecer a análise de dados, fornecendo insights que vão além do básico, ajudando a <strong>OurTech</strong> a tomar decisões mais embasadas.
</p>

<p>
Confira o dashboard abaixo e explore os insights que podem guiar estratégias sustentáveis de negócios.
</p>
