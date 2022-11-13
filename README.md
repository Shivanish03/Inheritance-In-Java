# Inheritance-In-Java
class Base{
  int X;
  public int getX() {
      System.out.println("I'm in base and applying inheritance.");
        return X;
    }
    public void setX(int x) {
        X = x;

    }

}
  class Derived extends Base{
   int Y;
   public int getY() {
        return Y;
    }

      public void setY(int y) {
          Y = y;
      }
  }

public class New {
    public static void main(String[] args) {
        System.out.println("Start");
        Base Bose = new Base();
        {
            Bose.setX(96);
        }
        Derived Objct = new Derived();
        {
            Objct.setY(43);
        }
       // System.out.println(Objct.getY());
        System.out.println(Bose.getX());
    }
}
