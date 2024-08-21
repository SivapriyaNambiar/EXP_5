# Condtional statements 
# Experiment 5: -To study and implement C++ decision making statements

## Aim
To learn how to implement decision making statements in C++ programming language

## Theory 
Decision-making in C++ helps to write decision-driven statements and execute a particular set of code based on certain conditions.

C++ has different types of decision making statements like
1. if
2. else if
3. else
4. switch
5. default

### if statement

if statement is the most simple decision-making statement.
It is used to decide whether a certain statement or block of statements will be executed or not executed based on a certain type of condition.

#### Syntax: -
if(condition)

{

   // will execute the code here depending on if the condition is satisfied 
   
}

### else if statement

An if-else statement controls conditional branching. Statements in the if-branch are executed only if the condition evaluates to a nonzero value (or true ). 
If the value of condition is nonzero, the following statement gets executed, and the statement following the optional else gets skipped.

#### Syntax: - 

if(condition_a)

{

  // will execute the code depending whether the condtion_a is satisfied 
  
}

else if(condition_b)

{

   // will excecute the code depending whether the condtion-a is not satisfied and condition_b is satsified
  
}

else

{

  // will execute the code if both t e condtions are not satisfied 
  
}

### switch and default statements 

Switch case is basically an optimised version of multiple else if statements with a difference of approximately 10^-3% faster speed meaning that it does not really matter if a person is using else if or switch and if micro management is required then try using looup or hash table in the codes.

Switch case has better readabilty, can be typed faster, easier to debug and harder to make mistakes compared to multiple else if statements.

default statements are like elese staement where in if the all cases are false then the block of the code will be executed. 

#### syntax:- 

switch (expression)

{

  case value_1;
  // statement 1 
  break;

  case value_2:
  //statement 2
  break;

  default:
  //default_statements
  break;
  
}


## Code 
~~~
#include <iostream>
using namespace std;

int main()
{
    int a,b,c;
    cout<<"Enter 3 variables: "<<endl;
    cin>>a;
    cin>>b;
    cin>>c;
    if(a>=b && a>=c)
    {
        cout<<"a is the largest number: "<<endl;
    }
    else if(b>=a && b>=c)
    {
        cout<<"b is the largest number: "<<endl;
    }
    else if(c>=a && c>=b)
    {
        cout <<"c is the largest number: "<<endl;
}
int month;
cout<<"Enter a number between 1 to 12"<< endl;
cin>>month;
switch (month)
{
    case 1:
    cout<<"Jan"<<endl;
    break;

    case 2:
    cout<<"February"<<endl;
    break;

    case 3:
    cout<<"march"<<endl;
    break;
    
    case 4:
    cout<<"April"<<endl;
    break;
    
    case 5:
    cout<<"May"<<endl;
    break;

    case 6:
    cout<<"June"<<endl;
    break;

    case 7:
    cout<<"July"<<endl;
    break;

    case 8:
    cout<<"August"<<endl;
    break;
    
    case 9:
    cout<<"September"<<endl;
    break;

    case 10:
    cout<<"October"<<endl;
    break;

    case 11:
    cout<<"November"<<endl;
    break;

    case 12:
    cout<<"December"<<endl;
    break;

    default:
    cout<<"Invalid input"<<endl;

}
}

    
~~~
## Output of the code
![image](https://github.com/user-attachments/assets/d2de0257-136b-4353-a598-5d31db9aec97)


## Conclusion
We learnt how to implement decision making statements like if, else if, switch in C++ programming language 
