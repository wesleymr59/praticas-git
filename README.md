![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
<h1>GIT Dicas:</h1>

<!--ts-->
* [Padrões de Commit](#padroes)
    * [Fix](#fix)
    * [Feat](#feat)
    * [Test](#test)
    * [Docs](#docs)
    * [Ci](#ci)
    * [Style](#style)
    * [Refactor](#refactor)
    * [Perf](#perf)
    * [Test](#test)
* [Exemplos](#exemplos)
    * [Exemplo Feat](#exemplosFeat)
    * [Exemplo Docs](#exemplosdocs)
    * [Exemplo Chore](#exemplosChore)
* [Comandos](#comandos)
    * [Git Config](#gitconfig)
    * [Git Init](#gitinit)
    * [Git Clone](#gitclone)
    * [Git Add](#gitiadd)
    * [Git Commit](#gitcommit)
    * [Git Branch](#gitbranch)
    * [Git Ignore](#gitignore)
    * [Git Branch](#gitbranch)
    * [Git Checkout](#gitcheckout)
* [Dicas](#dicas)
* [Referencias](#referencias)
<!--te-->

<h1 id="padroes">Padrões de Commit para serem utilizados:</h1>
<p>
 • <span id="fix">fix -> Commit do tipo fix indica que o trecho do código commitado está solucionando um Bug (Bug Fix)</span>
<br>
 • <span id="feat">feat -> Commit do tipo feat indica que o trecho do código está incluindo um novo recurso (Feature)</span>
<br>
 • <span id="test">test -> Commit do tipo test são utilizado quando há alterações em testes</span>
<br>
 • <span id="docs">docs -> Commit do tipo docs indicam mudanças na documentação</span>
<br>
 • <span id="chore">chore -> Mudanças de configuração ou de código que não entra em produção</span>
<br>
 • <span id="ci">ci -> Alteração em algum arquivo de CI do projeto</span>
<br>
 • <span id="docs">docs -> Mudanças na documentação</span>
 <br>
 • <span id="style">style -> Alteração apenas no estilo do código, sem mudança de algoritmo</span>
 <br>
 • <span id="refactor">refactor -> Refatoração de determinado bloco de código</span>
 <br>
 • <span id="perf">perf -> Alterações que impactam o desempenho da aplicação</span>
<br>
 • <span id="test">test -> Mudanças na estrutura ou na forma de testar o projeto</span>
</p>

<br>

<h1 id="exemplos">Exemplos:</h1>
• <span id="exemplosFeat">Exemplo -> "feat: adicionado nova forma de requisição utilizando RestShap"</span>
 <br>
• <span id="exemplosdocs">Exemplo -> "docs: adiciona stack de Pyhon e Ruby a documentação"</span> <br>
• <span id="exemplosChore">
    Exemplo -> "chore!: remove suporte ao Node 14
            Para suportar novas funcionalidades que vão
            agregar mais desempenho a aplicação como o
            `Promises.any` estamos subindo o requerimento
            mínimo do projeto. <br>
        BREAKING CHANGE: a versão minima do Node agora é a 16."
</span>
<br><br>
• <span id="" >Uma forma simples que nos diz se o seu commit faz sentido completando a frase: “Se aplicado, esse commit ______________”</span>
</p>
<br>

<h1 id="comandos">Comandos:</h1>
• <span id="gitconfig"> git config -> comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit. </span> <br>
<p style="padding-left:5em;">git config --global user.name “Seu nome” <br>
          git config --global user.email “Seu email”
</p><br>

• <span id="gitinit"> git init -> O comando irá criar um repositório novo em branco.</span> <br>
<p style="padding-left:5em;">git init</p><br>

• <span id="gitclone"> git clone -> Esse comando Git cria uma cópia exata de um repositório já existente.  </span> <br>
<p style="padding-left:5em;">git clone &lt; URL do seu projeto &gt; </p><br>

• <span id="gitiadd"> git add-> adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados.</span> <br>
<p style="padding-left:5em;">git add &lt; Seu Arquivo &gt; </p>
<p style="padding-left:5em;">git add .</p>
<br>

• <span id="gitcommit"> git commit -> Executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log.  </span> <br>
<p style="padding-left:5em;"> git commit -m "seu comentário"</p>
<br>

• <span id="gitbranch"> git branch -> Branches "ramificações". A grosso modo, um branch é um caminho independente de desenvolvimento, uma alternativa.  </span> <br>
<p style="padding-left:5em;">git branch</p>
<p style="padding-left:5em;">git branch &lt;nome_do_branch&gt; (cria um branch com o nome especificado)</p>
<p style="padding-left:5em;">git branch -d &lt;nome_do_branch&gt; (deleta o branch com o nome especificado)</p>
<br>

• <span id="gitcheckout"> git checkout -> Ainda sobre branches, esse comando Git pode ser utilizado para trocar de uma ramificação para outra.  </span> <br>
<p style="padding-left:5em;">git checkout &lt;nome_do_branch&gt;</p>
<br>

<br>

<h1 id="dicas">Dicas:</h1>
• <span id="gitignore"> Git Ignore -> Site onde ajuda a montar um bom <a href ="https://www.toptal.com/developers/gitignore"> Git Ignore</a> </span> <br>
• <span id="gitignore"> Git Ignore -> Criar <a href ="https://shields.io/">  Badges </a> para o seu Repositorio </span><br>

<br>

<h1 id="referencias">Referencias:</h1>
• <a href="https://instruct.com.br/publicacoes/boas-praticas-ao-escrever-commits-no-git/">https://instruct.com.br/publicacoes/boas-praticas-ao-escrever-commits-no-git/</a> <br>
• <a href="https://medium.com/boas-pr%C3%A1ticas-para-commits-no-git/boas-pr%C3%A1ticas-de-git-commit-628f3ec088e">https://medium.com/boas-pr%C3%A1ticas-para-commits-no-git/boas-pr%C3%A1ticas-de-git-commit-628f3ec088e</a><br>
• <a href="https://www.alura.com.br/artigos/escrever-bom-readme">https://www.alura.com.br/artigos/escrever-bom-readme</a><br>
• <a href="https://www.codigofonte.com.br/artigos/top-25-comandos-do-git">https://www.codigofonte.com.br/artigos/top-25-comandos-do-git</a><br>

<br>