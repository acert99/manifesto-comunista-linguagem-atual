# Manifesto Comunista — versão em linguagem atual

> Uma leitura crítica precisa começar pelo texto que está sendo criticado.

## Por que este projeto existe?

Eu sou conservador e de direita.

Durante muito tempo, como acontece com muita gente no debate político, eu conhecia o comunismo principalmente pelas críticas feitas ao comunismo. Isso é insuficiente.

Se eu quero dizer que discordo de Marx, do marxismo ou do comunismo, considero intelectualmente mais honesto conhecer aquilo de que estou discordando.

Não quero combater um espantalho. Quero conseguir ler o argumento, compreender seus conceitos e então dizer com clareza onde concordo, onde discordo e por quê.

Foi com essa intenção que li o **Manifesto do Partido Comunista**, de Karl Marx e Friedrich Engels.

A leitura foi útil inclusive para alguém que continua sendo de direita. Ela permite reconhecer no texto ideias sobre classe, propriedade, capital, organização econômica, Estado e transformação das relações sociais que continuam aparecendo, de diferentes formas, no debate político contemporâneo.

Isso não significa que toda política de esquerda, toda intervenção estatal ou toda proposta social contemporânea derive automaticamente do Manifesto. Fazer essa afirmação seria cometer justamente o erro que este projeto tenta evitar: simplificar posições diferentes até transformá-las em um único espantalho.

A proposta aqui é outra:

> **ler primeiro, compreender depois e criticar com conhecimento do texto.**

---

## O projeto em quatro versões

Para tornar o processo auditável, o projeto passa a ser organizado em torno de **quatro referências claramente separadas**:

| Versão | Idioma | Papel no projeto | Situação |
|---|---|---|---|
| **1. Edição inglesa de 1888** | Inglês | Controle histórico de estrutura e cobertura | Referência externa |
| **2. Edição-base em português** | Português | Referência portuguesa usada no início do projeto | Fonte-base |
| **3. V1 — condensada** | Português contemporâneo | Primeira tentativa de atualização da linguagem | Arquivada |
| **4. V2 — integral** | Português contemporâneo | Versão atual, reconstruída sem condensação deliberada | Principal |

### 1. Edição inglesa de 1888

A principal referência cruzada é a tradução inglesa de **Samuel Moore, realizada em cooperação com Friedrich Engels em 1888**, disponibilizada pelo Marxists Internet Archive.

Fonte:

https://www.marxists.org/archive/marx/works/download/pdf/Manifesto.pdf

Ela é usada principalmente para conferir:

- presença ou ausência de passagens;
- estrutura do texto;
- divisão dos argumentos;
- preâmbulo;
- notas históricas;
- exemplos e objeções desenvolvidos pelos autores.

Mais informações em [sources/marxists-internet-archive.md](./sources/marxists-internet-archive.md).

### 2. Edição-base em português

Esta é a edição em português a partir da qual o projeto começou.

Ela funciona como referência para:

- terminologia em português;
- escolhas de tradução já consolidadas;
- comparação com a linguagem contemporânea;
- conferência de conceitos como **luta de classes**, **burguesia**, **proletariado**, **capital**, **meios de produção** e **trabalho assalariado**.

Importante: ela é chamada aqui de **edição-base em português**, e não de “texto original”, porque o Manifesto não foi originalmente escrito em português.

A identificação e o hash do arquivo estão em [sources/README.md](./sources/README.md).

### 3. V1 — versão condensada

A primeira adaptação conseguiu tornar a leitura mais simples, mas a comparação posterior mostrou que ela também **condensava partes relevantes do texto**.

Ela preservava os conceitos principais e as quatro partes do Manifesto, mas:

- omitia o preâmbulo do “espectro do comunismo”;
- reunia argumentos originalmente separados;
- reduzia exemplos históricos;
- condensava várias objeções e respostas da Parte II;
- encurtava significativamente a Parte III;
- simplificava a Parte IV.

A v1 não foi apagada. Ela permanece no projeto como registro do processo:

[versions/v1-condensada.md](./versions/v1-condensada.md)

### 4. V2 — versão integral

A v2 é a versão principal do projeto.

Ela foi reconstruída com dupla conferência:

**edição-base em português + edição inglesa de 1888**

O objetivo passou a ser:

> **modernizar a forma sem condensar o conteúdo.**

A v2 recupera, entre outros pontos:

- o preâmbulo;
- o desenvolvimento completo da Parte I;
- o lumpemproletariado;
- a discussão mais extensa sobre capital e trabalho assalariado;
- a oposição entre trabalho vivo e trabalho acumulado;
- a passagem sobre os “nove décimos”;
- as objeções sobre propriedade, família, educação, mulheres, nacionalidade, religião e moral;
- as dez medidas apresentadas na Parte II;
- o desenvolvimento das correntes socialistas criticadas na Parte III;
- as posições políticas específicas da Parte IV.

Versão principal:

[manifesto.md](./manifesto.md)

Cópia versionada:

[versions/v2-integral.md](./versions/v2-integral.md)

---

## Comparativo das quatro referências

| Critério | Inglês 1888 | Edição-base PT | V1 condensada | V2 integral |
|---|---|---|---|---|
| Idioma | Inglês | Português | Português atual | Português atual |
| Natureza | Tradução histórica | Tradução/edição em português | Adaptação | Adaptação integral |
| Preâmbulo | Sim | Conferido pela edição | Não | Sim |
| Partes principais | 4 | 4 | 4 | 4 |
| Conteúdo condensado | Não | Não intencionalmente | **Sim** | **Não intencionalmente** |
| Vocabulário marxista preservado | Sim | Sim | Sim | Sim |
| Função no projeto | Controle histórico | Base portuguesa | Registro da primeira tentativa | Versão atual |
| Palavras no arquivo do projeto | — | extração não confiável | **6.037** | **10.544** |
| Blocos de texto | — | — | **279** | **451** |
| PDF gerado pelo projeto | — | arquivo-base | **16 páginas** | **32 páginas** |

### Sobre as métricas

As métricas da v1 e da v2 são reproduzíveis porque foram calculadas diretamente sobre os arquivos Markdown do repositório.

A edição-base em português possui um mapeamento interno de fontes que dificulta a extração automática confiável. Por isso, este projeto evita apresentar uma contagem de palavras dessa edição como se fosse exata.

Também não se deve comparar diretamente o total de páginas do PDF do Marxists Internet Archive com o PDF gerado neste projeto: o arquivo do MIA inclui, além do Manifesto, introdução editorial, prefácios históricos e documentos complementares.

Para uma auditoria mais detalhada, consulte:

[COMPARISON.md](./COMPARISON.md)

---

## Por que uma versão em linguagem atual?

O Manifesto foi publicado em 1848.

Durante a leitura em português, encontrei trechos difíceis não necessariamente por causa dos conceitos, mas pela forma: construções antigas, períodos longos e uma linguagem menos natural para o leitor contemporâneo.

Por isso pedi ao ChatGPT para atualizar a redação.

A regra central foi:

> **modernizar a linguagem sem modernizar os conceitos.**

Termos teóricos não deveriam ser substituídos apenas para facilitar a leitura.

Entre os termos preservados estão:

- luta de classes;
- burguesia;
- proletariado;
- capital;
- meios de produção;
- relações de produção;
- trabalho assalariado;
- propriedade privada burguesa;
- antagonismo de classe;
- lumpemproletariado.

Por exemplo, **“luta de classes”** não é substituída por “conflito social”, porque as expressões não possuem exatamente o mesmo significado dentro da teoria apresentada no texto.

---

## O que a v2 é — e o que ela não é

A v2 é uma **adaptação integral para o português contemporâneo**, construída com auxílio de inteligência artificial e conferida contra duas referências.

Ela procura preservar:

- a sequência dos argumentos;
- o conteúdo substantivo;
- os conceitos;
- as objeções apresentadas pelos autores;
- os exemplos históricos relevantes;
- as conclusões de cada seção.

Ela **não é**:

- uma tradução acadêmica oficial;
- uma edição crítica;
- uma substituição das fontes históricas;
- uma tentativa de tornar Marx e Engels mais moderados;
- uma tentativa de atualizar as ideias para o século XXI;
- um texto de defesa do comunismo;
- um resumo das minhas opiniões políticas.

Quando uma formulação do Manifesto é radical, incômoda ou difícil, o objetivo da v2 não é suavizá-la.

O objetivo é torná-la compreensível.

---

## Leia e compare

| Conteúdo | Arquivo |
|---|---|
| **V2 integral — versão principal** | [manifesto.md](./manifesto.md) |
| **V1 condensada** | [versions/v1-condensada.md](./versions/v1-condensada.md) |
| **V2 versionada** | [versions/v2-integral.md](./versions/v2-integral.md) |
| **Leitura em HTML** | [index.html](./index.html) |
| **Edição-base em português** | [sources/README.md](./sources/README.md) |
| **Edição inglesa de 1888** | [sources/marxists-internet-archive.md](./sources/marxists-internet-archive.md) |
| **Comparação detalhada** | [COMPARISON.md](./COMPARISON.md) |
| **Metodologia e transparência** | [NOTICE.md](./NOTICE.md) |

---

## Minha posição

Disponibilizar este texto não significa endossá-lo.

Continuo me identificando politicamente como **conservador e de direita** e continuo discordando de conclusões centrais do comunismo e de várias propostas apresentadas ou decorrentes dessa tradição.

Mas considero uma crítica muito mais séria quando ela começa com:

> **“Eu li. Eu entendi o argumento. E é por isso que discordo.”**

do que quando começa apenas com frases repetidas sobre aquilo que supostamente está no livro.

Foi justamente essa a motivação deste projeto.

Se eu nunca tivesse lido o Manifesto, teria muito menos base para afirmar que conheço aquilo a que me oponho.

A leitura não mudou automaticamente minhas convicções políticas. Mas melhorou a qualidade da discordância.

Esse é o ponto.

---

## Transparência sobre o uso de IA

O ChatGPT foi utilizado no processo.

Na **v1**, ele foi usado para atualizar a linguagem, mas a revisão posterior mostrou que houve condensação excessiva.

Essa falha passou a fazer parte do próprio registro do projeto.

Na **v2**, o processo foi refeito com um critério mais rigoroso:

1. preservar a estrutura;
2. preservar todos os argumentos substantivos;
3. não substituir termos teóricos por expressões mais genéricas;
4. conferir a cobertura contra a edição inglesa de 1888;
5. conferir terminologia contra a edição-base em português;
6. manter a v1 disponível para comparação.

A intenção não é pedir que o leitor confie na IA.

É justamente o contrário:

> **as fontes e as versões são mantidas separadas para que o leitor possa conferir o trabalho.**

Veja [NOTICE.md](./NOTICE.md) para mais detalhes.

---

## Uma recomendação ao leitor

Não leia apenas a v2.

Se uma passagem parecer especialmente importante, polêmica ou estranha:

1. leia a v2;
2. compare com a edição-base em português;
3. confira a edição inglesa de 1888;
4. forme sua própria interpretação.

O princípio deste projeto pode ser resumido em uma frase:

> **não terceirize a compreensão daquilo que você pretende criticar.**

---

## Arquivos binários

O PDF da v2 foi gerado e validado com **32 páginas**.

O conector utilizado nesta sessão não permite publicar diretamente os bytes dos PDFs locais no GitHub, por isso os arquivos binários são identificados por hash em vez de serem apresentados no repositório como se estivessem disponíveis quando não estão.

**SHA-256 — PDF da v2 integral**

\`3eda34e3140e50b31da283690b6c6dbea3019308a5dfb12b2f32151e2d886196\`

**SHA-256 — edição-base em português**

\`3277d5bbf04ecba777e65a7df00c5b2c8c18255b157330d6563292bc0118abd4\`

Os hashes permitem verificar a identidade exata dos arquivos usados e produzidos durante o projeto.
