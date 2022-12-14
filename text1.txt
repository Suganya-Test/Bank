package com.java;

public class AverageArray {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a[]= {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
int sum=0;
double average=0;
for (int i = 0; i < a.length; i++) {
	sum=sum+a[i];
	
}
average=sum/a.length;
System.out.println("Average of array element is :"+average);
	}

}
