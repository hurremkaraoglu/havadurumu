# havadurumu

package first;

import java.util.Scanner;

public class Etkinlik {
    public static void main(String[] args) {
    Scanner input = new Scanner(System.in);
        System.out.print("Hava sıcaklığını giriniz:");
        int hava = input.nextInt();
        if(hava<5){
            System.out.println("Uludağ'a kayak yapmaya gidebilirsin");
        }
        else if(5<=hava&&hava<15){
            System.out.println("Sıcak Çikolata eşliğinde film seyredebilirsin");
        }
        else if(15<=hava &&hava<25) {
            System.out.println("Lunaparka gidebilirsin");
        }else if(25<=hava){
            System.out.println("Arkadaşlarınla havuza gidebilirsin");
        }
    }
}
