# Codeforcescpp-71A
#include<iostream>
#include<string.h>
 
using namespace std;
 
void printWordAbbre(string word){
 
    int len = word.length();
    if(len > 10){
        cout << word[0] << len-2 << word[len-1];
    }
 
    else{
        cout << word;
    }
}
 
int main(){
    int a;
    cin >> a;
    for(int i=0;i<a;i++){
        string word;
        cin >> word;
        printWordAbbre(word);
        cout << endl;
    }
    return 0;
}
