import java.util.Scanner;
class ProjectMenuCard
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
int status=0;
int plate=0;
int add=0;
System.out.println("welcome to MEHFIL RESTAURANT");
while (status==0)
{
System.out.println(" press 1 for Soups menu");
System.out.println("press 2 Hyderabad Dum Biryani menu");
System.out.println("press 3 Family Jumbo pack menu");
System.out.println("press 4 Starters menu");
System.out.println("press 5 Veg.Starters menu");
System.out.println("press 6 Tandoori Kebabs menu");
System.out.println("press 7 Veg.Kebabs menu");
int status1=sc.nextInt();
while(status1==1 || status1==0)
{
System.out.println("press 1 for Veg.Corn Soup - 80 RS ");
System.out.println(" press 2 for Veg.Hot Sour Soup - 80 Rs ");
System.out.println("press 3 for Tomato Soup  -  80 RS  ");
System.out.println("press 4 for Chicken hot & Sour Soup - 80 RS ");
System.out.println("press 5 for Chicken Corn Soup - 80 Rs ");
int choice=sc.nextInt();
switch (choice)
{
case 1:{
//System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;
case 2:{
//System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;
case 3:{
//System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;
case 4:{
//System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;
case 5:{
//System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;

default :System.out.println("Invalid choice");

}
System.out.println("press 0 to repate the Same menu");
System.out.println("Press 2 to come out of the menu");
status1=sc.nextInt();
}
while(status1==2 || status1==0)
{
System.out.println("press 1 for Mutton Biryani Single - 180 Rs ");
System.out.println("press 2 for Mutton Biryani Full - 200 Rs ");
System.out.println("press 3 for Spl.Mutton Biryani - 260 Rs ");
System.out.println("press 4 for Chicken Biryani Single - 110 Rs ");
System.out.println("press 5 for Chicken Biryani Full - 180 RS");
System.out.println("press 6 for Spl.Chicken Biryani - 250 RS ");
System.out.println("press 7 for Bone Less Chicken Biryani - 240 Rs ");
System.out.println("press 8 for Fish Biryani - 230 Rs ");
System.out.println("press 9 for Prawns Biryani - 230 RS ");
System.out.println("press 10 for Veg Biryani Single - 80 Rs");
System.out.println("press 11 for Paneer Biryani - 150 RS ");
System.out.println("press 12 for Mushroom Biryani - 150 RS ");
System.out.println("press 13 for  Biryani  Rice - 70 RS ");
System.out.println("press 14 for Kaju Biryani - 150 Rs ");
int choice=sc.nextInt();
switch (choice)
{
case 1:{
//System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 2:{
// System.out.println("Each plate is 200 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*200;
}break;
case 3:{
// System.out.println("Each plate is 260 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*260;
}break;
case 4:{
// System.out.println("Each plate is 110 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*110;
}break;
case 5:{
// System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 6:{
// System.out.println("Each plate is 250 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*250;
}break;
case 7:{
// System.out.println("Each plate is 240 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*240;
}break;
case 8:{
// System.out.println("Each plate is 230 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*230;
}break;
case 9:{
// System.out.println("Each plate is 230 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*230;
}break;
case 10:{
// System.out.println("Each plate is 80 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*80;
}break;
case 11:{
// System.out.println("Each plate is 150 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*150;
}break;
case 12:{
// System.out.println("Each plate is 150 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*150;
}break;
case 13:{
// System.out.println("Each plate is 70 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*70;
}break;
case 14:{
// System.out.println("Each plate is 150 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*150;
}break;
default :System.out.println("Invalid choice");

}
System.out.println("press 0 to repate the Same menu");
System.out.println("Press 1 to come out of the menu");
status1=sc.nextInt();
}
while(status1==3 || status1==0)
{
System.out.println("press 1 for Mutton Family Pack - 450 RS ");
System.out.println("press 2 for Mutton Jumbo Pack - 580 RS ");
System.out.println("press 3 for Chicken Family Pack - 400 RS  ");
System.out.println("press 4 for Chicken Jumbo Pack - 550 RS");
System.out.println("press 5 for Veg/Egg Family Pack - 260 Rs ");
System.out.println("press 6 for Egg Jumbo -350 Rs ");
System.out.println("press 7 for Veg Jumbo - 350 RS ");
System.out.println("press 8 for Veg Combo - 400 RS ");
System.out.println("press 9 for Mix Family - 410 RS ");
System.out.println("press 10 for Mix Jumbo - 600 RS");
int choice=sc.nextInt();
switch (choice)
{
case 1:{
// System.out.println("Each plate is 450 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*450;
}break;
case 2:{
// System.out.println("Each plate is 580 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*580;
}break;
case 3:{
// System.out.println("Each plate is 400 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*400;
}break;
case 4:{
// System.out.println("Each plate is 550 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*550;
}break;
case 5:{
// System.out.println("Each plate is 260 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*260;
}break;
case 6:{
// System.out.println("Each plate is 350 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*350;
}break;
case 7:{
// System.out.println("Each plate is 350 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*350;
}break;
case 8:{
// System.out.println("Each plate is 400 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*400;
}break;
case 9:{
// System.out.println("Each plate is 410 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*410;
}break;
case 10:{
// System.out.println("Each plate is 600 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*600;
}break;
default :System.out.println("Invalid choice");

}
System.out.println("press 0 to repate the Same menu");
System.out.println("Press 2 to come out of the menu");
status1=sc.nextInt();
}
while(status1==4 || status1==0)
{
System.out.println("press 1 for Chicken 65");
System.out.println(" press 2 for Chilly Chicken");
System.out.println("press 3 for Chicken Manchuria");
System.out.println("press 4 for Ginger Chicken");
System.out.println("press 5 for Chicken Drum Stick");
System.out.println("press 6 for Pepper Chicken");
System.out.println("press 7 for Lolly Pop");
int choice=sc.nextInt();
switch (choice)
{
case 1:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 2:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 3:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 4:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 5:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 6:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;
case 7:{
System.out.println("Each plate is 180 RS");
System.out.println("How Many Plates Do you want");
plate=sc.nextInt();
add=plate*180;
}break;

default :System.out.println("Invalid choice");

}
System.out.println("press 0 to repate the Same menu");
System.out.println("Press 2 to come out of the menu");
status1=sc.nextInt();
}
System.out.println("press 0 to continue");
System.out.println("press 1 to stop");
status=sc.nextInt();
System.out.println("Total Bill is"+add);
System.out.println("Thank you visite again");

}

}
}
