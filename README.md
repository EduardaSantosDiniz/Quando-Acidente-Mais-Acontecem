# Como saber se você está em uma situação que causa mais acidentes no ano?      
Criei um projeto que revela qual a situação que mais causa acidentes no Brasil.  
Utilizei todos os dados registrados de acidentes em 2018 para usar como embasamento para esse projeto, você encontra facilmente todos os dados que usei aqui:
 
RENAEST: https://dados.transportes.gov.br/dataset/renaest/resource/0459b4ba-f7f5-469f-8ff3-c999b11f7cf2   
            
         
            
  
                    
      
Caso o site ficou inativo ou por algum outro motivo você não conseguiu baixar os dados, me mande uma mensagem no meu e-mail que tentarei te ajudar eduardafaculdade0306@gmail.com
   
Essa base de dados nos dá bastante detalhes sobre cada acidente que aconteceu no ano de 2018 porém existem alguns dados que dependem de outras informações que não temos, por isso mostrarei os dados que irei utilizar:

Clima 
Dia da Semana  
Fase do Dia 
Estado da Pista
Não vou usar dados como gênero, estado e tipo de veículo.

# Por quê?
Pelo simples fato de que são dados que dependem do seu número total, é importante que possamos verificar quando um dado depende de outro que é o que acontece nesse caso, gênero por exemplo existem muito mais homens que dirigem do que mulheres, então provavelmente homens causam mais acidentes, mas não pelo fato de realmente causarem mais, mas sim pelo fato que são maiores em número, mesma coisa com estado, São Paulo tem muito mais habitantes que a maioria dos outros estados então provavelmente acontece mais acidentes lá. Conseguiu entender?

# Chegou o momento de analisar os números
Pedi a frequência de acidentes divididos por dias da semana.
![Image](https://github.com/user-attachments/assets/ba77bbdd-6e16-4b55-85ca-3f0d83e6d0dd)

Percebemos que os três primeiros são praticamente iguais.

(na verdade tirando domingo, podemos dizer que não existe dia específico que acontece mais acidentes, porém irei utilizar os 3 primeiros).
# Diferente do Clima
No clima já conseguimos perceber um grande padrão.
![Image](https://github.com/user-attachments/assets/f69d2a9b-63da-4d44-a2ea-facaf116a258)

# Podemos dizer o mesmo da condição da pista
A condição que mais acontece acidentes é a Seca.
![Image](https://github.com/user-attachments/assets/7f268d93-d82b-43e5-885a-bcb20cc2fa5e)

# Fase do Dia
O período da tarde é quando ocorrem mais sinistros.
**![Image](https://github.com/user-attachments/assets/a7a02bee-aa32-4e24-8325-a7487849a16d)**

Agora que coletamos todos os dados necessários
# Qual a maior probabilidade de acontecer um acidente?
![Image](https://github.com/user-attachments/assets/aca111ca-b33d-4ae3-bd8f-800e3aaa5e46)

Como os dias quarta, segunda e sexta ficaram praticamente empatados decidi usar os 3 dias

# Insights
Podemos verificar que no ano de 2018 os acidentes ocorreram mais durante o período da tarde, com a pista seca, o clima claro e provavelmente em uma segunda-feira ou quarta-feira.

Por incrível que pareça os dados foram contra a previsão, muitos pensam que seria em uma madrugada pela falta de luz, ou em uma sexta pelo aumento de condutores dirigindo com efeito do álcool, porém o que os dados nos mostram são que os condutores acabam se envolvendo em sinistros justamente por estarem mais relaxados, quando um condutor se encontra em um clima chuvoso em uma madrugada, ele costuma redobrar sua atenção, evitando um possível acidente.

# Percebeu o quanto é importante usar os dados para tomar decisões?
Gostou do Projeto e gostaria de mais detalhes?

Link com o código completo: https://github.com/EduardaSantosDiniz/Acidentes_Transito/blob/main/Acidentes_Transito.ipynb

Medium: https://medium.com/@eduardafaculdade0306/qual-a-maior-probabilidade-de-acontecer-um-acidente-d2fec902f7e0
