# Given-Number-Even-
import java.util.Scanner;

public class printingnumber {
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("Enter Starting Number");
		int SN = scanner.nextInt();
		System.out.println("Enter Ending Number");
		int EN = scanner.nextInt();
		int a = SN;
		while(a<=EN) {
			if(a%7==0)
				System.out.println(a);
			a++;

		}scanner.close();
	}
}
