Dados relativos ao nº de diplomados em Portugal no ano letivo 2012/2013
ℹ️ Fonte dos dados: Dados extraídos da plataforma dados.gov – portal de dados abertos da Administração Pública (https://dados.gov.pt/) 
Dados.gov é o portal de dados abertos da Administração Pública portuguesa.
Tem como função agregar, referenciar e alojar dados abertos de diferentes organismos e setores da Administração Pública, constituindo-se como o catálogo central de open data em Portugal. Além de funcionar como um serviço partilhado de alojamento e publicação de dados, que pode ser utilizado por qualquer organismo público, funciona também como um portal indexador de conteúdos alojados noutros portais/catálogos de dados abertos, sejam setoriais (ex. Saúde, Justiça, Ambiente) ou locais (ex. Câmara Municipal de Lisboa, Câmara Municipal de Águeda).
O dados.gov promove também casos de reutilizações que utilizam dados partilhados públicos, e disponibiliza informação variada sobre o movimento de dados abertos, publicação e reutilização de dados, entre outros.
O dados.gov é um portal aberto, o que significa que qualquer utilizador, em nome próprio ou em representação de uma organização, pode criar uma conta e carregar dados, para que sejam partilhados com a comunidade, ao abrigo de licenças abertas.
Disponibiliza também vários mecanismos de interação entre fornecedores de dados e reutilizadores, como a possibilidade de trocar comentários, submeter versões complementares de dados e propor melhorias à plataforma.
É desenvolvido e gerido pela Agência para a Modernização Administrativa, IP (AMA), e baseia-se na plataforma udata, um produto criado pelo Etalab, uma estrutura de missão da Administração Pública francesa, e que é desenvolvido e disponibilizado numa lógica open source.

ℹ️ Ficheiro base de trabalho: Alunos diplomados no Ensino Superior (ADES) - dados.gov.pt - Portal de dados abertos da Administração Pública

👁️ Utilização da base de dados: a base de dados escolhida para trabalhar deveu-se ao facto de entre as bases de dados disponíveis ser a que continha os dados mais recentes.



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


</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-y6fn"><span style="font-weight:bold">Nome da coluna</span><br></th>
    <th class="tg-y6fn"><span style="font-weight:bold">Significado</span></th>
    <th class="tg-y6fn"><span style="font-weight:bold">Possíveis valores</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Cod_Estabelecimento</td>
    <td class="tg-0lax">Código atribuído a Instituição MACRO</td>
    <td class="tg-0lax">Integer &gt;=100</td>
  </tr>
  <tr>
    <td class="tg-kftd">Estabelecimento</td>
    <td class="tg-kftd">Nome da Instituição</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax">Cod_UO</td>
    <td class="tg-0lax">Código atribuído a UOE (dentro da instituição)</td>
    <td class="tg-0lax">Integer &gt;=110</td>
  </tr>
  <tr>
    <td class="tg-kftd">UO</td>
    <td class="tg-kftd">Nome da UOE</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-0lax">NUTS1</td>
    <td class="tg-0lax">Nomenclatura das Unidades Territoriais para Fins Estatísticos – Continente e Regiões Autónomas da Madeira e Açores</td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-kftd">NUTS2</td>
    <td class="tg-kftd">Nomenclatura das Unidades Territoriais para Fins Estatísticos – <br>Região Autónomas da Madeira e Açores, Regiões Norte, Centro, <br>Área Metropolitana de Lisboa, Alentejo, Algarve</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-0lax">NUTS3</td>
    <td class="tg-0lax">Nomenclatura das Unidades Territoriais para Fins Estatísticos – <br>Alto Minho, Cávado, Ave, Área Metropolitana do Porto, Alto Tâmega, <br>Tâmega e Sousa, Douro, Terras de Trás-os-Montes, Oeste, Região de Aveiro, <br>Região de Coimbra, Região de Leiria, Viseu Dão e Lafões, Beira Baixa, Médio Tejo, <br>Beiras e Serra da Estrela, Área Metropolitana de Lisboa, Alentejo Litoral, Baixo Alentejo, <br>Lezíria do Tejo, Alto Alentejo, Alentejo Central, Algarve, Regiões Autónomas dos Açores e Madeira</td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Distrito</span></td>
    <td class="tg-kftd">Nome de Distritos</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Concelho</span></td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Conselhos</span></td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-kftd">Subsistema_ensino</td>
    <td class="tg-kftd">Publico ou Privado</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax">Tipo_ensino</td>
    <td class="tg-0lax">Universitário ou Politécnico</td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-kftd">Cod_curso</td>
    <td class="tg-kftd">Código do curso</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">String</span></td>
  </tr>
  <tr>
    <td class="tg-0lax">Curso</td>
    <td class="tg-0lax">Nome do Curso</td>
    <td class="tg-0lax">String</td>
  </tr>
  <tr>
    <td class="tg-kftd">Nivel_forma</td>
    <td class="tg-kftd">Nível de formação (Licenciatura, Mestrado, Doutoramento)</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax">Cnaef_cod_grande_grupo</td>
    <td class="tg-0lax">Código de Classificação Nacional de Áreas de Educação e Formação – Grande Grupo</td>
    <td class="tg-0lax">String</td>
  </tr>
  <tr>
    <td class="tg-kftd">Cnaef_grande_grupo</td>
    <td class="tg-kftd">Nome de Classificação Nacional de Áreas de Educação e Formação – Grande Grupo</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax">Cnaef_cod_area_estudo</td>
    <td class="tg-0lax">Código de Classificação Nacional de Áreas de Educação e Formação – Área de Estudo</td>
    <td class="tg-0lax">Integer &gt;=140</td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Cnaef_area_estudo</span></td>
    <td class="tg-kftd">Nome de Classificação Nacional de Áreas de Educação e Formação – Área de Estudo</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Cnaef_cod_area_edu_forma</span></td>
    <td class="tg-0lax">Código de Classificação Nacional de Áreas de Educação e Formação – Área de Educação e Formação</td>
    <td class="tg-0lax">Integer &gt;=142</td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Cnaef_area_edu_forma</span></td>
    <td class="tg-kftd">Nome de Classificação Nacional de Áreas de Educação e Formação – Área de Educação e Formação</td>
    <td class="tg-kftd">String</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Total</span></td>
    <td class="tg-0lax">Número total de diplomados por CNAEF – Área de Educação e Formação</td>
    <td class="tg-0lax">Integer &gt;=0</td>
  </tr>
  <tr>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Sexo_h</span></td>
    <td class="tg-kftd">Número total de diplomados do sexo masculino - CNAEF – Área de Educação e Formação</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Integer &gt;=0</span></td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Sexo_m</span></td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Número total de diplomados do sexo feminino - CNAEF – Área de Educação e Formação</span></td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Integer &gt;=0</span></td>
  </tr>
  <tr>
    <td class="tg-kftd">Estrangeiro</td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Número total de diplomados de nacionalidade estrangeira - CNAEF – Área de Educação e Formação</span></td>
    <td class="tg-kftd"><span style="font-weight:normal;font-style:normal;text-decoration:none">Integer &gt;=0</span></td>
  </tr>
  <tr>
    <td class="tg-0lax">Portugues</td>
    <td class="tg-0lax">Número total de diplomados de nacionalidade portuguesa - CNAEF – Área de Educação e Formação</td>
    <td class="tg-0lax"><span style="font-weight:normal;font-style:normal;text-decoration:none">Integer &gt;=0</span></td>
  </tr>
</tbody>
</table>


----------------------------------------------------------------------------------------
💡 Contexto
O sistema educativo português encontra-se regulado pela Lei de Bases do Sistema Educativo e é desenvolvido em três níveis: ensino básico, secundário e superior.
O ensino superior português organiza-se num sistema binário que integra o ensino universitário e o ensino politécnico e é ministrado em instituições públicas e privadas. Os estabelecimentos de ensino superior privado obtêm reconhecimento de interesse público prévio do Governo.

O ensino universitário inclui as universidades, os institutos universitários e outros estabelecimentos de ensino universitário. O ensino politécnico compreende os institutos politécnicos e outros estabelecimentos de ensino politécnico.
Estrutura dos graus e diplomas do ensino superior
Em 2005 foi iniciado um processo de reforma da Lei de Bases do Sistema Educativo de modo a implementar o Processo de Bolonha, tendo sido introduzido o European Credit Transfer System (ECTS) nos ciclos de estudo, mecanismos de mobilidade, suplemento ao diploma, entre outros. 
O ensino superior passou a ter uma nova estrutura de três ciclos de estudos, conducentes aos graus académicos de licenciado, mestre e doutor. Esta estrutura foi introduzida em 2006 e totalmente implementada, em Portugal, a partir do ano letivo de 2009/2010. 
Foram também estabelecidos, para cada ciclo de estudos, descritores de qualificação genéricos, com base nas competências adquiridas, assim como a definição de intervalos ECTS para o primeiro e segundo ciclo de estudos.
Em 2014, foi criado um ciclo de estudos superior não conferente de grau académico, denominado curso técnico superior profissional, que corresponde ao ciclo de estudos curto ligado ao 1.º ciclo previsto no Quadro de Qualificações do Espaço Europeu do Ensino Superior.
Informações retiradas de: dges.pt

💡 Tratamento de dados
Considerando o atual contexto social e tendo como princípio a questão da “atribuição de um grau académico” optou-se por apenas tratar os dados relativos às Licenciaturas, Mestrados e Doutoramentos, na medida em que os cursos de CTeSP e Pós-Graduações – presentes no ficheiro original, não atribuem aos seus diplomados um grau académico, mas sim uma especialização.
Pelo contexto profissional dos participantes e pelo contexto académico, consideramos que no desenvolvimento e tratamento destes dados seria, igualmente, interessante e relevante a distinção, não só dos diplomados que se formaram através do ensino superior público e/ou privado, como dos diplomados que se formaram através do ensino superior universitário e politécnico.
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
http://www.tablesgenerator.com/

💡 Legislação útil

LEI N.º 46/86, DE 14 DE OUTUBRO - LEI DE BASES DO SISTEMA EDUCATIVO
Lei nº 46/86, de 14 de outubro

LEI N.º 62/2007, DE 10 DE SETEMBRO - REGIME JURÍDICO DAS INSTITUIÇÕES DE ENSINO SUPERIOR
Lei nº 62/2007, de 10 de setembro

DECRETO-LEI N.º 74/2006, DE 24 DE MARÇO - GRAUS E DIPLOMAS DO ENSINO SUPERIOR
Decreto-Lei nº 74/2006, de 24 de março

LEI N.º 38/2007, DE 16 DE AGOSTO - AVALIAÇÃO DO ENSINO SUPERIOR
Lei nº 38/2007, de 16 de agosto



💡 Outras informações
Para o desenvolvimento deste trabalho os alunos consultaram páginas e respetivo código disponíveis na internet e nos respetivos sites dedicados a esta temática.
As aulas lecionadas e o material partilhado pelo docente da unidade curricular, Prof. Doutor João Orvalho, foram igualmente preponderantes para o desenvolvimento e organização deste trabalho.
