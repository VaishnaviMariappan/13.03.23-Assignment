# 13.03.23-Assignment

## 1. Create program for the given pattern.
    ```
    * * * * *
    * * * * *
    * * * * *
    * * * * *
    * * * * *
    ```
```java
public class pattern
{
    public static void main(String[] args) {
        int row = 5, i, j;
        for (i = 1; i <=row; i++) {
            for (j = 1; j <= row; j++)
                System.out.print("* ");
            System.out.print("\n");
        }
    }
}
```
### Output: 

![image](https://user-images.githubusercontent.com/94169913/224884569-ae12235a-d8d3-4f26-958f-0160e3004491.png)

## 2. Create program for the given pattern.
    ```
    * * * * * * * * *
      * * * * * * *
        * * * * *
          * * *  
            * 
    ```
```java
public class pattern2
{
    public static void main(String[] args)
    {
        for(int i=5;i>=0;i--)
        {
            for(int j=0;j<=5-i;j++)
            {
                System.out.print("  ");
            }
            for(int k=1;k<=(2*i-1);k++)
            {
                System.out.print("* ");
            }
            System.out.print("\n");
        }
    }
}
```
### Output:

![image](https://user-images.githubusercontent.com/94169913/224884587-374a5f87-9bc7-45ac-b43d-b3f6e6010151.png)

### 3. Create a program for the given pattern. 

    ```
    *
    * *
    * * *
    * * * * 
    * * * * *
    * * * * 
    * * * 
    * * 
    *
    ```
```java
public class pattern3
{
    public static void main(String[] args)
    {
        for(int i=0;i<5;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
        for(int i=5-1;i>=0;i--)
        {
            for(int j=0;j<=i-1;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```
### Output:

![image](https://user-images.githubusercontent.com/94169913/224884608-ebf17a5d-8b63-4612-9732-db03afe83db8.png)
