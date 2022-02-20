#include <stdio.h>
#include <stdlib.h>
//partners: dylanjb5, aadim2
// This code below takes user input of row index and prints out the row using formula of
// coefficients of given expression given k(entry) and n(row).Program iterates row+1
//number of times and finds n factorial, k factorial, and n-k factorial to find and
//print out result. If k is 0, then entry will be 1.
int main()
{
  int row;

  printf("Enter a row index: ");
  scanf("%d",&row);

  // Write your code here
  for(int k=0; k<row+1; k++){

    if(k==0){                           //if k=0, result=0
      unsigned long int  result=1;
      printf("%lu ", result);           //print out result and end iteration
      continue;
    }else{
     int n_fact=1;                      //if k isnt 0, find factorial of n
    for(int i=row;i>0; i--){
      n_fact*=i;
    }
    int nmink=row-k;                   //find row-k
    int nmink_fact=1;                  //set variable for (row-k) factorial
    if(nmink!=0){                      //if row-k isnt 0 find factorial, otherwise
      for(int i=nmink; i>0;i--){       //leave factorial as 1
	nmink_fact*=i;
      }
    }
    int k_fact=1;                      //find k factorial
    for(int i=k; i>0; i--){
      k_fact*=i;
    }
    unsigned long int result=n_fact/(nmink_fact*k_fact);
    printf("%lu ", result);            //set result equal to formula using factorials, print result
    continue;
    }
}
  
}
