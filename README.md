# path_to_the_file
import java.io.*;
import java.io.File;
public class path_to_file{
public static void main(String[] args){
File file =new File("C:" + File.separator + "java" +File.separator" + "abc.txt" );
System.out.println(" File path =",file.getPath());
}
}
