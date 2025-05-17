
# *** LOOPS! ***
###### Control Structure to execute code for multiple instances within a range, until a condition is met


### for loops
##### used for arrays where the final number is usually known
```
public class ForLoopExample {

  public static void main(String[] args){

    for (int i = 1; i <= 5; i++){

      System.out.println("Counter = " + i);

      }
   }
}
```

### while loops
##### repeat as long as condition is true
```
public class WhileLoopExample {

  public static void main(Sting[] args){

    int counter = 1;

    while (counter <= 5){

      System.out.println("Counter = " + counter);

      counter++;
      }
    }
  }
```

### do-while loops - ensures the code runs at least once and then checks condition after each iteration
##### repeat as long as condition is true
```
public class DoWhileLoopExample {

  import java.util.Scanner;

  public static void main(String[] args){

    Scanner scanner = new Scanner(System.in);
    int number;

    do {

      System.out.println("Enter a number greater than 10 or I will keep repeating myself: ");

      number = scanner.nextInt();

    }while (number <=10);

  System.out.println("Thanky you, you entered: " + number);

  scanner.close();

      }
   }
}
```




# *** ARRAYS! ***
##

### When using Arrays, import them:
```
import java.util.Arrays;
```


### Basic Array example to hold 5 elements
```
public static void main(String[] args){

int[] grades = new int[5];

grades[0] = 88;
grades[1] = 80;
grades[2] = 90;
grades[3] = 80;
grades[4] = 100;

System.out.println("Student Grades: " + Arrays.toString(grades));

}

```


### Array example with for loop
```
public static void main(String[] args){

int[] grades = new int[5];

grades[0] = 88;
grades[1] = 80;
grades[2] = 90;
grades[3] = 80;
grades[4] = 100;

for(i = 0 ; i < grades.length; i++){

  System.out.println("Grade at element " + i + ": " + grades[i]);

  }
}

```
