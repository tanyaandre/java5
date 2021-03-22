## **Код для подсчета бонуса**

    public class Main {
        public static void main(String[] args) {
            int payment = <ñóììà ïëàòåæà>;
            int bonus;
            if(payment >= 1000){
                bonus = payment / 100;
            } else {
                bonus = 0;
            }
            System.out.println(bonus);

        }
    }
