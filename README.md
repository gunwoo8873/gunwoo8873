```rust
struct Datatype {
    name : String,
    age : i32,
    email : String,
    address : String,
    skill : String,
    count : u64,
    ative : bool,
}

fn main() {
    user_info();
}

fn user_info() {
    let user = Datatype {
        name : String :: from("choigunwoo"),
        age : 27,
        email : String :: from("gunwoo8873@outlook.kr"),
        address : String :: from("seoul"),
        skill : String :: from("Shell, Powershell, Rust"),
        count : 1,
        ative : true,
    };

    println!("name : {}", user.name);
    println!("age : {}", user.age);
    println!("email : {}", user.email);
    println!("address : {}", user.address);
    println!("skill : {}", user.skill);
    println!("count : {}", user.count);
    println!("ative : {}", user.ative);
}
```
[notion](https://gunwoo8873.notion.site/Home-815249bf872b4cabb900895ad0dd31ff?pvs=4)
<!--
**gunwoo8873/gunwoo8873** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
