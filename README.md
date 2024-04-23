```java
public class TharinduWijayarathna {
    String[] pronouns = {"he", "him"};
    String[] location = {"Kandy, Sri Lanka"};
    String[] contact = {"wikum.dev@gmail.com"};
    String[] portfolio = {"https://www.wikum.live"};
    String[] collaborations = {"IoT", "Robotics", "Web Apps", "Mobile Apps", "Embedded systems engineering"};
    String[] workingOn = {"Building optimized web apps for every suitable environment"};
    String[] learning = {"Flutter", "Go", "Kotlin"};
    String[] askMeAbout = {"Emerging trends", "Web Development", "Mobile Development", "Robotics", "Tech"};
    Hobbies hobbies = new Hobbies();

    class Hobbies {
        Major major = new Major();
        FunFact funFact = new FunFact();

        class Major {
            String[] indoor = {"Watching TV Series", "Gaming"};
            String[] outdoor = {"Traveling", "Joining Hackathons"};
        }

        class FunFact {
            String[] secret = {"I freaking love music", "dogs"};
        }
    }
}
```
