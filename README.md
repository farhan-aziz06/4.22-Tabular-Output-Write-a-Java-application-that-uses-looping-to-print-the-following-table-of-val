# 4.22-Tabular-Output-Write-a-Java-application-that-uses-looping-to-print-the-following-table-of-val
4.22 (Tabular Output) Write a Java application that uses looping to print the following table of values:


  (Tabular Output) Write a Java application that uses looping to print the following table of
        values:     N   10*N    100*N   1000*N
                    1   10      100     1000
                    2   20      200     2000
                    3   30      300     3000
                    4   40      400     4000
                    5   50      500     5000
                    
                    
                    
                    
                    
                    
import java.util.Scanner;

public class Main {
    public static void main(String[] args){
     

        int N=1;
        System.out.println("N   10*N    100*N   1000*N");
        while (N<=5){

            System.out.println(N+"   "+N*10+"     "+N*100+"     "+N*1000);
            N++;
        }
    }
}
