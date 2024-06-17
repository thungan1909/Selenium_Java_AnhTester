## Các cách để lấy Locator

## 1. ID

WebElement username = driver.findElement(By.id("login-username"));

## 2. Name

WebElement password = driver.findElement(By.name("password"));

## 3. LinkText

WebElement askViblo = driver.findElement(By.linkText("Ask on Viblo »"));

## 4. PartialLinkText

WebElement PartialLinkText = driver.findElement(By.partialLinkText("Testing"));

## 5. TagName

WebElement TagName = driver.findElements(By.tagName(a));

## 6. ClassName

<input type="email" name="email" value="" placeholder="Email" required="required" autofocus="autofocus" class="form-control mt-3 form-control-lg">

WebElement ClassName = driver.findElement(By.className("form-control mt-3 form-control-lg"));

## 7. CSS Selector

WebElement password = driver.findElement(By.cssSelector("[type='password'][placeholder='Your Password']"));

## 8. Xpath

driver.findElement(By.xpath("chuỗi xpath của element"));​

Có 2 loại Xpath: Xpath tuyệt đối và Xpath tương đối.

- Xpath tuyệt đối bắt đầu bằng dấu gạch chéo đơn "/"
- Xpath tương đối bắt đầu bằng 2 dấu gạch chéo "//"
