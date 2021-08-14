# password_generator
Goal:-
We need a secure password right. So, our password contains Digit, Lower and Uppercase alphabets, Symbols. So, first we ask users how much your password long.

Installation :-
We use these two models, string and random. so we have to install it by using pip install command.

Here, we convert s1,s2,s3, and s4 in list type because above string functions like string. ascii lowercase return a string. And extend() is used to concrete list. This list looks like this.

['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z', '0', '1', '2', '3', '4', '5', '6', '7', '8', '9', '!', '"', '#', '$', '%', '&', "'", '(', ')', '*', '+', ',', '-', '.', '/', ':', ';', '<', '=', '>', '?', '@', '[', '\', ']', '^', '_', '`', '{', '|', '}', '~']

So, we get all character in one list. We use this list to get our password. For that we use sample() function to get random character of given length.

sample() is an inbuilt function of a random module in Python that returns a particular length list of items chosen from the sequence i.e. list, tuple, string, or set. Used for random sampling without replacement.

At last, join all character in a list into a string, using a “” character as separator.

Output:-
Enter password length: 8

Your password: lrOuG#6$
