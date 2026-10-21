# Treinadores do Pip

Jornada de literacia em inteligência artificial para crianças dos 7 aos 9 anos. A criança treina o Pip, um robô aprendiz, ao longo de sete paragens sobre como a IA funciona, os seus prós e contras e os cuidados a ter. Pode ser feita sozinha em casa ou acompanhada na sala de aula.

**Estado:** protótipo. Estão prontas a entrada, o mapa, a paragem 1 e o painel do professor. As paragens 2 a 7 aparecem como "em construção".

## As sete paragens

| # | Paragem | Ideia-chave para a criança |
| --- | --- | --- |
| 1 | O robô que só obedece | Uma máquina faz exatamente o que lhe dizem, nem mais nem menos |
| 2 | Ensinar com exemplos | A IA não recebe regras, descobre-as a partir de exemplos |
| 3 | O Pip só viu gatos laranja | Se os exemplos forem maus ou poucos, a IA aprende mal |
| 4 | A máquina de adivinhar palavras | Um chatbot escolhe a palavra que costuma vir a seguir; parecer certo não é ser verdade |
| 5 | Real ou inventado? | A IA cria imagens e textos que parecem reais; antes de acreditar, verifica |
| 6 | Os meus dados são meus | Há informação que nunca se dá a uma máquina nem a um desconhecido |
| 7 | Conselho dos Guardiões | A IA ajuda muito e também erra; quem decide como a usar somos nós |

## Como funciona

- **Duas vozes.** O Narrador explica os conceitos e lembra que o Pip não pensa nem sente. O Pip anima e encoraja. Ambos leem em voz alta através da síntese de voz do navegador.
- **Entrada sem dados pessoais.** A criança não escreve o nome: escolhe um animal e uma cor ("Raposa Azul").
- **Código do explorador.** Cada criança tem um código de 9 caracteres, por exemplo `K7PM-3QAZX`. Os 4 primeiros são um número aleatório que a identifica; os restantes guardam o animal e as estrelas. Serve para continuar noutro aparelho e para o professor a juntar à turma.
- **Painel do professor.** O professor cria turmas, junta alunos pelo código e dá-lhes um nome ou número que fica só no aparelho dele. Vê o progresso por paragem e quem tem uma paragem a rever. Para atualizar, cola os códigos novos.
- **Área dos pais.** Notas de cada paragem e gestão dos perfis do aparelho.

## Privacidade

O site é estático e não tem servidor. Não recolhe nomes, emails, idades nem fotografias, e não envia nada para terceiros: as fontes estão alojadas no próprio repositório. O progresso fica no `localStorage` do navegador. Em Portugal, o consentimento de menores para serviços da sociedade da informação só é válido a partir dos 13 anos (Lei n.º 58/2019); por isso esta versão evita qualquer tratamento de dados no servidor.

## Publicar com GitHub Pages

Em **Settings > Pages**, escolher **Deploy from a branch**, branch `main`, pasta `/ (root)`. O site fica em `https://gpilatti.github.io/AI_literacy/`.

Para testar localmente basta abrir `index.html` num navegador ou servir a pasta com qualquer servidor estático.

## Créditos

Fontes [Fredoka](https://fonts.google.com/specimen/Fredoka) e [Atkinson Hyperlegible](https://fonts.google.com/specimen/Atkinson+Hyperlegible), ambas sob a SIL Open Font License 1.1.
