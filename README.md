# lisa-csc491
my capstone assignments codes attached csc 491

Jframe
package uGolf;

import java.awt.Color;
import java.awt.Image;

import javax.swing.JFrame;
import javax.swing.JLabel;

public class ugolfframe<newGridBag> {

	public ugolfframe() {
		// TODO Auto-generated constructor stub
	}
	 

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		JFrame frame = new Jframe();
		frame.setBackground(Color.GREEN);
		JPanel contentPane = new JPanel(newGridBagLayout());
		JLabel golfBallLabel = new JLabel (new Image Icon ("golf_ball.png"));
		golfBallLabel.setActionMap(Bounds(new Rectangle(100,100,50,50)));
		
		// try position golf ball in center using GridBagConstraints
		
		GridBagConstraints c = newGridBag Constraints() {
		c.insets= new Insets(20,20,20,20);
		c.gridx =0;
		c.gridy =0;
			
			ContentPane.add(golfBallLabel, c);
		
		JLabel textLabel = newJLabel("Lisa UGolf Handicap App");
		textLabel.setFontnew Font("Arial", Font.BOLD, 24));
		contentPane.add(text Label);
		
	//I dont know how to fix errors, I can try adding expressions.  This was suppose
		//to be a green background with a spinning golf ball in the middle.   
		
		//next attempt to make scorecards
  package uGolf;

import java.util.Scanner;


public class golfscorecard 

	public static void main(String[] args) {
		 Scanner scanner = new Scanner(System.in);

		 int[] [] scores = new int [4][18];
		 int[] handicaps = new int[4];
		 
		 for (int : = 0; < 4; i++) {
			 	System.out.print("Enter player " + (i + 1) + "'s handicap:");
			 	
			 	handicaps[i] = scanner.nextInt();
		 }
		 		for (int j = 0; j < 18; j++) {
		 			System.out.print("enter player " + (i + 1) + ";s score for hole" + 
		 (i + 1) + " :  ");
		 				scores[i][j] = scanner.nextInt();
		 		 
		 		
		 		//create a database with MySQL  and JDBC driver. should work when I create a user 
		 		//name and password to console.  
		 		
		
		
}
