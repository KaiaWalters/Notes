## CSharp Notes 

### DateTime 

    var dt = new DateTime()


### Verify if a character is a letter or a number or anything else. 

    class MainClass {
    public static void Main (string[] args) {
        char c = '7';
        bool isVowel = "aeiouAEIOU".IndexOf(c) >= 0;
        bool isInt = "1234567890".IndexOf(c) >= 0;
        Console.WriteLine (isInt);
    }
    }

