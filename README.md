# 🧺 MCO3 - Laundry Hub  
**Group 5**

**Developers:**  
- Keira Alcantara  
- Reina Althea Garcia  
- Miko Santos  
- Alliyah Zulueta  

---

## About the Project  
Laundry Hub is a review-based web application that allows users to:
- Locate laundry services
- Leave reviews and ratings
- Like other users’ reviews

User Features:
- Must create an account before accessing interactive features
- Can like or post reviews only after logging in

Owner Features:
- Edit shop info
- Shop owners can respond to user reviews

---

## 📦 Install Instructions
To get started, run the following commands in your terminal:
```bash
npm init -y
npm i express express-handlebars express-fileupload body-parser mongoose bcrypt passport passport-local connect-mongodb-session express-flash express-session cookie-parser
```

For importing the JSON files into MongoDB, there's a function that automatically handles it. Ensure that upon the initial run, there are no existing Laundry_Shop databases in the MongoDB database to ensure that the JSON files are updated. 
This is because the function, when it detects that the database and its schema already exist, will not add any more data.

Common Project Heirarchy\
  Project Folder\
    = views (required for handlebars)\
        = layouts\
        = partials\
    = public (images, js, css)\
    = node_modules\
    = node.js\
    = package.json\
  
