package ounisha;

import java.util.Scanner;
public class bat1
{
public static void main(String args[])
{

int a;
int b,c;
Scanner sc=new Scanner(System.in);
System.out.println("enter your option");
int option=sc.nextInt();
switch(option)
{
case 1:
System.out.println("please open the score of player1");
break;
case 2:
System.out.println("please open the score of player2");
break;
case 3:
System.out.println("please open the score of player3");
break;
case 4:
System.out.println("please open the score of player4");
break;
case 5:
System.out.println("please open the score of player5");
break;
case 6:
System.out.println("please open the score of player6");
break;
//continue;

default:
//System.out.println("Enter corect option"+option);
}
System.out.println("******CRICKET SCORE BOARD *******");

System.out.println("enter the player name");
String name1=sc.next();
System.out.println("enter the age of player");
int age1=sc.nextInt();
System.out.println("enter the total score in his carrer");
int score1=sc.nextInt();

System.out.println("enter the total wickets in his carrer");
int wickets1=sc.nextInt();
System.out.println("enter the total no of matches he played");
int match1=sc.nextInt();
System.out.println("enter the runs in his carrer");
int runs1=sc.nextInt();

	if(runs1<3000)
{
System.out.println("player is not completed 3000 runs in his carrer");
}
else

System.out.println("player completed 3000 runs in his carrer" + "so give worldcup to player" );
}
{
Scanner sc=new Scanner(System.in);
System.out.println("enter the score of player in 1 over");
int over1=sc.nextInt();
System.out.println("enter the score of player in 2 over");
int over2=sc.nextInt();
int totalscore;
totalscore=over1+over2;
{
System.out.println("the total score of player is"+ totalscore);
}
}
}
