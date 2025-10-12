## Steps that I followed to run a HelloWorld.java Program on CMD :

1. Installed JDK (Java Development Kit)  
   - Downloaded and installed JDK 25 from Oracle’s official website.  
   - Added the JDK bin path to the system environment variables.

2. Checked Installation  
   - Verified Java installation using the commands:  
     
     java -version
     javac -version
     

3. Created the Java File  
   - Opened Notepad and wrote the following code:
     java
     public class HelloWorld {
         public static void main(String[] args) {
             System.out.println("Hello, World!");
         }
     }
     
   - Saved the file as HelloWorld.java on the Desktop.

4. Opened Command Prompt  
   - Used the command to go to the file location:
     
     cd Desktop
     

5. Compiled the Program  
   - Typed:
     
     javac HelloWorld.java
     
   - This generated a new file named HelloWorld.class.

6. Ran the Program  
   - Executed the class file using:
     
     java HelloWorld
     

7. Output Displayed
