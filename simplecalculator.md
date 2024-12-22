#include <iostream>
using namespace std;
int main() {
    int a,b;
    double result;
    char ch;
    cout<<"first no."<<endl;
    cin>>a;
    cout<<"second no."<<endl;
    cin>>b;
    cout<<"enter the choice"<<endl;
    cin>>ch;
    switch(ch){
        case '+':result=a+b;
        cout<<result;
        break;
        case '-': result=a-b;
        cout<<result;
        break;
        case '*':result=a*b;
        cout<<result;
        break;
        case '/':
            if (b != 0) {  
                result=a/b;
                cout<<result;
            } else {
                cout << "Error: Division by zero is not allowed." << endl;
            }
            break;
        default:
        cout<<"error in input";
    }

    return 0;
}
