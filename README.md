# black-jack

import java.util.*;
public class blackjack
{
  public static void main(String [] args)
  {
    Scanner myScanner = new Scanner(System.in);
    boolean playAgain=true;

      while(playAgain==true)
      {
      boolean invalid = false;
        do
        {
        System.out.println("Do you wish to stop playing?");
        System.out.println("1:Yes");
        System.out.println("2: No");
 
        int rematch = myScanner.nextInt();
 
            if(rematch==1)
            {
            System.out.println("Game finished")
            playAgain=false;
            invalid=false;
            }
            else if(rematch==2)
            {
            playAgain=true;
            invalid=false;
            }
            else
            {
             System.out.println("Invalid Entry!");
            invalid=true
            }
         }
         while(invalid==true);
        }
      }
    }
