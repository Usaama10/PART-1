import java.util.ArrayList;
import java.util.Collections;
import java.util.List;

import java.util.regex.Pattern;
import javax.swing.JOptionPane;

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/GUIForms/JFrame.java to edit this template
 */

/**
 *
 * @author 
 */
public class RegisterAndLogin extends javax.swing.JFrame {

    /**
     * Creates new form RegisterAndLogin
     */
    
    //Declare Variables
    public boolean con1 = true;
    public boolean con2 = true;
    
    
    //Declare Array List
    ArrayList<Integer> ID = new ArrayList<>();
    ArrayList<String> Username = new ArrayList<>();
    
    ArrayList<String> FirstName = new ArrayList<>();
    ArrayList<String> LastName = new ArrayList<>();
    
    ArrayList<String> Password = new ArrayList<>();
    
   boolean requirement1;
   boolean requirement2;
   boolean requirement3;
   boolean requirement4;
   boolean requirement5;
   boolean requirement6;
   boolean requirement7;
   
    int C = -1;
    
    private String username; // private = restricted access

  // Getter
  public String getUsername() {
    return username;
  }

  // Setter
  public void setUsername(String newuserName) {
    
      
      this.username = newuserName;
  }
  
  private String Fname; // private = restricted access

  // Getter
  public String getFName() {
    return Fname;
  }

  // Setter
  public void setFName(String newFName) {
    this.Fname = newFName;
  }
  
  private String Lname; // private = restricted access

  // Getter
  public String getLName() {
    return Lname;
  }

  // Setter
  public void setLName(String newLName) {
    this.Lname = newLName;
  }
  
  private String pass; // private = restricted access

  // Getter
  public String getPass() {
    return pass;
  }

  // Setter
  public void setPass(String newpass) {
    this.pass = newpass;
  }
