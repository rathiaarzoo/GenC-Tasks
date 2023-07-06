// a simple program to demonstrate the use of stream in java
import java.util.*;
import java.util.stream.*;
 
class Task {
    public static void main(String args[])
    {
        // create a list of integers
        List<Integer> number = Arrays.asList(3, 9, 11, 5);
 
        // demonstration of map method
        List<Integer> square
                  = number.stream()
                    .map(i -> i * i)
                    .collect(Collectors.toList());
 
        // create a list of String
        List<String> names = Arrays.asList(
            "Reflection", "Collection", "Stream");
 
        // demonstration of filter method
        List<String> result
            = names.stream()
                .filter(s -> s.startsWith("S"))
                .collect(Collectors.toList());
       
        System.out.println(result);
 
        // demonstration of sorted method
        List<String> show
                  = names.stream()
                   .sorted()
                   .collect(Collectors.toList());
       
        System.out.println(show);
 
        // create a list of integers
        List<Integer> numbers
            = Arrays.asList(3, 9, 11, 5, 2);
 
        // collect method returns a set
        Set<Integer> squareSet
                = numbers.stream()
                  .map(i -> i * i)
                .collect(Collectors.toSet());
       
        System.out.println(squareSet);
 
        // demonstration of forEach method
        number.stream()
            .map(i -> i * i)
            .forEach(y -> System.out.println(y));
 
        // demonstration of reduce method
        int even
                  = number.stream()
                  .filter(i -> i % 2 == 0)
                  .reduce(0, (ans, x) -> ans + x);
 
        System.out.println(even);
    }
}
