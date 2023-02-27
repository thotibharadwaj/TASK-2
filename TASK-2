import java.util.Scanner;
class Main
{
   public static void main(String args[])
    {
        int Uno,Sno,n=7;
        Sno=1+(int)(100*Math.random());
        while(n>0)
        {
            Scanner sc = new Scanner(System.in);
            System.out.println("enter a number between 1-100:");
            Uno=sc.nextInt();
            if(Sno==Uno)
            {
                System.out.println("Congratulations Your number matches with system number");
                break;
            }
            else if (Sno<Uno)
            {
                if(n>1 && n!=2)
                {
                    System.out.println("OOPS! Your number doesn't match with the system number. You have "+(n-1)+" "+"chances");
                    System.out.println("HINT: Your number should be smaller than entered number.");
                }
                if(n==2)
                {
                    System.out.println("OOPS! Your number doesn't match with the system number. You have only "+(n-1)+" "+"chance");
                    System.out.println("HINT: Your number should be smaller than entered number.");
                }
            }
            else
            {
                if(n>1 && n!=2)
                {
                    System.out.println("OOPS! Your number doesn't match with the system number. You have "+(n-1)+" "+"chances");
                    System.out.println("HINT: Your number should be greater than entered number.");
                }
                if(n==2)
                {
                    System.out.println("OOPS! Your number doesn't match with the system number. You have only "+(n-1)+" "+"chance");
                    System.out.println("HINT: Your number should be greater than entered number.");

                }
            }
            n--;
        }
        if(n==0)
        {
            System.out.println("Sorry! Your chances completed.");
            System.out.println("The number is "+Sno);
        }
    }
}
