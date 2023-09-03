import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.util.*;
class TestClass {
    public static void main(String args[] ) throws Exception {
        Scanner sc=new Scanner(System.in);
        String S=sc.next();
        String S1="";
        for(int i=0;i<S.length();i++){
            Character c=S.charAt(i);
            if(Character.isLowerCase(c)){
                S1=S1+Character.toUpperCase(c);
            }else{
                S1=S1+Character.toLowerCase(c);
            }
        }
        System.out.print(S1);
    }
}
