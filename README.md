## 🧭 5-Day Java Console Adventure: *Mystery Dungeon Quest*

This week, you'll build a fun little **dungeon game** in Java. Each day adds a small piece. Your goal is to create a text-based adventure game with choices, treasure, and maybe even a trap or two!

---

### 📅 **Day 1: Meet the Hero**

#### 🎯 Objective:

Learn how to use `Scanner`, `String`, and `print/println` to greet the player.

#### 🛠 Instructions:

1. Create a new Java file called `DungeonGame.java`.

2. At the top of your `main`, ask the player:

   * “What is your name?”

3. Save their name using a `String` variable.

4. Print a welcome message using their name. Example:

   ```
   Welcome to the Mystery Dungeon, Alex!
   ```

5. Then ask:

   * “What is your favorite animal?”
   * “What number would you wear on your jersey?”

6. Save the answers and print something like:

   ```
   You are now Alex the Tiger, wearing jersey #7. Let's begin!
   ```

#### ✅ Submission:

Take a screenshot of your console showing your welcome messages and submit your `.java` file.

---

### 📅 **Day 2: Enter the Dungeon!**

#### 🎯 Objective:

Learn how to use `int` variables and show simple status screens.

#### 🛠 Instructions:

1. Add two `int` variables:

   * `health = 100`
   * `treasure = 0`

2. After your greeting from Day 1, print:

   ```
   You enter the dungeon with 100 health and 0 treasure.
   ```

3. Ask the player:

   * “How many gold coins do you see on the ground?”

4. Let the player type a number, store it in `int coins`, and add it to their `treasure`.

5. Print:

   ```
   You now have [treasure] treasure!
   ```

#### ✅ Submission:

Make sure your game prints the updated treasure amount. Share your updated `.java` file!

---

### 📅 **Day 3: Choose Your Path (First `if` Statement!)**

#### 🎯 Objective:

Learn how to use an `if` statement to make a decision.

#### 🛠 Instructions:

1. Ask the player:

   * “Do you go left or right?” (store answer as `String`)

2. Use `if` to check the answer:

   ```java
   if (choice.equals("left")) {
     // Print something cool
   } else {
     // Print something funny or spooky
   }
   ```

3. If they go left:

   * Print: “You find a friendly wizard who gives you 50 treasure!”
   * Add 50 to `treasure`.

4. Else (they go right):

   * Print: “Oops! You fall into a trap and lose 30 health.”
   * Subtract 30 from `health`.

5. Print updated health or treasure.

#### ✅ Submission:

Share your updated file and test both "left" and "right" choices!

---

### 📅 **Day 4: The Potion Room**

#### 🎯 Objective:

Add a second decision and track player status.

#### 🛠 Instructions:

1. Print:

   ```
   You find a glowing potion on a pedestal.
   ```

2. Ask:

   * “Do you drink the potion? (yes/no)”

3. Use another `if`:

   * If yes: add 20 health (but max is 100).
   * If no: print “You save it for later.”

4. Use `if (health > 100)` to make sure health doesn’t go above 100.

5. Print updated health:

   ```
   Your current health is now: [health]
   ```

#### ✅ Submission:

Test both “yes” and “no.” Share your `.java` file and console output.

---

### 📅 **Day 5: The Final Gate**

#### 🎯 Objective:

Use everything you’ve learned to make a mini ending.

#### 🛠 Instructions:

1. Ask the player a final riddle:

   ```
   What has keys but can’t open locks?
   ```

2. Get the answer. If it’s “piano” (case-insensitive), print:

   ```
   You solved the riddle! The dungeon gate opens. You win!
   ```

3. Else, print:

   ```
   Wrong answer! You're trapped forever... (just kidding)
   ```

4. Finally, print:

   ```
   Game Over. You finished with [health] health and [treasure] treasure.
   ```

#### ✅ Submission:

Test your final boss riddle and submit your finished `DungeonGame.java`!

---
