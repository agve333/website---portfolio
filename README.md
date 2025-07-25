Hey - its a pleasure to meet u - i will detail the steps i took to make this site and to attemt to defend it against low level attacks
step 1 - a html/css site
step 1.5 - nothing to acces seeing as its on a open server and the contents are free to all
step 2 - add a login part for admin acces - (no real diffrence to acces)
step 2.5 - make a scrypt to bruteforce the login page - proof of concept - (in the bruteforce library the corrct credentiols were placed)
step 3 - make the site authorised user only - (login page to view tha basic site)
step 3.5 - create an exploit to allow us to acces the site without the id credentials - create a js exploit that would modify page elements and remove the "pay wall"
why this works - site is clients side only -no password hashing - this would require the exsitence of a backend which would mean it wasnt based on client side only
because its client side only the client has full accses to all the info however our lo=gin page acts as a paywall despite this because the user has the info page its just behind the
pay wall - all he needs to do is reomve the paywall elements using something likt the "burp suite" 
step 4
