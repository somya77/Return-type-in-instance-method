# Return-type-in-instance-method
Here int main is used as the method is returning integer value
class Test5
{
 int add(int a,int b)
{
  int x=a;
  int y=b;
 return(x+y);
}
int mul()
{
 int c=5;
 return(c*c);
}
public static void main(String args[])
{
 Test5 obj = new Test5();
  System.out.println(obj.add(20,50));
  System.out.println(obj.mul());
}
}
 
