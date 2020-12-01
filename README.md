```elixir
# Feel free to reach out to me @ petter.hoegmo.kaspersen@gmail.com if you have any questions

%Person{
  :name => "Petter",
  :tech => [
      "JavaScript/Node.js", "React", "Next.js", "Elixir", 
      "Phoenix", "Python", "HTML5", "CSS/SCSS", 
      "Angular", "Vue", "Django", "Flask"
  ],
  :experience => [
      %Company{
        :name => "APCOA Parking",
        :from => "November 2020",
        :to => Date.utc_now(),
        :role => "Full-stack developer"
      },
      %Company{
        :name => "VG",
        :from => "March 2019",
        :to => "November 2020",
        :role => "Full-stack developer"
      },
      %Company{
        :name => "Nettrakett",
        :from => "September 2017",
        :to => "March 2019",
        :role => "Web developer"
      }
  ],
  :education => nil
}
```
