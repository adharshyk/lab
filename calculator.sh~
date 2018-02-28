sum=0
t=1
while [ $t -eq 1 ]
do
	echo "Enter the operand1"
	read num1
	echo "Enter the operand2"
	read num2
	echo "SELECTION MENU"
	echo "1 ADDITION"
	echo "2 SUBTRACTION"
	echo "3 MULTIPLICATION"
	echo "4 DIVISION"
	echo "Enter your choice"
	read ch
	if [ $ch -eq 1 ]
	then
		sum=$((num1 + num2)) 
  		echo "Sum ="$sum
	elif [ $ch -eq 2 ]
	then
		sum=$((num1 - num2))
  		echo "diff ="$sum
	elif [ $ch -eq 3 ]
	then
		sum=$((num1 * num2))
  		echo "pro ="$sum
	elif [ $ch -eq 4 ]
	then
		sum=$((num1 / num2))
  		echo "div ="$sum
	else	
		echo "Invalid entrant"
	fi
	echo "Do you want to continue(0/1)?"
	read t
done
