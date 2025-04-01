자바설치 개발자환경설치 // amazon-corretto-21.0.3.9.1-windows-x64-jdk\jdk21.0.3_9
환경 변수 설정 (JAVA_HOME) 시작-> 제어판 -> 시스템 -> 환경변수
JAVA_HOME 변수값(자바 설치 경로) 확인 // 시스템 변수 설정
환경 변수 path 파일 설정 
[환경 변수] 대화상자
– [시스템 변수]에서 Path 환경변수 선택 후 [편집]
• [환경 변수 편집] 대화상자
– [새로 만들기] - %JAVA_HOME%\bin 입력
환경 변수 설정 cmd(명령 프롬프트)
-java -version 
헬로우 자바 출력문 
class HelloJava {
	public static void main(String[] args) {
		System.out.println("Hello, JAVA!");
	}
}
class 전환 cmd 이후
javac.exe HelloJava.java 엔터
java.exe HelloJava 으로 확인
이클립스 다운 2024_09 버전 다운로드
println 출력
package kr.or.ddit.basic;

/**
 * 도큐멘트 주석.
 */
public class HelloJava {
	/**
	 * 
	 * @param args
	 */
		public static void main(String[] args) {
			
			// 이것은 라인 주석입니다.
			// 이것은 두번째 라인 주석입니다.
			/*
			  이곳은
			  범위주석입니다.
			  1
			  2
			  3
			  4
			  5
			 */
			System.out.println("Hello, JAVA!");
			
			int x;
			x = 1;
			int y = 2;
			int result = x + y;
			System.out.println(result);

		}
}
