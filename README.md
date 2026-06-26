# E-voting-System-Java
##Features
- Voter registration with CNIC validation  
- Secure login system (Admin & Voter)  
- Admin panel for candidate management  
- Electronic voting system  
- Duplicate vote prevention  
- Real-time result calculation  
- File-based data persistence (Candidates, Voters, Votes)  
- Input validation and exception handling  
- Java Swing GUI interface  

---

## OOP Concepts Used
- Encapsulation (private fields + getters/setters)  
- Inheritance (Person → Voter/Admin)  
- Polymorphism (login method overriding)  
- Abstraction (abstract Person class)  
- Interfaces (Storable, Authenticatable)  
- Modular class structure  

---
##Project Structure
```
src/
├── model/
│ ├── Person.java
│ ├── Voter.java
│ ├── Admin.java
│ └── Candidate.java
├── ui/
│ ├── MainMenu.java
│ ├── AdminPanel.java
│ ├── VotingPage.java
│ └── LoginScreens...
├── service/
│ └── FileService.java
├── manager/
│ └── VoterManager.java
└── main/
└── EVotingSystemFinal.java
```

---


##Data Storage
- Candidates.txt → Candidate records  
- Voters.txt → Voter records  
- Votes.txt → Vote records  

---
