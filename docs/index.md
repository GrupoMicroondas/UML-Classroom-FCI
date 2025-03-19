<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da Computação</a></h3>


<font size="+12"><center>
Sistema Falcão Sombrio para Drones
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades)
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)


# Autores

* Henrique Brainer Costa
* Henrique Lemos Parrera Silva Catanha
* João Pedro Queiroz de Andrade
* João Victor Vidal Barbosa 

# Descrição do Projeto

A Securus Dynamic, empresa reconhecida internacionalmente pelo desenvolvimento de drones bélicos equipados com inteligência artificial e tecnologias avançadas para combate, tem como principal produto uma frota de drones de nome Aquila-X e está desenvolvendo um sistema de operação remota e autônoma para esses drones chamado de Falcão Sombrio. No entanto, foram observadas falhas na arquitetura desse sistema e por isso contratou nosso serviço de consultoria da Cyber Bullet System para desenvolver um banco de dados eficiente e reformular a arquitetura do sisetma para operações críticas dos drones.

# Análise de Requisitos Funcionais e Não-Funcionais
## Requisitos Funcionais

| ID | Nome | Descrição |
| -- | ---- | --------- |
| RF01 | Controle | O controle dos drones devem ser realizados de forma remota e/ou autônomas | 
| RF02 | Sensores | Os sistema deve receber e interpretar o sensoriamento do ambiente que os drones se encontram via LIDAR, câmeras e GPS |
| RF03 | Robustez | O sistema deve ser capaz de interpretar e detectar ameaças em tempo real e reagir de forma coerente ao contexto |
| RF04 | Conexão | O sistema deve conter mecanismos de fallback para evitar a perda de conexão |
| RF05 | Registro de Missões | O sistema deve armazenar eventos ocorridos com os drones nas missões performadas |
| RF06 | Interface de Controle | Os dados de telemetria, status e comandos a serem realizados pelos drones devem ser apresentados por meio de uma interface gráfica para os operadores |
| RF07 | Autenticação | O sistema deve conter um processo de autenticação biometria e em dois fatores para os operadores |
| RF08 | Segurança de Comunicação | A comunicação do sistema com os drones deve ser realizada com criptografia para garantir a integridade das partes |


- Controle remoto e autônomo dos drones
- Sensoriamento do ambiente via LIDAR, câmeras e GPS
- Detecçao e evasão de ameaças em tempo real
- Mecanismos de fallback para evitar perda de conexão
- Logs de missões realizadas e eventos críticos
- Banco de dados NoSQL distribuído para dados em tempo real 
## Requisitos Não-Funcionais
- Interface para gerenciamento de frotas de drones
- Dashboard em tempo real com telemetria
- Protocolos para comunicação segura e em tempo real com os drones
- Criptografia de ponta e assinaturas digitais
- Autenticação de operadores via biometria e autenticaçao multifator

| ID | Nome | Descrição |
| -- | ---- | --------- |
| RNF01 | Segurança | O sistema deve ter protocolos e criptografia para manter a comunicação segura com os drones |
| RNF02 | Banco de Dados | O sistema deve utilizar NoSQL distruibuido |
| RNF03 |      |           |
|    |      |           |
|    |      |           |
|    |      |           |
|    |      |           |


# Diagrama de Atividades

# Diagrama de Casos de Uso
