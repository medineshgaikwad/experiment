# experiment

package allaboutscreenshot;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class D {
	public static void main(String[] args) {
		System.setProperty("webdriver.chrome.driver", B.a);
		WebDriver driver = new ChromeDriver();
		driver.get("https://www.facebook.com/signup");
		driver.manage().window().maximize();
	}

}
