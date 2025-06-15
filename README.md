![](https://skillicons.dev/icons?i=apple,neovim,java,gradle,mysql)

# Hi, I'm Harrison

```java
public class Profile {
	private String name;
	private String discipline;
	private university uni;

	public Profile() {
		this.name = "Harrison";
		this.discipline = "Software Engineering";
		this.uni = university.RMIT;
	}

	@Override
	public String toString() {
		return "Hi, I'm " + this.name + ". I'm currently studying " 
            + this.discipline + " at " + this.uni + ".";
	}

	public static void main(String[] args) {
		Profile me = new Profile();
		System.out.println(me.toString());
	}
}
```

```bash
➜  harrisonablack git:(main) javac Profile.java
➜  harrisonablack git:(main) java Profile

Hi, I'm Harrison. I'm currently studying Software Engineering at RMIT.
```
