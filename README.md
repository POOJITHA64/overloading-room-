# overloading-room-
class Over 
{
    int v,v1,v2;
    void method()
    {
        System.out.println("method with no paramter");
        v1=20;
        v2=40;
        v=v1*v2;
        System.out.println("area of room"+v);
    }
    void method(int a)
    {
        System.out.println("method with one paramter");
        v1=a;
        v2=50;
        v=v1*v2;
        System.out.println("area of room"+v);
    }
    void method(int a,int b)
    {
        System.out.println("method with two paramters");
        v1=a;
        v2=b;
        v=v1*v2;
        System.out.println("area of room"+v);
    }
}
class Main 
{
    public static void main(String args[])
    {
        Over m=new Over();
        m.method();
        m.method(20);
        m.method(40,60);
    }
}
