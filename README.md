import java.util.Scanner;

public class Pago {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int ravioles, valor, precio;
        valor = 200;

        System.out.print("Ingrese su nombre: ");
        String nombre = sc.next();

        System.out.print("Ingrese el tipo de fideos que quiere: ");
        String fideos = sc.next();

        System.out.print("Ingrese la cantidad de kilos que quiere: ");
        ravioles = sc.nextInt();

        precio = (ravioles * valor);

        System.out.println("Señor " + nombre + ", el kilo de " + fideos + " cuesta " + valor + " por comprar " + ravioles
                + " kilos, el cargo es de " + precio + "$. Dele clic en continuar para terminar el pedido.");
    }
}
