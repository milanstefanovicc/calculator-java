File calulator java  188 loc -  razvojno okruzenje mi je prijavilo 8 gresaka u kodu  premestanje fajla u imenovani paket ,preimenovavanje metode, dodti privatni konstruktor da bi sakrili implicitni javni,nekonzistentnosti u imenovanju promenljivih,nepotrebnih metoda

file start java 26 loc- razvojnno okruzenje je prijailo 4 greske u kodu (preimenovnje promenljive)premestanje fajla u imenovni paket,preimenovanje promenljive


assignment2

}

import static org.junit.jupiter.api.Assertions.assertEquals;
import static org.junit.jupiter.api.Assertions.assertTrue;

import org.junit.Test;
import org.junit.jupiter.*;
 
public class kalkulatoriUtilsTest {
 
    @Test
     public void testIsEven() {
    int number1 = 4;
    int number2 = 5;
    int sum = Kalkulatori.add(number1, number2);

    assertEquals(sum,9);
    }
}
