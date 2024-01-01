# github-integration-example

Exemplo de como integrar o Threagile em fluxos de trabalho do GitHub:

Este repositório de exemplo atua como uma espécie de modelo para ver a integração do Threagile em um fluxo de trabalho do GitHub em ação. Use e modifique de acordo com o que melhor se encaixa no seu fluxo de trabalho. Normalmente aqui seria um projeto real com fonte real e outras coisas. Além disso, esse repositório contém um arquivo threagile.yaml, que contém a entrada do modelo de ameaça (consulte os documentos do Threagile para obter informações sobre isso). Aqui estamos usando o arquivo YAML de exemplo Threagile como uma entrada de modelo de ameaça de exemplo.

### Integração do fluxo de trabalho do GitHub
Este repositório de exemplo tem um fluxo de trabalho do GitHub associado, que executa um trabalho quando o arquivo de modelo Threagile (threagile.yaml) é alterado em um push (consulte o arquivo .github/workflows/main.yaml para isso).

Esse fluxo de trabalho executa a ação run-threagile (publicada no mercado de ações do GitHub como open-source) para trabalhar no arquivo de modelo de ameaça threagile.yaml e gerar o diagrama de fluxo de dados (DFD), relatório de modelo de ameaça (PDF), exportações de Excel e JSON, etc. em cada alteração de threagile.yaml.

O conjunto completo de resultados gerados é preservado como artifcats da ação (consulte a guia ações). Além disso, o diagrama de fluxo de dados e o relatório de modelo de ameaça são salvos na árvore de origem (na pasta threagile/output) para referência automática adicional de dentro desse README.md (ou qualquer outro arquivo de markdown) no repositório.

Sinta-se à vontade para modificar o fluxo de trabalho de acordo com o que melhor se adapta ao seu cenário.

Veja abaixo... ;)



### Análise do Modelo de Ameaças
O kit de ferramentas de código aberto para modelagem ágil de ameaças, Threagile, foi usado para modelar e analisar ameaças potenciais.

### Diagrama de fluxo de dados (DFD)
O seguinte DFD foi gerado pelo Threagile durante a análise do modelo de ameaças:

![Data-Flow Diagram (DFD)](/threagile/output/data-flow-diagram.png?raw=true "Data-Flow Diagram (DFD)")

### Relatório do Modelo de Ameaças
O relatório a seguir foi gerado pelo Threagile durante a análise do modelo de ameaça:
[Threat Model Report](/threagile/output/report.pdf?raw=true)

