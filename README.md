# Venturesity-Need-For-Code-Challenge-Application
Venturesity | Need For Code Challenge Application

import java.util.Scanner;
public class HelloWorld{

     public static void main(String []args){
        Scanner s = new Scanner(System.in);
      System.out.print("Enter first Pair: ");
      String firstPair = s.nextLine();
      System.out.print("Enter first number:"+firstPair);
      System.out.print("Enter second Pair: ");
      String secondPair = s.nextLine();
      System.out.print("Enter third Pair: ");
      String thirdPair = s.nextLine();
      System.out.print("Enter fourth Pair: ");
      String fourthPair = s.nextLine();
      checkValues(firstPair,secondPair,thirdPair,fourthPair);


     }
      checkValues(String firstPair,String secondPair,String thirdPair,String fourthPair)
      {
          String first,second,third,four,five,six,seven,eight;
          ArrayList a = new ArrayList();
          String concat=firstPair+","+secondPair+","+thirdPair+","+fourthPair;
          String[] temp;
          temp = concat.split(,);
          
          first =temp[0];
          second= temp[1];
          third =temp[2];
          fourth =temp[3];
          five=temp[4];
          six=temp[5];
          seven=temp[6]
          eight=temp[7];
          
          if(first<=third && second <=fourth){
              if(first<=five && second<=six){
                  if(first<=seven && second<=eight){
                      a[0]=first;
                      a[1]=second;
                  }
              }
          }else if(third<=five && four<=six){
              else if(third<=seven && four<=eight){
                  a[0]=third;
                  a[1]=four;
              }
          }
          else if(five<=seven && six<=eight){
              a[0]=five;
              a[1]=six;
          }
          else{
              a[0]=seven;
              a[1]=eight;
          }
          if((third==a[0] && four==a[1]+1 ) || (five ==a[0] && six==a[1]+1)  || (seven==a[0]) && eight==a[1]+1) ){
              if((third==a[0]+1 && four==a[1]+1) || (five ==a[0]+1 && six==a[1]+1)  || (seven==a[0])+1 && eight==a[1]+1)){
                  if((third==a[0]+1 && four==a[1]) || (five ==a[0]+1 && six==a[1])  || (seven==a[0])+1 && eight==a[1])){
                  }
                  System.out.println(" Eligible for Parallelogram & positions are : ("+ a[0]+","+a[1]+") ("+a[0]+","+a[0]+1+") ("+a[0]+1+","+a[0]+1+") ("+a[0]+1+","+a[0]);
              }  
          }
          else{
              System.out.println("Not Eligible for Parallelogram");
          }
              
          
          
          
      }
      
      }
}
