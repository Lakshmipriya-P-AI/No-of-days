# No-of-days
## Experiment 3: Number of Days
### AIM:
To Write a Java program to find the number of days in a month.

### ALGORITHM:
Step 1:
Take input from the user for the month and store it in a variable

Step 2:
Create a switch statement based on the month variable.

Step 3:
For each case, print the corresponding number of days and break out of the switch statement.

Step 4:
Handle the special case of February separately, considering leap years. If the month is February, check if it's a leap year. If it is, print 29 days otherwise, print 28 days.

Step 5:
If the input month does not match any of the cases, display an error message indicating an invalid month.

### PROGRAM:
```
import java.util.Scanner;
public class days
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter month no. : ");
        int month = sc.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.print("Enter the year: ");
                int year = sc.nextInt();
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                    System.out.println("29 days");
                } 
                else{
                    System.out.println("28 days");
                }
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Invalid Month");
        }
    }
}
```
### OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/No-of-days/assets/93427923/69de8160-c77a-4aa9-ab43-d9d0653c990d)


### RESULT:
Thus, a java program is written to find the number of days in a month.
