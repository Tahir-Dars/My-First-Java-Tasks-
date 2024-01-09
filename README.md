# My-Tasks
These are very initial and basic tasks of Java that you need to practice in order in be good at programming .<br> The ideas of theses tasks are taken from YouTube, Google and ChatGPT . 
..Write a Java program to fill in a letter template which looks like below:
letter = " Dear name, Thanks ";
Replace name with a String(Same name)
Ans: 
 import java.util.Scanner;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sck= new Scanner(System.in);
        String letter="Dear Name, Thanks!";
        System.out.println(letter.replace("Name","Tahir"));
    }
}
