# Kutle-indeksi-hesaplama
Kendimi geliştirmek için denemeler.

#include<stdio.h>
#include<conio.h>

int main () {
	
	while(1) {
	
	
	double K,B;
	double Kutle;
	
	
	printf("Kilonuzu girin: ");
	scanf("%lf",&K);
	
	printf("Boyunuzu girin (Örn:1.80): ");
	scanf("%lf",&B);
	
	Kutle=K/(B*B);
	
	printf("Sonuc=%.1lf\n",Kutle);
	
	if(Kutle>=44.9)
	{
		printf("Sonuc= Asiri sisman(Asiri Obez)III.sinif\n");
	}
	
	if(Kutle<44.9 && Kutle>=35.0)
	{
		printf("Sonuc= Sisman(OBEZ)II.sinif");
	}
	
	if(Kutle<35.0 && Kutle>=30.0)
	{
		printf("Sonuc= Sisman(OBEZ)I.sinif\n");
	}
	
	if(Kutle<30.0 && Kutle>=25.0)
	{
		printf("Sonuc= fazla kilolu\n");
	}
	
	if(Kutle<25.0 && Kutle>=18.5)
	{
		printf("Sonuc= normal\n");
	}
	
	if(Kutle<18.5)
	{
		printf("Sonuc= zayıf\n");
	}
	

	
}
	
	
	
	
	
	getch ();
	
	return 0;
}
