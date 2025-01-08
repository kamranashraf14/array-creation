# array-creation
create an array with different proccess 

1st process:
import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
    
    // dataType [] name = new dataType[4]
    
      int[] numberArray = new int[4];
     
      numberArray[0] = 99; 
      numberArray[1] = 88;
      numberArray[2] = 77;
      numberArray[3] = 66;
     
      System.out.println(Arrays.toString(numberArray));
      
  }
}

2nd process:
import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
          
    int numberArray[] = {99,88,77,66};
     
      System.out.println(Arrays.toString(numberArray));
      
  }
}

3rd process:

import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
      
    int numberArray[] = {99,88,77,66}; 
      
      for (int i=0; i<4; i++){
     
      System.out.println(numberArray[i]);
        
      }
      
  }
}
