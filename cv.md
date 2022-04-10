# Krzysztof Rykowski

## Contact
- E-mail: **rykowski.krzysztof@gmail.com**
- [GitHub](https://github.com/chrisryk)

## About myself
My main goals are learning and developing programming skills in C#, SQL and web applications to be a full-stack develeper and work with HTML, CSS, JavaScript and ASP.NET.

## Skills
Basic knowledge:
- C#
- JavaScript
- HTML
- CSS
- SQL, PL/SQL
- Git, GitHub
- Visual Studio 2022, Visual Studio Code

## Code example

```
public static class DiffieHellman
    {
        public static BigInteger PrivateKey(BigInteger primeP)
        {
            Random random = new Random();
            return random.Next(1, (int)primeP);
        }

        public static BigInteger PublicKey(BigInteger primeP, BigInteger primeG, BigInteger privateKey) =>
            BigInteger.Pow(primeG, (int)privateKey) % primeP;

        public static BigInteger Secret(BigInteger primeP, BigInteger publicKey, BigInteger privateKey) =>
            BigInteger.Pow(publicKey, (int)privateKey) % primeP;
    }
```
## Experience
No experience yet.
## Education
10.2021 - present\
University of Lodz - Information Technologies - postgraduate studies

Udemy - HTML, CSS, JavaScript, C#
## Languages
- English B2
- Polish native
