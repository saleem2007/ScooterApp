PSEUDO CODE
* I want to be able to sign up on scooter app.
* I want to be able to rent a scooter and pay with credit card.
* return scooter at a charging station.
* report for broken scooter.
* scooter can only be rented to age 18 and above .
* safety guidelines need to be acknowledge by the user before rent begins.
* app should separate broken scooter from the inventory.
* user return and pay the final bill.

CLASSES

class User {

    username;
    password;
    phonenumber;

   changeusername();
   changepassword();
   reportdamage();


}

class scooterApp extend user {

    username;
    password;
    phonenumber;
    age;

    registration();
}

class Scooter {

   serialnumber;
   batterylevel;

   inventorystock();
        
}

class station {

    location;
    status;

    rental();
    returnscooter();

}