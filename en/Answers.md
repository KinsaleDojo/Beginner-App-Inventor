1. Android apps are made of **Screens**. You've created your first question on one **Screen** and you're going to want to add more. You'll put them on new screens, but you need a way of keeping score between those screens. On this card, you'll be adding a **TinyDB** database to keep the score in, and some code to mark the right answer!
2. First, in the **Palette** under **Storage** find the **TinyDB** component and drag it on to the **Viewer**. You won't see anything new there, but *TinyDB1* should appear in the **Components** section.

  ![](/assets/tinydb.png)
3. Now it's time to start putting together the code that will power your quiz! In the top right of the screen, click on the **Blocks** button to access the blocks view.

  ![](/assets/blocks button.png)
4. Just like the previous **Designer** screen, this **Blocks** screen has sections:  
  * **Blocks**—where you pick code blocks
  * **Viewer**—where you drag your code blocks to assemble them
5. There are lots of kinds of code blocks, but you're just going to need a few of them for now. In the **Blocks** section, click on whichever button matches the right answer to your question. For me, it was **Button1**. Grab the `When Button1.Click do` block and drag it onto the viewer.

  ![](/assets/when click.png)
6. Now click on **TinyDB1** and choose the `call TinyDB1.StoreValue` block. Drag it into the last block and then go to the **Built-in** blocks grab the pieces from **Math** and **Text** to make it look like this:
  
  ![](/assets/store score.png)
7. Finally, update the text value to "score" and the number to 1, like this:
  
  ![](/assets/score vals.png)