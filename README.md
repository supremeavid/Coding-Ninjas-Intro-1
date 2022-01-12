# Coding-Ninjas-Intro-1
#include <iostream>

using namespace std;

int main()
{
    //How negative numbers are stored?===>Done
    //Write a program to convert fahreneit to celsius
    int f;
    cin>>f;
    double cel= (f-32)*5/9.0;
    cout<<cel<<endl;

    return 0;
}

  Intro-2:::
  
  
  #include <iostream>

using namespace std;

int main()
{
    //Write a program to check whether a number is even or odd:
   /* int n;
    cout<<"Write the number to be tested"<<endl;
    cin>>n;
    if(n%2==0){
        cout<<"Even"<<endl;
    }
    else{
        cout<<"Odd"<<endl;
    } */



    //While loop revision:
    //While the condition inside is true, loop the code again and again
    //Print all the numbers from one to n, take n from user


    /*int n;
    cout<<"Write the number"<<endl;
    cin>>n;
    int i=1;
    while(i<=n){
        cout<<i<<endl;
        i++;
    }
    */

    //More on while loop:
    //Check whether a given number n is prime or not:
   /* int n;
    cout<<"Write the number to be tested"<<endl;
    cin>>n;

    bool isPrime=0;
    int i=2;
    while(i<=(n-1)){
        if(n%i==0){
            isPrime=1;

        }
        i++; //This updation line is most important don't commit mistakes here bruh
       // else{
       //     cout<<"Prime"<<endl;        //This is a very big mistake, 2 se divide karke dekha, nahi hua toh not prime?
       // }
    }
    if(isPrime==0){
        cout<<"Prime"<<endl;
    }
    else{
        cout<<"Not prime"<<endl;
    } */



    //Find sum of all even numbers from 1 to n:
   /* int n;
    cout<<"Write the number to be tested"<<endl;
    cin>>n;
    int sum=0;
    int d=2;
    if(n%2==0){
        while(d<=n){
            sum=sum+d;
            d=d+2;
        }
        cout<<sum;
    }
    else{
         while(d<n){
            sum=sum+d;
            d=d+2;
        }
        cout<<sum;

    } */

    //Patterns using while loop:
    //1
    //12
    //1234
    //12345

/*    int i=1;
    int n;
    cout<<"Write the number of stairs in pattern"<<endl;
    cin>>n;
    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<j;
            j++;
        }
        cout<<endl;
        i++;

    }  */


    //Patterns using while loop:
    //1
    //23
    //456
    //78910
/*    int n;
    cout<<"Write the number of stairs in pattern"<<endl;
    cin>>n;
    int i=1;
    int sum=1;

    while(i<=n){
        int j=1;
        while(j<=i){
            cout<<sum;
            j++;
            sum=sum+1;
        }
        cout<<endl;
        i++;
    }   */

    //print the above same pattern but the layout should be starting from right instead of left
/*     int n;
    cout<<"Write the number of stairs in pattern"<<endl;
    cin>>n;
    int i=1;
    int sum=1;

    while(i<=n){
        for(int i=1;i<=(n-1);i++){
            cout<<" ";
        }

        int j=1;
        while(j<=i){
            cout<<sum;
            j++;
            sum=sum+1;
        }
        cout<<endl;
        i++;
    }       */

    //Print the first pattern but the orientation shall be starting from right
      int n;
    cout<<"Write the number of stairs in pattern"<<endl;
    cin>>n;
    int i=1;
    int val=1;
    while(i<=n){
        int k=1;
        while(k<=(n-i)){
            cout<<" ";
            k++;
        }
        int j=1;
        while(j<=i){
            cout<<val;
            j++;
            val=val+1;
        }
        cout<<endl;
        i++;
    }



    return 0;
}

      
      
  
