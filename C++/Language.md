### Input Output:
* **cin** for input, **cout** for output

Standard namespace:
#using namespace std;
OR 
* **std::cin**
* **std::court**

Endline:
* **"\n"** or endl; for ending line

String input: 
* **getline(cin, str);**
* getline takes 1 line into string str


### Data types: 

![image](https://github.com/s1mran/DSA/assets/35377484/cf205871-9c8b-4471-9397-f56829aef7e2)

### If Else statements

### Switch statements
```
switch(a) {
    case 1:
    do this;
    break;
    
    case2: 
    do it;
    break;
    
    default:
    do last;
}
```
* If we do not add break in any case, all the cases written after that case will get executed until it finds a break, when that case matches the condition.

### Loops
* For Loop: 
```
for (initialization for var; condition for var; change the var){
// do anything;
}
```

* While Loop:
```
Initialize var;
while(condition for var){
    change the var;
}
```
* Do While loop:
  
//DO executes the do block at least once before checking the condition
```
Initialize var;
do {
    change the var;
} while(condition for var)
```
### Functions (Pass by Reference and Value)
* functions can be **void**, **return**, **non parameterized**, **parameterized**

* we can pass by value or reference

* takes the copy of passed var
```int byValue (int b){ b = 1;}```

* changes passed var
```int byRef(int &b){b = 3;}```

### Pointers 
* Points to a var, stores it's memory address

### Double pointer
* Points to a pointer, stores pointers memory address

![image](https://github.com/s1mran/DSA/assets/35377484/e25874ae-1d99-4e78-8350-1b8f8710c812)

```
int a = 1;
int *ptr = &a; // address of a
*ptr = 2; // value of a or a is *ptr, now a is changed to 2
int **ptr2 = &ptr; // address of ptr
*ptr2 is address of a
**ptr2 is => *(*(ptr2)) => *(*(ptr address)) => *(a address) => a
**ptr2 = 4 => a is 4 now

```

