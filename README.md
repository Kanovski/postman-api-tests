# My Postman Test Project 🚀

Hello! This is a simple project for testing APIs. 

## 📁 What is inside?
Inside this folder, you will find more  thanone special file:
 (This file holds all my API tests!).

---

## 🛠️ How to use this file?

You can open and run these tests in two easy ways:

### Way 1: Inside Postman (Easy)
1. Open your **Postman** application.
2. Click the **Import** button at the top.
3. Choose the `.json` file from this folder.
4. Click **Run** to see the magic! 🎉

### Way 2: With Newman (Using Terminal)
If you want to run it like a real programmer in the black screen (Terminal), do this:

1. Install **Node.js** on your computer.
2. Open your Terminal and type this code to install Newman:
   ```bash
   npm install -g newman
   ```
3. Run the tests by typing this code:
   ```bash
   newman run Trello Api Test.postman_collection.json
   ```

That is it! Happy testing! 🎈
