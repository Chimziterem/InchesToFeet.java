# InchesToFeet.java

class InchesToFeet {
    public static void main(String[] args) {
int feet, inch;
int inches = 86;
final int onefeet = 12;
//Compute the whole number of feet with integer division
feet = inches/onefeet;
//compute the remaining number of inches
inch = inches%onefeet;
    System.out.println(inches + " inches " + " = " + feet + " feet " + inch + " inches ");
    }    
}
