echo "Enter a number"
read n
count=0
for((i=1;i<=n;i++))
 do
	 if [ `expr $n % $i` -eq 0 ]
	 then 
		 ((count++))
	 fi
 done
	 if [ `expr $count` -eq 2 ]
       then 
	       echo "The number is  prime."
       else
	       echo "The number is not prime"
       fi
