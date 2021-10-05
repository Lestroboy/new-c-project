#include <iostream>
#include <string>
using namespace std;

int main()
{
    int A, age;
    string name;
    
    cout<<"WELLCOME TO MY PROGRAM."<<endl<<endl;
    
    //ASKING IF HE/SHE IS GOOD.
    
    cout<<"ARE YOU GOOD?"<<endl<<endl;
    cout<<"ENTER 1 FOR 'YES'\nENTER 0 FOR 'NO'."<<endl<<endl;
    cin>>A;
    
    if(A == 1){
        cout<<"FEEL'S GOOD TO HEAR THIS :)"<<endl<<endl;
    }
    
    else if(A == 0){
        cout<<"IT'S :( FEEL'S BAD!"<<endl;
        cout<<"I AM PROMISING YOU TILL THE END OF THIS PROGRAM,\nYOU WILL START FELLING GOOD :)"<<endl<<endl;
    }
    
    else{
        cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
    }
    
    //ASKING WEATHER HE/SHE WANT TO KNOW ABOUT ME.
    
    cout<<"DO YOU WANT TO KNOW ABOUT ME"<<endl;
    cout<<"            OR              "<<endl;
    cout<<"JUST WANT TO ENJOY THIS PROGRAM."<<endl<<endl;
    
    cout<<"ENTER 1 TO KNOW ABOUT ME.\nENTER 0 TO JUST ENJOY THIS PROGRAM."<<endl;
    cin>>A;
    
    if(A == 1){
        cout<<"IT SEEMS LIKE YOU ARE CURIOUS ABOUT ME :)"<<endl<<endl;
        
        cout<<"MY REAL NAME IS SUDHIR, JUST SUDHIR.\nI AM 16 YEAR OLD BOY.\nI LOVE TO COOK, YA YOU CAN SAY I AM GOOD AT COOKING.\nI AM NOT MUCH SOCIAL IN REAL LIFE.\nI MOSTLY LOVE TALKING PEOPLE ON INTERNET.\nI LOVE TO PROGRAM WHEN I WAS 15.\nFOR NOW I JUST KNOW TWO PROGRAMMING LANGUAGES\n1.HTML\n2.C++.\nMY FAVRIOUT YOUTUBER'S ARE\nDANI\nMR.BEAST\nMYTHPAT\nIAMBIXU\nMY DREAM IS TO BE A GAME DEVELOPER AND YOUTUBER."<<endl<<endl;
    }
    
    else if(A == 0){
        cout<<"HMM... :( I SEE. IT'S OK!"<<endl;
        cout<<"..............................."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".    ......         ......    ."<<endl;
        cout<<".    .    .         .    .    ."<<endl;
        cout<<".    .    .         .    .    ."<<endl; 
        cout<<".    ......         ......    ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".   ...                 ...   ."<<endl;
        cout<<".   . .                 . .   ."<<endl;
        cout<<".   . ................... .   ."<<endl; 
        cout<<".   .......................   ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl;
        cout<<".                             ."<<endl; 
        cout<<"..............................."<<endl;
        }
        
        else{
            cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
        }
        
        //ASKING GENDER.
        
        cout<<"SO WHAT IS YOUR GENDER?"<<endl<<endl;
        cout<<"ENTER 1 IF YOU ARE A 'BOY'.\nENTER 0 IF YOU ARE A 'GIRL'."<<endl<<endl;
        cin>>A;
        
        if(A == 1){
            cout<<"HMM... I SEE.BOY'S SHOULD ALWAYS RESPECT TO GIRL'S."<<endl<<endl;
        }
        
        else if(A == 0){
            cout<<"HMM... RIGHT NOW A GIRL IS CHECKING MY PROGRAM\nTHANKS FOR COMING :)"<<endl<<endl;
        }
        
        else{
            cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
        }
        
        //ASKING GOOD NAME.
        
        cout<<"COULD YOU TELL ME YOUR GOOD NAME :)"<<endl<<endl;
        cout<<"ENTER 1 FOR 'YES'.\nENTER 0 FOR 'NO'."<<endl<<endl;
        cin>>A;
        
        if(A == 1){
            cout<<"ENTER YOUR NAME BELOW!"<<endl;
            cin>>name;
            
            cout<<"HI "<<name<<" NICE TO MEET YOU :)"<<endl<<endl;
        }
        
        else if(A == 0){
            cout<<"IT SEEMS LIKE YOU DON'T WANT ANYONE TO KNOW YOUR NAME!"<<endl<<endl;
        }
        
        else{
            cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
        }
        
        //ASKING TO PLAY A GAME.
        
        cout<<"WELL "<<name<<" THEIR ARE MANY THINGS TO ASK AND TALK"<<endl<<endl;
        cout<<"BUT, BEFORE THAT LET'S PLAY SOME TRICKY GAME :)"<<endl<<endl;
        
        cout<<"ENTER 1 IF YOU WANT TO PLAY A TRICKY GAME .\nENTER 0 IF YOU DON'T WANT TO PLAY A TRICKY GAME ."<<endl<<endl;
        cin>>A;
        
        if(A == 1){
            cout<<"SO "<<name<<" YOU ARE READY TO START A TRICKY GAME, THAT'S GOOD."<<endl<<endl;
            
            cout<<"STEP 1.THINK A NUMBER BETWEEN 1 TO 10."<<endl;
            cout<<"STEP 2.NOW MULTIPLY THE NUMBER YOU CHOOSED BY 2."<<endl;
            cout<<"STEP 3.THE ANSWER YOU GOT MULTIPLY IT BY 5."<<endl;
            cout<<"STEP 4.THE ANSWER YOU GOT DIVIDE IT BY THE NUMBER YOU CHOOSED AT THE START."<<endl;
            cout<<"STEP 5.THE ANSWER YOU GOT NOW SUBSTRACT IT BY 7."<<endl;
            
            //TELLING THE ANSWER OF MATHS TRICK.
            
            cout<<"SO LET ME TELL YOU THE ANSWER YOU GOT IS [3]"<<endl;
            
            //ASKING TO USE CALCULATOR.
            
            cout<<"DO YOU WANT TO USE THE CACULATOR?\nFOR CROSS CHECKING THE ANSWER."<<endl;
            cout<<"ENTER 1 FOR 'YES'.\nENTER 0 FOR 'NO'."<<endl;
            cin>>A;
            
            if(A == 1){
                cout<<"ENTER THE NUMBER YOU THOUGHT"<<endl;
                cin>>A;
                
                int ansum = A*2*5/A-7;
                
                cout<<"SO "<<name<<" "<<ansum<<" IS THE ANSWER YOU GOT FROM CALCULATOR"<<endl;
            }
            
            else if(A == 0){
                cout<<"SEEMS LIKE YOU HAVE YOUR OWN CALCULATOR!"<<endl<<endl;
            }
            
            else{
                cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
            }
            
        }
        
        else if(A == 0){
            cout<<"HMM... OKAY IF YOU ARE NOT INTERESTED IN THE GAME."<<endl<<endl;
        }
        
        else{
            cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTIONS :("<<endl<<endl;
        }
         
         cout<<"WELL "<<name<<"! LET'S GET BACK TO THE CONVERSATION."<<endl<<endl;
         
         //ASKING THE AGE.
         
         cout<<"I FORGOT TO AGK YOUR AGE?"<<endl;
         cout<<"ENTER YOUR AGE BELOW!"<<endl;
         cin>>age;
         
         if(age == 1){
             cout<<"YOU ARE 1 YEAR OLD!"<<endl;
             cout<<"ARE YOU KIDDING ME?"<<endl;
             cout<<"YOU ARE JUST CHECKING MY ABILITY, RIGHT?"<<endl;
         }
         
         else if(age == 2){
             cout<<"YOU ARE 2 YEAR OLD!"<<endl;
             cout<<"CAN YOU EVEN WALK?\nHAHAHAHAHA......NICE JOKE!"<<endl;
         }
         
         else if(age == 3){
             cout<<"YOU ARE 3 YEAR OLD!"<<endl;
             cout<<"CAN YOU EVEN ANSWER WHAT IS 1+1+?\nHAHAHAHAHAHA.....NICE JOKE!"<<endl;
         }
         
         else if(age == 4){
             cout<<"YOU ARE 4 YEAR OLD!"<<endl;
             cout<<"FIRST YOU SHOULD LEARN TO WALK PROPERLY!\nHAHAHAHAHA......NICE JOKE!"<<endl;
         }
         
         else if(age == 5){
             cout<<"YOU ARE 5 YEAR OLD!"<<endl;
             cout<<"I THINK YOU SHOULD JOIN A SCHOOL!\nHAHAHAHA.....NICE JOKE!"<<endl;
         }
         
         else if(age == 6){
             cout<<"YOU ARE 6 YEAR OLD!"<<endl;
             cout<<"I THINK YOU SHOULD LEARN TABLE FIRST!\nHAHAHAHA....NICE JOKE!"<<endl;
         }
         
         else if(age == 7){
             cout<<"YOU ARE 7 YEAR OLD!"<<endl;
             cout<<"I THINK YOU ARE GENIUS!\nTHAT'S GREAT YOU MIGHT KNOW TO USE ELCTRONICS DEVICES!"<<endl;
         }
         
         else if(age == 8){
             cout<<"YOU ARE 8 YEAR OLD!"<<endl;
             cout<<"I THINK! YOU SHOULD START LEARNING CODING!"<<endl;
         }
         
         else if(age == 9){
             cout<<"YOU ARE 9 YEAR OLD!"<<endl;
             cout<<"GREAT YOU ARE NOT WASTING YOUR TIME\nYOU SHOULD SEARCH STUFFS LIKE THIS!"<<endl;
         }
         
         else if(age == 10){
             cout<<"YOU ARE 10 YEAR OLD!"<<endl;
             cout<<"I THINK YOU SHOULD DO SOME CRAZY STUFFS ON INTERNET\nLIKE THIS, HOW I DID THIS FIND OUT AND LEARN!"<<endl;
         }
         
         else if(age == 11){
             cout<<"YOU ARE 11 YEAR OLD!"<<endl;
             cout<<"I DON'T REMEMBER WAT WAS I DOING AT YOUR AGE!\nMIGHT BE PLAYING WITH MY TOYS :)"<<endl;
         }
             
         else if(age == 12){
             cout<<"YOU ARE 12 YEAR OLD!"<<endl;
             cout<<"I REMEMBER AT THIS AGE I CELEBRATED MY FIRST BIRTHDAY"<<endl;
         }
         
         else if(age == 13){
             cout<<"YOU ARE 13 YEAR OLD!"<<endl;
             cout<<"YOU ARE GOING GOOD, GREAT!"<<endl;
         }
         
         else if(age == 14){
             cout<<"YOU ARE 14 YEAR OLD!"<<endl;
             cout<<"YOU SHOULD NOW FOCUS ON YOUR STUDY'S\nYOU ARE DOING GREAT CHECKING STUFFS LIKE THIS!"<<endl;
         }
         
         else if(age == 15){
             cout<<"YOU ARE 15 YEAR OLD!"<<endl;
             cout<<"I STILL REMEMBER AT THIS AGE I WAS REALLY USE TO STUDY 18+ HOUR'S.\nI KNOW IT'S HARD TO BELIVE!"<<endl;
         }
         
         else if(age == 16){
             cout<<"YOU ARE 16 YEAR OLD!"<<endl;
             cout<<"YOU ARE ENOUGH TO HOLD YOUR FATHER'S WORK, GREAT!\nEVEN I AM TOO 16.\nIF YOU WOULD HAVE READ ABOUT ME IN THE STARTS :)"<<endl;
         }
         
         else if(age == 17){
             cout<<"YOU ARE 17 YEAR OLD!"<<endl;
             cout<<"YOU MIGHT BE KNOEING MORE THAN ME!"<<endl;
         }
         
         else if(age == 18){
             cout<<"YOU ARE 18 YEAR OLD!"<<endl;
             cout<<"CONGRAT'S YOU ARE ADULT NOW\nAH..ACCORDING TO THE LOGIC!"<<endl;
         }
         
         else{
             cout<<"SORRY BUT....THEIR'S NOTING TO SAY ANYTHING ABOUT YOUR AGE.\nAS I AM JUST 16 :)"<<endl;
         }
         
        
    

    return 0;
}
