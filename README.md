# matrix-addition
package com.payil.poly;

public class Matrix {

	public static void main(String[] args) {
		int a[][]={{2,3,4},{2,2,2}};
		int b[][]={{1,2,3},{2,4,6}};
		int c[][]={{0,0,0},{0,0,0}};
		for(int i=0;i<2;i++){
			for(int j=0;j<3;j++){
				c[i][j]=a[i][j]+b[i][j];
				System.out.print(c[i][j]);
				
			}
			System.out.println(" ");
		}
		
	

	}

}
