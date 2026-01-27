# DisplayPattern
###code:
~~~
class DisplayPattern {
    public static void main(String[] args) {

        System.out.println("    J     A     V     V    A");
        System.out.println("    J    A A     V   V    A A");
        System.out.println("J   J   AAAAA     V V    AAAAA");
        System.out.println(" J J   A     A     V    A     A");

    }
}
~~~
# CommandLine
### code:
~~~
import java.text.DecimalFormat;

class CommandLine {
    public static void main(String[] args) {

            double width = Double.parseDouble(args[0]);
            double height = Double.parseDouble(args[1]);
            double area = width * height;
            
            DecimalFormat df = new DecimalFormat("0.000");
	
            System.out.println("Area: " + df.format(area));

    }
}
~~~

# RectangleJava
### copde:
~~~
import java.text.DecimalFormat;

class Rectangle {
    public static void main(String[] args) {

        double width = 4.5;
        double height = 7.9;
        double area = width * height;
        double perimeter = 2 * (width + height);

	DecimalFormat df = new DecimalFormat("0.000");

        System.out.println("Area: " + df.format(area));
        System.out.println("Perimeter: " + df.format(perimeter));

    }
}
~~~
