<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da Computação</a></h3>


<font size="+12"><center>
Sistema Falcão Sombrio para Drones
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#descrição-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#analise-de-requisitos-funcionais-e-nao-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades)
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)


# Autores

* Henrique Brainer Costa
* Henrique Lemos Parrera Silva Catanha
* João Pedro Queiroz de Andrade
* João Victor Vidal Barbosa 

# Descrição do Projeto

A Securus Dynamic, empresa reconhecida internacionalmente pelo desenvolvimento de drones bélicos equipados com inteligência artificial e tecnologias avançadas para combate, tem como principal produto uma frota de drones de nome Aquila-X e está desenvolvendo um sistema de operação remota e autônoma para esses drones chamado de Falcão Sombrio. No entanto, foram observadas falhas na arquitetura desse sistema e por isso contratou nosso serviço de consultoria da Cyber Bullet System para desenvolver um banco de dados eficiente e reformular a arquitetura do sisetma para operações críticas dos drones.

# Análise de Requisitos Funcionais e Não Funcionais
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

## Requisitos Não-Funcionais

| ID | Nome | Descrição |
| -- | ---- | --------- |
| RNF01 | Segurança | O sistema deve ter protocolos e criptografia para manter a comunicação segura entre o drone e o operador |
| RNF02 | Banco de Dados | O Banco de Dados deve utilizar NoSQL distruibuido |
| RNF03 | Logs e auditoria | O sistema deve possuir logs de registros de atualizações e modifcações do sistema feita pelos operadores |
| RNF04 | Interface | O sistema deve conter uma interface intuitiva |
| RNF05 | Autenticação | O sistema deve garantir a confiabilidade dos operadores |
| RNF06 | Eficiência | O sistema deve utilizar algoritmos otizimados para melhor desempenho e velocidade|
| RNF07 | Falhas | O sistema deve registrar falhas de operações |


# Diagrama de Atividades
![Diagrama de Atividades](https://github.com/GrupoMicroondas/UML-Classroom-FCI/blob/c148f668b9a9ab5a8e80600c9483384272674f9c/docs/imgs/printDiaddeAtivs.png)
# Diagrama de Casos de Uso
![Diagrama de Atividades](https://github.com/GrupoMicroondas/UML-Classroom-FCI/blob/2fd46ea979d3845b388bab60eadbe8c4644e5950/docs/imgs/diagCasosUso.png)
