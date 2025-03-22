# remindersystem.java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;

public class ReminderSystemTest {
    @Test
    public void testNotifyUser() {
        ReminderSystem reminder = new ReminderSystem(60, 120);
        reminder.notifyUser("break");
        reminder.notifyUser("exercise");
    }
}
