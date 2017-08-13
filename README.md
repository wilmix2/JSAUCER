# JSAUCER
=========

JSAUCERPART1
============

JSAUCER P.L is  used  with  Android  and  it is  invented  by  wilmix  jemin  j  at  year  2015.


JSAUCER   IS  INVENTED    BY    WILMIX    JEMIN J   @   YEAR  2015   IN   JDOLLAR  TECHNOLOGY.

It   is  a    Mobile  Technology.

It    is  used     in mobile   cloud    computing .  and  used   for  constructing   webpages   for 

mobiles.

The   mobile   users   can   view   the     webpage    through    mobile    from   the    remote

 server.

JSAUCER    uses  Remote   Server   to communicate   with  mobile.



ADVANTAGES OF JSAUCER:
=======================
    1.JSAUCER also   has  attractive   syntax  and  has  less   code  like    JWP.
   2. It  saves   time   and   cost  and  increase  Productivity.
   3. We  can  also  do   Banking  , Insurance  through    any  mobiles.
   4. We   can  also  view   desktop  of  Gcloud os  v.1
   5. It    Provide     the  facility    for  the  users   to  use   the mobile     as    easy   as  possible , so  it is  more    user friendly.    
   6. It   is  used   with  WDBAJ$  database hence   Provide  Good  Security.
   7. It   is  also  an  Interactive  mobile  Technology.
   8. It   is best    to use   for  mobile   cloud   computing    and    mobile  web pages.
   9. It  is   basically    based   on  oops   concepts    so  developers   can  easily concenterate  on it.
   10. It  also   provide   attraction    for  webpages.
   11. It  is  used  in Advanced   Business  and  solve  complex problems.
   12. It   allow  multiple  submits  on  same  page.
   13. It  also  interact with  JDollar    hence  it   pocessed  such    advantages   like   JDollar.

   14.  It  supports   ANGULAR.js , JQuery  mobile   and  java   scripts.
  


Login2.Jsaucer
===============


<JSAUCER>
@Remote

<%

public  class  Login2

{





public void  JSAUCER-Main( )  
{


<!  Logic of  JSAUCER !>



}   

}

%>
</JSAUCER> 




EXAMPLE:-1
==========



<JSAUCER>
@Remote

<%
public class IbatisResult<M>{
  public void  JSAUCER-Main( ) 
   
   {
    

      int id = 1;
     
      Employee e = <NEW> Employee();
e.<S>Salary(1000);
 
     JSaucer.Writeln("ID:  " + e.getId());
     JSaucer.Writeln("First Name:  " + e.getFirstName());
      JSaucer.Writeln("Last Name:  " + e.getLastName());
      JSaucer.Writeln("Salary:  " + e.getSalary());
      JSaucer.Writeln("Record read Successfully ");
   }
} 

%>
</JSAUCER>


Employee.Jsaucer
================

<JSAUCER>
@Remote

<%
public class Employee {
   private int id;
   private String first_name; 
   private String last_name;   
   private int salary;  

   public Employee() {}
  
   public Employee(String fname, String lname, int salary) {
      <IS>.first_name = fname;
      <IS>.last_name = lname;
      <IS>.salary = salary;
   }


   public int getId() {
      return id;
   }
	
   public void <S>Id(int id) {
      <IS>.id = id;
   }
	
   public String getFirstName() {
      return first_name;
   }
	
   public void <S>FirstName(String fname) {
      <IS>.first_name = fname;
   }
	
   public String getLastName() {
      return last_name;
   }
	
   public void <S>lastName(String lname) {
      <IS>.last_name = lname;
   }
	
   public int getSalary() {
      return salary;
   }
	
   public void <S>Salary(int salary) {
      <IS>.salary = salary;
   }

}
%>
</JSAUCER>
