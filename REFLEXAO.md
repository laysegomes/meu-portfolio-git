
# Reflexão Pessoal — Portfólio Git

## O que foi difícil
O início deste exercício foi, sem dúvida, o momento de maior tensão. Como aluna iniciante em Sistemas de Informação, a interface de linha de comando ainda parece um "terreno hostil". O que achei mais complicado foi entender a sincronia entre o meu computador local e o servidor do GitHub. 

Houve um momento específico em que tentei dar um `git push` e recebi um erro de `src refspec main does not match any`. Isso me travou por um tempo, pois eu não entendia que o Git precisava de um commit inicial para "reconhecer" a branch principal. Outro ponto de grande dificuldade foi o fluxo de resolução de conflitos. Entender o estado do HEAD durante um merge conflict e ver aquelas marcações estranhas (`<<<<<<<`, `=======`, `>>>>>>>`) dentro do meu código no VS Code foi intimidador. Exigiu muita tentativa e erro para compreender que eu precisava editar o arquivo manualmente, salvar e só então realizar um novo commit para finalizar o processo. A lógica de "abrir e fechar" branches também foi confusa no começo, especialmente quando eu tentava criar uma branch que já existia localmente.

## O que ficou claro
Apesar dos tropeços, o conceito de "commits semânticos" ficou muito claro para mim. Antes, eu via o commit apenas como um botão de "salvar", mas agora entendo que ele é uma ferramenta de comunicação profissional. Usar prefixos como `feat`, `fix` e `docs` ajuda a organizar o histórico de uma forma que qualquer outra pessoa consiga entender o que foi feito sem precisar ler linha por linha do código.

Também ficou muito clara a analogia de que o Git funciona como uma "máquina do tempo". A ideia de que posso criar branches para testar funcionalidades novas sem estragar a versão principal (`main`) faz muito sentido agora que vi o gráfico de merges no GitHub. O uso de Pull Requests como uma unidade de revisão também se tornou algo lógico: é o momento de pedir "licença" para unir meu trabalho ao projeto principal, permitindo que haja uma conversa e revisão antes do merge final.

## O que ainda é confuso
Ainda sinto certa insegurança com o comando `git pull`. Às vezes fico na dúvida se devo dar um pull antes de começar qualquer alteração ou se o Git vai reclamar de algum conflito inesperado se eu esquecer. O conceito de "tracking branches" e a diferença exata entre o que o comando `git fetch` faz em relação ao `git pull` ainda são nebulosos para mim. 

Além disso, embora eu tenha conseguido resolver o conflito neste exercício, ainda me sinto nervosa com a possibilidade de causar conflitos em arquivos grandes e complexos em um projeto de equipe real. A gestão de múltiplos contribuidores editando as mesmas áreas de um sistema ainda parece algo que exigirá muita prática e atenção nas próximas semanas da disciplina de Desenvolvimento de Software.