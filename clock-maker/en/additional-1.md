<p style="text-align: right">
  <a href="https://ptmpn.github.io/interview-challenge/clock-maker/th/additional-1">ไทย</a>
  |
  <a href="https://ptmpn.github.io/interview-challenge/clock-maker/en/additional-1">English</a>
</p>

---

# Clock Maker +1

An analog clock can provide more precise time by adding a second hand. The second hand moves continuously in a circle, completing a full rotation every 60 seconds. Simultaneously, the minute and hour hands also move slightly with each passing second. Write a function to calculate the degrees of the hour hand, minute hand, and second hand at a given input time, displaying the degree of each hand to three decimal places.

## Test Cases

```ruby
30 / 3600
clock_arms_radius("09:00:30")
> [270.25, 3, 180]

clock_arms_radius("09:30:45")
> [285.375, 184.5, 270]

clock_arms_radius("12:10:10")
> [5.083, 61, 60]

clock_arms_radius("20:41:52")
> [260.933, 251.2, 312]
```

---

[< Prev](https://ptmpn.github.io/interview-challenge/clock-maker/th/main)
|
[Next >](https://ptmpn.github.io/interview-challenge/clock-maker/th/additional-2)
