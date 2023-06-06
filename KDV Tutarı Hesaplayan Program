import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double tutar, kdvOran, kdvTutari, kdvliTutar;
        Scanner input = new Scanner(System.in);
        System.out.print("Tutarınızı giriniz: ");
        tutar = input.nextDouble();

        kdvOran = tutar > 100 ? 0.08 : 0.18;
        kdvTutari = kdvOran * tutar;
        kdvliTutar = tutar + kdvTutari;

        System.out.println("KDV'siz tutar :" + tutar);
        System.out.println("KDV oranı :" + kdvOran);
        System.out.println("KDV tutarı :" + kdvTutari);
        System.out.println("KDV'li tutar :" + kdvliTutar);


        }
    }
