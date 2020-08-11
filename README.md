```elixir
%Person{
  :name => "Petter",
  :tech => ["JavaScript/Node.js", "React", "Next.js", "Elixir", "Phoenix", "Python", "HTML5", "CSS/SCSS"],
  :experience => [
      %Company{
        :name => "VG",
        :from => "March 2019",
        :to => Date.utc_now,
        :role => "Full-stack developer"
      },
      %Company{
        :name => "Nettrakett",
        :from => "September 2017",
        :to => "March 2019",
        :role => "Web developer"
      }
  ]
}
```
