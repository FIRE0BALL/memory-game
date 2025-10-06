# memory-game
---

# **Project Report: LED Memory Game (Simon Says)**

**Presented at:** Khalsa College Science Festival, November 2024

---

## **1. Introduction**

This project, titled **"LED Memory Game"**, is an interactive electronic game inspired by the classic **"Simon Says"** memory challenge. It was designed and developed to present at **Khalsa College Science Festival held in November 2024**, where we were showcasing Robotics desk form our **Department of Mechanical Engineering, Guru Nanak Dev University**.

The purpose of this project was to demonstrate how simple electronic components and microcontroller programming can be combined to create an engaging and competitive memory-based game. It was well-received at the festival and became one of the main attractions due to its interactive nature and competitive gameplay.

![MEMORYGAMEGIF-min](https://github.com/user-attachments/assets/b4b36331-2fa2-4a01-9632-30e049d89792)

---

## **2. Objective**

The primary objective of this project was:

* To design and implement an interactive **memory game** using **Arduino UNO** and basic electronic components.
* To enhance problem-solving and programming skills by implementing **increasing difficulty levels**.
* To provide a **fun and competitive experience** to visitors while showcasing practical applications of microcontroller-based systems.

---

## **3. Concept and Working Principle**

The LED Memory Game operates on the principle of **pattern recognition and recall**. The Arduino generates a random sequence of LED blinks, and the player must replicate the sequence by pressing the corresponding push buttons.

As the player progresses through levels, the **length and complexity** of the LED sequence increases, thus challenging the memory and concentration of the player.

---

## **4. Components Used**

| Component    | Quantity    | Description                                                            |
| ------------ | ----------- | ---------------------------------------------------------------------- |
| Arduino UNO  | 1           | Microcontroller board used to control LEDs and read input from buttons |
| Breadboard   | 1           | For circuit prototyping and component connections                      |
| LEDs         | 4           | Visual indicators for the blinking sequence                            |
| Push Buttons | 4           | User input to repeat the LED sequence                                  |
| Buzzer       | 1           | Audio feedback for correct/incorrect input                             |
| Jumper Wires | As required | Connections between components and Arduino                             |
| Batteries    | 1 set       | Power supply for Arduino UNO                                           |

---


<img width="1270" height="686" alt="LED memory game" src="https://github.com/user-attachments/assets/6d06a031-54b7-4c5c-94a0-628a1fe1fe4b" />


## **5. Implementation and Methodology**

The project was implemented in the following steps:

1. **Circuit Design:**
   The components were arranged on a breadboard. Each LED was connected to a digital output pin of the Arduino, and each push button was connected to a digital input pin with pull-down resistors.

2. **Programming the Arduino:**
   A program was written in the Arduino IDE to:

   * Generate random LED blinking sequences.
   * Read button inputs from the player.
   * Compare the player's input with the original sequence.
   * Advance to the next level if the sequence is correct or signal a loss if incorrect.

3. **Game Levels:**
   The game was designed with **12 levels**.

   * **Level 1:** The player memorizes and reproduces a single LED blink.
   * **Level 2–12:** With each level, the length of the sequence increases by one, requiring the player to remember more complex patterns.
   * **The game still requires 12 rounds to win, and the player has a 3-second time limit to respond.
  
4. **Feedback System:**
   A **buzzer** was used to give audio feedback:

   * A short beep indicated blink and button pressed.
   * A long beep indicated a mistake and the end of the game.

---

## **8. Conclusion**

The **LED Memory Game** project successfully demonstrated how simple components and programming can come together to create an engaging and educational experience. It was not only a crowd-puller at the science festival but also highlighted the innovative spirit of students from the **Department of Mechanical Engineering, Guru Nanak Dev University**.

The project reinforced key skills in circuit design, programming, and logical problem solving and demonstrated the potential of microcontroller-based systems in real-world applications.

---

## **9. Future Scope**

* Adding an **LCD display** to show level numbers and scores.
* Designing a **custom PCB** and casing for a more professional product-like finish.

---

**Prepared by:**
Gavish Sharma
<img src="[your-image-url](https://github.com/user-attachments/assets/c0c095cf-e222-40c6-91b3-44e0d205206d)" alt="description" width="100" height="75">

---
