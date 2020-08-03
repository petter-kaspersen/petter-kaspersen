```elixir
%Person{
  :name => "Petter",
  :languages => ["JavaScript", "Elixir", "Python", "HTML5", "CSS/SCSS"],
  :current_job => %Company{
       :name => "VG",
       :since => "March 2019",
       :to => Date.utc_now,
       :description => "TODO"
  }
}
```
