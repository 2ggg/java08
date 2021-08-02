package test;

import java.util.Scanner;

public class Test1 {
	
	public static void main(String[] args) {
		/*박승재 문제
		성적이 100이하 80이상이면 A
		80미만 60이상이면 B
		60미만 40이상이면 C
		40미만 20이상이면 D
		20미만이면 F
		 */
		
		Scanner scanner = new Scanner(System.in);
		System.out.print("점수를 입력하시오>>");
		int numA = scanner.nextInt();
		char resultA ='0';
		if (80<=numA&&numA<=100) {
			resultA = 'A';
		}else if(60<=numA&&numA<80) {
			resultA = 'B';
		}else if(40<=numA&&numA<60) {
			resultA = 'C';
		}else if(20<=numA&&numA<40) {
			resultA = 'D';
		}else {
			resultA ='F';
		}
		System.out.println("성적: "+numA+"점\n"+resultA);
		
		/////전우진 문제
		/*
		연도(year)를 입력했을 때,
		윤년이면 1, 아니면 0을 출력
		윤년은 연도(year)가 4의 배수이면서, 100의 배수가 아닐 때 또는 400의 배수일 때이다.
		 */
		System.out.print("연도 입력>>");
		int year = scanner.nextInt();
		String resultYun = "";
		int a=0;
		if(year%4==0) {
			if(year%100!=0) {
				resultYun = "윤년이다.";
				a=1;
			}else if((year%100==0)&&(year%400!=0)) {
				resultYun = "윤년이 아니다.";
				a=0;
			}
			System.out.println(a+"\n"+year+"년은 "+resultYun);
		}
		
		
	}
}
