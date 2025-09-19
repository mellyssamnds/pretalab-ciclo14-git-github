# Atividade 


## Introdução a Git e GitHub
Nas prmeiras aulas do Aprofunda - Ciclo 14 foram abordados os conceitos essenciais de Git e GitHub, que são ferramentas fundamentais para o desenvolvimento de software e o controle de versão. O objetivo é ajudar as alunas a entenderem e utilizarem essas plataformas para gerenciar e colaborar em projetos de programação.

## O que é linha de comando?
É uma forma de interagir com o computador usando apenas texto através do terminal, em vez de cliques e menus gráficos. Essa abordagem é direta, eficiente e flexível de executar tarefas, manipular arquivos e rodar programas.

### Principais interfaces de linha de comenado:
- **Command Prompt (CMD)**: Um interpretador simples para Windows;
- **PowerShell**: Criado pela Microsoft, é mais robusto e tem maior capacidade de programação;
- **Bash**: Um shell Unix de código livre.

### Comandos básicos de linha de comando:
- `pwd`: para imprimir o diretório atual;
- `ls`: lista os arquivos;
- `cd nome-da-pasta`: entra em uma pasta dentro da que você estiver;
- `mkdir nome-da-pasta` para criar pastas;
- `rm nome-do-arquivo`: deleta um arquivo;
- `rm -r nome-da-pasta`: deleta um repositório;

## Controle de Versão
Controle de versão é um sistema que registra as mudanças feitas em um arquivo ou em um conjunto de arquivos ao longo do tempo. Ele permite que você volte a versões anteriores, compare diferentes versões entre si e veja quem fez cada alteração. É como uma máquina do tempo para seus arquivos.

Esse tipo de sistema é muito importante em ambientes onde várias pessoas trabalham juntas, como empresas e universidades, especialmente quando há muitos colaboradores no mesmo projeto ao mesmo tempo. Além de ser usado com códigos de programação, o controle de versão também funciona com qualquer outro tipo de arquivo, como documentos, planilhas ou imagens.

## Git
O Git é um programa de código aberto que foi criado pelo engenheiro Linus Torvalds, originalmente para ajudar no desenvolvimento do Kernel Linux. Ele é rápido e funciona bem, especialmente em projetos maiores. Hoje em dia, o Git é um dos sistemas de controle de versões mais populares, principalmente na área de desenvolvimento de softwares. Ele se destaca por ser:
- **Gratuito e de Código Aberto**: O software é livre para qualquer pessoa usar, modificar e distribuir, o que impulsiona sua adoção em escala global.
- **Velocidade e Eficiência**: Mesmo com um grande volume de arquivos e alterações, o Git é otimizado para ser rápido, garantindo um fluxo de trabalho sem interrupções.
- **Natureza Distribuída**: Cada desenvolvedor tem uma cópia completa do histórico do projeto em sua máquina, proporcionando flexibilidade para trabalhar offline e resiliência no acesso a todas as funcionalidades de controle de versão.

## Conceitos básicos de Git
- **Repositório**: diretório ou pasta onde seu projeto é armazenado, onde o Git rastreia todas as mudanças feitas no projeto. Pode ser encontrado em seu computador (local) ou internet (remoto, como no GitHub);
- **Clone**: cria uma cópia total do repositório remoto em seu computador local (por exemplo, do GitHub), permitindo trabalhar no projeto de maneira independente;
- **Branches (ramificações)**: permitem trabalhar em diferentes partes de um projeto sem afetar a linha principal de desenvolvimento. Cada branch funciona como “braço” do projeto, pois permite que desenvolvedores façam alterações e experimentos sem interferir no trabalho de terceiros;
- **Pull**: baixa as últimas atualizações do repositório remoto para o repositório local, para garantir que você esteja sempre trabalhando na versão mais recente do projeto;
- **Commit**: registra as mudanças do projeto junto a uma mensagem explicando o que foi alterado;
- **Push**: envia mudanças feitas no repositório local para o remoto, como no GitHub;
- **Merge**: combina mudanças de diferentes branches em um único branch. Especialmente útil ao integrar o trabalho feito por diferentes desenvolvedores de um mesmo projeto em uma só versão, unificada;
- **Fork**: cria uma cópia de um projeto preexistente na sua conta do GitHub impedindo que mudanças e melhorias afetem o repositório original;
- **Pull Request**: solicitação para que suas mudanças feitas em branch ou fork sejam integradas ao projeto principal. Uma maneira de colaborar com projetos de outros desenvolvedores;
- **Rebase**: similar ao merge, reorganiza o histórico de commits apagando ou combinando-os para um histórico mais limpo. É recomendado para a integração de mudanças entre branches de desenvolvedores, antes do envio ao branch principal.

## Comandos Básicos de Git
- `git init`: inicia um novo repositório Git em uma pasta local;
- `git add`: adiciona arquivos modificados à área de staging (preparação), onde você decidirá quais mudanças incluir no próximo commit;
- `git status`: mostra o estado atual dos arquivos em seu repositório e indica quais foram modificados, adicionados ou removidos;
- `git commit-m (“mensagem”)`: cria um commit salvando suas mudanças no histórico do projeto com uma mensagem descritiva; 
- `git pull`: atualiza seu repositório local com as mudanças mais recentes do repositório remoto (“remoto → local”);
- `git push`: envia as mudanças do seu repositório local para o remoto (“local → remoto”);
- `git remote add origin (URL do repositório)`: conecta seu repositório local a um remoto no GitHub;
- `git checkout (nome-do-arquivo)`: desfaz alterações locais em um arquivo específico revertendo-o para a última versão confirmada (commited).
