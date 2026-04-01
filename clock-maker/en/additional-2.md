<p style="text-align: right">
  <a href="https://ptmpn.github.io/interview-challenge/clock-maker/th/additional-2">ไทย</a>
  |
  <a href="https://ptmpn.github.io/interview-challenge/clock-maker/en/additional-2">English</a>
</p>

---

# Clock Maker +2

The latest analog clock models not only display time in seconds but also feature "sweeping" hands to reduce noise. Each hand moves slightly every millisecond, with 1,000 milliseconds making up one second. Write a function to calculate the degrees of the hour hand, minute hand, and second hand at a given input time, displaying the degree of each hand to five decimal places.

## Test Cases

```ruby
30 / 3600
clock_arms_radius("09:00:30.500")
> [270.25416, 3.055, 183]

clock_arms_radius("09:30:45.700")
> [285.38083, 184.57, 274.2]

clock_arms_radius("12:10:10.200")
> [5.08466, 61.02, 61.2]

clock_arms_radius("20:41:52.292")
> [260.93543, 251.2292, 313.752]
```

---

[< Prev](https://ptmpn.github.io/interview-challenge/clock-maker/th/additional-1)
