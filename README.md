# DizidekiElemanlarinOrtalamasi
import java.sql.SQLOutput;
import java.util.Arrays;
public class Main {
    public static void main(String[] args) {

        int[] list = {1,2,3};
        double average=0.0;
        for(int i=0; i<list.length; i++){
            average =average+ 1./list[i];
        }
        System.out.println(average);
    }
}
