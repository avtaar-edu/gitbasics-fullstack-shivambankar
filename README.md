## Java language is used for coding.

## Algorithm : 

* Start
* Input name
* Generate random id between 0 to 999    
* Generate date, tiime of the request.
* Output name, id, date-time
* End


## Source Code :

/**
 DOCUMENTATION
 Author : Shivam Bankar
 Created on : 30-9-2021
 Company : Avtaar

 This program is a first assignment.
 */

package com.company;

import java.util.Scanner;
import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.util.Date;
import java.util.Random;

public class Assignment1 {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);

        System.out.print("Enter your name : ");
        String name = s.next();
        Random random = new Random();      // creating an object of Random class
        int x = random.nextInt(1000);       // Generates random integers between 0 to 999
        DateFormat dateFormat = new SimpleDateFormat("yyyy/MM/dd HH:mm:ss");
        Date date = new Date();
        System.out.println("ID : "+ x);
        System.out.println("Name : "+ name);
        System.out.println("Date and Time : "+ dateFormat.format(date) );
        //System.out.println(dateFormat.format(date));
    }
}


## Output screenshots :
<img src="![1 1](https://user-images.githubusercontent.com/78548929/135451292-55e1d41c-4987-438a-a3f7-cbe152bd357c.png)
">







![1 1](https://user-images.githubusercontent.com/78548929/135451457-b1a290dc-33f6-4e3d-a815-372d74dd668b.png)
![1 2](https://user-images.githubusercontent.com/78548929/135451585-372b5765-7c78-4ca1-9366-8c34233ef7ed.png)
![1 3](https://user-images.githubusercontent.com/78548929/135451593-fe6c207f-0fcf-4897-8ae7-589d9e4123a7.png)
