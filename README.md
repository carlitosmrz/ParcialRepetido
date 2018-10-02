# ParcialRepetido
parcial1
#include <stdio.h>
int main(){
	
	
	int fil, col, i, j;
	
	printf("ingrese el numero de filas que desea");
	scanf("%d", &fil);
	printf("ingrese el numero de columnas que desea");
	scanf("%d", &col);
	
	int matriz1[fil][col];
	int matriz2[fil][col];
	
	
	for(i=0; i<fil; i++){
		
		for(j=0; j<col; j++){
			
			printf("Ingrese valor de la matriz 1:");
			scanf("%d", &matriz1[i][j]);
		}
	}
	for(i=0; i<fil; i++){
		
		for(j=0; j<col; j++){
			
			printf("Ingrese valor de la matriz 2:");
			scanf("%d", &matriz2[i][j]);
		}
	}
	
	for(int a=0; a<fil; a++){
		for(int b=0; b<fil; b++){
			
			if(matriz1[a][b]>matriz1[a][b+1]){
				int x;
				x=matriz1[a][b];
				matriz1[a][b]=matriz1[a][b+1];
				matriz1[a][b+1]=x;
			}
		}
	}
	
				
				
			
			
			
			
	
	
	
	
	
			
			
			
			
	

}
	






