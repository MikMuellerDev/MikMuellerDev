### Hi there 👋

```rust
struct Portfolio;

impl Portfolio {
    const NAME: &'static str = "Mik Müller";
    const PROFILE: &'static str = "Student";
    const LOCATION: &'static str = "Germany, Europe";
    const EXPERIENCE: &'static str = "2+ years";
}

struct Skills;

impl Skills {
    const LANGUAGES: [&'static str; 6] = ["Rust", "JavaScript", "Python", "Java", "HTML / CSS"];
    const OPERATING_SYSTEM: &'static str = "Arch Linux";
    const DEVOPS: [&'static str; 4] = ["Docker", "Debian", "Portainer", "Ansible"];
    const WEB_FRAMEWORKS: [&'static str; 3] = ["Flask", "ExpressJS", "Rocket"];
}
```
