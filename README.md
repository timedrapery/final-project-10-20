# Oct 2020 Cohort Final Project

## **Minimum Viable Product (MVP) Iteration #1**

### **FRAMING SESSION**

- *Who*: Students

- *What*: Record and track assignments

- *When*: Anytime

- *Where*: The internet

- *Why*: To better plan and prepare for coursework

### **TIME, COST/PRIORITY, SCOPE (TCS)**

- TIME: **6** *hours*, **0** *minutes*

- COST/PRIORITY: **$0.00**

  - **Scale**:

    - **H** - *High*
    - **M** - *Medium*
    - **L** - *Low*

- SCOPE:

  - **Scale**:

    - **C** - *Comfortable*
    - **N** - *Need assistance*
    - **X** - *No idea*

### **FEATURES LIST**

- *Create a task* - John inputs an assignment and upon clicking "Add", it appears on John's screen.

  - [**T**: 30 *mins*; S: **C**, P: **H**]

- *Complete a task* - when John completes an assignment, it's added to a "Completed" list or strikethrough styling is applied to the text.

  - [**T**: 45 *mins*; S: **N**, P: **M**]

- *Updating a task* - John made a mistake and needs to fix the assignment they entered.

  - [**T**: 30 *mins*; S: **N**, P: **M**]

- *Delete a task* - John finds out his instructor has determined an assignment won't be turned in so he wants to clear his assignment list
  - [**T**: 30 *mins*; S: **C**, P: **M**]

- Order of list - time vs priority.

  - [**T**: 2 *hours*; S: N, P: H]

### **CONSIDERATION(S)**

- Mobile friendly or mobile only

  - [**T**: 1 *hour* **S**: *C*]

### **MVP**

*Develop a web application that allows creation of tasks and the display of these tasks as a prioritized list.*

- **Create an assignment** - John inputs a task and upon clicking "add", it appears on John's screen.

  - [**T**: 30 *mins*; **P**: *H*; **S**: *C*]

- **Complete an assignment** - when John completes an assignment, completed list or strikethrough.

  - [**T**: 45 *mins*; **P**: *M*; **S**: *N*]

- **Updating an assignment** - John needs to clear the assignment list.

  - [**T**: 30 *mins*; **P**: *M*; **S**: *N*]

### ***POST***-**MVP**

- **Delete a single assignment** - *John should be able to delete assignments one by one*
  - [**T**: 30 *mins*; **P**: *M*; **S**: *C*]

## mockUp

<a href="https://ibb.co/FXmtShq"><img src="https://i.ibb.co/pQbpt1r/assign-Mentor.jpg" alt="assign-Mentor" border="0"></a>

## **pseudoCode**

### **1. if user inputs text in the field**

        Print "user text"
    else
        Print ""

### **2. if user double-clicks a line item**

        apply strikethrough styling
        add the user input text to the "completed" list

### **3. if user clicks "Empty List"**

        clear list

### **4. if user clicks "Save List"**

        store saved list locally

### **5. if user clicks "Clear Completed"**

        clear only the line items with strikethrough syling applied
