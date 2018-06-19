---
title: BattleCode 2018
published: true
---

A bot I made for the 2018 BattleCode competition. Hosted annually by MIT at a chance to fight for a chance at $50,000 in prizes.

The bot that I created:
[Github link](https://github.com/chrischapman82/BattleCode2018).

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)What is Battlecode?
Battlecode is a real-time strategy game, for which you will write an AI player. In Battlecode, two teams of virtual robots roam the screen managing resources and executing different offensive strategies against each other. Your AI player will need to strategically manage your robot army and control how your robots work together to defeat the enemy team. As a contestants, you will learn to use artificial intelligence, pathfinding, distributed algorithms, and network communications to make your player as competitive as possible.

Related information about BattleCode 2018:
[BattleCode Website](https://www.battlecode.org/#/)
[Project specs](https://s3.amazonaws.com/battlecode-2018/specs/battlecode-specs-2018.html)


## [](#header-2)Unit BreakPoints
Spread sheet looking at unit cost and damage breakpoints.

[Unit Breakpoints](https://drive.google.com/file/d/1NOH2xxM89EaEMuqX00Z1wZpqstE9W_d9/view?usp=sharing)
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Reflections:

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   Used A star to create a static map to overcome bit limits.
*   This year was high
*   This is an unordered list following a header.

##### [](#header-5)Reflections:
In this process, due to the time limits, I learnt how to use A-star effectively. I also used Breadth First Search to create several maps containing directions from each square to key destinations.

Unfortunately, this year was not as well organised as the previous year. This lead to a frustrating time, where ovver the weeks competitors had to deal with:
1.  Having no replay system for the first 2 of 3 weeks. This made it hard to get good feedback on how the bot was performing. Thankfully, another student created an open source a replay viewer.
2.  Documentation was never written, making understanding the code very arduous.
3.  Docker problems plagued me throughout the tournament. I lost 2 days cumulative in patching, updating, clearing, removing and re-installing docker to run the BattleCode scaffold.
4.  Massive unit balance changes were implemented 2 days before the final international tournmanent, doubling unit build times, and making my rushing strategies much weaker. 
