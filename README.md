### 👋 Hi there, I'm Tom

```Ruby
class Me < SoftwareDeveloper
  
  def initialize
    @name = "Tom Musselman"
    @pronouns = ["He", "Him"]
    @technologies = {
      languages: ["Ruby", "JavaScript", "Python", "HTML/CSS", "SQL/PostgreSQL],
      frameworks: ["Rails", "React"],
      tools: ["Git/GitHub", "CI/CD", "Heroku"],
      testing: ["RSpec", "VCR/Webmock"]
    }
    @linked_in = "https://www.linkedin.com/in/tmussel/"
    @portfolio = ~~~"https://www.tommusselman.com"~~~
    @status = "Seeking Employment"
    super
  end
  
  def contact(message)
    ContactMailer.send(message, "tmusselman@gmail.com")
  end
  
end
```
