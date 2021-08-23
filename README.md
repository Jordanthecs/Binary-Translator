package binary;
import java.util.Scanner;

public class binary {
	
	public static void main(String []args) {
		Scanner sentence = new Scanner(System.in);
		
		String sen = " ";
		System.out.println("Enter a phrase: ");
		sen = sentence.nextLine();
		
		
		for ( int i = 0; i < sen.length() ; i++) {
		
		if(sen.charAt(i) == 'a') {
			System.out.print("01100001");
		}else if(sen.charAt(i) == 'b') {
				System.out.print("01100010");
			}else if(sen.charAt(i) == 'c') {
				System.out.print("01100011");
			}else if(sen.charAt(i) == 'd') {
				System.out.print("01100100");
			}else if(sen.charAt(i) == 'e') {
				System.out.print("01100101");
			}else if(sen.charAt(i) == 'f') {
				System.out.print("01100110");
			}else if(sen.charAt(i) == 'g') {
				System.out.print("01100111");
			}else if(sen.charAt(i) == 'h') {
				System.out.print("01101000");
			}else if(sen.charAt(i) == 'i') {
				System.out.print("011001001");
			}else if(sen.charAt(i) == 'j') {
				System.out.print("01101010");
			}else if(sen.charAt(i) == 'k') {
				System.out.print("01101011");
			}else if(sen.charAt(i) == 'l') {
				System.out.print("01101100");
			}else if(sen.charAt(i) == 'm') {
				System.out.print("01101101");
			}else if(sen.charAt(i) == 'n') {
				System.out.print("01101110");
			}else if(sen.charAt(i) == 'o') {
				System.out.print("01101111");
			}else if(sen.charAt(i) == 'p') {
				System.out.print("01110000");
			}else if(sen.charAt(i) == 'q') {
				System.out.print("01110001");
			}else if(sen.charAt(i) == 'r') {
				System.out.print("01110010");
			}else if(sen.charAt(i) == 's') {
				System.out.print("01110011");
			}else if(sen.charAt(i) == 't') {
				System.out.print("01110100");
			}else if(sen.charAt(i) == 'u') {
				System.out.print("01110101");
			}else if(sen.charAt(i) == 'v') {
				System.out.print("01110110");
			}else if(sen.charAt(i) == 'w') {
				System.out.print("01110111");
			}else if(sen.charAt(i) == 'x') {
				System.out.print("01111000");
			}else if(sen.charAt(i) == 'y') {
				System.out.print("01111001");
			}else if(sen.charAt(i) == 'z') {
				System.out.print("01111010");
			}else if(sen.charAt(i) == ' ') {
				System.out.print("00100000");
			}
				}
			}
		}
		
