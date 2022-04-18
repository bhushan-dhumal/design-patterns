Singleton implmentation using reference.

``` c++

#include<iostream>>
using namespace std;

class Singleton
{
    public:
    static Singleton& getInstance()
    {
        return sInstance;
    }
    
    void test()
    {
        cout<<"testing method"<<endl;
    }
    
    private:
    Singleton() {};
    Singleton(const Singleton& sr) {}
    Singleton(Singleton&& sr) {}
    static Singleton sInstance;
};

Singleton Singleton::sInstance;

int main()
{
    Singleton& sr = Singleton::getInstance();
    sr.test();
}

```


links

[YT](https://www.youtube.com/watch?v=PPup1yeU45I)

[YT](https://www.youtube.com/watch?v=IJKu2pebSwc)
