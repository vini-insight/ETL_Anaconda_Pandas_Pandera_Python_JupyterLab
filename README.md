###### ETL_Anaconda_Pandas_Pandera_Python_JupyterLab
# ETL Fundamentals with Anaconda Pandas Pandera Python JupyterLab

### Goals

This project intends to learn ETL (Extract, Transform, Load) Extraction, Validation, Cleaning and Data Transformation.

To achieve this goal, we will use Open Data from the [Center for Investigation and Prevention of Aeronautical Accidents](https://www2.fab.mil.br/cenipa/). It is the body of the Aeronautics Command responsible for the investigation of aeronautical accidents in civil aviation and the Brazilian Air Force.

After applying ETL techniques to these data, we will create data models to facilitate understanding, representation and availability of new information, for example: filtering occurrences by city, state, day, number of occurrences by classification, among others. With this new knowledge, they can be used to make important decisions that will reduce the number of aeronautical incidents or accidents.

### Data Source

We use as an example a file with aeronautical occurrence data available [HERE](https://dados.gov.br/dataset/ocorrencias-aeronauticas-da-aviacao-civil-brasileira/resource/9d8a7e09-5f75-47b3-891b-b5f1bab26d59)

In this project, we are not going to use all the data from the original spreadsheet. Let's delete some columns from the original spreadsheet. The following columns will be excluded:

codigo_ocorrencia1, codigo_ocorrencia3, codigo_ocorrencia4, ocorrencia_latitude, ocorrencia_longitude, ocorrencia_pais, investigacao_aeronave_liberada, investigacao_status, divulgacao_relatorio_numero, divulgacao_relatorio_publicado, divulgacao_dia_publicacao, total_aeronaves_envolvidas, ocorrencia_saida_pista.

This leaves only nine columns in the .CSV source file.
