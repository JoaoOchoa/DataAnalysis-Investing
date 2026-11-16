# DataAnalysis
My investing Data Analysis project.

Primeiro projeto - da plataforma Dio - Ferramenta de controle e projeção de investimentos.

[Ferramenta de projeção de investimentos.xlsx](https://github.com/user-attachments/files/34920841/Ferramenta.de.projecao.de.investimentos.xlsx)


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

<br><img width="528" height="287" alt="image" src="https://github.com/user-attachments/assets/b1fa55b6-13a2-4571-af53-6895feadfb3f" />

<br><img width="501" height="362" alt="image" src="https://github.com/user-attachments/assets/7cea48c5-b46a-40df-b3bd-0823599f39c0" />

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

<img width="867" height="656" alt="image" src="https://github.com/user-attachments/assets/4fbd4947-db72-4500-8d9a-a79a63a4bb5c" />
<img width="866" height="552" alt="image" src="https://github.com/user-attachments/assets/ae903f88-f1c0-4482-aab2-c543a1570d2e" />
<img width="873" height="493" alt="image" src="https://github.com/user-attachments/assets/e9e6ddee-819c-47b9-a76e-3dd8f931d4d1" />
<img width="875" height="657" alt="image" src="https://github.com/user-attachments/assets/62743733-0e1f-4589-9d6b-2700c65ecd7e" />
<img width="867" height="575" alt="image" src="https://github.com/user-attachments/assets/2806aa37-bfa6-4ac0-bcbc-9cb21a6be572" />
<img width="870" height="471" alt="image" src="https://github.com/user-attachments/assets/05382b39-aed4-4cd2-b0b0-849c1985a6ee" />



João Ochôa
