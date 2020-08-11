```elixir
%Person{
  :name => "Petter",
  :tech => ["JavaScript/Node.js", "React", "Elixir", "Phoenix", "Python", "HTML5", "CSS/SCSS"],
  :current_job => %Company{
       :name => "VG",
       :since => "March 2019",
       :to => Date.utc_now,
       :role => "Full-stack developer"
  }
}
```
