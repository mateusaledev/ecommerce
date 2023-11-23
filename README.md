
# E-commerce Project

Este projeto é uma aplicação distribuída de e-commerce que abrange vários serviços para processar pedidos, detectar fraudes, enviar e-mails, gerar relatórios, entre outras funcionalidades. O projeto utiliza o Apache Kafka para a comunicação assíncrona entre os serviços.

## Módulos

O projeto é dividido em vários módulos, cada um representando um serviço específico ou uma biblioteca comum:

- **service-email**: Serviço responsável pelo envio de e-mails relacionados a novos pedidos.
- **service-fraud-detector**: Serviço que detecta fraudes em novos pedidos.
- **service-log**: Serviço para registro de logs.
- **service-new-order**: Serviço para processamento de novos pedidos.
- **common-kafka**: Biblioteca comum para configurações e utilitários relacionados ao Apache Kafka.
- **service-users**: Serviço relacionado à gestão de usuários.
- **service-http-ecommerce**: Serviço para interações HTTP relacionadas ao e-commerce.
- **service-reading-report**: Serviço para geração de relatórios.
- **service-email-new-order**: Serviço para o envio de e-mails relacionados a novos pedidos.
- **common-database**: Biblioteca comum para configurações e utilitários relacionados a banco de dados.

## Configuração

O projeto utiliza o Maven para construção e gestão de dependências. Cada módulo possui seu próprio arquivo `pom.xml` para configuração específica.

### Dependências Principais

- **Kafka Clients (2.3.1)**
- **SLF4J Simple (1.7.29)**
- **Gson (2.8.6)**

## Como Executar

1. Clone o repositório: `git clone https://github.com/seu-usuario/ecommerce.git`
2. Navegue até o diretório do módulo desejado.
3. Execute a aplicação, por exemplo: `mvn clean install exec:java`

## Contribuição

Contribuições são bem-vindas! Se você identificar problemas, melhorias ou tiver sugestões, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).