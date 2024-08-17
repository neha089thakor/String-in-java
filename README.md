# String-in-
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
    int a=78;
    float b=8.999f;
    System.out.printf("The number of a value is %d and number of b value is %f",a,b);
    //>>string input by user....first add a Scanner  library
        Scanner sc= new Scanner(System.in);
     String st=sc.nextLine();//>>only next leva thi only first latter j print thase
     System.out .println(st);
        //>>for find to string length
        String sr="Neha";
        int value= sr.length();
        System.out.println(value);
        //>>For lower case:return a new string which has all the uppercase character from the string name
        String in="Neha";
        String lstring= in.toLowerCase();
        System.out.println(lstring);
       //>> same as for upper cash
        String on="Neha";
        String ustring= on.toUpperCase();
        System.out.println(ustring);
 //>> using trim for leading and trading spaces remove
        String nonTrimmedString="    NEHA   ";//space rakhva
        System.out.println(nonTrimmedString);
        String trimmedString=nonTrimmedString.trim();//space remove krva
        System.out.println(trimmedString);
        //>>name.substring for return start to the end substring"ry".//int start//last valu return thase
        System.out.println(sr.substring(2));
        //>>2nd name.substring aama end ma hse aae nai aave pphela nu avse//int start ,int end
        System.out.println(sr.substring(0,4));
        //>>replace string replace and old string in new string....

        System.out.println(sr.replace('e','y'));
        //>>one word thi vadhare replace krva.......
        System.out.println(sr.replace("eh","iy"));
        System.out.println(sr.replace("e","aa"));
        //>>>>>>name.startsWith string return a true or false string.....
        System.out.println(sr.startsWith("Neh"));
      System.out.println(sr.endsWith("ha"));
        //>>>>name.charAt.....
        System.out.println(sr.charAt(1));
        //>>name.indexOf(s)....index returns substring....
       String modifiedName= "nehyxtaaaa";
        System.out.println(modifiedName.indexOf("a",4));
        //>>>name.equal for check name is equal or not(>>>valur match or not<<<)......
        System.out.println(sr.equals("Neha"));
       //  >>>>for ignore cash lower or upper cash>>>>>name.equals ignore cash<<<<<<<<<<<<<....
        System.out.println(sr.equalsIgnoreCase("neHA"));
    }
}
