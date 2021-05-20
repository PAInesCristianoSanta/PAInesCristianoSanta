👁️ Aplicações deste repositório
Este é um trabalho académico em desenvolvimento no âmbito da unidade curricular de Programação e Algoritmos 2, do 1º ano do curso de Comunicação e Design Multimédia ministrado na Escola Superior de Educação de Coimbra, do Politécnico de Coimbra.

Sendo um trabalho em desenvolvimento ainda não nos é possível aferir as aplicações deste repositório. Contudo acreditamos que este trabalho poderá ser uma referências para outros trabalhos desenvolvidos no futuro.

--------------------------------------------------------------------------------------------------------------------------
🧱 Estrutura
O repositório está organizado da seguinte forma:
•	data.csv: Dados extraídos da dashboard Diplomados 12_13
•	jupyter
•	projeto
----------------------------------------------------------------------------------------

📔 Dicionário dos dados
Uma explicação do conteúdo em data.csv.

Nome da coluna	Significado	Possíveis valores
Código Estabelecimento	Código atribuído a Instituição MACRO	Integer >=100
Estabelecimento	Nome da Instituição	String
Código Unidade Orgânica	Código atribuído a UOE (dentro da instituição)	Integer >=110
Unidade Orgânica	Nome da UOE	String
NUTS I	Nomenclatura das Unidades Territoriais para Fins Estatísticos – Continente e Regiões Autónomas da Madeira e Açores
	String
NUTS II	Nomenclatura das Unidades Territoriais para Fins Estatísticos –Região Autónomas da Madeira e Açores, Regiões Norte, Centro, Área Metropolitana de Lisboa, Alentejo, Algarve
	String
NUTS III	Nomenclatura das Unidades Territoriais para Fins Estatísticos –Alto Minho, Cávado, Ave, Área Metropolitana do Porto, Alto Tâmega, Tâmega e Sousa, Douro, Terras de Trás-os-Montes, Oeste, Região de Aveiro, Região de Coimbra, Região de Leiria, Viseu Dão e Lafões, Beira Baixa, Médio Tejo, Beiras e Serra da Estrela, Área Metropolitana de Lisboa, Alentejo Litoral, Baixo Alentejo, Lezíria do Tejo, Alto Alentejo, Alentejo Central, Algarve, Regiões Autónomas dos Açores e Madeira
	String
Distrito	Nome de Distritos	String
Concelho 	Nome de Conselhos	String
Subsistema de Ensino	Publico ou Privado	String
Tipo de Ensino	Universitário ou Politécnico	String
Código Curso	Código do curso	String
Curso	Nome do Curso	String
NÍvel de Formação	Nível de formação (Licenciatura, Mestrado, Doutoramento)	String
CNAEF - Código Grande Grupo	Código de Classificação Nacional de Áreas de Educação e Formação – Grande Grupo	Integer >=100
CNAEF - Grande grupo	Nome de Classificação Nacional de Áreas de Educação e Formação – Grande Grupo	String
CNAEF - Código Área de Estudo	Código de Classificação Nacional de Áreas de Educação e Formação – Área de Estudo	Integer >=140
CNAEF - Área de Estudo	Nome de Classificação Nacional de Áreas de Educação e Formação – Área de Estudo	String
CNAEF - Código Área de Educação e Formação	Código de Classificação Nacional de Áreas de Educação e Formação – Área de Educação e Formação	Integer >=142
CNAEF - Área de Educação e Formação	Nome de Classificação Nacional de Áreas de Educação e Formação – Área de Educação e Formação	String
Total	Número total de diplomados por CNAEF – Área de Educação e Formação	Integer >=0
Sexo M – CONFIRMAR	Número total de diplomados do sexo masculino - CNAEF – Área de Educação e Formação	Integer >=0
Sexo F - CONFIRMAR	Número total de diplomados do sexo masculino - CNAEF – Área de Educação e Formação	Integer >=0
Nacionalidade Estrangeira - CONFIRMAR	Número total de diplomados de nacionalidade estrangeira - CNAEF – Área de Educação e Formação	Integer >=0
Nacionalidade Portuguesa - CONFIRMAR	Número total de diplomados de nacionalidade portuguesa - CNAEF – Área de Educação e Formação	Integer >=0

----------------------------------------------------------------------------------------
💡 Contexto

💡 Tratamento de dados
Considerando o atual contexto social e tendo como princípio a questão da “atribuição de um grau académico” optou-se por apenas tratar os dados relativos às Licenciaturas, Mestrados e Doutoramentos, na medida em que os cursos de CTeSP e Pós-Graduações – presentes no ficheiro original, não atribuem aos seus diplomados um grau académico, mas sim uma especialização.
💡 Problemas, inconsistências e melhorias
Algumas das questões detetadas ao longo do tratamento de dados, prenderam-se, sobretudo com a questão da não uniformização das denominações, quer das áreas de estudo, quer o nível de Formação.
Como tal e de forma a tratarmos os dados com maior precisão, optámos por atribuir a mesma denominação aos níveis de Formação.
💡 Bibliografia
https://github.com/dssg-pt/covid19pt-data
https://dados.gov.pt/pt/docs/about_dadosgov/
https://dados.gov.pt/pt/datasets/alunos-diplomados-no-ensino-superior/#_
https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html#sphx-glr-gallery-lines-bars-and-markers-barchart-py
https://matplotlib.org/stable/gallery/index.html
http://localhost:8889/notebooks/PA2/barchart.ipynb
http://localhost:8889/notebooks/PA2/Aula%2021%2C%2028%20Abril%20e%205%20de%20Maio%20-%20Python%20Maltplotlib%20exercicios.ipynb
https://www.dges.gov.pt/ 

💡 Outras informações
Para o desenvolvimento deste trabalho os alunos consultaram páginas e respetivo código disponíveis na internet e nos respetivos sites dedicados a esta temática.
As aulas lecionadas e o material partilhado pelo docente da unidade curricular, Prof. Doutor João Orvalho, foram igualmente preponderantes para o desenvolvimento e organização deste trabalho.



<!--
**PAInesCristianoSanta/PAInesCristianoSanta** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
