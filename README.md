## Como configurar concessionária
 ##### Tudo se varia no princípio básico de: **NÃO PODE MISTURAR CARRO, MOTO, VIP e CAMINHÃO**

 O modelo é o seguinte: 

 ```lua
 local carros = { 
	{id = 1, nome = "carroVIP", nomeloja = "Infernus", estoquecarro = 40, precocarro = 5000,   pesocarro = 30, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    {id = 2, nome = "carronaoVIP", nomeloja = "Infernus", estoquecarro = 40, precocarro = 5000,   pesocarro = 30, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    -- vamos supor que tenhamos 40 carros, depois disso, vem as motos.
    {id = 41, nome = "moto", nomeloja = "BMWS1000", estoquecarro = 100, precocarro = 1500,   pesocarro = 10, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    {id = 42, nome = "hornet", nomeloja = "HORNET", estoquecarro = 100, precocarro = 1500,   pesocarro = 15, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    -- vamos supor que acabou as motos, agora vem os caminhões
    {id = 60, nome = "mule4", nomeloja = "Mule4 Caminhão", estoquecarro = 1000, precocarro = 1500,   pesocarro = 10, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    {id = 61, nome = "mule", nomeloja = "Mule", estoquecarro = 10000, precocarro = 1500,   pesocarro = 15, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    --- por ultimo, os carros vip (NESSA PARTE, ÚNICA QUE É NECESSARIA ADICIONAR A VÁRIAVEL `vip = true`)
    {id = 62, nome = "infernus", nomeloja = "Carro VIP", estoquecarro = 10000, precocarro = 1500, vip = true, pesocarro = 15, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},
    {id = 63, nome = "carrofoda", nomeloja = "Carro VIP 2", estoquecarro = 10000, precocarro = 1500, vip = true, pesocarro = 15, imagemcarro = "https://wiki.rage.mp/images/e/e2/Rhapsody.png"},

}
```

Regras: 
* Não pode repetir ID, por isso, é necessário que seja feito em equipe. Se mandar lista diferentes, os ids vão ser diferentes.
* O nome, tem que ser o nome de spawn in-game, o modelo.
* A váriavel `vip` só é necessária na parte dos VIPS.
* A mais importante: **não mistura os carros com motos, nem caminhões, nem vips**
* A váriavel `nomeloja` é o nome que irá aparecer na NUI, na hora de comprar.
* A imagem, precisa ser link direto, de preferência, em png.

- [ ] Motos
- [ ] Carros
- [ ] VIP
- [ ] Caminhão
