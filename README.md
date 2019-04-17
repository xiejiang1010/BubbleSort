# BubbleSort
//冒泡排序
public class BubbleSort{
  public static void main(String[] args){
     
    //print 10 random numbers
    int str[] = new int[10];
    Sytstem.out.println("排序前:");
    for(int i = 0; i <= str.length;i++){
      str[i] = (int)(Math.random()*100);
      System.out.print(str[i]+" ");
    }
    System.out.println(" ");
    
    //sort
    for(int x = 0;x < str.length-1;x++){
      for(int y = 0;y< str.length-x-1;y++){
        int temp;
        if(str[y]>=str[y+1]){
          temp = str[y+1];
          str[y+1] = str[y];
          str[y] = temp;
        }
      }
    }
    
    //print sort number
    System.out.println("排序后:");
    for(int j = 0;j< str.length-1;j++){
      System.out.print(str[j]+" ");
    }
  }
}
