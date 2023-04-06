# chaitu.cs

using System;
class user
{
    private string name;
    private string location;
    public string Name
    {
        get { return name; }
        set { name = value; }
    }
    public string Location
    {
        get { return location; }
        set { location = value; }
    }
}

class program
{
    static void Main(string[] args)
    {
        user u = new user();
        u.Name = "Test";
        u.Location = "chn";
        Console.WriteLine(u.Name);
        Console.WriteLine(u.Location);
        Console.ReadLine();

    }
}
