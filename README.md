# 186-3-7

## part I 
I use the set function of python instead of list
``` python
 #array = [200, 400, 100, 50, 350]

array = {200,400,100,50,350}

array = {
    200: True,
    400: True,
    100: True,
    50: True,
    350: True
}


```
## part II 
``` C++

#include <iostream>

using namespace std;
int main() {
string name = "xiaofeng xing ";
 size_t theHashValue = hash<string>{}(name);

 cout << theHashValue ;

}
```

## part III

too many tombstone will slow the probing search time. like the figure 16 , H(33) the value 555322 became to the tombstone. while probing find out the index of 33, it will countinue search since it became to the mark, won't return the result . That's why the textbook said , too many tombstone will slow the time search the number, need creat the new list. 


### video 
https://youtu.be/6IrcCvqwcUE







