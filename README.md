# Zadacha-2-
package ja;   public class JA {           public static void main(String[] args) {       int n,k,m=0,r=0;       n = 58798;       while (n > 0){           k = n%10;           r = k%2;           if (r == 0){           m += k;}                  n = n/10;}                    System.out.print(m);                       }      }
