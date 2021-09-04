# WeVeLearned



package printf;

import java.util.Scanner;

public class printf {
	public static void main(String[] args) {

		
	// printf : 출력 형식 잡을 때 사용
		
		int a = 1;
		double b = 1.23456;
		String c = "abc";
	
// %d : 정수형 변수 값 들어올 자리 - %03d : 3자리 수로 출력 ex ) 001
// %f : 실수형 변수 값 들어올 자리 - %.2f : 소수점 2자리로 출력 ex) 1.23
// %s : String 변수 값 들어올 자리
		
		System.out.printf("%03d\n", a);
		System.out.printf("%.1f\n", b);
		System.out.printf("%s\n", c);
		
		// a는 ㅇ이고 b는 ㅇ고 c는 ㅇ다.
		System.out.println("a는 " + a + "이고 b는" + b + "이고, c는 " + c + "이다");
		
		//a는 2자리수로, b는 소수점 이하 1자리 
		System.out.printf("a는 %02d이고 b는 %.1f이고 c는 %s이다\n", a,b,c);
		
		// 결과출력하기 & 탭키, 줄바꿈
		// 탭 : \t
		// 줄 바꾸기 : \n
		
		// Carriage return (커서를 맨 앞으로) : \r\n
		
	//Test
		
		// 키보드 입력받을 준비
		Scanner keyboard = new Scanner(System.in);
		// 이름, 나이, 키, 체중 입력받기
		
		
		// 결과출력		printf
		// 이름 : ㅇㅇ
		// 나이 : ㅇㅇ
		// 키	: ㅇㅇ (소수점 1자리)
		// 체중 : ㅇㅇ
		
		// 조건.
		// 신장과 체중은 소수점 이하 몇자리를 입력하든,
		// 신장은 소수점 1자리, 체중은 소수점 2자리로
		/*
		System.out.printf("이름\t: ");
        String name = keyboard.next();	 
        System.out.printf("나이\t: ");
        int age = keyboard.nextInt();	
        System.out.printf("키\t: ");
        double height = keyboard.nextDouble();	
        System.out.printf("체중\t: ");
        double weight = keyboard.nextDouble();	
		
        System.out.printf("이름\t: %s\n", name);
        System.out.printf("나이\t: %d\n", age);
        System.out.printf("키\t: %.1f\n", height);
        System.out.printf("체중\t: %.2f\n", weight);
        
        System.out.println("-----------------------");
        */
        //출력 결과
		/*
		 *  003)-------------
		 *  model : i6
		 *  Cost  : 1200$
		 *  Weight : 120.5g
		 * 
		 *  Designed By "Apple"
		 * 
		 * 
		 * 
		 */
		
		// 제품번호는 그냥 int num = 3; 넣어서 시작
        
        // 입력받는 내용 (모델, 가격, 무게, 회사)
		int num = 3;
        
		System.out.printf("model\t:");
		String modelName = keyboard.next();
		System.out.printf("cost\t:");
		int price = keyboard.nextInt();
		System.out.printf("weight\t:");
		double weight = keyboard.nextDouble();
		System.out.printf("maker\t:");
		String maker = keyboard.next();
        
		
		System.out.printf("%03d)------------------\n", num);
		System.out.printf("model\t: %s\n", modelName);
        System.out.printf("cost\t: %d$\n", price);
        System.out.printf("weight\t: %.1fg\n\n", weight);
        System.out.printf("Designed by \"%s\" ", maker);
        // 문자열 큰따옴표 출력 , 자바 인용부호 출력
        
    /*    //int num = 3;
    	
    	// 입력 받을거 쭉 입력받기
    	System.out.println("모델명 : ");
    	String model = k.next();
    	System.out.println("가격 : ");
    	int price = k.nextInt();
    	System.out.println("무게 : ");
    	double weight2 = k.nextDouble();
    	System.out.println("회사 : ");
    	String comp = k.next();
    	
    	// 결과 출력
    	System.out.printf("%03d)---------\n", num);
    	System.out.printf("Model	: %s\n", model);
    	System.out.printf("Price	: %d$\n", price);
    	System.out.printf("Weight	: %.1fg\n", weight2);
    	System.out.printf("Designed By \"%s\"\n", comp);

		*/
        
        
        
        
        
        
	}

}


































