# LatihanUKL-SoalMudahNo2-Faktorial-AzkyaRahma-XRPL2

Program menghitung faktorial bilangan positif yang dimasukkan user menggunakan loop for. Hasil faktorial ditampilkan di layar.



    import java.util.Scanner;
    public class SOAL2_Faktorial {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        System.out.print("Masukkan bilangan bulat =  ");
        int n = sc.nextInt();

        if (n < 0) {
            System.out.println("Bilangan harus > = 0");
            return;
        }

        long hasil = 1;

        for (int i = 1; i <= n; i++) {
            hasil *= i;
        }

        System.out.println(n + "! = " + hasil);
    }
}
