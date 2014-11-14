TugasProcedurMenghitungLuas
===========================

package id.blits.Tugas;


public class NewMainMenu {

 
    public static void main(String[] args) {
        // TODO code application logic here
        PersegiPanjang perpanj =  new  PersegiPanjang();
        perpanj.nama="hitung Persegi Panjang";
        perpanj.Panjang=20;
        perpanj.Lebar=12;
        
        perpanj.tampilPersegiPanjang();
        
        Segitiga Sgt = new Segitiga();
        Sgt.nama="hitung Luas Segi Tiga";
        Sgt.Alas=25;
        Sgt.Tinggi=30;
        
        Sgt.tampilSegiTiga();
        
        Lingkaran widia = new  Lingkaran();
        widia.nama="hitung Luas Lingkaran";
        widia.Jari2=20;
        
        widia.tampilLingkaran();

        

        
    }
    
}
