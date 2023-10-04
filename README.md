# Isabel
git clone: O git clone é usado sobretudo para apontar para um repositório existente e fazer um clone ou cópia deste repositório no novo diretório, em outro local. O repositório original pode estar localizado no sistema de arquivos local ou em protocolos com suporte a acesso por máquinas remotas.

git branch: O comando git branch permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo.

git push: O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando push transfere commits do repositório local a um repositório remoto. É o oposto do comando git fetch , que importa commits para branches locais, enquanto o comando push exporta commits para branches remotos.

git checkout: O objetivo dele é fazer a pessoa programadora mudar de branch. Você pode usar o “git branch” para saber quais existem e depois trocar de uma para outra. É importante destacar que é preciso fazer um checkout para a master branch quando queremos captar as mudanças de outra ramificação.

git status: O comando git status exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

git add: O comando git add adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, git add não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar git commit .

git commit: O comando git commit é uma das funções principais do Git. Antes de usar o comando git add é necessário selecionar as alterações que vão ser preparadas para o próximo commit. Então, git commit é usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git.

git push: O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando push transfere commits do repositório local a um repositório remoto. É o oposto do comando git fetch , que importa commits para branches locais, enquanto o comando push exporta commits para branches remotos.

git pull: O comando git pull é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em Git.

git revert: O comando git revert permitirá a edição da mensagem do commit antes de fazer a reversão do commit. Esta é a predefinição caso execute o comando em um terminal. Geralmente, você não pode reverter uma mesclagem porque não sabe qual o lado da mesclagem deve ser considerado a linha principal.

git merge: Git merge é o comando que unifica algum histórico bifurcado. Resumindo, o Git merge permite que você pegue as linhas criadas a partir do Git branch e faça uma integração para a ramificação principal.



 1. Teste de Unidade:
   - Foca em testar partes individuais (unidades) do código, como funções ou métodos.
   - O objetivo é garantir que cada unidade funcione corretamente de forma isolada.
   - Pode ser automatizado e é realizado pelos desenvolvedores.

2. Teste de Integração:
   - Concentra-se na interação entre as diferentes unidades ou módulos do sistema.
   - Verifica se as unidades se comunicam e funcionam juntas de maneira adequada.
   - Ajuda a identificar problemas de integração e dependências.

3. Teste de Sistema:
   - Avalia o sistema como um todo, após a integração de todas as partes.
   - Verifica se o sistema atende aos requisitos e funciona corretamente em um ambiente semelhante ao de produção.
   - Pode incluir testes funcionais, de desempenho e de segurança.

4. Teste de Aceitação:
   - Realizado para verificar se o sistema atende aos critérios de aceitação definidos pelo cliente ou partes interessadas.
   - Pode ser executado pelo cliente ou equipe de qualidade.
   - Geralmente, abrange cenários de uso real para determinar se o sistema está pronto para ser implantado.
 ### aula sobre testes
