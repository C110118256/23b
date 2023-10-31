```java
class CTriangle extends CShape{
  private double area = 0;
  public String color = null;

  public CTriangle(double a, double b, double c){
    area = 0.5 * a * b;
  }

  public void Show(){
    System.out.print("color is " + color + " area is " + area);
  }

  public static void main(String[] arg){
    CTriangle ctr = new CTriangle(3d,4d,5d);
    ctr.color = "紅色";
    ctr.Show();
  }
}
```
