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
   - ![Home Page]()

2. **Search Results:**
   - [Search Results](https://drive.google.com/file/d/1NMW-5ICQ2c_dkgbwMo9tOA6qIudBKC5y/view?usp=sharing)
2.1. **Filters**
     - [Refining Product]([screenshots/az_search_results.png](https://drive.google.com/file/d/1O3vKhIQ5qljUKLvBTnoHVYOUtuLGCZmS/view?usp=sharing))
     
3. **Product Details:**
   - [Product Details]([screenshots/az_product_details.png](https://drive.google.com/file/d/1DS7aifWrxSQR-mDe_g1d3cC4vVDsQi6h/view?usp=sharing))

4. **Added in cart:**
   - [Cart Page]([screenshots/az_cart_page.png](https://drive.google.com/file/d/1CiVJXoSsqe1Xus2zgvke7f-uGlgHTubn/view?usp=sharing))

5. **Checkout Page:**
   - [Checkout Page]([screenshots/az_checkout_page.png](https://drive.google.com/file/d/1fW_W6sjr6uhpucB5kTcJ-DnECwT3abTF/view?usp=sharing))

## Acknowledgments

Thanks to the Selenium community for providing a powerful automation tool.
