# FastScanner
PrintWriter output&amp;BufferedReader input  
Use     
&emsp;&emsp;FastScanner in=new FastScanner(System.in);  
&emsp;&emsp;PrintWriter out = new PrintWriter(System.out);
    
For example

    public static void main(String[] args) {
        FastScanner in=new FastScanner(System.in);
        PrintWriter out = new PrintWriter(System.out);//import java.io.PrintWriter
        int a=in.nextInt();
        out.println(a);
        out.close();//This line is a must 
    }  
