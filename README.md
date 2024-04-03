# Vector

#include<iostream>
#include<bits/stdc++.h>
using namespace std;
/*int main(){
    vector<int> v;
    v.push_back(1);
    v.emplace_back(3);
    for(int x:v)
    cout<<x<<" "<<endl;
    vector<int> vec(5,100);
    for(int x:vec)
    cout<<x<<" ";
    vector<int> vect(vec);
    cout<<endl;
    for(int x:vect){
        cout<<x<<" ";
        
    }
    
}*/



int main(){
    vector<int> v;
    int a;
    for(int i=0;i<5;i++){
    cin>>a;
    v.push_back(a);
    }
    for(int x: v){
        cout<<x<<" ";
    }
cout<<endl;
    vector<int>::iterator it=v.begin();
    cout<< *it;

    cout<<*v.end()<<endl;;
    cout<<*v.begin()<<endl;
    cout<<*v.rend()<<endl;
    cout<<*v.rbegin()<<endl;
    v.insert(v.begin()+1,5);
    for(int x: v){
        cout<<x;
    }
    
}

//v.back,v.erase,v.copy,v.size,v.popback,v1.swap(v2),v.clear,v.empty












