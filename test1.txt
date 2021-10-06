package exe;

import java.util.Scanner;

public class test1 {
  public static void main(String[] args) {
    Scanner input = new Scanner(System.in);

    String data = "123456";

    System.out.println("请输入123456中第一个字符");
    String a = "" + input.nextInt();
    int aIndex = data.indexOf(a);
    System.out.println(aIndex);

    System.out.println("请输入123456中第二个字符");
    String b = "" + input.nextInt();
    int bIndex = data.indexOf(b);
    System.out.println(bIndex);

    String c = data.substring(aIndex+1,bIndex);
    //substring [   )
    System.out.println(c);}

}
