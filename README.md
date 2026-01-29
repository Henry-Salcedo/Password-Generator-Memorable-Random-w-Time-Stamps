# Password-Generator-Memorable-Random-w-Time-Stamps
2 simple password generators focused using random package to create both a memorable, and random generation. 
Then later both given time-stamps upon generation, and then randomed into either 1000 times/and saves into a batch.

## a) Purpose of the Program(s):

    The purpose of this program was to create 2 password generators one of each memorable, and random, then generate time-stamps 
    for when each password was generated, then generate (at random) between the 2 generations into 1000 passwords that are then 
    batched saved. Also as a class assignment to better understand how the spcific packages (string, timne, and random) 
    could have been used into such applications.
    
    The following modules that were used for the project only consisted of:
    Random
    Time
    String

## b) Input:

    The program takes the following inputs:
        A '.txt' file containing 100000 noun words for the memorable generator.
       Giving the attributes of what the passwords should contain/be: memorable_password(nouns, words=4, digits=2, symbols=1)
        How long the random password should be as needed: generate_simple_password(length=12)
        
## c) Expected Output:

    The following code both generates memorable passwords, random passowords, and time-stamps them along with batching it up 
    and stores randomization of both of 1000 passwords.
    
    Memorable example outputs are:"ferro-pisarev-serov-Tomfoolery60*","eies-clemen-homeschooling-Sonia31*".
    Random example of the expected output would look akin to: "u1yr.PcPF>Z%", "@>?x44COjrXr".

    Then with the inclusion of time-stamps: 
    "2026-01-29 10:34:41 | memorable  | ferro-pisarev-serov-Tomfoolery60*"
    "2026-01-29 10:34:41 | simple     | u1yr.PcPF>Z%"
    
## d) Type of Execution:

        Sequential Execution: The code is executed in a linear order from top to bottom.

    The program:
    Loads the noun list
    Defines the password generator functions
    Prints multiple generated passwords using loops        
    The inclusion of time-stamping when made
    Combines the later into a batch generation for n times, and saves as '.txt' file.

## e) Possible Improvements:

    The program could be improved by:
    1. Rathar than creating multiple function for the generators and then for the time-stamp parts, to incoroprate such things into one each.
    2. Another improvement is adjusting the random time-stamp for generating it 2 times rather than once (simple fix).
    3. Later down the line could include security function to supporth the strength and quality of the random generated passowords.

    
