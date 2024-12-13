## Hi i'm Corentin 😶‍🌫️

```cs

class People
{
    public int Age { get; private set; }
    public string FirstName { get; private set; }
    public string LastName { get; private set; }

    public People(int age, string firstName, string lastName)
    {
        Age = age;
        FirstName = firstName;
        LastName = lastName;
    }

    public void Present()
    {
        Console.WriteLine($"Hello, my name is {FirstName} {LastName}. I'm {Age} years old.");
    }
}

People Me  = new People(20, "Corentin", "Nelhomme");
Me.Present();
```
## Language & Tools

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vuejs,nuxtjs,sass,tailwind,bootstrap,express,postgres,prisma,cs" />
  </a>
</p>
