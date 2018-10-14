import com.sun.javafx.css.CalculatedValue;
import com.sun.org.apache.xpath.internal.operations.Equals;
import org.junit.After;
import org.junit.Before;
import org.junit.Test;
import static junit.framework.TestCase.assertEquals;


public class void calculatorTest {

   Calculator calc = new Calculator();

    @Before
    public static void consolePrint(); {
        System.out.println("Tests started!!! ");
    }

    @Test
    public void testAddTwoPositiveValues(); {
        assertEquals("10 + 5 must be 15", 15, calc.Add(10, 5));
    }

    @Test
    public void testAddTwoNegativeValues(); {
       assertEquals("-10 + -5 must be -15", -15, calc.Add(-10, -5));
    }

     @Test
    public void testSubTwoNegativeValues() ;{
        assertEquals("-10 - -5 must be -5", -5, calc.Sub(-10, -5));
    }

     @Test
    public void testMultTwoNegativeValues(); {
        assertEquals("-10 * -5 must be 15", 50, calc.Mult(-10, -5));

    }
    @Test
    public void testDivTwoNegativeValues(); {
        assertEquals("-10 / -5 must be 2", 2, calc.Div(-10, -5));
    }
    @Test
    public void testSqTwoNegativeValues(); {
        assertEquals("-10 / -5 must be 2", 2, calc.Sq(-10, -5));
    }
    @After
    public void consolePrintAfter();{
        System.out.println("Tests finished!!! ");
        }

}
