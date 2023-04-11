      import java.util.Scanner;
      public class sıfre {
    public static void main(String[] args) {
        String userName, password;

                Scanner inp = new Scanner(System.in);
        System.out.println("Kullanıcı Adınız : ");
        userName = inp.nextLine();

        System.out.println("Şifreniz : ");
        password = inp.nextLine();

                if(userName.equals("patika") && password.equals("java123")) {
                    System.out.println("Giriş Yaptınız !");
                } else {
                    System.out.println("Bilgileriniz Yanlış !");
                }
    }
}
