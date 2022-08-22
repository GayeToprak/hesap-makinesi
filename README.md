# hesap-makinesi
import java.util.Scanner;

public class hesap makinesi {
    public static void main(String[] args) {

        int n1, n2, select;

        Scanner inp = new Scanner(System.in);
        System.out.print("ilk sayıyı giriniz:");
        n1 = inp.nextInt();
        System.out.print("ikinci sayıyı giriniz:");
        n2 = inp.nextInt();


        System.out.println("1-toplama\n 2-çıkarma\n 3-çarpma\n 4-bölme");
        System.out.print("seçiminiz:");
        select = inp.nextInt();

        switch (select) {
            case 1:
                System.out.println("toplam:" + (n1 + n2));
                break;
            case 2:
                System.out.println("toplam:" + (n1 - n2));
                break;
            case 3:
                System.out.println("toplam:" + (n1 * n2));
                break;
            case 4:
                if (n2 != 0) {
                    System.out.println(n1 / n2);
                } else {
                    System.out.println("o bölünmez");
                }
                break;
                default:


                System.out.println("yanlış seçim yaptınız");
                }


        }



    }
