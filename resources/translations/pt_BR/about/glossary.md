Glossário
====
Esta página explica alguns dos termos do setor empregados pela Cura. A Cura nem sempre é a mais consistente no que diz respeito ao uso da terminologia, portanto, alguns termos são sinônimos.

* Camadas adaptativas:** Uma técnica que varia a altura da camada ao longo da impressão para reduzir a visibilidade da topologia e, ao mesmo tempo, imprimir razoavelmente rápido.
* Aliasing:** Um defeito de impressão em que o limite de resolução dos motores de passo é visível na parte externa da impressão.
* Malha anti-superfície:** Um modelo que impedirá a geração de suporte para suportar qualquer saliência com a qual o modelo se sobreponha. Sinônimo de "bloqueador de suporte".
**Bead:** Um fio de material após ter sido colocado no chão pelo trem da extrusora. O termo "bead" é usado na ciência, onde é importante considerar a forma real do filamento após sua solidificação. Semelhante a "linha".
**Blob:** Um ponto de excesso de material na parte externa da impressão.
* Tubo Bowden:** Um tubo oco e flexível usado para guiar o filamento através do sistema de extrusão.
* Ponte: Uma técnica para imprimir linhas salientes no ar, esticando linhas retas entre dois pontos de repouso. O Cura pode ajustar os parâmetros das linhas de ponte e ajustará a direção de algumas linhas para criar pontes.
* Brim:** Uma borda de material, presa à impressão, que funciona como uma saia, mas também prende melhor a impressão à placa de construção, fornecendo mais área de superfície para o material aderir.
* Placa de construção:** A placa na qual a impressão é colocada enquanto está sendo construída. Algumas placas de construção são aquecidas para fazer o material aderir melhor enquanto a impressão está em andamento.
* Volume de construção:** O espaço 3D que a impressora pode alcançar para extrudar o material.
* Coasting: Uma técnica em que a última parte de um caminho de extrusão é impressa com 0% de fluxo, drenando o bocal de sua sobrepressão.
* Pentear:** Um movimento que tenta evitar atravessar paredes durante as viagens, para evitar a criação de uma cicatriz visível na parte externa da impressão.
* Origem da coordenada: O local na placa de construção onde um bocal se moveria se fosse instruído a se mover para as coordenadas [0, 0, 0].
* CuraEngine:** Um programa que o Cura usa para fazer o trabalho pesado do processo de corte. Converte modelos 3D em código g.
**Malha de corte:** Um modelo na placa de construção que pode alterar as configurações da parte de seu volume que se sobrepõe aos modelos impressos reais. O modelo em si não é impresso, mas corta pedaços de outros modelos e pode alterar as configurações ou a extrusora com a qual essas peças são impressas.
* Área não permitida:** Um local na placa de construção onde não é permitido colocar um modelo para impressão. Por exemplo, porque ele atingiria os grampos que seguram a base, a torre principal ou porque sua impressão teria peças auxiliares que sairiam do volume de construção.
* Proteção contra correntes de ar: Um invólucro de material sendo impresso ao redor do objeto que mantém a temperatura consistente ao redor da impressão.
* Pata de elefante: Um defeito de impressão em que o lado inferior da impressão é ligeiramente mais largo do que o desejado.
* Extrusora:** O alimentador, o tubo Bowden opcional, a zona de calor, a extremidade quente e o bocal juntos. Algumas impressoras têm várias extrusoras ou têm mais de uma de algumas partes do trem de extrusão. Abreviação de "extruder train" (trem de extrusão).
* Interruptor da extrusora:** Normalmente, apenas uma das extrusoras está ativa por vez. Um interruptor de extrusora é quando a extrusora ativa muda de uma extrusora para outra.
* Trem de extrusão:** O alimentador, o tubo Bowden opcional, a zona de aquecimento, a extremidade quente e o bocal juntos. Algumas impressoras têm vários trens de extrusoras ou têm mais de uma de algumas partes do trem de extrusoras.
* Extrusão: O ato de empurrar o filamento através do trem de extrusão, de modo que o material saia do bocal e, com sorte, seja depositado no local correto para formar a impressão.
* Face:** Uma superfície plana de uma malha 3D. Com malhas triangulares (o único tipo que o Cura pode processar), todas as faces são triângulos no espaço 3D.
* Ventilador: Não é qualquer ventilador da impressora, mas especificamente o(s) ventilador(es) conectado(s) ao cabeçote de impressão que resfria(m) a impressão logo após a extrusão do material.
* Impressão FDM:** Modelagem por deposição fundida. Um tipo de impressão 3D feito por meio da extrusão de linhas de plástico em um determinado formato. Essa é a única técnica de impressão 3D que o Cura suporta. Sinônimo de "impressão FFF".
* Alimentador: Um motor e uma caixa de engrenagens que empurra ou puxa o filamento pelo trem de extrusão.
* Taxa de alimentação: A velocidade na qual o filamento é alimentado no trem de extrusão.
* Impressão FFFF:** Fabricação de filamento fundido. Um tipo de impressão 3D feito pela extrusão de linhas de plástico em um determinado formato. Essa é a única técnica de impressão 3D que o Cura suporta. Sinônimo de "impressão FDM".
**Filamento:** Uma corda de plástico que está sendo alimentada na impressora 3D. Vem em carretéis. Depois de extrudado, ele deixa de ser filamento e passa a ser apenas material.
* Fluxo:** A taxa de extrusão de material como proporção de sua taxa normal. Teoricamente, mais de 100% de fluxo extrude mais material do que caberia no volume alocado. Menos de 100% de fluxo, teoricamente, extrude muito pouco material.
* Gantry: A estrutura mecânica que move o cabeçote de impressão ao redor do volume de construção.
* Preenchimento de lacunas:** Técnica usada pelo Cura para preencher pequenas lacunas na impressão com material usando segmentos de linha muito pequenos.
* Preenchimento gradual:** Uma técnica em que a quantidade de material é reduzida nas partes inferiores de um volume, mas ainda é alta nas partes superiores para suportar adequadamente o material acima dele. Isso não é usado apenas para o material, mas também para o suporte.
* Dureza:** Medida de uma impressão que indica o quanto ela pode resistir à deformação elástica ou à perfuração.
* Aquecedor:** Um elemento de aquecimento que leva o filamento à temperatura necessária para a impressão 3D.
* Zona de aquecimento:** A zona em que o filamento está se aquecendo enquanto se dirige ao bocal. No início da zona de aquecimento, o filamento está em temperatura ambiente. No final, ele está na temperatura de impressão.
* Hop:** Uma técnica em que o bocal é movido para cima (+Z) a fim de percorrer a impressão com um pouco de folga. Sinônimo de "Z hop".
* Hot end:** O bit de metal quente ou cerâmica que contém o bico, o elemento de aquecimento e o sensor de temperatura.
* Preenchimento: Uma estrutura criada na parte interna de uma impressão que sustenta a camada superior e fornece resistência adicional à impressão.
* Malha de preenchimento:** Semelhante à "malha de corte", mas só se aplica quando se sobrepõe ao volume de preenchimento de outro modelo. Esse é um modelo que ajusta as configurações de preenchimento de outro modelo.
* Paredes internas:** Todas as paredes, exceto a parede mais externa. Embora uma peça em uma camada tenha apenas uma parede externa, ela pode ter qualquer número de paredes internas.
* Inserção:** Uma operação em polígonos que produz um polígono menor/mais fino, cujo contorno mantém uma certa distância do contorno do polígono original. Uma inserção com uma distância negativa é chamada de "offset".
* Passar a ferro: técnica que passa mais uma vez sobre a superfície superior para torná-la mais lisa.
* Jerk:** Um limite na quantidade de mudança instantânea na velocidade aplicada no início de cada movimento. Isso não é o mesmo que a definição comum de "jerk" na física!
* Camada:** A impressão 3D é feita em camadas finas de material. Essas camadas são formas 2D com uma determinada espessura que, quando empilhadas verticalmente, formam uma impressão 3D.
* Deslocamento de camada:** Um defeito de impressão em que a posição horizontal de uma camada é deslocada involuntariamente, normalmente deslocando também o restante da impressão.
* Divisão de camada:** Um defeito de impressão em que as camadas não se unem bem o suficiente e se abrem.
* Linha: Um fio de material depois de ter sido colocado pelo trem da extrusora. No Cura, as linhas são modeladas como blocos retangulares com uma determinada largura, espessura (altura da camada) e comprimento. Semelhante ao "bead".
* Segmento de linha:** Para não haver ambiguidade com o termo de impressão 3D "linha", ao se referir a um segmento de linha em um sentido matemático, o Cura sempre usará o termo completo "segmento de linha" para indicar uma linha geométrica reta de comprimento limitado.
**Material:** O material que compõe sua impressão 3D. Normalmente, um termoplástico na impressão FFF.
* Malha:** Uma coleção de triângulos que, juntos, formam um modelo. Embora às vezes seja usado como sinônimo de "objeto" e "modelo", é normalmente usado no contexto de um dado em vez de algo que se deseja imprimir.
**Modelo:** Um modelo 3D carregado na cena 3D do Cura (antes do fatiamento). Sinônimo de "objeto".
* Bocal: A abertura por onde o material de impressão sai do trem da extrusora.
* Objeto:** Um modelo 3D carregado na cena 3D do Cura (antes do corte). Sinônimo de "modelo".
* Offset:** Uma operação em polígonos que produz um polígono maior/mais gordo, cujo contorno mantém uma certa distância do contorno do polígono original. Um deslocamento com uma distância negativa é chamado de "inset".
* Modo um por vez:** Um modo de impressão de vários objetos em que cada objeto é totalmente concluído antes de continuar com o próximo objeto, enquanto normalmente ele imprime uma camada para cada objeto antes de continuar com a próxima camada.
* Proteção contra vazamento: Uma concha de material sendo impressa ao redor da impressão que captura qualquer material vazado quando um deslocamento move o bocal em direção à impressão.
* Escorrimento: vazamento de material pelo bocal quando não é a intenção. Normalmente, isso deixa um fio de material ao longo do caminho de deslocamento.
* Parede externa:** A parede mais externa. Há apenas uma parede externa por peça e por camada.
* Sobreextrusão: Extrusão de muito material em um volume limitado, fazendo com que o material se espalhe para onde não deveria ir.
* Saliência:** Uma parte da impressão que não é (ou não é completamente) suportada pelo material nas camadas abaixo dela. Se a saliência for muito grande para imprimir bem, será necessário um suporte ou uma ponte.

* Sobrepressão:** Durante a impressão, a câmara do bocal é mantida sob grande pressão para garantir que o material seja extrudado de forma consistente.
* Estacionamento: O ato de pausar a impressão por um momento enquanto o bocal está longe da impressão, para permitir que o material esfrie por algum tempo.
* Parte:** Uma forma contínua (polígono) em uma única camada. Um único modelo pode se dividir em várias partes em determinadas camadas, quando fatiado.
* Padrão:** Uma técnica de preenchimento de um volume com material, embora não necessariamente com 100% de densidade. O Cura oferece opções entre vários padrões, como linhas, grade, concêntrico, tetraédrico, etc.
* Preenchimento:** Um defeito de impressão em que a pele superior se projeta ou se quebra entre as linhas de preenchimento abaixo.
* Polígono:** Uma forma 2D ou loop fechado que consiste em uma série de pontos com segmentos de linha reta entre eles.
* Blob primário:** Um blob de material que está sendo purgado no início de uma impressão para preparar uma extrusora.
* Torre de escorva:** Uma estrutura criada além da impressão que permite que a impressora escorve seus bicos em camadas mais altas sem que o excesso de material acabe na lateral da impressão real. Usada para impressões em que várias extrusoras estão envolvidas para preparar uma extrusora após ficar em espera por algum tempo.
* **Priming:** O ato de purgar algum material para garantir que o filamento esteja alinhado com a ponta do bico e a câmara do bico esteja preenchida e pressurizada corretamente. Geralmente é feito no início de uma impressão ou após a troca da Extrusora
**Purga:** O ato de extrudar algum material como resíduo. Um motivo comum para a purga é o "priming".
* **Raft:** Uma técnica para melhorar a adesão da placa de construção, imprimindo uma placa sólida sob a impressão posteriormente descartada. A placa tem uma grande área de superfície e é impressa com linhas grossas que aderem bem e capturam qualquer irregularidade na planicidade da placa de montagem.
**Retração:** O ato de usar o alimentador para puxar o material de volta para a câmara do bocal. Normalmente, isso é feito para impedir temporariamente que o material flua para fora do bocal para fazer um percurso limpo.
* Ringing:** Um defeito de impressão em que a superfície oscila devido à extrusão inconsistente ou à oscilação do bocal. Normalmente, ocorre depois de fazer cantos agudos muito rapidamente.
* Cicatriz: Um ponto de dano na parte externa da impressão em que o bocal derreteu o material durante a passagem.
* Costura: O local onde um loop fechado começa e termina. Esse ponto geralmente é visível na impressão final, portanto, você deve posicioná-lo em um local onde não seja muito visível.
* Concha: Tanto as paredes quanto a pele.
* Pele: Os lados superior e inferior da impressão. Elas são sempre impressas com 100% de densidade, normalmente com o padrão de linhas. Sinônimo de "superior/inferior".
* Saia:** Um contorno desenhado ao redor da impressão na primeira camada para preparar o material e permitir que o usuário veja se a placa de construção está completamente nivelada.
* Fatiamento:** O processo de conversão de um modelo 3D em instruções para a impressão em uma impressora 3D. No contexto da CuraEngine, isso também é usado às vezes para o processo de criação de seções transversais do modelo, que é um dos estágios do processo completo de fatiamento.
* Modo de espiralização:** Um modo para imprimir apenas o contorno dos modelos, normalmente enquanto aumenta gradualmente a coordenada Z em toda a camada para eliminar a costura Z, imprimindo o modelo em uma grande espiral. Fora do Cura, isso também é conhecido como "modo vaso".
* Em espera: Ao imprimir com várias extrusoras, normalmente apenas uma delas está ativa por vez. As outras extrusoras ficarão em stand-by.
* Costura:** Uma parte do processo de corte. A criação de seções transversais de um grupo de triângulos resulta em vários segmentos de linha em cada camada. A costura combina esses segmentos de linha em polígonos e determina qual é o interior da camada.
* Força:** Termo abrangente que indica várias medidas de resistência ao movimento, incluindo dureza, rigidez e resistência quando vários tipos de força estão sendo aplicados.
* Estrangulamento:** Ao se deslocar enquanto exsuda material, isso cria fios finos de material chamados de "estringência". Os fios não necessariamente se estendem por toda a extensão de um movimento de deslocamento. Uma forma menos extrema desse fenômeno resulta em "bolhas".
* Suporte: Uma parte da impressão que é removida após a impressão, mas que era necessária para manter partes da impressão no lugar enquanto ela ainda estava em andamento, para evitar que o material caísse ou balançasse demais.
* Bloqueador de suporte:** Um modelo que impedirá a geração de suporte para suportar qualquer saliência sobre a qual o modelo se sobreponha. Sinônimo de "malha anti-superfície".
* Piso do suporte:** O lado inferior do suporte, usado onde o suporte se apóia no modelo. Essa parte do suporte pode, opcionalmente, ser impressa com configurações diferentes. Não há piso de suporte onde o suporte repousa sobre a placa de construção.
* * **Preenchimento de suporte:** O principal componente do suporte. Se não houver interface de suporte, o suporte consistirá apenas no preenchimento de suporte.
* Interface de suporte: O teto e o piso do suporte, onde o modelo se apóia no suporte e onde o suporte se apóia no modelo. O lado inferior do suporte, onde o suporte se apóia na placa de construção, não tem interface de suporte.
* Malha de suporte: Um modelo que está sendo preenchido com estrutura de suporte, em vez de ser impresso como uma impressão normal. Pode ser usado para personalizar a forma do seu suporte.
* Teto do suporte:** O lado superior do suporte, usado onde o modelo se apóia no suporte. Essa parte do suporte pode, opcionalmente, ser impressa com configurações diferentes.
* Torres de suporte:** Uma técnica para suportar partes muito finas ou pequenas da impressão. A peça é apoiada pela ponta de uma torre que fica mais larga na parte inferior para que o suporte não tombe durante a impressão.
* Termoplástico:** Um tipo de plástico que se torna macio ao derreter. Somente termoplásticos podem ser usados para impressão FFF.
* Espessura:** O tamanho de alguma estrutura na direção vertical (Z). Compare com "largura".
* Parte superior/inferior:** Os lados superior e inferior da impressão. Elas são sempre impressas com 100% de densidade, normalmente com o padrão de linhas. Sinônimo de "skin".
* Superfície superior:** A parte mais alta da pele superior. Raramente com mais de uma camada, essa superfície superior pode ser impressa com configurações separadas para obter maior qualidade sem gastar muito tempo extra de impressão.
* Topografia:** O efeito em que a altura limitada da camada transforma uma superfície quase plana em algo que se assemelha a um mapa geográfico de altura com anéis onde as camadas terminam.
* Dureza:** Medida de uma impressão quanto à resistência à deformação plástica.
* Transição (de paredes):** O local onde diferentes números de paredes se unem para tornar a peça mais fina ou mais grossa usando um número diferente de paredes em algumas partes do que em outras.
* Deslocamento (movimento):** Mover o bocal de um lugar para outro sem extrusão de material.
* Subextrusão: extrusão de material insuficiente para preencher adequadamente um volume ou para criar contas fortes e contínuas.
* Subpressão: Enquanto estiver retraída, a câmara do bocal é mantida em uma pressão negativa para sugar o material de dentro, evitando a exsudação.
* Modo vaso:** Um modo para imprimir apenas o contorno dos modelos, normalmente enquanto aumenta gradualmente a coordenada Z em toda a camada para eliminar a costura Z. O Cura sempre chama isso de "modo de espiralização".
* Paredes: As laterais da impressão. Elas circundam o modelo horizontalmente.
* Deformação da impressão após a impressão, devido ao encolhimento do material ou a tensões internas que puxam o material enquanto ele ainda não está solidificado.
* Largura:** O tamanho de alguma estrutura na direção horizontal (X/Y). Compare com "espessura".
* Ordem de enrolamento:** A ordem dos pontos que formam um polígono. Pode ser no sentido horário ou anti-horário. No Cura, uma ordem de enrolamento no sentido anti-horário indica uma forma positiva, enquanto uma ordem de enrolamento no sentido horário indica um buraco. Os modelos 3D de entrada devem ter triângulos com ordem de enrolamento no sentido anti-horário quando vistos de fora.
* **Limpeza:** Uma técnica para fazer com que o bocal atravesse uma estrutura impressa anteriormente com o objetivo de limpar qualquer material pendente da ponta do bocal, para evitar que esse material seja colocado na parte externa da impressão.
* Impressão de arame:** Uma técnica para imprimir um modelo imprimindo apenas uma estrutura de arame em torno de sua concha. Altamente experimental.
* Costura Z:** Um ponto visível na parede externa onde o bocal se moveu de uma camada para a outra. Frequentemente usado de forma incorreta em vez de apenas "costura".
* Z hop:** Uma técnica em que o bocal é movido para cima (+Z) a fim de percorrer a impressão com um pouco de folga. Sinônimo de "hop".