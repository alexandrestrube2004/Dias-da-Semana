import java.util.Scanner;
public class numerossemana
{
    public static void main()
    {
        Scanner ler= new Scanner(System.in);
        //String dia = "Você informou um valor inválido";
        int d;
        
        System.out.printf ("\n Digite o número referente ao dia:");
        d= ler.nextInt();
        
       /*if (d==1) dia= "Domingo";
       if (d==2) dia = "Segunda";
       if (d==3) dia = "Terça";
       if (d==4) dia = "Quarta";
       if (d==5) dia = "Quinta";
       if (d==6) dia = "Sexta";
       if (d==7) dia = "Sábado";*/
       
       if (d>7 || d==0) System.out.printf ("\n Valor inválido");
       switch (d)
       {
           case 1:
           System.out.printf ("\n Domingo");
           break;
           case 2:
           System.out.printf ("\n Segunda-feira");
           break;
           case 3:
           System.out.printf ("\n Terça-feira");
           break;
           case 4:
           System.out.printf ("\n Quarta-feira");
           break;
           case 5:
           System.out.printf ("\n Quinta-feira");
           break;
           case 6:
           System.out.printf ("\n Sexta-feira");
           break;
           case 7:
           System.out.printf ("\n Sábado");
           break;
       }
       //System.out.printf ("O dia da semana é %s", dia);
    }
}
