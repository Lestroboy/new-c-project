#include <iostream>
#include <string>
#include <cstdlib>
#include <ctime>
using namespace std;

int main()
{
{
    int A, age, num, guess, tries = 0;
    string name, bot, yesno;
    
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
            
            //ASKING THE PERSON WHO NAMED YOU.
            
            cout<<"SO "<<name<<" COULD I KNOW WHO NAMED YOU SUCH A CUTE NAME?"<<endl<<endl;
            cout<<"ENTER 1 IF 'YES'.\nENTER 0 IF 'NO'."<<endl;
            cin>>A;
            
            if(A == 1){
                cout<<"IT FELLS GOOD YOU AGREED WITH ME :)"<<endl<<endl;
                
                cout<<"ENTER 1 IF MOTHER."<<endl;
                cout<<"ENTER 2 IF FATHER."<<endl;
                cout<<"ENTER 3 IF BROTHER."<<endl;
                cout<<"ENTER 4 IF SISTER."<<endl;
                cout<<"ENTER 5 IF UNCLE."<<endl;
                cout<<"ENTER 6 IF AUNT."<<endl;
                cout<<"ENTER 7 IF YOU YOURSELF."<<endl;
                
                cout<<"ENTER THE NUMBER DOWN BELOW."<<endl;
                cin>>A;
                
                if(A == 1){
                    cout<<"OH! IT'S YOUR MOTHER."<<endl;
                    cout<<"SO LISTEN "<<name<<" SHE IS JUST LIVING BECAUSE OF YOU"<<endl;
                    cout<<"SO, NEVER FEEL HER SAD"<<endl<<endl;
                }
                
                else if(A == 2){
                    cout<<"OH! IT'S YOUR FATHER."<<endl;
                    cout<<"LISTEN "<<name<<" HE IS BEING YOUR BACK BONE FROM BITH."<<endl;
                    cout<<"SO FROM NOW ON YOU NEED TO BE HIS BACKBONE :)"<<endl<<endl;
                }
                
                else if(A == 3){
                    cout<<"OH! IT'S YOUR BROTHER."<<endl;
                    cout<<"YOU ARE SO LUCKY "<<name<<" :)"<<endl;
                    cout<<"HE MUST BE TEACHING YOU GREAT THINGS :)"<<endl<<endl;
                }
                
                else if(A == 4){
                    cout<<"OH! IT'S YOUR SISTER."<<endl;
                    cout<<"I WISH I COULD HAVE A SISTER :("<<endl;
                    cout<<"BTW... YOU ARE TOO LUCKY :)"<<endl<<endl;
                }
                
                else if(A == 5){
                    cout<<"OH! IT'S YOUR UNCLE."<<endl;
                    cout<<"HMM...YOU MUST BE HAVING A GREAT UNCLE"<<endl<<endl;
                }
                
                else if(A == 6){
                    cout<<"OH! IT'S YOUR AUNT."<<endl;
                    cout<<"OH! IT SEEMS LIKE YOU MUST BE GETTING LOT'S OF STUFFS TO EAT :)"<<endl<<endl;
                }
                
                else if(A == 7){
                    cout<<"OH! IT'S YOU YOURSELF."<<endl<<endl;
                    cout<<"DOES THIS MAKE SENSE "<<name<<" :("<<endl;
                    cout<<"HAHAHA LET IT BE I WON'T SAY ANYTHING."<<endl<<endl;
                }
                
                else{
                    cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTION :("<<endl<<endl;
                }
                  
            }
            
            else if(A == 0){
                cout<<"HMM... OK! IF YOU DON'T WANT TO TELL :)"<<endl<<endl;
            }
            
            else{
                cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTION :("<<endl<<endl;
            }
              
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
             cout<<"SORRY BUT....THEIR'S NOTING TO SAY ANYTHING ABOUT YOUR AGE.\nAS I AM JUST 16 :)"<<endl<<endl;
         }
         
         
         cout<<"YOU ARE GOING TO PLAY AN AMAZING GAME :)"<<endl<<endl;
         
         cout<<"GAME INFO :YOU NEED TO PUT A RANDOM NUMBER\nAND THIS PROGRAM WILL TELL YOU\nHOW CLOSE YOU ARE TO THE NUMBER WHICH COMPUTER HAD DECIDED\nIT WILL SHOW HOW FAR AND CLOSE YOU ARE TO THE NUMBER\nIF YOU WILL ENTER THE NUMBER EXACTLY WHAT COMPUTER HAD DECIDED\nYOU WIN AND WILL SHOW HOW MANY TRIES IT TOOKED YOU TO WIN THIS GAMME."<<endl<<endl;
         
        //GUESS NUMBER GAME. 
         
         
        //seed random number generator
        
    	srand(time(0));
    	
    	// random number between 1 and 100
    	 
    	num = rand() % 100 + 1;
    	
    	cout << "GUESS MY NUMBER GAME!"<<endl<<endl;
    
    	do
    	{
    		cout << "GUESS AND ENTER THE NUMBER BETWEEN 1 TO 100 : "<<endl;
    		cin >> guess;
    		tries++;
    
    		if (guess > num){
    			cout<<"TOO HIGH!"<<endl<<endl;
    		}
    		
    		else if (guess < num){
    			cout<<"TOO LOW!"<<endl<<endl;
    		}
    		
    		else{
    			cout<<"CORRECT! YOU GOT IT IN "<<tries<<" GUESSES!"<<endl<<endl;
    		}
    		
    	} while (guess != num);
         
        cout<<"HOPE YOU ENJOYED THIS GAME :)"<<endl<<endl;
        
        //ASKING AGAIN TO PLAY THAT GAME AGAIN.
        
        cout<<"DO YOU WANT TO PLAY THAT GAME AGAIN?"<<endl<<endl;
        cout<<"ENTER 1 IF 'YES'.\nENTER 0 IF 'NO'."<<endl;
        cin>>A;
        
        if (A == 1){
    			cout<<"IT SEEMS LIKE YOU REALLY LOVE THAT GAME :)"<<endl<<endl;
    			cout<<"HERE YOU GO :)"<<endl<<endl;
    			
    		cout<<"GAME INFO :YOU NEED TO PUT A RANDOM NUMBER\nAND THIS PROGRAM WILL TELL YOU\nHOW CLOSE YOU ARE TO THE NUMBER WHICH COMPUTER HAD DECIDED\nIT WILL SHOW HOW FAR AND CLOSE YOU ARE TO THE NUMBER\nIF YOU WILL ENTER THE NUMBER EXACTLY WHAT COMPUTER HAD DECIDED\nYOU WIN AND WILL SHOW HOW MANY TRIES IT TOOKED YOU TO WIN THIS GAMME."<<endl<<endl;
       
    	srand(time(0));
    	
    	num = rand() % 100 + 1;
    	
    	cout << "GUESS MY NUMBER GAME!"<<endl<<endl;
    
    	do
    	{
    		cout << "GUESS AND ENTER THE NUMBER BETWEEN 1 TO 100 : "<<endl;
    		cin >> guess;
    		tries++;
    
    		if (guess > num){
    			cout<<"TOO HIGH!"<<endl<<endl;
    		}
    		
    		else if (guess < num){
    			cout<<"TOO LOW!"<<endl<<endl;
    		}
    		
    		else{
    			cout<<"CORRECT! YOU GOT IT IN "<<tries<<" GUESSES!"<<endl<<endl;
    		}
    		
    	} while (guess != num);	
    		}
    		
    	//ELSE IF DON'T WANT TO PLAY.	
    		
    		else if (A == 0){
    			cout<<"IT SEEMS LIKE YOU ARE DONE WITH THAT GAME!"<<endl<<endl;
    		}
    		
    		else{
    			cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTION :("<<endl<<endl;
    		}
        
        
        cout<<"WELL! IS WAS A GREAT TIME WITH YOU :)"<<endl<<endl;
        cout<<"WELL "<<name<<" I AM GOING NOW BECAUSE I WANT SOME WATER"<<endl<<endl;
        cout<<"SO...IF YOU WANT TO HIRE A SERVANT YOU CAN!"<<endl<<endl;
        cout<<"ENTER 'YES' OR 'NO' DOWN BELOW."<<endl;
        
        
        cin>>yesno;
        
        if(yesno == "yes" || yesno == "YES" || yesno == "Yes"){
            cout<<"HELLO MY LORD :)"<<endl;
            cout<<"IT FEELS GOOD THAT I AM GOING TO BE YOUR SERVANT FRO NOW ON :)."<<endl<<endl;
            cout<<"COULD YOU TAG ME A NAME PLEASE :)"<<endl<<endl;
            cout<<"ENTER THE NAME BELOW."<<endl;
            cin>>bot;
            
            cout<<"SO FROM NOW ON I AM YOUR "<<bot<<" :)"<<endl<<endl;
        }
        
        else if(yesno == "no" || yesno == "NO" || yesno == "No"){
            cout<<"SO WELL "<<name<<" I AM LEAVING NOW YOU ARE ALONE HERE"<<endl<<endl;
        }
        
        else{
            cout<<"YOU MIGHT HAVE NOT FOLLWED THE INSTRUCTION :("<<endl<<endl;
        }
        
        cout<<"SO MY LORD YOU ARE GOING TO PLAY AN AMAZING AND THE BEST GAME EVER!"<<endl<<endl;
        
    //CASINO GAME GOES HERE.    
        
        string playerName;
        int balance; // stores player's balance
        int bettingAmount;
        int gues;
        int dice; // stores the random number
        char choice;
        srand(time(0)); // "Seed" the random generator
        cout << "\n\t\t========WELCOME TO CASINO WORLD=======\n\n";
        cout << "\n\nWhat's your Name : ";
        cin >> playerName;
        getline(cin, playerName);
        cout << "\n\nEnter the starting balance to play game : $";
        cin >> balance;
        do
        {
            system("cls");
            
            cout << "\n\nYour current balance is $ " << balance << "\n";
    // Get player's betting balance
            do
            {
                cout << "Hey, " << playerName<<", enter amount to bet : $";
                cin >> bettingAmount;
                if(bettingAmount > balance)
                    cout << "Betting balance can't be more than current balance!\n"
                           <<"\nRe-enter balance\n ";
            }while(bettingAmount > balance);
    // Get player's numbers
            do
            {
                cout << "Guess any betting number between 1 & 10 :";
                cin >> gues;
                if(gues <= 0 || gues > 10)
                    cout << "\nNumber should be between 1 to 10\n"
                        <<"Re-enter number:\n ";
            }while(gues <= 0 || gues > 10);
            dice = rand()%10 + 1;
            if(dice == guess)
            {
                cout << "\n\nYou are in luck!! You have won Rs." << bettingAmount * 10;
                balance = balance + bettingAmount * 10;
            }
            else
            {
                cout << "Oops, better luck next time !! You lost $ "<< bettingAmount <<"\n";
                balance = balance - bettingAmount;
            }
            cout << "\nThe winning number was : " << dice <<"\n";
            cout << "\n"<<playerName<<", You have balance of $ " << balance << "\n";
            if(balance == 0)
            {
                cout << "You have no money to play ";
                break;
            }
            cout << "\n\n-->Do you want to play again (y/n)? ";
            cin >> choice;
        }while(choice =='Y'|| choice=='y');
        cout << "\n\n\n";
        cout << "\n\nThanks for playing the game. Your balance is $ " << balance << "\n\n";
        return 0;
    }
    
    {
        system("cls");
        cout << "\t\t======CASINO NUMBER GUESSING RULES!======\n";
        cout << "\t1. Choose a number between 1 to 10\n";
        cout << "\t2. Winner gets 10 times of the money bet\n";
        cout << "\t3. Wrong bet, and you lose the amount you bet\n\n";
    }
     
    return 0;
}
