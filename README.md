# BubbleSort
//冒泡排序
public class BubbleSort{
  public static void main(String[] args){
    //print 10 random numbers
    int str[] = new int[10];
    Sytstem.out.println("排序前：");
    for(int i = 0; i <= str.length;i++){
      str[i] = (int)(Math.random()*100);
      System.out.println(str[i]+" ");
    }
    
  }
}
