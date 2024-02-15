#include<iostream>
using namespace std ;
int add (int n1,int n2,int n3){
    int sum (n1+n2+n3);
    return sum;
}
int add (int n1,int n2){
    int sum (n1+n2);
    return sum;
}
float add(float n1,float n2,float n3){
    float sum (n1+n2+n3);
    return sum;
}
int main (){
    float a,b,c;
    cin >>a>>b>>c;
    cout<<"the result is: "<<add(a,b,c)<<endl;
    
    return 0;
}
