# course.masaischool.com-assignments-10351
Print "Hello World!" in the java console followed by "Hello World! How are you doing!!" in a different line

class first{
  public static void main(String[] args){
    System.out.println("Hello World!");
    System.out.println("Hello World! How are you doing!!");
  }
}



#---------------#----------------$



(JAVA) VARIABLES PRINTING
Define a variable called number  of int dataType
Initialise the number with value 10
Print the value stored in the variable number
Assign the same variable number with 20
Print the value stored in the variable number


class second{
  public static void main(String[] args)
  {
    int number = 10;             {first print 10 then print 20}
    System.out.println(number); 
       int number = 20;
    System.out.println(number); 
    }
}







#---------#----------&



(JAVA) NAME AGE PRINTING
Create a variable name to store your name
Create a variable age to store your age
Print the values stored in the variable on one line followed by the type of the variable in the next line



class third{
  public static void main(String[] args)
  {
    String name = "PRIYANKA";
    int age = 20;
    System.out.println(name + "  " + age);
    System.out.println("name " + "  " + "   age");
  }
}






#-----------------------%%^&*((



(JAVA) REPORT CARD
Store the name as int, school as String, grade as character, section as character, rollNo as int and the marks scored as int by the student in 3 subjects (Maths , Science and English)
Print the report card of the student (You can make it look nice by using some keyboard symbols )
Explore ASCII ART (https://en.wikipedia.org/wiki/ASCII_art) or Text Art (https://fsymbols.com/text-art/) for some inspiration




import java.util.*;
class Student
{
 int rollno,Maths,Science,English;
 String name, school, section;
 public static void main(String...args)
 {
  Student s1=new Student();
  Scanner sc=new Scanner(System.in);
  System.out.print("Roll no. : ");
  s1.rollno=sc.nextInt();
  System.out.print("Name : ");
  s1.name=sc.next();
  System.out.print("School : ");
  s1.school=sc.next();
  System.out.print("Section : ");
  s1.section=sc.next();
  System.out.println("Enter the Marks following...");
  System.out.print("Maths : ");
  s1.Maths=sc.nextInt();
  System.out.print("Science : ");
  s1.Science=sc.nextInt();
  System.out.print("English : ");
  s1.English=sc.nextInt();
  
  int total=s1.Maths+s1.Science+s1.English;
  
  int avg=(total*100)/300;
  
  String grade;
  if(avg<33)
  {
   grade="Fail";
  }
  else if ( avg >=34 && avg <= 44 )
  {
   grade="III";
  }
  else if ( avg >= 45 && avg <= 59 )
  {
   grade="II";
  }
  else if ( avg >=60 && avg <= 74 )
  {
   grade="I";
  }
  else
  {
   grade="Distinction";
  }
  
  //Report card..
  System.out.println("\n***Report Card***");
  System.out.println("Roll no. : "+s1.rollno);  
  System.out.println("Name : "+s1.name);  
  System.out.println("School : "+s1.school);
  System.out.println("Section : "+s1.section);
  System.out.println("Maths : "+s1.Maths);  
  System.out.println("Science: "+s1.Science);  
  System.out.println("English : "+s1.English);  
  System.out.println("Grade : "+grade);  
  
  
 }
}
