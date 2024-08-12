# Rede Social de Música
## Diagrama

![Diagrama](./DER-RSM.png)

## Dicionário de Dados


| Entidade| Atributo|Tipo|Tamanho|Descrição|                                                   
|-|-|-|-|-|
| **Usuário**| Nome | Varchar | 100 | Identificação do usuário|
| **Usuário** | Idade | Int |  | Observações sobre o usuário    |                                    
| **Usuário** | Foto |Varchar|255| Identificação do usuário|
|**Usuário** |Data de Nascimento | Date | | Identificação do usuário|
| **Playlist**  | Número ||| Identificador único da playlist|
| **Playlist**| Usuário|Varchar|100| Quem criou a playlist|
| **Playlist**| Data | Date||Quando foi criada|
| **Playlist**| Músicas |Varchar|100| Quais estão presentes na playlist|
| **Música** | Código |Int|| Identificador da playlist|
| **Música** | Título |Varchar|100| Nome da música|
| **Música**| Duração |Int|| Duração da música|
| **Like** | Data | Date || Quando foi deixado o like|
| **Like**| Número da Playlist|Int|| Identificação da playlist|
| **Like**|Id_user| Int||Identificação do usuário|
 
***Produzido por Beatriz e Laila***