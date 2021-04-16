# Assignment



using System;
using System.IO;
using System.Linq;
using System.Web;
using System.Collections.Generic;
using System.Globalization;
using System.Configuration;

namespace CSharp_Shell
{

    public static class Program 
    {
    	public static void Main(String[] args){
    		
    		
       
      Console.WriteLine("Product Complaint Management System");
  
      
      Console.Write("Complaint No.:");
      Console.ReadLine();
      Console.Write("Date: ");
      Console.ReadLine();
      Console.Write("Name: ");
      Console.ReadLine();
      Console.Write("Telephone No.:");
      Console.ReadLine();
      Console.Write("Person Called:");
      Console.ReadLine();
      Console.Write("Complaint Details:");
      Console.ReadLine();
    
      
    
    
    Console.Write("Press Y to submit or N to cancel:");
     Console.ReadLine();
     char ab= char.Parse(Console.ReadLine());
      
      
      
      if (ab=='Y')
      {
      	Console.WriteLine("Submitted");
      	
      	
      }else if(ab=='N'){
      	
      Console.Write("Complaint No.:");
      Console.ReadLine();
      Console.Write("Date: ");
      Console.ReadLine();
      Console.Write("Name: ");
      Console.ReadLine();
      Console.Write("Telephone No.:");
      Console.ReadLine();
      Console.Write("Person Called:");
      Console.ReadLine();
      Console.Write("Complaint Details:");
      Console.ReadLine();
      }
      
      else{
      	Console.WriteLine("Invalid input");
      }
      
    
      
      }
      
    	}
    }
