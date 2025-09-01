## This is my activity Arrays 1

''' Cpp
#include <iostream>
using namespace std;

int main() {
    //1. Create array of 100 integers
    int arr[100];
    for (int i=0;  i < 100; i++){
        arr[i]=i;
    }
    //2. Size of the each elements
    cout<< "Element size :" << sizeof(arr[0] )<<" bytes"<< endl;
    //3.The number of steps for operation (theoritical)
    // let's call it N=100
    //reading 1 step
    //Searching N steps ( must check all elements )
    //Insertion of the beggining N steps ( shift all teh elements to the right)
    //INsertation at the end 1 step ( just place arr[N])
    //Deletion at the begining N steps
    // Deleting at the end 1 steps ( just remove the last elements )
    
    //4. Count all the instance value
    // If array lenght=N , it takes N steps
    
    //5. Memory Address of the Array
    cout<<arr<<endl;
    cout<<"Array start: " <<arr<<endl;
    cout<<"First elements:"<<&arr[0] <<endl;
    
}

##This is my video 
https://youtu.be/HFTylNwaykM
