    # Algo-5.9
Bulat Positif

    #include <iostream>
    #include <conio.h>
    using namespace std;
    int main ()
    {
        int bil,jum,i;
        cout<<"masukan bilangan bulat positif :";
        cin>>bil;
        jum = 0;
        for(i=1;i<=bil;i++)
            if (bil&1==0)
            jum++;
        if(jum==2)
            cout<<"bilangan tersebut adalah bilangan prima \n";
        else
            cout<<"bukan bilangan prima \n";
        std::cout<<" \n";
        std::cout<<"nama : muhammad safii \n";
        std::cout<<"nim  : 311810210";
        return 0;

    }
    
  Aplikasi
  
  ![img](https://github.com/muhammadyusufalfaqih/Algo-5.9/blob/master/bulat%20positif%20img.png)
