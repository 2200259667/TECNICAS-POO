// Clase abstracta Vehiculo
abstract class Vehiculo {
    abstract void arrancar();
}

// Clase Concreta Coche que extiende Vehiculo
class Coche extends Vehiculo {
    void arrancar() {
        System.out.println("El coche está arrancando.");

        // Clase CuentaBancaria con encapsulación
class CuentaBancaria {
    private double saldo;

    public double getSaldo() {
        return saldo;
    }

    public void depositar(double cantidad) {
        if (cantidad > 0) {
            saldo += cantidad;
        }
    }
}
// Clase base Empleado
class Empleado {
    protected String nombre;
    protected double salario;
    
    public void datosEmpleado() {
        System.out.println("Nombre: " + nombre + ", Salario: " + salario);
    }
}

// Clase Gerente que hereda de Empleado
class Gerente extends Empleado {
    private String departamento;
    
    public void datosGerente() {
        datosEmpleado();
        System.out.println("Departamento: " + departamento);
    }
}
// Clase base Animal
class Animal {
    public void sonido() {
        System.out.println("El animal hace un sonido");
    }
}

// Clase Perro que sobrescribe el método sonido
class Perro extends Animal {
    public void sonido() {
        System.out.println("El perro ladra");
    }
}

// Clase Gato que sobrescribe el método sonido
class Gato extends Animal {
    public void sonido() {
        System.out.println("El gato maúlla");
    }
}

