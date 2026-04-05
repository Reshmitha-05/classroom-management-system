🎯 Objectives

* Understand MongoDB database operations
* Perform CRUD (Create, Read, Update, Delete)
* Apply schema validation using JSON Schema
* Manage collections efficiently

 🧪 Experiments

 🔹 Experiment 1: Collection Operations

* Created `students` collection
* Viewed collections using `show collections`
* Dropped collection

---

 🔹 Experiment 2: Basic Validation

* Applied validation using `$jsonSchema`
* Inserted valid document ✔
* Rejected invalid document ❌

---

 🔹 Experiment 3: Advanced Validation

* Used:

  * Pattern (`^TCH[0-9]{3}$`)
  * Enum (subjects list)
  * Range (minimum salary)

---

🔹 Experiment 4: Modify Collection

* Used `collMod`
* Added validation to existing collection

---

 🔹 Experiment 5: View Validation

* Used `getCollectionInfos()`
* Verified schema rules

---

 🔄 CRUD Operations

### ➕ Insert

* `insertOne()`
* `insertMany()`

### 📖 Read

* `find()`
* Filtering (`class: "10A"`)
* Sorting (`age: -1`)

### ✏️ Update

* `updateOne()`
* `updateMany()`
* `$set`, `$inc`

### ❌ Delete

* `deleteOne()`
* `deleteMany()`
* `drop()`


## 🛠️ Tools Used

* MongoDB Compass
* Mongo Shell (mongosh)
* GitHub

---

 📊 Conclusion

MongoDB provides a flexible and powerful NoSQL database system.
This project demonstrates how classroom data (students, teachers, classes) can be efficiently managed using validation and CRUD operations.



 📎 Academic Details
**Topic:** Classroom Management System
