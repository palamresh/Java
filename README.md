# Java

1.Solid Rectange



// Solid Rectangle

class A{
    public static void main (String[] args) {
        int x,y;
        x = 4;
        y =5;
        for(int i = 1;i<=x;i++){
            for(int j = 1 ;j<=y;j++)
            {
            System.out.print("*");
            }
            System.out.println();
        }
    }
    
}

Output:
*****
*****
*****
*****


** Process exited - Return Code: 0 **

2.Hollow Rectangle



// Solid Rectangle

class A{
    public static void main (String[] args) {
        int x,y;
        x = 4;
        y =5;
        for(int i = 1;i<=x;i++){
            for(int j = 1 ;j<=y;j++)
            {
              if(i==1||j==1||i==x||j==y){
                  System.out.print("*");
              }else{
                  System.out.print(" ");
              }
            
            
            }
            System.out.println();
        }
    }
    
}

Output :

*****
*   *
*   *
*****


** Process exited - Return Code: 0 **

3.Half Pyramid

class A{
    public static void main (String[] args) {
        int x,y;
        x = 4;
       
        for(int i = 1;i<=x;i++){
            for(int j = 1 ;j<=i;j++){
           
            System.out.print("*");
            
            }
            System.out.println();
        }
    }
    
}

Output :

*
**
***
****


** Process exited - Return Code: 0 **
