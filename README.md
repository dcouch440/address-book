# Address Book
#### *Co-Created By: David Couch*
#### *Co-Created By: Ashley Porter <https://github.com/KirbyPaint>*
#### *This app takes multiple inputs from the user and stores it*

* * *

## Description  
This app is designed to use showcase constructors and prototype methods to manipulate existing object data.

* * *
## Specs
```js
Describe: Contact();
Test: "It will produce a new contact object based on user-inputs: First Name, Last Name, Phone Number"
Expect(Contact("John", "Smith", "5035551234").toEqual({firstName: "John", lastName: "Smith", phoneNumber: "5035551234"}));

Describe: Contact.prototype.fullName();
Test: "It will return the contact's first and last name as one string"
Expect(Contact.prototype.fullName().toEqual("John Smith"));

Describe: AddressBook();
Test: "It will produce a prototype for proceeding objects to inherit from"
Expect(new AddressBook().toEqual({contacts: {}, currentId: 0}));

Describe: AddressBook.prototype.assignId();
Test: "It will grab the current id from AddressBook and increase its value by one and return it"
Expect(this.assignId().toEqual(1))

Describe: AddressBook.prototype.addContact();
Test: "It will grab the current id and index it into the AddressBook object"
Expect(this.addContact().toEqual({}))

Describe: AddressBook.prototype.findContact();
Test: "It will check if the provided index exists, and if it does, it returns the Contact object; otherwise it returns false."
Expect(AddressBook.prototype.findContact(1).toEqual({firstName: "John", lastName: "Smith", phoneNumber: "5035551234", id: 1}));

Describe: AddressBook.prototype.deleteContact();
Test: "It will check if the provided index exists, and if it does, it will delete the Contact object; otherwise it returns false."
Expect(AddressBook.prototype.deleteContact(1).toEqual(null));

Describe: $("form#new-contact").submit(function(event) {})
Test: "It will grab the submit event from the form with the id new-contact and return its information"
Expect($("form#new-contact").submit(function(event) {}).toEqual(Jquery.Event {originalEvent: MouseEvent, type: "click", target: "form#new-contact"...}));)

```
 
* * *

## Technologies used
* HTML
* CSS
* Git and Github
* Bootstrap
* JavaScript
* JQuery

* * *

## Setup instructions:  
### Want to see this webpage now?
###### See this web page in action on [Github Pages]()
*  Navigate to the code button on the github website.\
![Code button](/img/README/code.PNG)

* Click on the code button to open the menu.\
![Github Repo Example](/img/README/HTTPS.png)

- Copy the HTTPS code by clicking the clipboard next to the link.

- Within your Bash terminal navigate to your desired location by using cd fallowed by your desired directory.
```bash
 cd Desktop
``` 

- Once you have chosen your desired directory use the command.
```bash 
git clone https://github.com/dcouch440/address-book.git
```

<div 
  style="
    background-color: #d1ecf1; 
    color: grey; padding: 6px; 
    font-size: 9px; 
    border-radius: 5px; 
    border: 1px solid #d4ecf1; 
    margin-bottom: 12px"
> 
  <span 
    style="
      font-size: 12px; 
      font-weight: 600; 
      color: #0c5460;"
  >
    ⓘ
  </span>
  <span 
    style="
      font-size: 12px; 
      font-weight: 900; 
      color: #0c5460;
      margin-bottom: 24px"
  >
    Note : 
  </span> 
  If you have any problems make sure your HTTPS code is correct! The example above might not be the most recent HTTPS code!
</div>


* Then after the process is completed use the command.

``` bash
code .
```
* This will open the directory in your default code editor and from there it is required that you open the index.html file from live server (Visual Studio Code) or your code editors counterpart. You <strong>must</strong> use this method. Opening this web app from the index.html file alone will cause it to not function correctly!

<p 
  style="
    font-size: 12px; 
    background-color: #8c8c8c; 
    border-radius: 2px; 
    padding: 1px 5px; 
    text-align: center; 
    color: white; 
    margin-bottom: 24px"
>
  <span style="font-weight: 700; color: purple">Live server</span>
  <img src="img/README/liveserver.PNG">
</p>


## To Do:
* {future changes to the project}

* * *

## Addition comments:
* Created on 1/25/21

* * *

## License:
> *&copy; David Couch, 2021*

Licensed under [MIT license](https://mit-license.org/)

* * *

## Contact Information
_David Couch: [Email](dcouch440@gmail.com)_