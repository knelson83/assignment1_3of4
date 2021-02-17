# assignment1_3of4
public class array{
    
    public static void main(String[] args){
        
        int[] array1 = {45,21,22,31,44,65,12,56,78,19,100};
        int count = 0;
        for (int index = 0; index < array1.length; index++){
            if(array1[index] % 2 != 0){
                count = count +1;
            }
        }
        
        System.out.println("Numbers remaning in the array: " + count);
            
        } 
