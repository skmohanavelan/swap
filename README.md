import java.util.Scanner;
public class Swap {
public static void main(String[] args)
{
int a = 150, b = 250;
System.out.println(&quot;Before Swap&quot;);
System.out.println(&quot;x = &quot; + a);
System.out.println(&quot;y = &quot; + b);
int temp = a;
a = b;
b = temp;
System.out.println(&quot;After swap&quot;);
System.out.println(&quot;a = &quot; + a);
System.out.println(&quot;b = &quot; + b);
}
}
