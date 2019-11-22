# hello-word
public static String test1(String str){
  char[] ch = new char[str.length()];
  for(int i=0;i<str.length();i++){
    ch[i] = str.charAt(str.length()-1-i);
  }
  return String valueOf(ch);
 }
 public static void main(String[] args){
    Scanner scanner = new Scanner(System.in);
    System.out.print("请输入字符串：")；
    String str = scanner.next();
    str = test1(str);
    System.out.print(str);
    
 }
