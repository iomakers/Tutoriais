## Arduino

<p align="center">
  <img src="https://raw.githubusercontent.com/iomakers/Tutoriais/master/img/Arduino-uno-perspective-transparent.png"/>
</p>

A ideia deste tutorial e dar uma rapida introducao sobre essa placa, e te ensinar de maneira sucinta, a instalar e comecar a usar, passando pelo minimo necessario para que voce possa comecar a produzir com ela. De acordo com o Wikipedia:

> Arduíno é uma plataforma de prototipagem eletrônica de hardware livre e de placa única, projetada com um microcontrolador Atmel AVR com suporte de entrada/saída embutido, uma linguagem de programação padrão, a qual tem origem em Wiring, e é essencialmente C/C++.

---

### Menu
- [Comecando]()
- [Configuracoes Iniciais]()
- [Gravando seu primeiro programa]()
- [Funcao Setup & Loop]()
- [Funcoes Basicas]()
  - [pinMode( );]()
  - [digitalWrite( );]()
  - [delay( );]()
  - [analogWrite( );]()
  - [map( );]()
- [Links Uteis]()
  
---

### Comecando

Atraves [deste link](https://www.arduino.cc/en/Main/Software), voce pode fazer o download e instalacao da IDE (Ambiente de Desenvolvimento) do Arduino. Com ele, voce podera escrever o codigo, ver exemplos, manipular entrada e saida de dados, e gravar seu codigo dentro da placa, atraves de um cabo USB.

Para instalar, voce pode seguir um desses tutoriais (em ingles), de acordo com seu Sistema Operacional:
- [Windows](https://www.arduino.cc/en/Guide/Windows)
- [Mac OS](https://www.arduino.cc/en/Guide/MacOSX)
- [Linux](https://www.arduino.cc/en/Guide/Linux)

Voce tambem tem a opcao de usar a IDE sem precisar instalar, atraves do navegador, [neste link](https://www.arduino.cc/en/Main/Software).

---

### Configuracoes Iniciais

Depois da instalacao, abra o programa, clique na aba **Tools**, selecione a placa, de acordo com a versao do seu arduino.

<p align="center">
  <img src="https://raw.githubusercontent.com/iomakers/Tutoriais/master/img/101_Board_select.png"/>
</p>

Conecte sua placa a qualquer porta USB do seu computador, va na aba **Tools > Port**, e selecione a porta onde foi plugada a placa (ex. COM5).

<p align="center">
  <img src="https://raw.githubusercontent.com/iomakers/Tutoriais/master/img/101_Com_port.png"/>
</p>

---

### Gravando seu primeiro programa

Va em **File > New**, apague tudo, copie e cole o codigo abaixo.

```
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```

Para gravar na placa, aperte *Ctrl+U*, ou clique na *setinha*:
<p align="center">
  <img src="https://raw.githubusercontent.com/iomakers/Tutoriais/master/img/101_Upload.png"/>
</p>

---

### Funcao Setup & Loop

---

### Funcoes Basicas
### pinMode( );
### digitalWrite( );
### delay( );
### analogWrite( );
### map( );

---

### Links Uteis
