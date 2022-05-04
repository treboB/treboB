- 👋 Hi, I’m @treboB

publc static void main(String[] args){
  System.out.println("hello I am" + reverseString("treboB")); 

}


public static String reverseString(String s) {
  String newS = "";
  for (int i = s.length() - 1; i >= 0; i--) {
    newS += s.subString(i, i - 1);
  }
  return newS;
}
