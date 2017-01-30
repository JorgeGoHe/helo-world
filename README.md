# helo-world
Tutorial
public class Sueldo {

	public static void main(String[] args) {
		
		int horas;
		Scanner sc;
		
		sc = new Scanner(System.in);
		System.out.println("Por favor introduce el valor: ");
		horas = sc.nextInt();
		System.out.println("Las horas trabajadas son: " + horas );
		
		double salario;
		salario = (horas*15);
		System.out.println("El salario total es de: " + salario);
		
		
		

	}

}
