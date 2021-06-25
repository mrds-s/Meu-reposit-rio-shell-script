# Meu-reposit-rio-shell-script
# Neste repositório, estão alguns códigos que eu aprendi em aula e outros que desenvolvi sozinha para material de estudo.

#!/bin/bash 
echo "MENU DE OPERAÇÕES, INFORME OS NUMEROS PARA PROSSEGUIR:"

echo "Informe o primeiro numero"
read num1
echo "Informe o segundo numero" 
read num2

clear

echo "Qual operação gostaria de realizar?"
read opcao

echo " 1 - Soma"
echo " 2 - Subtracao"
echo " 3 - Multiplicacao"
echo " 4 - Divisao"

function escolha {
 
if [ $opcao -eq 1 ]; then

soma= $ (( $ num1 +  $ num2))  # realizando a soma
	echo  " $num1 + $num2 = $resultado"

 
  elif [ $opcao -eq 2 ]; then
    echo "$[num1-num2] = $resultado"
    
    elif [ $opcao -eq 3 ]; then
      echo "$[num1*num2] = $resultado"
      
      elif [ $opcao -eq 4 ]; then
        echo "$[num1/num2] = $resultado"
        
        else
          echo "Opcao invalida. Tente novamente."
         fi
}                                                                                                                                       
                           
