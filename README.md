# Projeto da disciplina de Sistemas Distribuidos ( Projetos interdisciplinar de Sistemas de Informação IV)

### Contextualização da arquitetura
A Arquitetura do projeto inicialmente estava projetada para na extração utilizar o serviço AWS lambda para extração dos dados da api da PCR ( Prefeitura do Recife ) e do FNDE ( Fundo Nacional de Desenvolvimento da Educação), entretanto por instabilidades nas APIs decidi por fazer a extração manualmente visto que esse processo não se repetiria com freqência apenas a cada ano para atualização do modelo. Assim ele é carregado para os meus buckets da s3 e de lá eu faço o tratamento de dados com uma instancia do Jupyter Notebooks utilizando o serviço do AWS SageMaker.

### Pipeline
Pipeline de Extração, Tratamento e Carregamento de dados do Modelo
![image](https://user-images.githubusercontent.com/45744959/169662568-416b7230-522c-43f0-a60b-0b87c7a4a0fa.png)



