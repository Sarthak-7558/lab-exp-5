# lab-exp-5
package labexp5in;

import java.util.*;
interface Vehicle{
	void gear_change();
	void speed_up();
	void apply_breaks();
}

class Bicycle implements Vehicle{
	public void gear_change()
	{
		int x;
		Scanner sc =new Scanner(System.in);
		System.out.println("enter gear change from 1 to x in case of bicycle:");
		x= sc.nextInt();
		System.out.println("Bicycle is at gear:" +x);
		
	}
	public void speed_up()
	{
		int initial=20;
		int increase;
		int finalspeed;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter speed increased in bicycle:");
		increase= sc.nextInt();
		finalspeed=initial+increase;
		System.out.println("Final speed is"+finalspeed  );
		
		
	}
	public void apply_breaks()
	{
		int b;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter how many times break applied in bicycle:");
		b =sc.nextInt();
		System.out.println("breakes applied :" +b);
		
	}
	
	
	
}
class Bike implements Vehicle{
	public void gear_change()
	{
		int x;
		Scanner sc =new Scanner(System.in);
		System.out.println("enter gear change from 1 to x in case of Bike:");
		x= sc.nextInt();
		System.out.println("Bike is at gear:" +x);
		
	}
	public void speed_up()
	{
		int initial=20;
		int increase;
		int finalspeed;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter speed increased in bike:");
		increase= sc.nextInt();
		finalspeed=initial+increase;
		System.out.println("Final speed of bike is:"+ finalspeed );
		
	}
	public void apply_breaks()
	{
		int b;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter how many times break applied in bike:");
		b =sc.nextInt();
		System.out.println("breakes applied :" +b);
		
	}
	
	
	
}
class Car implements Vehicle{
	public void gear_change()
	{

		int x;
		Scanner sc =new Scanner(System.in);
		System.out.println("enter gear change from 1 to x in case of car:");
		x= sc.nextInt();
		System.out.println("Car is at gear:" +x);
		
		
	}
	public void speed_up()
	{
		int initial=20;
		int increase;
		int finalspeed;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter speed increased in case of car:");
		increase= sc.nextInt();
		finalspeed=initial+increase;
		System.out.println("Final speed of car is:"+ finalspeed );
		
		
	}
	public void apply_breaks()
	{
		int b;
		Scanner sc= new Scanner(System.in);
		System.out.println("enter how many times break applied in case of car:");
		b =sc.nextInt();
		System.out.println("breakes applied :" +b);
	}
	
	
}



public class Main {
	public static void main(String[] args) {
		Bicycle b= new Bicycle();
		Car c= new Car();
		Bike d = new Bike();
		
		b.gear_change();
		b.speed_up();	
		b.apply_breaks();
		
		c.gear_change();
		c.speed_up();	
		c.apply_breaks();
		
		d.gear_change();
		d.speed_up();	
		d.apply_breaks();
	}

}
