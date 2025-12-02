# <p style="text-align: center;">🌷 ｡･ﾟﾟ･ UniBookmark Manager ･ﾟﾟ･｡ 🌷</p>
<p style="text-align: center;">Your cozy console-based bookmark keeper ♡</p>

<p align="center">

             _ _                 _                         _    
 /\ /\ _ __ (_) |__   ___   ___ | | ___ __ ___   __ _ _ __| | __
/ / \ \ '_ \| | '_ \ / _ \ / _ \| |/ / '_ ` _ \ / _` | '__| |/ /
\ \_/ / | | | | |_) | (_) | (_) |   <| | | | | | (_| | |  |   < 
 \___/|_| |_|_|_.__/ \___/ \___/|_|\_\_| |_| |_|\__,_|_|  |_|\_\

</p>

<p style="text-align: center;">CS-2105</p>
<p style="text-align: center;">Bacay, Kotnie Edrae L.</p>
<p style="text-align: center;">Dadap, Amber Loveine R.</p>
<p style="text-align: center;">Derez, Eume C.</p>

---

### ✿˚｡⋆ Overview
UniBookmark Manager is a simple console program that helps users organize their reading progress.  
You can add, view, update, and delete bookmarks right from the terminal.It's perfect for tracking mangas, novels, and textbooks in one place!

This project demonstrates key **Object-Oriented Programming (OOP)** concepts such as **abstraction, inheritance, encapsulation**, and **polymorphism** through multiple book types.

With UniBookmark, users can:
 📚 Add bookmarks for **Manga**, **Novel**, or **Textbook**  
 🌸 View a neatly listed collection of bookmarked readings  
 🖊️ Update reading progress or creator details  
 🗑️ Delete bookmarks you no longer need  

#### Bookmark Storage  
🪄 All bookmarks are stored in memory using **`ArrayList<Book>`** while the program runs.

---

### 🐚˚｡⋆ Project Structure

📂 src/
└── 📂 UniBookMark/
🍃 Main.java — Main menu, user input, and program flow
🌼 Book.java — Abstract parent class for all bookmark types
🌸 Manga.java — Subclass with an added 'artist' field
📖 Novel.java — Subclass with an added 'author' field
📘 Textbook.java — Subclass with an added 'subject' field

 _____

### How to Run the Program
-Open your terminal inside the `src/` folder and compile the Java files:


`javac unibookmark/*.java`

-Then run the program:


`java unibookmark.Main`


---

### 🌸˚｡⋆Features
 ✨ **Add Bookmark**  
Choose whether you're saving a *Manga*, *Novel*, or *Textbook*, then enter its details.

 🌷 **View Bookmarks**  
Lists all saved bookmarks and automatically displays the correct details for each book type.

 🪶 **Update Bookmark**  
Modify the title, page, chapter, or unique attributes (artist/author/subject).

 💌 **Delete Bookmark**  
Remove any bookmark permanently based on its number.

---

### 🫧˚｡⋆Object-Oriented Principles

#### 💞 Encapsulation
Fields like title, page, chapter, artist, author, and subject are private and accessed through getters and setters.

#### 🌿 Abstraction
`Book` acts as a blueprint for all bookmarks, defining shared properties and the abstract `displayInfo()` method.

#### 🌼 Inheritance
`Manga`, `Novel`, and `Textbook` extend `Book`, inheriting and enhancing its structure.

#### 🌈 Polymorphism
Bookmarks are stored inside **`ArrayList<Book>`**.  
Calling `displayInfo()` automatically runs the correct version for the object type.

---

### 🌷˚｡⋆ Sample Output
--- Bookmark Manager ---
1. Add Bookmark
2. View Bookmarks
3. Update Bookmark
4. Delete Bookmark
5. Exit
Choose an option: 1

Choose type of bookmark:
1. Manga
2. Novel
Enter type: 1

Enter title: One Piece
Enter page number: 88
Enter chapter number: 1050
Enter artist: Eiichiro Oda

Bookmark for "One Piece" is added!

--- Bookmark Manager ---
Choose an option: 2

Bookmark #1
Title: One Piece (Manga)
Page: 88, Chapter: 1050
Artist: Eiichiro Oda

---

#### 🌼˚｡⋆ Contributors

<table>
<tr>
    <th> &nbsp; </th>
    <th> Name </th>
</tr>
<tr>
<td><img src="static/Kotnie%20Edrae%20L.%20Bacay.jpg" width= "100px" height= "100px"> </td> 
<td><strong>Bacay, Kotnie Edrae L.</strong><br/>
</tr>
<tr>
<td><img src ="static/Amber%20Loveine%20R.%20Dadap.jpg" width="100px" height="100px"></td>
<td><strong>Dadap, Amber Loveine R.</strong></td>
</tr>
<tr>
<td><img src="static/Eume C. Derez.jpg" width="100px" height="100px"> </td>
<td><strong>Derez, Eume C.</strong></td>
</tr>
</table>

_________________

#### 🍀˚₊· Acknowledgment

 We would like to express our gratitude to our most coquette soft girly instructor Ma’am Fatima Marie P. Agdon. We would like to extend our gratitude to our pets, Cotton Buds, Harris, Mingming, Mongmong, and Rado for their support throughout this project.  
