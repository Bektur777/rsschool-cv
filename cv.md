# Ulanbekov Bektur
## Contacts
* **Location:** Kyrgyzstan, Bishkek
* **Phone number:** +996 700 69 62 95
* **E-mail:** ubei003@mail.ru
* **Github:** Bektur777
## About me
My name is Bektur I am 18 years old. I am currently studying at the Kyrgyz-German Institute of Applied Informatics in the direction of web informatics. In the future I want to become a full-stack developer and develop different applications and websites.
## Skills
* HTML/CSS Basics
* Python, Java, SQL
* JavaScript Basics
* Django Basics
## Code example:
```
interface HabitsToSleep {
    void howSleep();
}

interface Human extends HabitsToSleep {

}

class Father implements Human {

    public void howSleep() {
        System.out.println("In right side");
    }

}

class Mother implements Human {

    @Override
    public void howSleep() {
        System.out.println("In left side");
    }

}

public class Bed {

    public static void main(String[] args) {

        for (int i = 0; i < 10; i++) {
            HabitsToSleep random = seeWhoSleeping();
            assert random != null;
            random.howSleep();

        }

    }

    public static HabitsToSleep seeWhoSleeping() {

        int a = (int) (Math.random() * 2 + 1);

        if (a==1) {
            return new Mother();
        }
        if (a==2) {
            return new Father();
        }
        return null;
    }

}
```

## Education
Kyrgyz-German Institute of Applied Informatics
## English level
B1