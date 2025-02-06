# Windows
## O que 
O Windows é um sistema operacional de interface gráfica multitarefa. Isso significa que podemos trabalhar com vários programas simultaneamente.
## Como e Quando foi criado
A Microsoft introduziu um ambiente operacional chamado Windows 1.0 em 20 de novembro de 1985, como um shell para MS-DOS, em resposta ao crescente interesse em interfaces gráficas de usuário (GUIs).O Windows não foi inovador, foi uma cópia de um sistema desenvolvido pela Apple, que, por sua vez, foi uma melhoria do sistema da Xerox. A dupla Steve Jobs e Steve Wozniak criaram o Lisa, sistema operacional baseado na interface gráfica da Xerox. 
## Lista evolutiva
### Windows 1.0 (1985)
A primeira versão do SO foi lançada no longínquo ano de 1985 e era mais uma extensão do MS-DOS do que um software completo. Ele se caracterizava pelo modelo colorido na tela e aplicações como bloco de notas e até um Paint. 
### Windows 2.0 (1987)
O Windows 2.0 chegou ao mercado em dezembro de 1987 e, tanto como o seu predecessor quanto o seu sucessor, usava uma estrutura de computação em 16 bits. Ele apresentou melhorias na interface, como a possibilidade de sobrepor janelas de programas, atalhos de teclado e suporte a VGA.
### Windows 95 (1995)
Considerado um dos sistemas operacionais mais importantes da história, o Windows 95 abriu uma nova era para a Microsoft. Ele foi programado em 32 bits e trouxe melhorias que incluíam o sistema plug and play, recursos de acessibilidade e o navegador Internet Explorer, sendo o responsável por ajudar o computador a se tornar um item popular nas casas das famílias do mundo todo.
### Windows XP (2001)
O Windows XP foi lançado em outubro de 2001 e à época era bastante inovador, principalmente no quesito visual. Ele apostou em um menu Iniciar verde e barras azuis que se tornaram bastante populares entre os usuários, popularizou programas do Windows Media Player, já que CDs poderiam ser lidos pelos drives e tocados no programa. Seu wallpaper, uma fotografia de planícies na Califórnia, tornou-se uma das imagens mais famosas da era da internet.
### Windows Vista (2006)
O Windows Vista teve um hiato bastante grande em relação ao anterior, se desconsiderarmos as atualizações e novas versões do XP, ele não foi tão bem recepcionado porque muitos usuários reclamavam que ele deixava o computador lento, o que fez muita gente continuar usando o XP por mais um bom tempo.
### Windows 10 (2015)
O software mais recente da Microsoft foi lançado em julho de 2015. Ele trouxe de volta o menu Iniciar e tem como um dos principais diferenciais o foco multimídia, que pode ser visto na integração com o Xbox, notebooks e tablets. De acordo com o site da Net Marketshare, ele é o SO mais utilizado no mundo atualmente, estando em mais de 66% dos computadores ao redor do globo. Logo atrás está o Windows 7, que mesmo mais de dez anos após o seu lançamento ainda está presente em 17% dos PCs.
### Windows 11 (2021)
Nesta quinta-feira (24), a Microsoft apresentou o futuro do seu produto mais popular, o sistema operacional terá várias novidades, incluindo um visual mais moderno, mais segurança e velocidade, bem como um novo método de organização de janelas. Além disso, pela primeira vez na história, aplicativos Android estarão presentes na Microsoft Store, o que marcará o início de uma nova era de integração.
![Windows](https://tm.ibxk.com.br/2021/06/24/windows-11-24170014082380.jpg)
## Arquitetura
### Kernel
>O núcleo do Windows, baseado no Windows NT, é responsável pela gestão dos recursos do sistema, como memória, processos e dispositivos de hardware,fornecendo ambiente seguro para a execução de programas e gerencia a comunicação entre o software e o hardware.
### Gerenciador de Arquivos>
>O Windows utiliza sistemas de arquivos como NTFS e FAT para armazenar e organizar dados em discos rígidos, cuidando da leitura, gravação e organização de arquivos, além de controlar permissões e acessos a dados.>
### Interface Gráfica 
>A interface gráfica do Windows, comumente conhecida como Windows Shell, é responsável pela interação do usuário com o sistema.>
## Comandos
### 1. Sfc
Se você quer identificar possíveis erros do Windows e descobrir o que é a melhor coisa a ser feita, o comando CMD pode ajudar. Ao realizar a execução do prompt, ele vai fazer uma varredura em todo seu sistema e encontrar as falhas. 
sfc /scannow
![comando 1](https://lh5.googleusercontent.com/Z_GeeJ9kLieE_iJQsGtcz7wCw964lZQDxM-14pbKxgjsX2Ylth8UnFkqiUyx5FGOG1EooXdd3OfPU-uH5--QDDhIHJ4VrtRPWCKvBaYXKCQeyhixj5JsJznMPZdum8mcWhvRd7kz)
![Comando 1](https://lh6.googleusercontent.com/iXWbfA_iKtbs4V6fduq7om-KXd-F7B3rgQfGp2wdYJiahP6t-guSK4UILaQBiMVE0pcK-kFRHP9UWQNbjS667pnAOLIovrYEkAk1mbAWf7GB4-5lI0-sMKYAWPCTZLAMA2t6C9ZW)
### 2 Ipconfig
Esse é um dos comandos mais comuns para quem é usa os comandos CMD do Windows. O comando “ipconfig /all” exibe diversas informações referentes à sua internet. Para quem trabalha com rede, é um excelente utilitário.

Ao digitar o comando ipconfig em seu terminal, ele exibirá o seguinte resultado:
![Comando 2](https://lh6.googleusercontent.com/8OW3w2ie_-AeOFHS5zaA0CgVma5LAeGiCtdNJrloDMzJYumFPElu_yvnnKez85o8NB1zed_sqDhYRLqHRKWhaPeEgo1dA60pXL7o4i_TgG_A7o-FXNOxAAm2HmP_8uOINK4m4ecO)
### 3 Assoc
Você baixou um arquivo da internet, mas não sabe qual programa e/ou aplicativo na sua máquina é ideal para executá-lo? Basta utilizar “assoc” juntamente com o tipo de arquivo em questão. 
![Comando 3](https://lh5.googleusercontent.com/-hGp-NU13Lz-Q9dTwETJsQdA3yF441gKG8OKSNmQocphG7beMTR3IpzZ7V5Mi9Ma_OULe9dd8cfOCC53IYQ_X3cTfytUU6AoYtvoij992q1dkTKTeAhBeAZFdEnjk9XEt5CO3KsR)

### 4. Taskkill
Se o computador travou e está difícil usar o gerenciador de tarefas, uma maneira de forçar o encerramento é por meio do taskkill. Insira o comando e, ao final, inclua o arquivo que precisa ser finalizado. No exemplo abaixo usamos o software Filezilla, que é um programa de auxílio para transferência de arquivos via FTP: 
taskkill /f /im filezilla.exe 
![Comando 4](https://blog.betrybe.com/wp-content/uploads/2020/05/image30.png)
### 5. Tasklist
Esse comando identifica todos os processos que estão em execução no momento. Além disso, ao utilizarmos com taskkill, que mencionamos anteriormente, destacamos quais são os arquivos que precisam ser finalizados para otimizar a experiência da máquina.
O resultado poderá ser uma listagem grande, conforme a imagem a seguir:
![Comando 4](https://lh4.googleusercontent.com/8M45lvWc0v3DxHd86Wx4Asr6fOsjkslBZgaDKbJ6j9kuhLcHAF0xF9ZpvrAWtse6ehJM9UuX-qP9JVYjwNvwiIUcTzErOpHP8nrEzw0HmSwJCpc3k8iN2Lx27iTxRLDJM249REey)
## Curiosidades
### 1
Existem pessoas que ainda usam o Windows XP. Ele oficialmente lançado em 2001, seu suporte foi oficialmente até 2014, entretanto ainda existem milhares de instalações ativas ao redor do mundo.
### 2
Por pouco que o Windows não se chamaria Windows. Bill Gates iria chamar o sistema operacional de “Interface Manager”, entretanto o nome Windows prevaleceu.
### 3
O Windows 95 foi um sucesso vendendo 40 milhões de cópias em um ano. Certamente foi uma grande revolução no mercado na época, colocando a Microsoft nas “paradas de sucesso”, a popularização do Windows 95 fez com que a Microsoft despontasse na frente dos concorrentes.
### 4
O Windows XP segundo a Microsoft possui cerca de 45 milhões de linhas de código. Sendo um dos sistemas mais bem sucedidos da Microsoft o Windows XP certamente contava com muitas linhas de código e conseguiu deixar sua marca.
### 5
O Android passou o Windows quando os smartphones se popularizaram. Até o surgimento do Android o Windows ganhava como sistema mais usado no mundo todo independente da plataforma. Entretanto isso mudou com a chegada dos smartphones, hoje o Android é o S.O mais usado, representando 40% do uso global.
