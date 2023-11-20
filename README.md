# Jogo de Xadrez com IA

É um jogo de xadrez simples que roda em um servidor flask. Ele é equipado com um mecanismo de xadrez integrado. Desenvolvido por mim, Felipe Botelho, Diego Moretti, Igor Marcucci, Karlos Eduardo e Henrique Santa Terra para um projeto de Inteligência Artificial. Ele roda em um servidor Flask, possui um mecanismo de xadrez integrado e a IA alerta sobre situações como xeque, xeque-mate ou impasse. O jogo é acessível em diferentes dispositivos, usando o host local ou a ferramenta ngrok. Não há restrições, permitindo que qualquer pessoa jogue a qualquer momento e em qualquer lugar.

# Instalação

Execute o seguinte comando em seu terminal:

```
git clone link.git
```

# Requerimentos

Você pode executar o `setup.py` pelo qual todos os módulos serão baixados automaticamente pelo pip:

```
python setup.py
```

# Execução

Execute o seguinte código em seu terminal:

```
python play.py
```

# Características

> 1. Assistente de voz
> 2. Segue todas as regras do xadrez
> 3. Pode ser reproduzido em dois dispositivos diferentes

# Jogando pela internet

Você pode usar a ferramenta [ngrok](https://ngrok.com/download) para jogar em dois lugares diferentes. Basta baixá-lo, fazer cd no seguinte diretório e digitar o seguinte código:

```
ngrok http 5000
```

Agora envie o seguinte link fornecido pelo ngrok para o usuário com quem deseja jogar. Basicamente, ele redirecionará o usuário para seu [localhost:5000](http://127.0.0.1:5000).

# Informações importantes

> 1. O jogo sempre começa pelas peças brancas, a IARA deve ser a primeira a jogar.
> 2. Em alguns momentos a IARA pode demorar até 30 segundos para fazer sua jogada, não fique solicitando repetidas vezes.

# Membros da Equipe

> 1. [Adrielly Isly](https://www.linkedin.com/in/adriellyisly/)
> 2. [Felipe Botelho](https://www.linkedin.com/in/felipe-gabriel-botelho/)
> 3. [Igor Marcucci](https://www.linkedin.com/in/igor-marcucci/)
> 4. [Diego Moretti](https://www.linkedin.com/in/diego-moretti-1267789a/)
> 5. [Karlos Eduardo](https://www.linkedin.com/in/karlos-eduardo-nunes-752b8a220/)
> 6. [Henrique Santa Terra](https://www.linkedin.com/in/henrique-s-ba48a8181/)
