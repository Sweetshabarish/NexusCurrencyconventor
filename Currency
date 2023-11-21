package NexusPhase1;
import java.util.Scanner;

/**
 * 
 * 1. Currency Converter using java
This project is a very basic project in Java that is used to convert a currency from one to
another. A web-based interface for converting currency and getting the output value, for
example, here displays converting the currency of the US dollar to INR.
 *
 */
public class CurrencyConventor {
	


	    public static void main(String[] args) {
	        Scanner scanner = new Scanner(System.in);

	        // Get the exchange rate from the user
	        System.out.print("Enter the exchange rate of currency 1 to currency 2: ");
	        double exchangeRate = scanner.nextDouble();

	        // Get the amount of currency 1 to convert
	        System.out.print("Enter the amount of currency 1 to convert: ");
	        double currency1Amount = scanner.nextDouble();

	        // Convert currency 1 to currency 2
	        double currency2Amount = convertCurrency(currency1Amount, exchangeRate);

	        // Display the converted amount
	        System.out.println("The converted amount is: " + currency2Amount + " currency 2");
	    }

	    private static double convertCurrency(double amount, double exchangeRate) {
	        return amount * exchangeRate;
	    }
	}



