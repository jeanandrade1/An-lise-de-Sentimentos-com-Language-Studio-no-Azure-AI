# Prática Análise de Sentimentos com Language Studio no Azure AI

Criação Recurso Speech to Text

## Criação de recurso de Speech to Text

Ir em criar recursos

- selecionar a categoria **IA + Machine Learning**
- Selecionar **Language** clicando ****em **criar**

[![Captura de Tela 2025-06-29 às 22.04.13.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.04.13.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%201.png)](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%201.png)

Clicar em **Continue to create resource**

![Captura de Tela 2025-06-29 às 22.06.05.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%202.png)

Na aba “**Noções básicas**”

- Selecionar a assinatura
- Criar o grupo de recursos caso não tenha um existente
- Selecionar a região (preferencialmente EUA por ser mais barato)
- Insira o nome
- Clicar em “**Examinar + criar**”

![Captura de Tela 2025-06-29 às 22.09.27.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.09.27.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%203.png))

## Portal Language Studio

Ir para [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)

Selecionar a subscrição, recurso Language e o recurso criado anteriormente

![Captura de Tela 2025-06-29 às 22.16.51.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.16.51.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%204.png))

Ir em **Classify text**

Selecionar **Analyze sentiment and mine opinions**

![Captura de Tela 2025-06-29 às 22.18.06.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.18.06.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%205.png))

Selecione a lingua e o recurso que será utilizado e insira um texto para avaliação. 

Exemplo: Um review de um hotel como o abaixo

> Review Hotel
> 
> 
> **1. Recepção desorganizada**
> 
> Cheguei às 15h e havia apenas uma pessoa atendendo, que parecia sobrecarregada e pouco disposta a ajudar. Esperei 20 minutos até conseguir entregarei meus documentos, sem nenhum pedido de desculpas.
> 
> **2. Quarto com limpeza duvidosa**
> 
> Ao entrar, encontrei manchas na roupa de cama e nos travesseiros. O chão estava visivelmente sujo (papéis e cascas de fruta no canto), como se não fosse varrido há dias. Solicitei um novo enxoval, mas só chegaram quase 2 horas depois — e ainda com a cadeira da escrivaninha manchada.
> 
> **3. Wifi precário e sem opções de amenidades**
> 
> O Wi‑Fi literalmente caiu em várias ocasiões — fiquei sem sinal por cerca de 6 horas no primeiro dia, prejudicando meus planos e trabalho remoto. Não havia sequer uma oferta básica de chá ou café no corredor — algo que é padrão na maioria dos hotéis.
> 
> **4. Café da manhã decepcionante**
> 
> No buffet, várias opções já estavam vazias às 8h30. Os itens disponíveis estavam frios ou sem reposição. Pedi à pessoa responsável e fui ignorado. Acabei saindo para comer fora.
> 
> **5. Atendimento negligente**
> 
> Pedi toalhas extras por telefone e disseram que entregariam “já já” — mas nunca chegaram. Quando desci à recepção para cobrar, a atendente disse que “não havia pedido registrado”. Senti que prometeram para evitar discussão, mas sem nenhuma ação concreta.
> 

Aceite os termos e clique em R**un**

![Captura de Tela 2025-06-29 às 22.22.17.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.22.17.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%206.png))

![Captura de Tela 2025-06-29 às 22.22.41.png]([Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.22.41.png](https://github.com/jeanandrade1/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/blob/main/images/Captura%207.png))

Próximo passo importar o SDK para a aplicação

![Captura de Tela 2025-06-29 às 22.28.06.png](Pra%CC%81tica%20Ana%CC%81lise%20de%20Sentimentos%20com%20Language%20Stud%2022220fca93d1803ba176d3e99d16995a/Captura_de_Tela_2025-06-29_as_22.28.06.png)
