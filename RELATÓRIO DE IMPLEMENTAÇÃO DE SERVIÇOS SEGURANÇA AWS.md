# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 08/03/2024
Empresa: Abstergo Industries 
Responsável: Igor Fonsêca Vilar da Rocha

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Igor Fonsêca Vilar da Rocha. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Autenticação Multifator
- A MFA é uma prática recomendada do AWS Identity and Access Management (IAM) que exige um segundo fator de autenticação, além das credenciais de login com nome de usuário e senha. É possível habilitar a MFA no nível da conta da AWS e para usuários raiz e do IAM que você criou na sua conta. Com a MFA habilitada, quando um usuário faz login no Console de Gerenciamento da AWS, ele é solicitado a fornecer o nome de usuário e a senha ( algo que ele sabe), bem como um código de autenticação de seu dispositivo de MFA ( algo que ele tem ou, no caso de usar um autenticador habilitado para biometria, algo que ele é). Juntos, esses fatores reforçam a segurança de suas contas e recursos da AWS.

Medida 2: Amazon Inspector
- O Amazon Inspector detecta automaticamente as workloads, como instâncias do Amazon EC2, contêineres e funções do Lambda, e as verifica em busca de vulnerabilidades de software e exposição não intencional da rede. Com este serviço, a Abstergo Industries terá gerenciamento de vulnerabilidade automatizado e contínuo em escala.

Medida 3: Amazon CloudWatch
- O Amazon CloudWatch é um serviço que monitora aplicações, responde às mudanças de desempenho, otimiza o uso de recursos e fornece insights sobre a integridade operacional. Ao coletar dados de todos os recursos da AWS, o CloudWatch fornece visibilidade sobre o desempenho de todo o sistema e permite que os usuários definam alarmes, reajam automaticamente às mudanças e obtenham uma visão unificada da integridade operacional.


## Conclusão
A implementação dessas ferramentas na empresa Abstergo Industries tem como esperado fornecer mais segurança para os dados e serviços da empresa, assim como para usuários AWS que fazem o gerenciamento e atuam nas contas. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto:

Igor Fonsêca Vilar da Rocha
