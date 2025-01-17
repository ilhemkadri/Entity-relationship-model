**Slide 1: Introduction**

**Title:** Gym Management Solution with Entity-Relationship Model

**Content:**
- **Objective:** Design a system to manage gym memberships, sessions, and coaches efficiently.
- **Focus Areas:**
  - Identifying key entities.
  - Establishing relationships between entities.
  - Creating a robust and scalable model.


---

**Slide 2: Identified Entities**

**Title:** Key Entities in the Gym System

**Content:**
1. **Gymnasium:**
   - Attributes: Name, Address, Phone Number.
2. **Member:**
   - Attributes: Unique ID, Last Name, First Name, Address, Date of Birth, Gender.
3. **Session:**
   - Attributes: Sport Type, Schedule, Max Capacity (20 members).
4. **Coach:**
   - Attributes: Last Name, First Name, Age, Specialty.


---

**Slide 3: Relationships and Cardinalities**

**Title:** Entity Relationships

**Content:**
1. **Gymnasium and Member:**
   - One gymnasium can have many members.
   - Each member registers at one gymnasium.

2. **Session and Member:**
   - One session can have up to 20 members.
   - Each member can attend multiple sessions.

3. **Session and Coach:**
   - One session can have up to 2 coaches.
   - Each coach can lead multiple sessions.

4. **Gymnasium and Session:**
   - One gymnasium can host multiple sessions.
   - Each session belongs to one gymnasium.


---

**Slide 4: Complete ER Model**

**Title:** Entity-Relationship Diagram

**Content:**
- **Entities and Attributes:**
  - Gymnasium (Name, Address, Phone Number).
  - Member (ID, Last Name, First Name, Address, DOB, Gender).
  - Session (Sport Type, Schedule, Max Capacity).
  - Coach (Last Name, First Name, Age, Specialty).

- **Relationships:**
  - Gymnasium ➔ Member (1:N).
  - Session ➔ Member (N:M).
  - Session ➔ Coach (1:N).
  - Gymnasium ➔ Session (1:N).


---

**Slide 5: Benefits of the Solution**

**Title:** Why This Model Works

**Content:**
- **Efficiency:** Automates registration and reduces errors.
- **Scalability:** Adapts to multiple gym locations.
- **Flexibility:** Supports diverse sessions and coach assignments.
- **User-Friendly:** Simplifies management for gym owners and staff.

**Conclusion:**
This system streamlines gym operations and enhances member satisfaction.


---


