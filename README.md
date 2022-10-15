import java.util.Scanner;
public static void main(String[] args) {
        
         Scanner input = new Scanner(System.in);
         int bil1, bil2, bilH ,pil, K1, RA,K2, RB,K3, RC,luas,hasil = 0;

            
         System.out.println("KALKULATOR KURANG SEDERHANA");
         System.out.println("1. kardus A seharga: 25000 ");
         RA = 25000;
         System.out.println("2. kardus b seharga: 20000 ");
         RB = 20000;
         System.out.println("3. kardus C seharga: 35000 ");
         RC = 35000;
         System.out.println("luas tanah 100m2");
         System.out.print("masukan berapa kardus A    : ");
         K1=input.nextInt();         
         System.out.print("masukan berapa kardus B    : ");
         K2=input.nextInt();         
         System.out.print("masukan berapa kardus C    : ");
         K3=input.nextInt();
         System.out.print("panjang keramik  : ");
         bil1=input.nextInt();
         System.out.print("lebar keramik    : ");
         bil2=input.nextInt();                 
         System.out.print("pilih kardus yang mana     : ");
         pil=input.nextInt();
                     
         switch (pil){
             case 1 : K1=K1*RA;
             case 2 : K2=K2*RB;
             case 3 : K3=K3*RC;
            
         }
        
         System.out.println("semua kardus A "+K1);
         System.out.println("semua kardus B "+K2);
         System.out.println("semua kardus C "+K3);
         luas = bil1*bil2/100;
         System.out.print("keramik per buah     : "+luas+" m "); 
        }
    }



