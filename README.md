# regex-patterns

To accept Number:
 {
        String input = "222123";
        if(input.matches("[0-9]*")) {
       System.out.println("true");
    }
    
To Accept Alphabets without numbers:
input.matches("[a-zA-Z]+")
To Accept Alphabets with space:
input.matches("[a-zA-Z ]+")
