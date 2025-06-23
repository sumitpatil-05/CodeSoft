import java.util.*;

class Grade {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Enter the number of subjects:");
        int sub = sc.nextInt();
        
        int[] marks = new int[sub];
        int total = 0;
        int totalmax = (sub*100);
        
        System.out.println("Enter the marks in " +sub+ " subjects out of 100:");
        for(int i=0; i<sub; i++)
        {
           System.out.println("Enter marks in subject " +(i+1)+" out of 100:");
           marks[i] = sc.nextInt();
           total = total + marks[i];
        }
        
        int avg = total/sub;
        float per = ((float)total/totalmax)*100;
        System.out.println("Total marks obtained by student: "+total);
        System.out.println("Average marks: "+avg);
        System.out.println("Percentage: "+per+"%");
       //Calculating the grade
       if(100<=per || per>35)
       {
           System.out.println("Result: PASS");
           
           if(100<=per && per>95)
           {
               System.out.println("Grade: EX");
           }
           
           else if(95<=per && per>90)
           {
                System.out.println("Grade: AA");
           }
           
           else if(90<=per && per>85)
           {
               System.out.println("Grade: AB");
           }
           
           else if(85<=per && per>80)
           {
               System.out.println("Grade: BB");
           }

           else if(80<=per && per>75)
           {
               System.out.println("Grade: BC");
           }
           
           else if(75<=per && per>70)
           {
               System.out.println("Grade: CC");
           }
           
           else if(70<=per && per>65)
           {
               System.out.println("Grade:CD");
           }
           
           else if(65<=per && per>55)
           {
               System.out.println("Grade: DD");
           }
           
           else if(55<=per && per>45)
           {
               System.out.println("Grade: DE");
           }
           
           else if(45<=per && per>35)
           {
               System.out.println("Grade: EE");
           }
       }
       
       else
       {
           System.out.println("Result: FAIL");
       }
    }
}