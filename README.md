## Hi there 👋
<img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=FFFFFF"/>
<img src="https://img.shields.io/badge/-C%23-000000?logo=Csharp&style=flat"/>

![](https://profile.renyaa.com/counter/kingjangjo)

```csharp
using UnityEngine;

public class DeveloperProfile : MonoBehaviour
{
    string name = "Jimin Lee";
    string role = "Game Developer";
    string language = "C#";

    string[] skills =
    {
        "Unity",
        "C#",
        "Game Development",
        "Git"
    };

    string[] interests =
    {
        "Casual Game Development",
        "Game Systems",
        "Gameplay Programming",
    };

    void Start()
    {
        Debug.Log("Hello, I'm " + name);
        Debug.Log("I develop games using " + language + " and Unity.");
        Debug.Log("Currently interested in building casual games and improving gameplay systems.");
    }
}
```
