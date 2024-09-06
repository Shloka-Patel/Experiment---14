# Experiment---14 

### Aim 

### Software 

### Theory 

### Code 
(A) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 14(A)  

# include <iostream>
# include <string>
using namespace std;

class Uni
{
    public:
    string uni= "Symbiosis";
    void discipline()
    {
        cout << "Engineering" <<endl;
    }
};
class Dep : public Uni
{
    public:
    string dept= " Electronics & Telecommunication";
};
int main()
{
    Dep u1;
    u1.discipline();
    cout<<u1.uni + " "+u1.dept ;
} 

```

(B) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 14(B) 

#include<iostream> 
#include<string> 
using namespace std; 

// Parent CLass1 
class Vehicle {
    public:
    string company=" Ford";
    void type(){
        cout << "Mustang"<< endl;
    }
};
// Parent Class 2
class Specs{
    public:
    string mileage="8 kmpl";
    void colour(){
        cout<<"Grey"<<endl;
    }
};
// Child Class-1 (derived from parent- 1&2)
class Car: public Vehicle,public Specs{
    public:
    string seater = " 4 seater";
};
int main(){
    //multiple inheritance
    Car f2;
    f2.colour();
    cout<<f2.company<<" ";
    f2.type();
    cout<<"("<<f2.seater<<")"<<endl<<"MILEAGE:"<<f2.mileage<<endl;
} 

```

(C) <br> 
```
```

(D) <br> 
```
```

### Output 
(A) <br>  
![](https://github.com/Shloka-Patel/Experiment---14/blob/main/Output_14A.png) 

(B) <br> 
![](https://github.com/Shloka-Patel/Experiment---14/blob/main/Output_14B.png) 

(C) <br> 
![]() 

(D) <br> 
![]() 

### Conclusion 
