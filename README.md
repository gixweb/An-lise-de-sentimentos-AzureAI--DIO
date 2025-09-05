# Analise-de-sentimentos-AzureAI--DIO
Um README com insights e anotações sobre meus primeiros passos com a plataforma Speech Studio e Leguage Studio do Microsoft Azure AI

#### Utilizando o Speech Studio
###### Transcrevendo um áudio
Gravei o áudio de uma fala de um personagem chamado Yoshikage Kira de um anime que eue gosto, por ser de uma obra japonesa, a precisão foi de 99.8%, acertando todas as partes que ditei, tirando o nome do personagem e a loja de departamento que ele diz que trabalha, que se chama "Kameyu"

Texto original:
O meu nome é Yoshikage Kira, tenho 33 anos, moro na zona noroeste da cidade de Morioh, eu não sou casado, sou empresário da loja de departamentos Kameyu e chega em casa todo dia por volta das oito horas, eu não sou fumante e bebo apenas socialmente, eu me deito todo dia às onze horas e faço questão de dormir por 8 horas não importa oque aconteça, desde que eu possa tomar um copo de leite quente e me exercitar fazendo alongamentos por pelo menos 20 minutos antes de ir pra cama, eu costumo ter um sono interrúpto e acordo pela manhã sem o mínimo cansaço ou estresse, como se fosse um bebezinho despreocupado, no meu último check-up de saúde não encontraram nenhum problema, eu estou dizendo isso para mostrar que sou uma pessoa tranquila que evita se envolver em encrencas ou criar inimizades e tenho certeza de que vivendo assim eu consigo ser feliz.

Texto gerado:
Novamente. É só um teste, então vamos lá. Meu nome é Oscar niqueira. Tenho 33 anos, moro na zonas noroeste da cidade de morio. Não sou casado, sou empresário da loja de departamentos kameo e chego em casa todo dia por volta das 8:00. Não sou fumante e bebo socialmente. Eu deito todo dia às 11:00 e faço questão de dormir por 8 horas e não me importa o que aconteça, desde que eu possa tomar um copo de leite quente e me exercitar fazendo alongamentos por pelo menos 20 minutos antes de ir pra cama. Eu costumo ter um sono ininterrupto e acordo pela manhã sem o mínimo de cansaço ou estresse, como se fosse um bebezinho despreocupado. No meu último check-up de saúde, encontraram nenhum problema. Eu estou dizendo isso pra mostrar que sou uma pessoa tranquila e evita se envolver em encrencas ou criar inimizades. E tenho certeza que vivendo assim eu consigo ser feliz. 

Obs:
- Essa ferramenta é muito útil para legendar na hora vídeos ou registrar falas importantes de uma ligação etc.
- O ruim é que provavelmente se paga um plano para áudios que são maiores que 1 minuto, na minha primeira tentativa o áudio foi cortado no meio quando comecei a ditar o texto do Yoshikage Kira

#### Utilizando o Language Studio
###### Analisando uma sentença
Observações: um pouco complicado de começar

Primeiramente precisamos criar um recurso de análise de texto, como a plataforma do Azure atualizou sua interface ao longo do tempo, ficou difícil achar o “language server” que estavam usando na dinâmica
Como achar: Pesquise Text Analysis e marque a caixa de serviços do Azure
Para criar o recurso é necessário um plano na microsoft Azure nem que seja estudantil (foi como eu consegui)

###### Finalmente analisando o sentimento de texto
Fui testar com uma copypasta besta do twitter e funcionou!
A copypasta em questão: "Fui dormir na casa da minha namorada ontem a noite. O pai dela não nos deixou dormir na mesma cama. E isso me deixou com muita raiva porque ele é realmente muito bonito"

![Analise do texto](./Downloads/image(1).png)
