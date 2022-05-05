# Reserva de hotel

Uma rede de hotéis em Miami gostaria de oferecer um serviço de reservas pela internet. A
rede é composta por três hotéis: Lakewood, Bridgewood e Ridgewood. Cada hotel tem taxas
diferenciadas para dia de semana ou final de semana, incluindo taxas específicas para
participantes do programa de fidelidade. Adicionalmente, cada hotel tem uma classificação,
indicando a excelência do serviço.

## Cada hotel tem uma quantidade de classificação associada a ele:

```
  - Lakewood possui uma classificação 3 e suas taxas de dia de semana são R$110 para
clientes normais e R$80 para participantes do programa de fidelidade. As taxas de
final de semana são respectivamente R$90 e R$80 para clientes normais e
participantes do programa de fidelidade.
    
 - Bridgewood possui uma classificação 4 e suas taxas de dia de semana são R$160 para clientes normais e R$110 para participantes do programa de fidelidade. As taxas de final de semana são respectivamente R$60 e R$50 para clientes normais e participantes do programa de fidelidade.

 - Ridgewood possui uma classificação 5 e suas taxas de dia de semana são R$220 para clientes normais e R$100 para participantes do programa de fidelidade. As taxas de final de semana são respectivamente R$150 e R$40 para clientes normais e participantes do programa de fidelidade.

O software deverá encontrar o melhor hotel para o cliente se hospedar. O melhor
hotel é aquele que fornecer o melhor preço no total de diárias. Em caso de empate de
preços, o hotel com mais estrelas deverá ser retornado.

##Exemplo de entrada:
  1. normais: 16Mar2015(seg), 17Mar2015(ter), 18Mar2015(qua)
  2. normais: 20Mar2015(sex), 21Mar2015(sab), 22Mar2015(dom)
  3. fidelidade: 26Mar2015(qui), 27Mar2015(sex), 28Mar2015(sab)

##Saída esperada:
  1. Lakewood: R$330
  2. Bridgewood: R$280
  3. Ridgewood: R$240

## Como rodar reserva-hotel-api
```
git clone https://github.com/AlineDaniel/reserva-hotel-api-master.git

cd reserva-hotel-api
mvn clean install
cd target

java -jar reserva-hotel-1.0.jar /path/input-data.txt 
obs: reserva-hotel-api/src/main/resources/input-data.txt

ou

java -jar reserva-hotel-1.0.jar
```








