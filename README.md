# Guia de Compra Segura de Veículos Usados

Projeto desenvolvido como parte do desafio de criação de um Caderno Temático com o NotebookLM.

O objetivo foi utilizar inteligência artificial, curadoria de fontes e engenharia de prompts para criar um guia prático que ajude compradores de veículos usados a tomar decisões mais seguras.

## Sobre o projeto

Comprar um veículo usado envolve riscos mecânicos, financeiros, documentais e jurídicos. Uma pessoa sem conhecimento técnico pode deixar de verificar informações importantes antes de fechar a negociação.

A partir desse problema, foi criado o **Guia de Compra Segura de Veículos Usados**, organizado como uma jornada de compra: do planejamento financeiro até a transferência e o pós-venda.

## Objetivos de estudo

Este projeto teve como objetivos:

- Identificar os principais riscos na compra de um veículo usado;
- Organizar as verificações em uma sequência prática;
- Diferenciar verificações que podem ser feitas pelo comprador daquelas que exigem um profissional;
- Utilizar fontes confiáveis e documentos oficiais;
- Testar diferentes prompts no NotebookLM;
- Transformar o conteúdo pesquisado em um material útil e reutilizável.

## Ferramenta utilizada

O projeto foi desenvolvido com o **NotebookLM**, utilizando fontes previamente selecionadas.

A ferramenta foi usada para:

- Analisar documentos;
- Comparar informações entre diferentes fontes;
- Criar resumos estruturados;
- Identificar conceitos importantes;
- Revisar afirmações;
- Apoiar a construção do guia final.

## Curadoria de fontes

Foram utilizadas fontes oficiais e materiais especializados relacionados à compra, inspeção, financiamento e transferência de veículos.

Entre as principais fontes estão:

1. Guia Prático do Consumidor Consciente — Detran-SP e Procon-SP;
2. Portal de Serviços da Senatran;
3. Resolução CONTRAN nº 941/2022;
4. Normas do Banco Central sobre o Custo Efetivo Total — CET;
5. Materiais de orientação ao consumidor e inspeção veicular.

A relação detalhada das fontes está disponível em:

[Consultar fontes utilizadas](fontes/fontes-consultadas.md)

## Engenharia de prompts

Durante o projeto, diferentes prompts foram testados para melhorar a organização, a profundidade e a confiabilidade do conteúdo.

Os principais testes envolveram:

- Criação inicial da estrutura do guia;
- Separação das verificações por etapa da compra;
- Classificação dos pontos por nível de importância;
- Identificação de quem poderia realizar cada verificação;
- Auditoria das afirmações com base nas fontes;
- Revisão de trechos com linguagem mais forte do que a documentação consultada;
- Criação de prompts reutilizáveis para futuras pesquisas.

Os prompts estão documentados em:

[Consultar prompts utilizados](prompts/prompts-utilizados.md)

## Cicatrizes do projeto: dificuldades e aprendizados

A primeira versão apresentou algumas afirmações categóricas que não estavam completamente sustentadas pelas fontes.

Entre os problemas identificados estavam:

- Recomendações práticas apresentadas como se fossem determinações legais;
- Uso de expressões absolutas;
- Informações inferidas pela IA sem indicação clara;
- Dificuldade para transformar um conteúdo extenso em um material visualmente organizado;
- Limitações do NotebookLM na criação automática do layout final.

Para corrigir esses problemas, foi criado um processo de auditoria que separava:

1. O que a fonte afirmava explicitamente;
2. O que havia sido inferido pela IA;
3. Se a recomendação estava totalmente, parcialmente ou não sustentada;
4. Quais trechos precisavam de revisão.

Esse processo mostrou que a qualidade do resultado não depende apenas do primeiro prompt, mas também da validação, da comparação das fontes e das revisões realizadas.

## Miniguia de estudo

O resultado final é um guia organizado pelas principais etapas da compra:

1. Planejamento financeiro;
2. Pesquisa de anúncios;
3. Perguntas ao vendedor;
4. Consulta de histórico, débitos e restrições;
5. Inspeção visual externa;
6. Verificação de pneus e rodas;
7. Inspeção mecânica;
8. Verificação interna e eletrônica;
9. Test-drive;
10. Vistoria veicular;
11. Negociação, contrato e garantias;
12. Transferência de propriedade;
13. Pós-venda e resolução de conflitos.

Cada etapa apresenta:

- O que verificar;
- Como realizar a verificação;
- Por que ela é importante;
- Qual risco está sendo evitado;
- O que fazer se houver algum problema;
- Quem deve realizar a avaliação;
- Fonte utilizada.

## Resultado final

O guia completo está disponível em:

[Baixar o Guia de Compra Segura de Veículos Usados](docs/guia-compra-veiculo-usado.pdf)

## Glossário

- **ATPV-e:** Autorização para Transferência de Propriedade do Veículo em formato digital.
- **CET:** Custo Efetivo Total de uma operação de crédito.
- **CRLV-e:** Certificado de Registro e Licenciamento de Veículo em formato digital.
- **ECV:** Empresa Credenciada de Vistoria.
- **Renajud:** Sistema de restrições judiciais sobre veículos.
- **Renainf:** Registro Nacional de Infrações de Trânsito.
- **Renave:** Registro Nacional de Veículos em Estoque.
- **Vício oculto:** Defeito que não era facilmente identificável no momento da compra.

## Prompts reutilizáveis

Os prompts desenvolvidos podem ser adaptados para:

- Avaliação de outros produtos de alto valor;
- Criação de checklists;
- Comparação de fontes;
- Auditoria de respostas produzidas por IA;
- Construção de novos cadernos temáticos;
- Revisão de afirmações jurídicas e técnicas.

## Principais aprendizados

Este projeto demonstrou que a inteligência artificial pode acelerar a organização do conhecimento, mas não substitui a seleção de fontes confiáveis e a revisão humana.

O uso do NotebookLM foi especialmente útil para trabalhar com documentos previamente selecionados. Entretanto, foi necessário revisar as respostas, identificar inferências e reduzir afirmações que ultrapassavam o conteúdo das fontes.

## Autor

Desenvolvido por **Gabriel Portugal**.
