# task_4.4

package sdo;

public class Main {

	public static void main(String[] args) {
		Cat cat = new Cat ("Tom", 20, 2);
		cat.display(cat);
		
		Dog dog = new Dog ("Spike", 50, 10);
		dog.display(dog);
		
		Mouse mouse = new Mouse ("Jerry", 5, 1);
		mouse.display(mouse);
	}

}

class Cat {

	private String name = "";
	private int height = 0;
	private int weight = 0;
	
	public Cat (String name, int height, int weight) {
		this.name = name;
		this.height = height;
		this.weight = weight;
	}
	
	public void display (Cat cat) {
		System.out.println("Имя персонажа: " + cat.name  + " Рост: " + cat.height + " Вес: " + cat.weight);
	}
}

class Dog {

	private String name = "";
	private int height = 0;
	private int weight = 0;
	
	public Dog (String name, int height, int weight) {
		this.name = name;
		this.height = height;
		this.weight = weight;
	}
	
	public void display (Dog dog) {
	System.out.println("Имя персонажа: " + dog.name  + " Рост: " + dog.height + " Вес: " + dog.weight);
	}
}

class Mouse {

	private String name = "";
	private int height = 0;
	private int weight = 0;
	
	public Mouse (String name, int height, int weight) {
		this.name = name;
		this.height = height;
		this.weight = weight;
	}
	public void display (Mouse mouse) {
	System.out.println("Имя персонажа: " + mouse.name  + " Рост: " + mouse.height + " Вес: " + mouse.weight);
	}

}

