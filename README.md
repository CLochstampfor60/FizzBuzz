# FizzBuzz

    public string FizzBuzz(int number)
    {
        var answer = "";

        if (number % 3 == 0)
        {
            answer = "Buzz: Your number is divisble by 3.";
        }
        if (number % 5 == 0)
        {
            answer += "Fizz: your number is divisible by 5.";
        }
        return answer;
    } 
