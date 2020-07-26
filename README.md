```elixir
%Person{
  :name => "Petter",
  :languages => ["JavaScript", "Elixir", "Python", "HTML5", "CSS/SCSS"],
  :experience => [
    %Company{
       :name => "VG",
       :since => "March 2019",
       :to => Date.utc_now,
       :description => "TODO"
    },
    %Company{
      :name => "Nettrakett",
      :since => "October 2017",
      :to => "March 2019",
      :description => "TODO"
    }
  ],
  :tech => [
    "TODO"
  ]
}
```
