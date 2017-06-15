class Trouble
{
  public static void main(String[] args){
    String yellow, red, green, blue;
    
    int positionNew=0;// position for yellow
   int position =0;// position for yellow
   int position2=0;// position for green
     int positionnew2=0;// green
     int position3=0;
     int positionnew3=0;
     int position4=0;
     int positionnew4=0;
    
    int table;
   
    String enter = "";
    
   
    //, position2, position3, position4;
    //String[][] boardGame = new String [7][7];
    
    System.out.println("Welcome to trouble, in order to play this game you need 4 players, if you have 4 players press enter. ");
    enter = In.getString();
    System.out.println("Goal of the game is to get 4 of your pieces to home: To start first player rolls a die and if he rolls a 5 for example then the piece moves 5 times to the left. When piece reaches home you win."); 
    System.out.println("Every player has been assigned a color as their player name such as yellow, green, blue and red but R, Y, B, and B for short. Press enter to start.");   
     enter = In.getString(); 
     String[][] boardGame = {
      {"\tY","\t","\t","\t","\t","\t","\tG"},
      
      {"\t_","\t_","\t_","\t_","\t_","\t_","\t_"},                                   
      {"\t_","\t","\t","\t","\t","\t","\t_"},
      {"\t_","\t","\t","\t","\t","\t","\t_"},
      {"\t_","\t","\t","\t","\t","\t","\t_"},
      {"\t_","\t","\t","\t","\t","\t","\t_"},
      {"\t_","\t","\t","\t","\t","\t","\t_"},
      {"\t_","\t_","\t_","\t_","\t_","\t_","\t_"},
      
      {"\tR","\t","\t","\t","\t","\t","\tB"},
      
      
      
      
      
    };
    
    boardGame[3][1] = "\tFinish";
    boardGame[3][5] = "\tFinish";
    boardGame[6][1] = "\tFinish";
    boardGame[6][5] = "\tFinish";
    
    PrintArray(boardGame);
    
   
    do
    {  
    boardGame[0][0]="\t";    
    positionNew = position("Yellow", 0); 
    boardGame[1][positionNew]="\tY";
    PrintArray(boardGame);
    
    boardGame[0][6]="\t";
     positionNew = position("Green", 0);
       boardGame[positionNew][6]="\tG";
      PrintArray(boardGame);
      
      
       
       //System.out.print(positionNew);
    
    //positionNew = position("Green", 0);  
   // System.out.print(positionNew);
    //positionNew = position("Red", 0);
   // System.out.print(positionNew);
   // positionNew = position("Blue", 0);
    
     
}
    while(boardGame[3][1] != "Y" || boardGame[3][5] != "G" || boardGame[6][1] != "R" || boardGame[6][1] != "B");
    
    System.out.println("Welcome to trouble, in order to play this game you need atleast 2 players or more to play, 4 players max.");
    
  }
  
  
  // 
  public static int position(String colour, int positionCur){
    int positionNew = 0;
    int roll =0;
    int dieRoll = (int)(6 * Math.random() ) + 1;
    System.out.println(colour + "'s roll, press anything");
    roll = In.getInt();
    System.out.println(colour + " has rolled a "  +  dieRoll);
    positionNew = positionCur + dieRoll;
    System.out.println(colour + " is now at " + positionNew);
    return positionNew;}
  
 // public static int position2(String colour2, int positionCur2){
   // int positionnew2 = 0;
  //  int roll2 =0;
   // int dieRoll2 = (int)(6 * Math.random() ) + 1;
   // System.out.println(colour2 + "'s roll, press anything");
   // roll2 = In.getInt();
  // System.out.println(colour2 + " has rolled a "  +  dieRoll2);
   // positionnew2 = positionCur2 + dieRoll2;
   // System.out.println(colour2 + " is now at " + positionnew2);
  //  return positionnew2;}
  
  
  
  
  
  //This Method is used to print any 1D array
  public static void PrintArray(String[][] ArrayToBePrinted){
    
    int rows = ArrayToBePrinted.length;
    int cols = ArrayToBePrinted[0].length;
    for (int i = 0; i < rows; i++)
    {
      for (int j = 0; j < cols; j++){
        System.out.print(ArrayToBePrinted[i][j]); 
      }
      System.out.println("");
    }
    
  }
}
