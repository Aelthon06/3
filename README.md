# 3
#include <iostream>
using namespace std;

int main()
{
    int num,remain;
    cout<< "Plese Enter a Number/n";
    cin >> num;
    remain = num % 2;
    if (remain == 0){
    cout <<  num << " is an Even Number";
    }else {
        cout << num << "is a odd Number";
        
    }
    
    
    return 0;
}
