//import org.openqa.
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver; 
public class Fourth {
	
	
	public static void main(String[] args) {
		System.setProperty("webdriver.chrome.driver","C://Users//Pavi//Desktop//Automation//Java//chromedriver.exe");
       WebDriver driver = new ChromeDriver();
       driver.get("http://www.youtube.com");
       //driver.findElement(By.xpath("//div[@id='details']//span[contains(text(),'The Life of Ram Video Song')]"));
String few = driver.getTitle();
System.out.println("Title of  page " +few);
driver.close();
	}
}
