                                      ,---------------------------------------.                               
                                      |iPhone                                 |                               
                                      |---------------------------------------|                               
                                      |-model: String                         |                               
                                      |-serialNumber: String                  |                               
                                      |+tocar(): void                         |                               
                                      |+pausar(): void                        |                               
                                      |+selecionarMusica(musica: String): void|                               
                                      |+ligar(numero: String): void           |                               
                                      |+atender(): void                       |                               
                                      |+iniciarCorreioVoz(): void             |                               
                                      |+exibirPagina(url: String): void       |                               
                                      |+adicionarNovaAba(): void              |                               
                                      |+atualizarPagina(): void               |                               
                                      `---------------------------------------'                               
                                                          |                                                   
                                                          |                                                   
,---------------------------------------.  ,----------------------------.   ,--------------------------------.
|ReprodutorMusical                      |  |AparelhoTelefonico          |   |NavegadorInternet               |
|---------------------------------------|  |----------------------------|   |--------------------------------|
|+tocar(): void                         |  |+ligar(numero: String): void|   |+exibirPagina(url: String): void|
|+pausar(): void                        |  |+atender(): void            |   |+adicionarNovaAba(): void       |
|+selecionarMusica(musica: String): void|  |+iniciarCorreioVoz(): void  |   |+atualizarPagina(): void        |
`---------------------------------------'  `----------------------------'   `--------------------------------'
