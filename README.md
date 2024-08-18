# olympics

The point of the Olympics in the modern era is broadly to determine which country is the best at sports, but does it actually do that?

Ever think to yourself "hey, why does judo get 6x more medals than golf just for dividing into weight classes?"

And when an allstar athlete in one sport wins multiple medals in less time than it takes a whole group of athletes to win one medal together in a team sport like basketball, should the country with today's Michael Phelps really get many times the credit?


Well, these Excel files have several ways to measure which country is the best at sports coming out of the Tokyo 2020 Olympic Games:
  - The normal way: number of gold medals
  - The other normal way: total number of medas
  - [2021 only] A weighted medal count (gold 3, silver 2, bronze 1)
  - A weighted medal count with teams getting a medal for every starting athlete
  - [2021 only] Aggregation by sport, like a track meet.  In this method, a country being the best at rugby is equivalent to a country being the best at gymnastics
    - For example, China did the best in the sport of artisitic gymnastics, so they receive one gold medal in this calculation
  - Aggregation by sport and gender.  In this method, a country being the best at women's rugby is equivalent to a country being the best at men's gymnastics
    - For example, Japan did the best in women's skateboarding in 2021, so they receive one gold medal in this calculation, just like Brazil, who did the best in men's skateboarding
    - Medals in mixed events are counted half towards the country's men's tally and half toward it's women's
    - I believe this is the fairest evaluation of which country is the best at sports
    - This measure is also available in 'Olympics Sport Winners Over Time.xlsx', but without attempting to compare across sports (as defined by the Olympics) -- see picture below
    
    
### Does this matter?
Yes.  After receiving only one gold medal in Atlanta in 1996, the UK changed their sports funding strategy to target higher medal count disciplines like rowing.

Other countries like France and the Netherlands are following suit, and seeing their medal counts rise.

But to many people, the winning at team sports is more impressive or more culturally important, and should be funded as such.

If we counted overall Olympic success by sport rather than by event, more funding would be incentivized to go towards team sports.

------
![image](https://github.com/user-attachments/assets/b6ea9420-7f48-41d1-b5c9-46947300cb1f)
