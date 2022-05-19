# URL-shortener
Built a simple URL shortener using Python and Flask
#
<img width="483" alt="image" src="https://user-images.githubusercontent.com/88205480/169330303-7793fca0-76fd-4ca5-97e8-e1ed9f8fe4f6.png">

This url shortner is  based on 2  conditions:-
1) "Long URL" is sent and converted into "Short URL".
2) "Short URL" is sent which is redirected to the Long URL which that long URL corresponds to.

# CONDITION 1:

long URL -->> short URL
When a long URL is entered we will be check does that long URL alerady exist and if it does exist a short version of that URL will be given back to the user.
But if the short version doesn't exist new code will be generated.
- Three random letters will be picked, and we are going to check if:- 
  -Those three random letters are already used or not
  -And if they weren't used new generated set of 3 letters will be our "NEW SHORT URL".
    Example:- XYZ will correspond to the long URL sent by the user.
  so the certain long URL is stored inside our database which will be returned back to our user.
  <img width="488" alt="image" src="https://user-images.githubusercontent.com/88205480/169337578-d12f7543-82ba-40fb-904a-a4e9274d993d.png">


# CONDITION 2: 
 
  user -- redirect-->> long URL
  When a short URL is given user will be redirected to whatever page the long URL represent.
  
  Example :- lets say a short URL "XYZ" is given
  
  <img width="483" alt="image" src="https://user-images.githubusercontent.com/88205480/169337103-170d7117-e12d-4442-95c2-f21038a29e1c.png">
