import java.io.FileNotFoundException;
import java.io.FileOutputStream;
import java.io.PrintWriter;

public class Jala {
	public static void main(String[] args) throws FileNotFoundException {
		FileOutputStream fos = new FileOutputStream("myfile.txt");
        PrintWriter pw = new PrintWriter(fos);
        pw.println("Sai");
        pw.println(55);
        pw.println("Byee!!");
        pw.close();
    }
}
