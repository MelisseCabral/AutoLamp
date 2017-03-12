# AutoLamp

<b>
Documentação: Central de Automação Residencial Modular<br>
Por: Julio Lima<br></b>

<h1>Análise de Mercado:</h1>

<p>Fomentado pela expansão do mercado imobiliário brasileiro nos últimos anos e o avanço da tecnologia possibilitado pelas várias plataformas de desenvolvimento disponíveis para o grande público, percebeu-se que apesar de toda a tecnologia disponível atualmente o setor imobiliário se mantém bem a parte disso. Talvez por ser um setor extremamente conservador seja tão carente de inovações.</p>

<p>A dificuldade de se implementar tecnologias no setor imobiliário vem da “injessabilidade” do setor devido aos custos para mudanças. Como exemplo disso podemos observar as mudanças que deveriam ser feitas em toda a instalação elétrica de uma casa caso fosse instalada uma central de controle qualquer. E o outro motivo é resistência que um Sr. dono de sua casa teria em pagar um valor de R$ 3000,00 para instalação de uma tecnologia de controle, da qual ele mal conhece.</p>

<p>Então o projeto em um primeiro âmbito é destinado a ser implementado por construtoras que ainda tenham a cotação total do imóvel a ser divulgada de forma que possa viabilizar a adição do custo de implementação da tecnologia no custo do total do imóvel, de forma que o consumidor não percebesse que pagou um valor relativamente alto para ter aquela tecnologia. Essa não percepção se dá por conta de a maioria dos imóveis serem financiados por bancos o valor da tecnologia numa parcela mensal, torna-se irrisório. </p>

<p>É de extrema importância observarmos no marketing que seria agregado a um condomínio ou residência, que tenha todo um sistema de controle a partir da planta, sem necessitar de modificação nenhuma pelo usuário, onde ele apenas usufruiria no conforto de seu SMARTPHONE ou SMARTWHATCH.</p>

<h1>Central de Controle:</h1>

<p>Existirá uma central de controle (chamaremos apenas de CDC), que se conectará a diversos periféricos (DPE), os controlará por meio de tecnologia sem fio (wifi) e fará aquisições montando planilhas estatísticas onde por meio da análise de um software poderá otimizar o consumo, assim economizando energia e integralizando tecnologias.</p>

<p>O avanço da tecnologia nos faz perceber que algumas tecnologias que de fato foram extraordinárias, facilitaram e ajudaram a vida das pessoas por muitos anos, porém hoje em dia se já se tornaram obsoletas e completamente substituíveis por outras mais ergonômicas e viáveis. Com a ampla propagação de conceitos como SMARTPHONE e SMARTWATCH, torna-se fácil a implementação dessas plataformas com outras como o proposto CDC. Por meio de um aplicativo dedicado a plataforma CDC o usuário poderá controlar e otimizar diversos aspectos de sua vida e casa via celular, por meio de uma senha pessoal.</p>

<p>Essa integração será viabilizada com a inserção do CDC na rede de internet da residência (wifi), assim ele não terá que se conectar a vários dispositivos como os DPE e sim apenas a um o CDC, que por sua vez se conectará aos respectivos DPE’s e fará toda a interface.</p>

<h1>Dispositivos Periféricos:</h1>
<p>Os dispositivos periféricos (DPE’s) serão destinados várias funções como controle de equipamentos, indicação de que equipamento está ligado, consumo, leitura de luminosidade do ambiente, quantas horas cada lâmpada fica acesa por dia entre outras.</p>

<p>Obedecendo ao padrão atual, existirão dois dispositivos básicos que fará tudo isso, um destinado a lâmpadas e outro destinado a tomadas.</p>

<p>O dispositivo de tomada basicamente controlará todas as tomadas, consequentemente todos os dispositivos que estiverem ligados a ela, agregando todas os controles de dispositivos citados acima, exceto, obviamente, o controle de lâmpada e luminosidade.</p>

<p>O dispositivo de lâmpada, visando o não descarte do equipamento caso a lâmpada queime e driblando uma possível baixa adaptação, será constituído de um bulbo e um receptáculo onde o usuário encaixara a lâmpada ele e por sua vez é encaixado no receptáculo da residência. Nele haverá um dispositivo que se conectará ao CDC, como dito acima, e alguns sensores de luminosidade visando um possível planejamento para controle de gasto, onde serão traçados gráficos de horas de lâmpada ligada e comparativos mostrando que em determinadas horas do dias é desnecessário a lâmpada está ligada.</p>

<p>Porém para não tornar o CDC limitado a um determinado número de dispositivos que ele pode se conectar, ou seja, para que ele não possa se conectar apenas a uma determinada quantidade de DPE’s que por ventura venha num kit junto com o CDC será implementado leitor de RFID em no CDC e um código RFID em cada DPE, de forma que possibilitará o cadastro de cada DPE novo, que o usuário queira instalar em sua residência. Tornando-o completamente ilimitado quanto ao número de controles permissíveis, bastando apenas o usuário comprar um novo DPE e cadastra-lo junto ao CDC e usufruí-lo do conforto do seu gadget.</p>

<h1>A proposta do Dispositivo</h1>

<p align="justify" >  O Dispositivo deve ser uma alternativa de baixo custo aos modelos de automação residencial existentes no
mercado atual.</p> 
<p> A processo de instalação é simples e pode ser feito sem a necessidade um técnico ou de qualquer conhecimento na área. A configuração também não deverá ser um problema para a maioria dos usuarios o processo será simples e bem explicado no manual que acompanhará o dispositivo.</p>
<p>O dispositivo conta também com a facilidade de funcionar para qualquer lâmpada encontrada no mercado e quando uma lâmpada queimar é só troca-lá e o dispositivo continuará a funcionar normalmente sem necessidade de troca ou reparo.</p>

<h1>Instalação </h1>

<p>Basta rosquear o dispositivo no soquete de lâmpada o qual você dejesa automatizar e em seguida rosquear a lâmpada no dispositivo. A parti dai o dispositivo estará em funcionando em uma configuração padrão e a qualquer momento o usuario poderá reconfigurar como desejar entrando no painel de configuração do dispositivo.</p>

<h1> O Funcionamento do dispositivo </h1>

<p>O dispositivo é composto por um microcontrolador da familia ESP12, reguladores de tensão entre outros componetes e seu ele cadastra e reconhece o dispositivo master utilizado (computador, tablet, smartphone e etc) a parti do seu RFID (do inglês "Radio-Frequency IDentification") é um método de identificação automática através de sinais de rádio, recuperando e armazenando dados remotamente através de dispositivos denominados etiquetas RFID.</p>

<p>Entretanto o usuario final não necessita de conhecimentos sobre essa tecnologia pois toda a utilização será por uma interface gráfica (Web Page) de uso intuitivo e agrádavel.</p>
