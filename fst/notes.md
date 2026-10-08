### Senha Wi-Fi: 996803467

<hr>

### DADOS SERVIDOR:
Acessar: \\\serv01 <br>
Login: SUPORTE <br>
Senha: FSTSOLUÇOES <br>

<hr>

### FORMATAÇÃO:
Apps para baixar no Ninite:
 - Firefox; 
 - Chrome; 
 - Winrar; 
 - Team Viwer; 
 - Foxit Reader; 
 - Antivírus (Essentials); 
 - Java (site oficial); 
 - Apps do Office (servidor):
 - AnyDesk (site oficial).

### ÁREA DE TRABALHO:
Personalizar -> Temas -> Ícones área de trabalho -> user, rede, computador e lixeira.

### BACKUP (SE SOLICITADO):
Pastas a serem salvas:
 - Área de trabalho;
 - Documentos;
 - Downloads;
 - Favoritos;
 - Imagens;
 - Músicas;
 - Originais;
 - Vídeos;
 - (Pastas importantes para o cliente).

Alterar o nome do usuário e papel de parede. <br>

### ATIVAR WINDOWS E PACOTE OFFICE:
Instruções estão no servidor: "PROGRAMAS" -> "irm.txt".

### VERIFICAR ATUALIZAÇÕES DO WINDOWS:
Pesquisar Windows Update.

### AO INSTALAR WINDOWS 10 E O SISTEMA OBRIGAR A CONECTAR À INTERNET:
Teclar shift + F10 e, quando abrir o CMD, digitar "oobe\bypassnro".
Se for Windows 10 antigo, digitar "taskkill /F /IM oobenetworkconnectionflow.exe".

<hr>

### PC NÃO DANDO VÍDEO:
 - Tirar e colocar novamente a RAM;
 - Se o PC tiver placa de vídeo dedicada, conectar o VGA ou HDMI no conector de baixo do gabinete, não no de cima;
 - Tirar a plaquinha da BIOS (que salva a data e hora) por 60seg, enquanto isso pressionar por 15seg o botão de desligar do computador (com o mesmo fora da tomada;
 - Verificar se a voltagem do PC está na mesma da casa (se tiver mais alta não dá vídeo, se mais baixa pode queimar algo dentro do PC).

<hr>

### ACESSAR BIOS:
F2 ou Delete.

<hr>

### VELOCIDADE DE TRANSFERÊNCIA IDEAL:
SSD:
 - Mais de 290 mbps -> bom;
 - Menos de 290 mbps -> trocar.

HD:
 - 120 à 190 mbps -> ótimo;
 - 70 à 120 -> ok;
 - Menos de 70: troca.

<hr>


### PROBLEMAS NA IMPRESSORA:
 - Desligar e ligar novamente com "net stop spooler" e "net start spooler";
 - Limpar os arquivos temporários que estão em spooler -> printers;
 - Baixar drivers atualizados***.

*** Precisa desinstalar a impressora, procurar o site oficial dela e instalá-la novamente junto de seus drivers, se tiver mais de uma impressora conectada à rede basta fazer isso com uma e desligar e ligar novamente as demais.<br>
O arquivo .bat que limpa os arquivos temporários e reinicia automaticamente a impressora está na área de trabalho do PC do fundo da empresa.

<hr>

### PC NÃO LIGA (sem ser questão de ligar e não dar imagem, simplesmente não ligar (ventoinha do cooler não rodar)):
 - Verificar se a voltagem da fonte é a mesma da casa (caso a fonte do cliente tenha vindo em 220v perguntar se na casa dele a voltagem de fato é esta para devolver conforme estava);
 - Verificar os fios dos botões ligar e reiniciar***;
 - Se não, verificar se a fonte está funcionando (retirá-la e testar com a fonte teste).

*** Segue modelo de como fica a ordem dos fios do botões ligar e reiniciar nos pinos da placa mãe:
<img width="1107" height="768" alt="image" src="https://github.com/user-attachments/assets/02a6c5b6-232d-43ac-a1da-ba8df0cdbde3" />

<hr>

### SUBSTITUIR IMPRESSORA (ordem):
 - 1: Tirar relatório de rede e configuração inicial da impressora que será substituída;
 - 2: Desmontar impressora antiga, montar a nova e tirar todo os embrulhos dela;
 - 3: Conectar a nova no cabo de rede e no estabilizador, em seguida ligá-la;
 - 4: Inserir o pen drive e atualizar os drivers da nova impressora;
 - 5: Acessar as configurações de ethernet e colocar o mesmo IP, máscara de rede e gateway da anterior (por isso precisou tirar o relatório da anterior);
 - 6: Fazer a mesma coisa do endereço de servidor DNS e servidor DNS backup.

<hr>

### ATIVAR WINDOWS/OFFICE E BAIXAR OS PROGRAMAS DO OFFICE:
irm https://get.activated.win | iex
 - Ativar Office: selecionar opção 4 e depois a 2;
 - Ativar Windows: selecionar opção 4 e depois a 1;

Windows 7: 
iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))

