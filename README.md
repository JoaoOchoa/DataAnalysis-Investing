# DataAnalysis
My investing Data Analysis project.

Primeiro projeto - da plataforma Dio.

[Ferramenta de projeção de investimentos.xlsx](https://github.com/user-attachments/files/34919542/Ferramenta.de.projecao.de.investimentos.xlsx)


Ferramenta de controle e projeção de investimentos.

Para que serve a ferramenta?

Ferramenta faz uma projeção simples de investimentos.

A partir do preenchimento do campo salário, a ferramenta sugere o investimento de 30% e mostra o valor.

A partir do preenchimento do Rendimento da carteira, a ferramenta calcula os seguintes cenários:
    <br>&emsp;- Patrimônio e dividendos em 2 anos;
    <br>&emsp;- Patrimônio e dividendos em 5 anos;
    <br>&emsp;- Patrimônio e dividendos em 10 anos;
    <br>&emsp;- Patrimônio e dividendos em 20 anos;
    <br>&emsp;- Patrimônio e dividendos em 30 anos;
    
A partir do preenchimento do perfil de investimento, dividido em: conservador, moderado e agressivo, a ferramenta trás:
    <br>&emsp;- Porcentual a ser investido em renda fixa;
    <br>&emsp;- Porcentual a ser investido em renda variável;

Com base no perfil de investidor e nos porcentuais de renda fixa e variável, a ferramenta divide cada uma delas da seguinte maneira:
    <br>&emsp;- Renda fixa:
        <br>&emsp;&emsp;- Pós-Fixado
        <br>&emsp;&emsp;- Pré-Fixado
        <br>&emsp;&emsp;- Inflação
    <br>&emsp;- Renda Variável:
        <br>&emsp;&emsp;- Ações
        <br>&emsp;&emsp;- Fundos Imobiliários

Ainda com base no perfil do investidor, e aporte indicado pelo usuário, a ferramenta mostra sugestão de porcentual e valor por categoria, conforme abaixo:
    <br>&emsp;- FIIs
        <br>&emsp;&emsp;- Papel; Tijolo; Híbrido; FoF; Desenvolvimento; Hotelaria
    <br>&emsp;- Ações:
        <br>&emsp;&emsp;- Dividendos; Valor; Crescimento; Small Caps
    <br>&emsp;- Renda Fixa:
        <br>&emsp;&emsp;- Pós-Fixado; Pré-Fixado; Inflação

Como o VF e o PROCV entram nos cálculos?
<br>VF foi utilizado para fazer as simulações do valor do patrimônio futuro do usuário.

<br>Procv foi utilizada para fazer o preenchimento dinâmico dos porcentuais sugeridos de investimento para cada perfil e categoria de investimento.

<br>Foram criados os intervalos nomeados: salario; rendimento_carteira; sugestao_investimento; aporte; qtd_anos; taxa_mensal

<br>Os percentuais de cada perfil foram definidos após pesquisa na internet.

<img width="493" height="207" alt="image" src="https://github.com/user-attachments/assets/94aa78f7-cde0-4944-bd24-038b419f2ee9" />

<br><img width="496" height="283" alt="image" src="https://github.com/user-attachments/assets/def26cf3-0000-40d7-ba8f-d0e81512548b" />

<br><img width="527" height="283" alt="image" src="https://github.com/user-attachments/assets/178f55ea-466a-4cf4-994e-7c794542481e" />

<br><img width="495" height="366" alt="image" src="https://github.com/user-attachments/assets/a519e4ed-f45c-48b9-a2ed-948315fe1610" />

<br><img width="530" height="522" alt="image" src="https://github.com/user-attachments/assets/4bff430e-f92c-4a72-9907-f099cfbf8766" />


O que você mudou em relação à ferramenta do Expert:

Alterações em relação à ferramenta do Expert: 
<br>&emsp;-Adicionei a divisão entre renda fixa e variável, dentro da renda fixa, adicionei 3 categorias: Pós-Fixado; Pré-Fixado; Inflação;
<br>&emsp;-Adicionei a divisão entre ações e FIIs;
<br>&emsp;-Adicionei a divisão das ações nas seguintes categorias: Dividendos; Valor; Crescimento; Small Caps
<br>&emsp;-Adicionei proteção nas tabelas, para que o usuário altere somente os campos de entrada de dados e não as fórmulas

Seguem prints de simulações:
<br>Salário: R$4.500,00
<br>Perfis: Agressivo e conservador:

<img width="822" height="832" alt="image" src="https://github.com/user-attachments/assets/43facf68-20f7-44e4-ac6c-223a9b740efd" />
<img width="817" height="818" alt="image" src="https://github.com/user-attachments/assets/9cfcb3bb-f722-4fcb-8918-b275d3ba6cc0" />
<img width="831" height="835" alt="image" src="https://github.com/user-attachments/assets/33f3a83c-1ac6-4f25-937e-834faf24915f" />
<img width="821" height="817" alt="image" src="https://github.com/user-attachments/assets/b05e9221-7953-4c81-81c6-bda176ba5893" />


João Ochôa
