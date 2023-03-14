# 13-03-23-pattern

## 1.Create programme for the given pattern:
```
*****
*****
*****
*****
*****
```

## Program:
```
public class pattern1
{
    public static void main(String[] args)
    {
        int row=5;
        for(int i=0;i<row;i++)
        {
            for(int j=0;j<row;j++)
            {
                System.out.print('*');
            }
            System.out.println();
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224885791-04a3857c-6e1a-4cd7-a00c-92a87b58f97b.png)

## 2.Create programme for the given pattern:
```
*********
 *******
  *****
   ***
    *
```

## Program:
```
{
    public static void main(String[] args) {
        int rows = 5;
        int spaces = 0;
        for (int i = rows; i >= 1; i--) {
            for (int j = 1; j <= spaces; j++) {
                System.out.print(" ");
            }
            for (int j = 1; j <= i * 2 - 1; j++) {
                System.out.print("*");
            }
            System.out.println();
            spaces++;
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224886093-62713af6-b6ec-4050-a175-188b04d10113.png)

## 3.Create programme for the given pattern:
```
*
**
***
****
*****
****
***
**
*
```

## Program:
```
public class pattern3
{
    public static void main(String[] args) {
        int rows = 5;
        for (int i = 1; i <= rows; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
        for (int i = rows - 1; i >= 1; i--) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## Output:
![image](https://user-images.githubusercontent.com/93992063/224886451-07f1247d-e7a0-4abd-a8cf-f122c286eda8.png)







