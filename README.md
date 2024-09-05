# DAY-3-Patterns
public class HollowRectangle {
    public static void main(String[] args) {
        for(int i=0; i<5; i++) {
            for(int j=0; j<10; j++) {
                if(i==0 || i==4 || j==0 || j==9) {
                    System.out.print("* ");
                } else {
                    System.out.print("  ");
                }
            }
            System.out.println();
        }
    }
}

