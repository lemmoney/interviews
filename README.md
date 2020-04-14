# Lemoney Test

The main goal of our coding interview is emulating real world problems we face daily at
Lemoney rather than asking you to solve math puzzles or asking you the performance or complexity of
an algorithm. To make some fun out of it, the cartoon below shows a smart way of solving the
travelling salesman problem, which is commonly asked on coding interviews

<p style='text-align:center'>
  <img src='travelling_salesman_problem.png'/>
</p>

We believe that code should be smart and organized and most of all, when you are working
with a team it should follow a common GUIDELINE

## Requirements for the test

There are no time constraints to make the test, so you have all the time you need to research and
implement the way you would in a real world scenario.(However, keep in mind that **time counts**
for our final evaluation). So our suggestion to you is to do the whole test at once if you can.
Reserve some time for it and do not split it.

### The challenge

1. Ruby on Rails v4.x or superior (required)
2. Twitter Bootstrap v3.x or superior (required)
3. Openssl (for non Mac and Linux users)

If you stick with this alternative we will look mainly to your skills
with Rails and your ability to build well crafted web components using HTML + CSS

## Starting the test

After installing the libraries above and setting up your environment, you are ready to follow the test instructions.

Instructions for testing are in **INSTRUCTIONS.pdf**. In order to verify that you are doing the correct test and that the contents of the file have not been altered by unauthorized third parties or damaged during the transfer process. We encrypted **INSTRUCTIONS.pdf** in **INSTRUCTIONS.locked** with a block cipher algorithm using a symmetric key.

To decrypt **INSTRUCTIONS.locked** we need you to send us a computed checksum of **INSTRUCTIONS.locked** using the same hashing algorithm used by **git to produce confirmation hashes.**

Send a `GET` request to `http://interviews.lemoney.com` with the parameter checksum that contains the computed `checksum` for **INSTRUCTIONS.locked** and the `email` with your email address. If the request is correct, our server will return the key required to unlock the instructions for your test.

IMPORTANT: When you send the GET request, we know that you have started your test. Just to clarify again, you have all the time necessary to take the test, but we will take it into account in the final assessment

After obtaining the key, run:

`openssl aes-256-cbc -d -md md5 -a -in INSTRUCTIONS.locked -out INSTRUCTIONS.pdf -k [your_key]`

PS: This step is useful to let us know if you're able to research solutions and solve unexpected problems that could happen.

Now that you have the **INSTRUCTIONS.pdf** file, open the file and follow the instructions

