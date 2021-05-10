# Test

```java
public class CashbackHackServiceTest {
    @Test
    public void testRemainAmount1000() {
        CashbackHackService service = new CashbackHackService();
        int actual = service.remain(1000);
        int expected = 0;
        assertEquals(actual, expected);
    }
}
```