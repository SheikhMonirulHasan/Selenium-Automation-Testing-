//How to open a website automatically in seleninum 
//To open a website from the different browser use the code justd remove the comment then it will active for the action.

package testpackage;

import org.openqa.selenium.chrome.ChromeDriver; import org.openqa.selenium.firefox.FirefoxDriver;

public class FirstCase {

public static void main(String[] args) {
	// setting chrome driver property
          
	//System.setProperty("webdriver.chrome.driver", "F:\\Chromedriver.exe");
	 System.setProperty("webdriver.gecko.driver","F:\\geckodriver.exe");


	//Instatiate the ChromeDriver
	//ChromeDriver driver = new ChromeDriver();

	//Instantiate Fireforx Driver
	FirefoxDriver driver = new FirefoxDriver();

	//Opening Google homepage in chrome browser and firefox

	driver.get("https://www.google.com");

	//Quiting the driver

	//driver.quit();
 }
}
