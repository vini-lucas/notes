# SEMANA 1

### SISTEMAS DE NUMERAÇÃO
 - Não posicional: nesse sistema não há um símbolo que represente o zero e não depende do lugar que o número ocupa (como os algarismos romanos). Um sistema não posicional não serve para efetuar cálculos matemáticos, devido às dificuldades para tal. Sua maior utilização é registrar informações numéricas;
 - Posicional: aqui cada algorismo possui peso e seu valor depende da posição que ocupa, ex.: "3.733 = 3.000 + 700 + 30 + 3", o "3" se repete três vezes mas em cada algorismo ele possui um peso diferente.

### BASE DE NUMERAÇÃO
Este conceito veio da ideia do homem poder citar números elevados com o menor número de algarismos possíveis, existe algumas bases para sistemas de numeração e podemos definí-las como quais algarismos (símbolos) o respectivo sistema pode possuir. Exemplos:
 - Sistema decimal: utiliza 10 símbolos, portanto sua base é 10, é o que usamos diariamente, composto por: 0, 1, 2, 3, 4, 5, 6, 7, 8 e 9;
 - Sistema binário: utiliza 2 símbolos, portanto sua base é 2, o que os computadores usam, composto por 0 e 1;
 - Sistema octal: utiliza 8 símbolos, composto por 0, 1, 2, 3, 4, 5, 6, 7 e 8;
 - Sistema hexadecimal: utiliza 16 símbolos, usado para sistema de cores, composto por 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E e F.

### NÚMEROS E ALGARISMOS
 - Algarismos/dígitos são cada parte daquele grupo, ex.: 375, possui os algarismos 3, 7 e 5, já o 375 é um número, o conjunto dos 3 algarismos;
 - Notação posicional: a posição do número muda seu peso, por isso o 375 é diferente do 573, mesmos algarismos mas estão em casas diferentes;

### CONVERSÃO DE NÚMEROS DE QUALQUER BASE PARA A BASE 10
Usa-se a seguinte fórmula: N = soma [dígito x base^posição], exemplo:<br>
O binário 111000, como fica: <br><br>
111000 = 1x2⁵ + 1x2⁴ + 1x2³ + 0x2² + 0x2¹ + 0x2⁰ <br>
111000 = 32 + 16 + 8 + 0 + 0 + 0 <br>
111000 em binário = 56 em base 10 <br><br>
Explicando: multiplica-se cada algarismo do número pela sua base (neste exemplo, como é um número binário, a base é 2) onde sua potência é o número da casa que ocupa, começando do 0 e da direita para a esquerda (igual no exemplo, a última expressão a potência da base é 0 e a primeira expressão possui potência 5 = posição da casa).

<hr>

# SEMANA 2

### FUNDAMENTOS DE ARQUITETURA DE COMPUTADORES
Todo computador possui componentes básicos específicos para seu funcionamento, estes são divididos em processador, memória e periféricos:
 - Processador: atua na realização das ordens e/ou instruções, é o que processa os dados daquela máquina e das aplicações que estão sendo executadas, como os dedicados ou que são integrados à uma placa de vídeo;
 - Memória: é responsável por armazenar os dados daquele dispositivo, como a memória RAM, ROM, HD, SSD entre outros;
 - Periféricos: são os hardware da respectiva máquina, periféricos de entrada e saída de dados, como o mouse, teclado, monitor, gabinete, caixa de som entre outros.

### COMO FUNCIONA UM MICROPROCESSADOR
Chamamos o processador de "cérebro" do computador, pois ele é o responsável por comandar e decodificar as informações da máquina, ele, por sua vez, é dividido em algumas partes, os registradores, são pequenas variáveis (células de memória) que armazenam para nós números em binário (onde convertidos transformam-se em informações). Seguem as partes:
 - AX e BX: registradores que são como variáveis uso geral;
 - PC: registrador de uso específico, ele aponta onde na memória será buscado a respectiva instrução;
 - IR: serve para armazenar temporariamente a instrução buscada na memória;
 - Unidade Lógico/Aritmética: responsável por executar operações lógicas (como com conectivos "e, ou" (como na tabela verdade)) e aritméticas (adição, subtração entre outros);
 - Unidade de Controle: assim como o microprocessador é o cérebro do computador a Unidade de Controle é o cérebro do microprocessador, ela é um autômato (máquina de estado) que coordena todas as ações dentro do microprocessador, ela é representada pelo diagrama chamado Ciclo de Máquina que, por sua vez, é composto por 3 passos fundamentais: a Busca (Fetch - como o nome diz, responsável por buscar a informação que ele irá executar), a Decodificação (responsável por entender aquela informação a fim de executá-la) e a Execução (a mais importante, executa a informação requerida).
