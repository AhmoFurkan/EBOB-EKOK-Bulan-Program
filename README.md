# EBOB-EKOK-Bulan-Program
Java ile iki sayının EBOB ve EKOK değerlerini "While Döngüsü" kullanarak yazınız.

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("n1 sayısını giriniz :");
        int n1 = inp.nextInt();

        System.out.print("n2 sayısını giriniz :");
        int n2 = inp.nextInt();
        int ebob=0;

        int i=1;
        while (i<=(n1*n2)) {

            if (i % n1 == 0 && i % n2 == 0) {
                System.out.println("Ekok :" + i);
                break;
            }
            i++;
        }

        int y=1;
       while (y<=n1){
            if (n1 % y == 0 && n2 % y == 0) {
                ebob = y;
            }
            y++;
        } System.out.println("Ebob :" + ebob);
        
        }
     }

  ![image](https://user-images.githubusercontent.com/107626332/181907840-05375426-8b83-409a-b858-39f524487ead.png)
https://app.patika.dev/ahmetfurkan



