# Prestaconcept Technical Test

Thank you for your candidature at Prestaconcept.


## The test

This test aim to estimate the technical level of our candidates during the 
recruitment process.

You will be asked to build an application that purpose will be to import a 
file within a command then display the imported data in an web page.

This test should be done in a dedicated time, we will ask you to provide a 
clean and efficient code.

**We do prefer a clean and efficient code, rather than incomplete parts or poorly structured code or even unefficient/copy-pasted code.**


## Steps

- Install Symfony and delete unneeded files
- Use the `AppBundle` provided by Symfony
- Create the model : `Doctrine` entities, stored in a `MySql` database 
  (you can determine the mapping by reading import files)
- Create a command to import a file, depending on your level :
    - [/data/import/developers_simple.csv](/data/import/developers_simple.csv)
    - [/data/import/developers_middle.csv](/data/import/developers_middle.csv)
    - [/data/import/developers_big.csv](/data/import/developers_big.csv)
- Create a web page that will display the list of imported developers, 
  lazy loaded :
    - the list must be composed of the following elements :
        - lastname : uppercased
        - firstname : first letter uppercased, following letters lowercased
        - badges count
    - on top of the list : display the total count of developers stored in 
      the database
    - the page should looks like Prestaconcept page 
      (see colors and theme of [our website](https://www.prestaconcept.net/), 
      but keep it simple)
    - add a select that will allow user to sort the list
- Create an action to export the list as a CSV file


## Things we will look at

- your code is clean, intuitive and readable (phpDoc, PSR, etc...) 
- you masters the PHP basics
- you know how to use Symfony
- you pay attention to the performance of your application
- you masters the HTML / CSS / JS / LESS basics
- you know how to use git 
  (several logic commits, clean history, merge request details, etc...)


## Deliver your code

You must open a merge request **before** the date.
Your branch name should be formatted as follows : `AAAAMMJJ_lastname_firstname`.

If you do succeed to demonstrate your skills, 
your motivation and your will to join us, 
we will be glad to contact you back and meet with you.
