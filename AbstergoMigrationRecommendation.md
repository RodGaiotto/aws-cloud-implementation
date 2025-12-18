# RELATORIO DE MIGRACAO PARA AWS

Data: 18/12/2025
Empresa: Abstergo Industries 
Responsavel: Rodrigo Gaiotto

## Introducao
Este relatorio apresenta o processo de implementacao de ferramentas na empresa Abstergo Industries, realizado por Rodrigo Gaiotto.
O objetivo do projeto foi elencar 3 servicos AWS, com a finalidade de realizar diminuicao de custos imediatos.

## Descricao do Projeto
O projeto de implementacao de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especi­ficos. A seguir, serao descritas as etapas do projeto:

Etapa 1:
- Amazon EC2 com Auto Scaling
- Foco da ferramenta: Ajuste automático de capacidade e redução de custos operacionais
- Descrição de caso de uso: Ambientes on‑premises exigem compra antecipada de servidores,
  licenças e infraestrutura de refrigeração, além de manutenção contínua. Isso gera custos fixos altos e
  capacidade ociosa. Com EC2 e Auto Scaling, a empresa paga apenas pela capacidade realmente utilizada,
  podendo reduzir entre 30% e 60% dos custos de computação ao eliminar superprovisionamento.
  Além disso, instâncias Spot podem reduzir o custo de workloads não críticos em até 90%.
  O resultado é uma infraestrutura elástica, mais barata e mais eficiente.

Etapa 2: 
- Amazon S3
- Foco da ferramenta: Armazenamento escalável, durável e com custo otimizado
- Descrição de caso de uso: Soluções on‑premises de armazenamento exigem compra de discos, expansão de racks,
 manutenção de SAN/NAS, energia e refrigeração. O Amazon S3 substitui esse modelo com armazenamento praticamente
 ilimitado e cobrança por uso. Ao migrar backups, arquivos estáticos e dados históricos para S3, empresas reduzem
 custos de armazenamento em 40% a 80%, especialmente ao usar classes como S3 Glacier e Glacier Deep Archive para
 arquivamento de longo prazo. A durabilidade de 99,999999999% (11 9s) elimina a necessidade
 de replicações físicas complexas.

Etapa 3: 
- AWS Lambda
- Foco da ferramenta: Execução de código sob demanda sem servidores dedicados
- Descrição de caso de uso: Em ambientes tradicionais, mesmo aplicações com baixa utilização precisam de servidores
  dedicados, gerando custos fixos e ociosidade. O AWS Lambda cobra apenas pelo tempo de execução, reduzindo drasticamente
  o custo de workloads event‑driven, APIs leves, automações e integrações. Empresas que substituem servidores on‑premises
  por Lambda costumam reduzir custos de execução em 50% a 90%, além de eliminar gastos com manutenção, patching e monitoramento
  de infraestrutura. Isso libera equipes para focar em desenvolvimento e inovação.



## Conclusao
A implementacao de ferramentas na empresa Abstergo Industries tem como esperado a economia, escalabilidade automática, armazenamento barato e execução sob demanda sem servidores, o que aumentarao a eficiencia e a produtividade da empresa. Recomenda-se a continuidade da utilizacao das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]

Assinatura do Responsavel pelo Projeto:

Rodrigo Gaiotto - gaiotto@gmail.com
Systems Engineer / IT Architect
