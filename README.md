# newbee_java
note
import java.util.Scanner;


public class main {
	

	public static void main(String[] args) {
		double hight,bmi,kg;
		System.out.println("请输入身高(m)：");
		Scanner s = new Scanner(System.in);
		hight = s.nextDouble(); 
		System.out.println("请输入体重：");
		kg = s.nextDouble(); 
		bmi = kg/(hight*hight);
		System.out.println("身高是(m)："+hight);
		System.out.println("体重是："+kg);
		System.out.println("BMI："+bmi);
		
	}

}
