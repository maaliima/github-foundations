# Git e GitHub

O GitHub é uma plataforma baseada em nuvem em que é possível armazenar, compartilhar e trabalhar com outras pessoas para escrever códigos.

O seguinte é possível ao armazenar códigos em um "repositório" no GitHub:

Demonstre ou compartilhe seu trabalho.
Acompanhe e gerencie alterações no código ao longo do tempo.
Permita que outras pessoas revisem o seu código e deem sugestões para melhorá-lo.
Colabore em um projeto compartilhado sem se preocupar que suas alterações afetarão o trabalho de seus colaboradores antes que você esteja pronto para integrá-los.
O trabalho colaborativo, uma das características fundamentais do GitHub, é possível graças ao software de código aberto Git, que serviu como base para a criação do GitHub.

## Sobre o Git

O Git é um sistema de controle de versão que acompanha as alterações nos arquivos de forma inteligente. O Git é particularmente útil quando você e um grupo de pessoas fazem alterações nos mesmos arquivos ao mesmo tempo.

Normalmente, para fazer isso em um fluxo de trabalho baseado no Git, você deve:

Criar uma ramificação com base na cópia main dos arquivos em que você (e seus colaboradores) estão trabalhando.
Faça edições nos arquivos de forma independente e segura em sua própria ramificação pessoal.
Permita que o Git mescle de forma inteligente suas alterações específicas na cópia main dos arquivos para que suas alterações não afetem as atualizações de outras pessoas.
Deixe o Git rastrear suas alterações e as de outras pessoas para que todos permaneçam trabalhando na versão mais atualizada do projeto.
Para tentar usar o Git por conta própria, consulte Primeiros passos com o Git.

## Como o Git e o GitHub trabalham juntos?

Ao carregar arquivos no GitHub, você os armazenará em um "repositório Git". Isso significa que, quando você faz alterações (ou "commits") nos arquivos que estão no GitHub, o Git começa automaticamente a monitorar e gerenciar essas alterações.

Há muitas ações relacionadas ao Git que você pode realizar diretamente no GitHub pelo navegador, como criar um repositório Git, criar branches e carregar e editar arquivos.

No entanto, a maioria das pessoas trabalha localmente nos arquivos (no próprio computador) e sincroniza continuamente essas alterações locais, além de todos os dados relacionados do Git, com o repositório central "remoto" no GitHub. Há muitas ferramentas que você pode usar para fazer isso, como o GitHub Desktop.

Depois de começar a colaborar com outros e todos precisarem trabalhar no mesmo repositório e ao mesmo tempo, você irá, de forma contínua:

Efetue pull de todas as últimas alterações feitas pelos colaboradores do repositório remoto no GitHub.
Efetue push das alterações no repositório remote no GitHub.
O Git descobre como mesclar de maneira inteligente esse fluxo de alterações, e o GitHub ajuda você a gerenciar o fluxo por meio de recursos como "pull requests".