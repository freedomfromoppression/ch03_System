# ch03_System
package ch03_system;

import java.util.Scanner;

/**
 * Class Name : SystemMain2024. 1. 3. Author : Kimgichan Created Date: 2024. 1.
 * 3. Version : 1.0 Purpose : system class study Descitption : 표준 입출력 공부
 */
public class SystemMain {

	/**
	 * @param args
	 * 
	 */

	public static void main(String[] args) {
		// 한줄 주석
		// javadoc 주석 shirt+Alt=j
		System.out.print("hi"); // 이어서 출력
		System.out.print("hi"); // 이어서 출력
		System.out.println("hi"); // 이어서 출력
		System.out.println("hi"); // 이어서 출력
		System.out.println("오류입니다");
		//자동 정렬 Ctrl+a 전체 선택 -> Ctrl=Shift+f
		
		//이스케이프 문자사용
		// \n줄 개행, \t탭
		System.out.println("즁간에\n넣으면 개행이됨");
		System.out.println("즁간에\t넣으면 텝 효과");
		System.out.println("즁간에 특수문자사용 \"이렇게\" ");
		// printf() 포멧 문자열 형태로 사용
		System.out.printf("원주율은%.2f\n",3.141592);
		//여러개 출력가능("대상문자열",값1 값2,.......)
		System.out.printf("%d 명이 %s 를 듣고 있습니다.", 21, "java수업");
		
		System.out.println("=====표준입력=====");
		Scanner scan = new Scanner(System.in);
		System.out.println("이름을 입력해주세요.");
		System.out.print(">>> ");
		//키보드 입력을 기다림
		String nm=scan.nextLine();
		//입력받은 내용을 출력
		System.out.println(nm=" 님 환영합니다.");
		System.out.println("나이를 입력해주세요");
		System.out.print(">>>");
		int age=Integer.parseInt(scan.nextLine());
		System.out.printf("%s님 나이는 %d 이군요.",nm,age);
		scan.close(); // 스케너 종료
		
