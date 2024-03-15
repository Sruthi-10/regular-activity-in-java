import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    System.out.println("   ----------Given below r my Daily activties--------------");
	    System.out.println("                       1.Wake up");
	    System.out.println("                       2.Walking");
	    System.out.println("                       3.Bathing");
	    System.out.println("                       4.Eating");
	    System.out.println("                       5.Studying");
	    System.out.println("                       6.Playing");
	    System.out.println("                       7.Talking with friends");
	    System.out.println("                       8.Fighting");
	    System.out.println("                       9.Watching mobile phone");
	    System.out.println("                       10.Sleeping");
	    System.out.println("Press any one key from 1 to 10 for Quiting the activity in daily life:");
	    Scanner sc=new Scanner (System.in);
	    int c=0;
	    while(true){
	    int n=sc.nextInt();
	    if(n==0){
	        break;
	    }
	    else{
	    switch(n){
	        case 1:
	            System.out.println("Your wake up activity has been quited!!");
	            c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	            System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	        case 2:
	            System.out.println("Your walking activity has been quited!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	            
	       case 3:
	            System.out.println("!!!!!Your Bathing activity has been quited!!!!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	            
	       case 4:
	            System.out.println("!!!!!Your Eating activity has been quited!!!!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	            
	       case 5:
	            System.out.println("!!!!!Your studying activity has been quited!!!!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	            
	       case 6:
	            System.out.println("!!!!!!Your playing activity has been quited!!!!!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	              break;
	           
	       case 7:
	            System.out.println("!!!!!Your Talking with friends activity has been quited!!!!!!");
	             c++;
	             System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	            
	       case 8:
	            System.out.println("!!!!!!Your fighting activity has been quited!!!!!!");
	             c++;
	             System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	            System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	       case 9:
	            System.out.println("!!!!!!Your watching mobile phone activity has been quited!!!!!");
	             c++;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	       case 10:
	            System.out.println("!!!!!!!Your Sleeping activity has been quited!!!!!!!!");
	             c=c+1;
	              System.out.println("--------------------------------------------------------------");
	        System.out.println(c+" activity has been quited");
	          System.out.println("----------------------------------------------------------------");
	             System.out.println("r u want to quit any ohter activity?");
	             System.out.println("IF yes :");
	             System.out.println("        press any key from 1 to 10");
	              System.out.println("else:");
	               System.out.println("    press 0");
	            break;
	       default:
	       System.out.println("!!!!!!Invalid press!!!!");
	       break;
	    }
	    }
	        
	    }
	    System.out.println("--------------------------------------------------------------");
	      System.out.println("  Atlast total number of daily activities r " +(10-c));
	    System.out.print("----------------------------------------------------------------");
	}
}
