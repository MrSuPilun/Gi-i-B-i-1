#include <stdio.h>

int main()
{
	float Diemt, Diemkt, DTB;
	do {
		printf ("\n Nhap Vao Diem Thi THCS : ");
		scanf ("%f", &Diemt);
	} while (!(0 <= Diemt && Diemt <= 10));
	do {
		printf ("\n Nhap Vao Diem Kiem Tra THCS : ");
		scanf ("%f", &Diemkt);
	} while (!(0 <= Diemkt && Diemkt <= 10));
	
	DTB = Diemt*0.7 + Diemkt*0.3;
	
	printf ("\n Diem Cua Ban La : %.2f", DTB);
	printf ("\n Xet Hoc Luc : ");
	if (DTB >= 7)
		printf (" Kha Gioi.");
	else
		if (DTB > 4)
			printf (" Trung Binh.");
		else 
			printf (" Yeu Kem.");
	return 0;
}
