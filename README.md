# cetec-2023-programacao2

- Revisão dos conceitos de programação - Python
- Desenvolvimento WEB: HTML 5, CSS3 e JavaScript e React
- Programação Orientada a Objetos
- API REST: Flask Framework


## Dicionário termos GIT

### Dicionário Git e GitHub
Os conceitos vão ser apresentados da forma mais básica possível para que se possa entender a ideia primordial do software. Os comandos serão baseados num terminal UNIX.

### Repositório
O repositório é a pasta do projeto. Todo repositório tem uma pasta oculta .git. Isso é o que mostra para o git e para você que existe um repositório naquela pasta.

### Commit
Um commit é um grupo de alterações no código. Toda vez que você quiser "salvar" as alterações feitas por você no repositório, você commita essas mudanças. Um commit contém as alterações que foram feitas nele e uma mensagem descritiva, além de informações meta (data, autor, etc).

O ideal é que os commit sejam feitos de forma lógica e organizada, por exemplo: Você criou uma alteração no layout e vai comitar ela depois, ao invés de fazer commits separados ("Adição de div no HTML", "Alteração do CSS", "link do CSS"), faça um só commit ("Alteração no layout: <pequena descrição sobre a alteração>").

Ou seja, faça commit de alterações já completas ou que possam ser completadas por alguém. Nunca separe alterações em pequenos commits de poucas mudanças.

### Branch
Branches são separações de código. O branch padrão do projeto é o master. Branches normalmente são utilizados para separar alterações grandes ou novas funcionalidades do projeto, por exemplo: Existe um projeto de blog, os desenvolvedores já fizeram quase toda a parte do blog, mas existem alterações para fazer no sistema de usuários do blog e algumas a fazer no sistema de posts do blog. Para isso, cria se uma branch "usuarios" e uma "posts" (ou algo do tipo) e fazem-se as alterações nessas branches, um time trabalha em cada uma dessas branches, enquanto isso, outro time continua trabalhando em pequenas mudanças ou bugfixes na branch master.


### Merge
Um merge é a união de duas branches, normalmente, merges são feitos na branch master. No exemplo do blog, quando a alteração do blog for terminada, alguém vai unir essas alterações na branch master para que elas possam finalmente fazer parte do projeto de fato.

Os merges costumam dar bastante problema, pois os códigos podem (e provavelmente vão entrar em conflito). Se houverem alterações no mesmo arquivo ou o git não conseguir definir se alguma linha deve ou não entrar no projeto por motivo de conflito, essas alterações deverão ser corrigidas manualmente.

### Clone
Um clone de um repositório funciona como uma branch de um repositório online em um repositório local. Ou seja, quando se deseja trabalhar em um repositório hospedado no github, clona-se esse repositório para o seu computador, trabalha-se nele, e então é pedida a permissão para atualizar as alterações online.

Ele abre em que lugar queres que a pasta fique, é só selecionar uma pasta onde são colocados os trabalhos
Após esse processo é só abrir a pasta no vscode

### Pull
É uma atualização do repositório local. É feito um merge do repositório online com o local para que os conflitos sejam resolvidos e seja possível enviar o código (sem conflitos) para o repositório online por meio de um push.

### Push
Envia (ou tenta enviar) o código para o repositório online.


### Fork
O fork é como um clone, porém dentro do github. Isso quer dizer que o repositório não vai ser baixado para seu computador, mas será criado um igual na sua conta.

### Pull Request
Um pull request é um pedido que se faz ao dono do repositório para que esse atualize o código dele com o seu código. Ou seja, você pede para que o dono do projeto ao qual você quer contribuir adicione suas modificações ao projeto oficial.