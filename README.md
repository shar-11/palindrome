# palindrome
   Import java.util.scanner;
   Class palindrome test{
      Public static void main(string args[])
       {
         String reverse string="";
         Scanner scanner=new scanner.nextline();
          
          Intlength=input string.length();
          For(inti=length-1;I>=0;i--)
              Reverse string=reverse string+inputstring.charAt(I);
          If(inputstring.equals(reverse string))
             System.out.println("input string is a palindrome");
          Else
             System.out.println("input string is not a palindrome ");
        }
   }
