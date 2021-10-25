#include <iostream>
#include <string>
using namespace std;


class school
{
    private:
        string name[5];
        int rollno[5];
        int number;
        
    public:
        void countnumber(void){number = 0;}
        void setdata(void);
        void displaydata(void);
};

void school :: setdata(void)
{
    cout<<"ENTER YOUR ROLLNO : "<<number + 1<<" PERSON."<<endl;
    cin>>rollno[number];
    
    cout<<"ENTER YOUR NAME : "<<endl;
    cin>>name[number];
    
    number++;
}

void school :: displaydata(void)
{
    for(int i = 0; i < number; i++)
    {
        cout<<"WELCOME "<<name[i]<<"!"<<endl;
        
        cout<<"YOUR ROLL NO IS : "<<rollno[i]<<endl;
    }
}

int main()
{
    school student;
    
    student.countnumber();
    student.setdata();
    student.setdata();
    student.displaydata();
      
    return 0;
    
    
}
