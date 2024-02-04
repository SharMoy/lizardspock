create the boxes for how it looks
create the header
create the rock paper scissors lizard spock buttons
create view for the contest
create an onclick event for the rock paper scissors lizard spock
hide buttons and show the winner on click button
figure out what the computer is going to pick math.random?
display score / compare results

<!--this was under title-->

Score
  Rules

  You Picked
  The House Picked

  You Win
  You Lose

  Play Again

 <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>

 .hands {
    background-image: url("assets/images/pentagon.svg");
    width: 200px;
    height: 400px;
    display: flex;
    flex-wrap: wrap;
    margin-top: 100px;
} 


src="assets/images/bg-pentagon.svg"

.choice-btn[data-choice="paper"] {
    grid-area: paper;
  }
  .choice-btn[data-choice="scissors"] {
    grid-area: scissors;
  }
  .choice-btn[data-choice="rock"] {
    grid-area: rock;
  }
  .choice-btn[data-choice="lizard"] {
    grid-area: lizard;
  }
  .choice-btn[data-choice="spock"] {
    grid-area: spock;
  }
  