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

If you stick with this alternative we will look mainly to your skills 
with Rails and your ability to build well crafted web components using HTML + CSS

## Starting the test

After choosing one of the options above and setting up your environment
you are ready to follow the test intructions.

We advise you to install `openssl`, which is probably installed by default 
if you are a MacOS or Linux user.

Before you carry on, **INSTRUCTIONS.locked** has been encrypted with a block cipher
algorithm using a symmetric key.

To double check that you are doing the right test and that the file content has neither been altered
by an unauthorized third party, nor been damaged during the transfer process, we need you to send us
a computed checksum of **INSTRUCTIONS.locked** using the same hashing algorithm used by **git to
produce commit hashes**

Just send a `GET` request to `http://interviews.lemoney.com` with the parameters
`checksum` containing the computed checksum of **INSTRUCTIONS.locked** and `email` containing your email address.
If the request is correct our server will return the key you need to unlock 
the instructions for your test.

IMPORTANT: When you send the GET request to us we know that you started
your test. Just to make it clear again, you have all the time you need to do the test,
but we'll take it into consideration for the final evaluation


After getting the key execute:

`openssl aes-256-cbc -d -md md5 -a -in INSTRUCTIONS.locked -out INSTRUCTIONS.pdf -k [your_key]`

Now that you have `INSTRUCTIONS.pdf`, open the file and follow the instructions

