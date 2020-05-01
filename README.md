    #include <stdio.h>
    #include <stdlib.h>
		
    int main() {

    int yukseklik;
    int cap;
    float A;
    float hacim;
    float pi= 3.1419;

    printf("Yuksekligi giriniz (cm): ");
    scanf("%d", &yukseklik);

    printf("Capi giriniz (cm): ");
    scanf("%d", &cap);

    printf("Girdi degerleri yukseklik %d ve cap %d \n", yukseklik, cap);

    A= pi*(cap*cap);
    hacim= (A*yukseklik)/3;

    printf("Dairesel kurenin hacmi: %f cm kuptur.", hacim);

    return 0; }
