# Grocery Steve

Grocery Steve is an online web application posing as a grocery list. It is a 
simple list with a C.R.U.D. interface for the user. 

## Getting Started

#### Launch Web Server

```
docker run -it --rm --name grocery_steve -v $PWD:/var/www/html -p "80:80" -d bobbyahines/php:7.4-apache
```

#### User Stories

AS A:    USER
I WANT:  The landing page to be a list of items
SO THAT: I can "see what is in my grocery list" (c.R.u.d.).

AS A:    USER
I WANT:  A form
SO THAT: I can add new items to the grocery list (C.r.u.d.).

AS A:    USER
I WANT:  A form
SO THAT: I can edit/update existing items on the list (c.r.U.d.).

AS A:    USER
I WANT:  A button
SO THAT: I can remove/delete an item on the list (c.r.u.D.).

