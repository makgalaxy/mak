# mak
guys can u tell me eror in this code
#include<iostream>
using namespace std;
  
class Test {
    int value;
public:
    Test(int v = 0) {value = v;}
    int getValue() {return value;}
};
  
int main() {
    const Test t;
    cout &lt;&lt; t.getValue();
    return 0;
}

#include<iostream>
using namespace std;
class Demo
{
    int value;
    public:
    Demo(int v = 0) {value = v;}
    void showMessage()
    {
        cout&lt;&lt;&quot;showMessage() Function&quot;&lt;&lt;endl;
    }
    void display()const
    {
        cout&lt;&lt;&quot;display() Function&quot;&lt;&lt;endl;

    }
};
int main()
{
    const Demo d1;
    d1.showMessage();
    d1.display();
    return(0);
}
