---
layout: project
type: project
image: img/cotton/dicegame.png
title: "Dice Game"
date: 2024-05-01
published: true
labels:
  - Javascript
  - Homework
summary: "For one of my homework assignments in ICS111, I had to code a dice game with a user panel."
---

As a mandatory assignment, I was tasked with creating a dice game using JavaScript and Eclipse IDE, complete with user panels, name and score inputs, and dice images. It was a project that was due towards the end of the semester, so it used a lot of programming techniques we learned over the course of several months. It was also an individual assignment, so we had to complete the game alone.

This was one of the first big coding projects I undertook, and I remember feeling somewhat overwhelmed at how many different parts the project required. A lot of time-management was also needed, as the assignment was longer than average and could not be made the night before. 

To complete the dice game, I created several files organizing each of the functions needed for the project, such as (but not excluding) the user interface to input player names and the desired score, the code to generate a two random sets of numbers between 1-6, and the images of the dice. Then I referenced each function in one file to execute everything in the desired manner. Creating the dice images and a visual user interface was the most difficult, because in order to generate an image you need to give Eclipse the exact measurements in accordance to the window. Thankfully, I managed to finish the project on-time and receive full credit for a successful dice game.

Here is some sample code of the file named TwoDicePigPanel.java
<hr>

<pre>
  /**
   * Creates a panel to play the game.
   */
  public TwoDicePigPanel() {
    String player1Name = JOptionPane.showInputDialog(this, "Enter Player 1's name: ");
    this.p1 = new PlayerPanel(player1Name);
    String player2Name = JOptionPane.showInputDialog(this, "Enter Player 2's name: ");
    this.p2 = new PlayerPanel(player2Name);
    this.currentPlayer = p1;
    this.dice = new DicePanel();
    this.roll = new JButton("Roll");
    roll.addActionListener(new ButtonListener());
    this.hold = new JButton("Hold");
    hold.addActionListener(new ButtonListener());
    this.turnLabel = new JLabel("", JLabel.CENTER);
    this.turnScore = 0;
    this.winTotal = 100;
    this.turnLabel.setText(getTurnText());

    this.turnLabel.setText("The game will be starting...");
    setLayout(new BorderLayout());
    add(p1, BorderLayout.WEST);
    add(p2, BorderLayout.EAST);
    add(dice, BorderLayout.CENTER);
    JPanel panel = new JPanel();
    panel.setLayout(new BorderLayout());
    panel.add(roll, BorderLayout.WEST);
    panel.add(turnLabel, BorderLayout.CENTER);
    panel.add(hold, BorderLayout.EAST);
    add(panel, BorderLayout.SOUTH);
  }
</pre>

<hr>
