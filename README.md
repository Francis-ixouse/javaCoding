public class fizzbuzz {
    public static void main(String args[]) {
    printResult(100);
        
    }
    public static void printResult(int h){
        for (int i=1; i<=h; i++)
        if((i % 3 ==0 )&& (i % 5 == 0)){
            System.out.println("FizzBuzz");
        }
       else if (i % 3 == 0){
            System.out.println("Fizz");
        }
        else if (i % 5 == 0){
            System.out.println("Buzz");
        }
        else {
            System.out.println(i);
    }
}
}  
