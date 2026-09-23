
# Week 3 — Requirements Analysis and Specification

## 1. Information from Week 2
We found the stakeholders, what they need, things we don't know and questions we need to ask.

## 2. Candidate Requirements
A - Problem / observation
B - Stakeholder need / concern
C - Candidate requirement
D - Solution idea
E - Assumption
F - Stakeholder need / concern

## 3. Requirements Surgery
### Requirement 1
**What is the problem?**
User-friendly is too vague.

**One clarification question**
What would make it easy to use?

**What information is missing?**
What the users need it to do.

### Requirement 2

**What is the problem?**
We don't know who gets the notifications or when.

**One clarification question**
Who should get the notification?

**What information is missing?**
Who gets it and when it is sent.

### Requirement 3

**What is the problem?**
We don't know who can change bookings or when reminders are sent.

**One clarification question**
When should the reminder be sent?

**What information is missing?**
Who can change bookings and when reminders are sent.

## 4. Functional Requirements

| Stakeholder     | What they might need         |
| --------------- | ---------------------------- |
| Students        | Easy way to book equipment   |
| Staff           | Easier way to check bookings |
| Equipment staff | Know where equipment is      |
| Lecturers       | Equipment for classes        |
| College         | Equipment to be looked after |

| ID     |Requirement                                                          | Source     | How could we verify it?            |
|--------|---------------------------------------------------------------------|------------|------------------------------------|
| FR-01: |The system a user to view equipment availability for a selected date.| Technician | See if the equipment is available. |
| FR-02: |The system shall allow an authorised user to book equipment.         | User       | Try to book equipment.             | 
| FR-03: |The system shall allow an authorised user to see their bookings.     | User       | Check if their bookings are there. |

## 5. Quality Requirements

### NFR-01

**Quality requirement**
Only authorised users can see booking information.

**Why does it matter?**
To keep the information private.

**How could it be checked?**
Try to access it without logging in.

## 6. Project Application

**Candidate requirement**
The system shall allow students to view their information.

**Source**
Student

**Type**
Functional requirement

**Clarification question**
What information do students need to see?

**Verification**
Check if the information can be viewed.

**Unknown**
What information students need.

**Who could provide the information?**
Students or college staff.

## 7. Reflection

### 1. What makes a requirement difficult to understand?
If it is vague or missing information.

### 2. What information do you still need for your project?
What information students need.

### 3. Who could provide that information?
Students or college staff.
