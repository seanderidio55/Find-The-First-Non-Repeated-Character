# Find-The-First-Non-Repeated-Character
Activity 1- Test your Java Programming Skills
public class FirstNonRepeatedCharFirst {
    public static void main(String args[]) {
     
        String inputStr ="better";

        for(char i :inputStr.toCharArray()){
        if ( inputStr.indexOf(i) == inputStr.lastIndexOf(i)) {
            System.out.println("First non-repeating character is: "+i);
            break;
        }
        }
    }
}
