# my-homeworks
 
public static int fib(int n){
if ((n==1)||(n==2))
return 1;
else
return fib(n-1)+fib(n-2);
}
 
public static void main(String[] args) {
int n;
System.out.println("Podaj wyraz ciągu Finonacciego");
n = Console.readInt("?");
System.out.println("odpowiedź: "+fib(n));
return;
}
}
