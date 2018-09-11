# TáxiQueixa

  
O  **TáxiQueixa** é uma plataforma que possibilita os clientes reclamarem sobre o serviço prestado numa viagem. Através desta plataforma os taxistas, associações de táxis ou centrais de táxis podem consultar todas as opiniões e avaliações feitas pelos passageiros. Em alguns casos, quando registados, os proprietários podem responder às reclamações feitas sobre o seu veículo. Este projeto nasceu com base na ideia de que é possível melhorar ainda mais o serviço prestado por estes profissionais.


# 📗 Base de Dados

A quantidade de veículos existentes em Portugal foi consultada no micro-site da [AMT - Autoridade da Mobilidade e dos Transportes](taxis.amt-autoridade.pt). Os dados nele contido são relativos a 2016, sendo que, é necessária a constante actualização da base de dados da plataforma **TáxiQueixa**.

## 🚖 Táxis

Cada táxi possui uma "ficha", nela consta quantas pesquisas foram feitas, comentários, matrícula, e quando possível, as informações de contacto dos proprietários.

ex: `taxiqueixa.com/porto/1`



## 👥 Utilizadores

Os utilizadores são registados através do número de telemóvel. Recorremos ao Facebook Account Kit para permitir esta funcionalidade. Os números são armazenados na base de dados para servir de ID da conta de utilizador, o mesmo nunca será divulgado.


## 🏙️ Concelhos

Os veículos estão agrupados por 309 concelhos, por isso, é necessário que o utilizador tenha sempre em atenção a numeração do veículo e o respetivo concelho.

ex: `taxiqueixa.com/porto`

## 🔍 Pesquisas


* `LOCAL` : As pesquisas são armazenadas no dispositivo do utilizador através da funcionalidade *[localStorage](https://medium.com/trainingcenter/simplificando-html5-web-storage-api-4ce0f904e0ee)*.
* `REMOTO` : Armazenado na base de dados, estes dados serão utilizados apenas para efeitos de estatística e nunca será revelado que utilizador pesquisou o veículo X.


# 📡 API

O acesso é público, porém é necessário requisitar uma chave de acesso *(token)*  através do e-mail:
suporte@taxiqueixa.com. No e-mail, especifique para que necessita da API, e indique o domíno/url onde esta irá requisitada.

URL da API
> api.taxiqueixa.com


🤟 Colaborar & Ficha Técnica
-----------------

*Helppppp!*
* `Android e iOS` : A nossa praia 🏖️ é a web... se tens experiência numa destas plataformas e queres ajudar fala connosco.

*Resolvido.*
* `Progressive Web App` : É a maneira ideal que encontrámos para divulgar a aplicação porque quer o Google Chrome, quer o Safari, deixam adicionar o ícone no smartphone e aceder mesmo quando offline..
* `Alojamento` : A **TáxiQueixa** está partilhado com a [
BlueStage](https://bluestage.net), os servidores são da [One.com](http://one.me/ptawsdls).
* `Domínio` : Está registado com a [One.com](http://one.me/ptawsdls)
