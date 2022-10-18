<h1 align="center">Scripts   </h1>
<p align="center">
<strong>Scripts de automatização de processos no bash</strong>
</p>


<p align="center">
  <a aria-label="Prando" href="https://github.com/hacklock/">
    <img src="https://img.shields.io/github/followers/hacklock?style=social"></img>
  </a>
    <img src="https://img.shields.io/github/last-commit/hacklock/scripts"></img>
    <img src="https://img.shields.io/github/languages/count/hacklock/scripts"></img>
</p>


<p align="center">
  <a href="#-instalação-e-execução">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
  
</p>

## 🚀 Instalação e execução

<br/>

1. Abra o terminal do seu computador. Se estiver no Windows, pode ser o Prompt de Comando ou PowerShell. Caso use o WSL no Windows, use o Windows Terminal, usando o Ubuntu ou qualquer distribuição suportada pelo WSL. 
2. Altere o diretório de trabalho atual para o local em que deseja ter o código do módulo salvo no seu computador.
3. Faça um clone desse repositório rodando: <br> `git clone https://github.com/hacklock/scripts`;
4. Entre na pasta rodando pelo terminal: `cd scripts`;
5. Dê permissão aos scripts <br/> `chmod +x *.sh `;
6. Para executar o script `sudo ./nomeDoScript.sh`.

### Adiconar scripts no PATH para poderem ser usados em qualquer diretório via terminal

- abrir arquivo .profile e atribuir o repositório dos scripts a variável PATH, no terminal:  
      
       vi ~/.profile  
      
    Atribuir no final do arquivo que a variavel PATH irá receber o valor atual + o novo repositório.  
      
      PATH="$PATH:$USER/caminhoDoRepositório"
    Após salvar os scripts poderão ser executados em qualquer repositório via bash !

#### Para Executar os scripts

  Em qualquer pasta `nomeScript.sh`




Depois que o *merge* da sua *pull request* for feito, você pode deletar a sua *branch*.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---


com  :heart: [Wilton R. Cruz](https://github.com/hacklock)    

