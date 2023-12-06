# Amazon Selenium Automation with Az WebDriver

## Overview

This Selenium automation project is designed to perform various actions on the Amazon website using the Az WebDriver. It covers functionalities such as searching for Realme products, applying filters, adding items to the cart, and proceeding to checkout.

## Prerequisites

- Firefox browser installed
- Az WebDriver

## Installation

1. Clone the repository.
   <dependencies>
	  
	  <dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>4.8.0</version>
</dependency>

<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>7.4.0</version>
    <scope>test</scope>
</dependency>

<!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
<dependency>
    <groupId>commons-io</groupId>
    <artifactId>commons-io</artifactId>
    <version>2.11.0</version>
</dependency>
<!-- https://mvnrepository.com/artifact/io.github.bonigarcia/webdrivermanager -->
<dependency>
    <groupId>io.github.bonigarcia</groupId>
    <artifactId>webdrivermanager</artifactId>
    <version>5.3.1</version>
</dependency>
<dependency>
<groupId>com.aventstack</groupId>
<artifactId>extentreports</artifactId>
<version>5.0.9</version>
</dependency>

  </dependencies>

2. Open this Maven project in IntelliJ or Eclipse.  

3. Run the Automation script as TestNG test.

## Test Cases

- **Positive Case:**
  - Search for Realme products, apply filters, add to cart, and proceed to checkout.
  - [Test case](https://docs.google.com/spreadsheets/d/1JzDEklJZEVZtaVZsjqzXKbS7aGh8j5jX/edit?usp=sharing&ouid=101508411653849235851&rtpof=true&sd=true)


## Screenshots

1. **Home Page:**
   - ![Home Page](https://github.com/0311nishant/seleniumTesting/issues/1#issue-2029084717)

2. **Search Results:**
   - [Search Results](https://github.com/0311nishant/seleniumTesting/issues/2#issue-2029111242)
2.1. **Filters**
     - [Refining Product](https://github.com/0311nishant/seleniumTesting/issues/3#issue-2029112955)
     
3. **Product Details:**
   - [Product Details](https://github.com/0311nishant/seleniumTesting/issues/4#issue-2029113903)

4. **Added in cart:**
   - [Cart Page]([screenshots/az_cart_page.png](https://drive.google.com/file/d/1CiVJXoSsqe1Xus2zgvke7f-uGlgHTubn/view?usp=sharing))

5. **Checkout Page:**
   - [Checkout Page]([screenshots/az_checkout_page.png](https://drive.google.com/file/d/1fW_W6sjr6uhpucB5kTcJ-DnECwT3abTF/view?usp=sharing))

## Acknowledgments

Thanks to the Selenium community for providing a powerful automation tool.
